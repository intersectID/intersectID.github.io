---
layout: main
title: "Registration"
subtitle: "Registration Page forINTERSECT 2025"
description: "Registration information for INTERSECT 2025"
keywords: "INTERSECT 2025, registration"
toc: true
auto_toc: true
date: 2025-01-29
og_image: "https://intersect.id/assets/img/INTERSECT25_CoverLight.jpg"
---

<style>
/* Remove color scheme forcing */
:root {
    color-scheme: auto;
}

/* Base table styles */
.fee-table {
    width: 100%;
    border-collapse: collapse;
    margin: 2rem 0;
    background: transparent;
    box-shadow: 0 1px 3px rgba(0,0,0,0.1);
}

/* Table wrapper for horizontal scroll */
.table-container {
    width: 100%;
    overflow-x: auto;
    -webkit-overflow-scrolling: touch;
    margin: 2rem 0;
    border-radius: 8px;
    position: relative;
}

/* Responsive styles */
@media screen and (max-width: 768px) {
    .table-container {
        margin: 2rem -1rem;  /* Negative margin to allow full-width scroll */
        padding: 0 1rem;
        width: calc(100% + 2rem);
    }
    
    .fee-table {
        margin: 0;  /* Remove table margin inside container */
        min-width: 600px;  /* Ensure minimum width for content */
    }
    
    .fee-table th,
    .fee-table td {
        min-width: 120px;  /* Minimum column width */
    }
    
    .fee-period,
    .deadline {
        white-space: nowrap;  /* Prevent date wrapping */
    }
}

.fee-table th,
.fee-table td {
    padding: 1rem 1.5rem;
    text-align: left;
    border-bottom: 1px solid #eee;
}

.fee-table th {
    background: #039311;
    color: white;
    font-weight: 600;
    text-transform: uppercase;
    font-size: 0.9rem;
    letter-spacing: 0.5px;
}

.fee-table tr:nth-child(even) {
    background: rgba(248, 249, 250, 0.9);
}

.fee-table tr:hover {
    background: rgba(241, 243, 245, 0.95);
}

.fee-category {
    font-weight: 600;
    color: #039311;
}

.fee-note {
    font-size: 0.9rem;
    color: #666;
    font-style: italic;
    margin-top: 1rem;
}

.fee-period {
    display: block;
    color: #039311;
    font-size: 0.85rem;
    margin-bottom: 0.25rem;
}

.deadline {
    color: #666;
    font-size: 0.85rem;
    display: block;
}

.faq-section {
    margin: 2rem 0;
}

.faq-item {
    border-bottom: 1px solid #eee;
    margin-bottom: 1rem;
}

.faq-question {
    font-weight: 600;
    color: #333;
    padding: 1rem;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: space-between;
    background: transparent;
    border-radius: 8px;
    transition: all 0.3s ease;
}

.faq-question:hover {
    background: rgba(248, 249, 250, 0.9);
}

.faq-question::after {
    content: '+';
    font-size: 1.2rem;
    color: #039311;
}

.faq-question.active::after {
    content: '−';
}

.faq-answer {
    padding: 0 1rem;
    max-height: 0;
    overflow: hidden;
    transition: all 0.3s ease;
    opacity: 0;
    color: #666;
    line-height: 1.6;
}

.faq-answer.active {
    padding: 1rem;
    max-height: 500px;
    opacity: 1;
    background: transparent;
    margin: 0.5rem 0;
    border-radius: 8px;
}

/* General Typography Improvements */
h1, h2 {
    color: #333;
    margin: 2rem 0 1rem;
}

h2 {
    font-size: 1.5rem;
    border-bottom: 2px solid #039311;
    padding-bottom: 0.5rem;
    display: inline-block;
}

.registration-steps {
    background: transparent;
    padding: 1.5rem;
    border-radius: 8px;
    margin: 2rem 0;
}

.registration-steps ol {
    margin: 0;
    padding-left: 1.2rem;
}

.registration-steps li {
    margin: 1rem 0;
    line-height: 1.6;
}

.contact-info {
    background: transparent;
    padding: 1rem 1.5rem;
    border-radius: 8px;
    margin: 1rem 0;
}

/* Update timeline table */
.timeline-table {
    background: transparent;
}
</style>

# Registration Fees

We have two types of registration fees: conference registration and executive workshop registration. Each type only covers its own event. If you wish to attend both the conference and the workshop, you need to register for both. Also, note that all fees are in USD and not including accommodation. We will publish a list of hotels and accommodations soon.

## Conference Registration

Conference registration fees are for the conference only (main event at November 20, 2025), full day. It does not include the workshop.

<!-- Conference Registration Table -->
<div class="table-container">
    <table class="timeline-table">
        <thead>
            <tr>
                <th>Category</th>
                <th>Early Bird<span class="date-range">Jul 1 - Aug 31, 2025</span></th>
                <th>Regular<span class="date-range">Sep 1 - Oct 31, 2025</span></th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td data-label="Category">Student</td>
                <td data-label="Early Bird (Jul 1 - Aug 31)">$50</td>
                <td data-label="Regular (Sep 1 - Oct 31)">$100</td>
            </tr>
            <tr>
                <td data-label="Category">Professional</td>
                <td data-label="Early Bird (Jul 1 - Aug 31)">$200</td>
                <td data-label="Regular (Sep 1 - Oct 31)">$300</td>
            </tr>
            <tr>
                <td data-label="Category">Remote Listener</td>
                <td data-label="Early Bird (Jul 1 - Aug 31)">$25</td>
                <td data-label="Regular (Sep 1 - Oct 31)">$50</td>
            </tr>
        </tbody>
    </table>
</div>

Each conference registration covers both the attendance and the publication fee, except for the remote listener. However, we reserve the right to remove your paper from the publication if you are not able to present your work at the conference.

## Executive Workshop Registration

Executive workshop registration fees are for the workshop only (3-day workshop at November 17-19, 2025). It does not include the conference. 

<div class="table-container">
    <table class="timeline-table">
        <thead>
            <tr>
                <th>Category</th>
                <th>Early Bird<span class="date-range">Mar 1 - Jun 30, 2025</span></th>
                <th>Regular<span class="date-range">Jul 1 - Oct 31, 2025</span></th>
                <th>Last-minute<span class="date-range">Nov 1 - 18, 2025</span></th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td data-label="Category">Standard</td>
                <td data-label="Early Bird (Mar 1 - Jun 30)">$2,000</td>
                <td data-label="Regular (Jul 1 - Oct 31)">$3,000</td>
                <td data-label="Last-minute (Nov 1 - 18)">$4,000</td>
            </tr>
            <tr>
                <td data-label="Category">Sponsor (Additional Person)</td>
                <td data-label="Early Bird (Mar 1 - Jun 30)">$1,500</td>
                <td data-label="Regular (Jul 1 - Oct 31)">$2,000</td>
                <td data-label="Last-minute (Nov 1 - 18)">$3,000</td>
            </tr>
        </tbody>
    </table>
</div>

<p class="fee-note">* Workshop fees do not include accommodations</p>
<p class="fee-note">* All fees are in USD</p>

<div class="registration-steps">
    <h2>How to Register</h2>
    <ol>
        <li>Fill out the registration form <a href="#">here</a> (link will be available soon)</li>
        <li>Complete the payment through our secure payment gateway</li>
        <li>You will receive a confirmation email with further instructions</li>
    </ol>
    <div class="contact-info">
        For group registrations or special arrangements, please contact us at <a href="mailto:intersect.indonesia@gmail.com">intersect.indonesia@gmail.com</a>
    </div>
</div>

## Frequently Asked Questions (FAQs)
<div class="faq-section">
    <div class="faq-item">
        <div class="faq-question">Why do we charge a conference registration fee?</div>
        <div class="faq-answer">
            We charge a registration fee to cover the costs of the conference, including the venue, catering, and other expenses. The fee is also used to cover the costs of the competition.
        </div>
    </div>
    
    <div class="faq-item">
        <div class="faq-question">Why do we charge a workshop registration fee?</div>
        <div class="faq-answer">
            The workshop is a separate event from the conference. The fee covers the costs of the workshop, including the venue, catering, faculty salary, supplies, and other expenses. A 3-day workshop means we need to rent campus facilities for 3 days, and we need to pay the faculty for 3 days of work. Unfortunately, it is not possible to cover the costs of the workshop with the registration fees. If you affiliated with any of the sponsors, you can get a discount on the workshop fee.
        </div>
    </div>
    
    <div class="faq-item">
        <div class="faq-question">Do we offer a refund?</div>
        <div class="faq-answer">
            We offer a refund if you cancel your registration before the early bird deadline. After the early bird deadline, the registration fee is non-refundable.
        </div>
    </div>
    
    <div class="faq-item">
        <div class="faq-question">Do we offer a discount for students?</div>
        <div class="faq-answer">
            Yes, we offer a discount for students.
        </div>
    </div>
    
    <div class="faq-item">
        <div class="faq-question">Do we offer additional discounts for group registrations?</div>
        <div class="faq-answer">
            Yes, we offer additional discounts for group registrations. Please contact us at intersect.indonesia@gmail.com for more information.
        </div>
    </div>
    
    <div class="faq-item">
        <div class="faq-question">Can we help with accommodation?</div>
        <div class="faq-answer">
            Yes, we can help with accommodation. Please contact us at intersect.indonesia@gmail.com for more information.
        </div>
    </div>
    
    <div class="faq-item">
        <div class="faq-question">Can we help with travel documents such as visa?</div>
        <div class="faq-answer">
            We can provide a letter of invitation for your visa application. Please submit a request at least 2 weeks before the conference.
        </div>
    </div>
    
    <div class="faq-item">
        <div class="faq-question">Can we help with travel arrangements?</div>
        <div class="faq-answer">
            Unfortunately, we cannot help with travel arrangements. You are responsible for your own travel arrangements.
        </div>
    </div>
</div>

<script>
document.querySelectorAll('.faq-question').forEach(question => {
    question.addEventListener('click', () => {
        const answer = question.nextElementSibling;
        const isActive = question.classList.contains('active');
        
        // Close all FAQs
        document.querySelectorAll('.faq-question').forEach(q => q.classList.remove('active'));
        document.querySelectorAll('.faq-answer').forEach(a => a.classList.remove('active'));
        
        // Open clicked FAQ if it wasn't active
        if (!isActive) {
            question.classList.add('active');
            answer.classList.add('active');
        }
    });
});
</script>