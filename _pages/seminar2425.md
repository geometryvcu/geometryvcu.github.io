---
layout: page
permalink: /seminar2425/
title: geometry seminar 2024-2025
description: schedule of lectures
nav: false
nav_order: #
---

<div class="embeddable_schedule" shortname="vcugeomandtop" daterange="all"></div>
<script src="https://researchseminars.org/embed_seminars.js" onload="seminarEmbedder.initialize({'addCSS': true});"></script>

<script>
    document.addEventListener('DOMContentLoaded', function() {
        // Define the start and end dates
        const startDate = new Date('2024-08-25');
        const endDate = new Date('2025-05-05');

        // Find all seminar elements (assuming they have a common class or data attribute)
        const seminars = document.querySelectorAll('.seminar'); // Adjust this selector as needed

        seminars.forEach(function(seminar) {
            // Assuming each seminar has a data-date attribute or a date text inside a specific element
            const seminarDateText = seminar.querySelector('.seminar-date').textContent; // Adjust this selector as needed
            const seminarDate = new Date(seminarDateText);

            // Hide seminars that are outside the desired date range
            if (seminarDate < startDate || seminarDate > endDate) {
                seminar.style.display = 'none';
            }
        });
    });
</script>
