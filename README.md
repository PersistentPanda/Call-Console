Call Console

A single-page web app that guides a sales reactivation call in real time. Built for calling past water-consultation contacts (24+ months since the last visit) where the old test results are often missing from the record.

What it does

Loads the customer record (name, visit date, well or city, finding on file, open appointment slots) and fills those values into every script line
Routes the call through a branching tree: opener, six customer responses, voicemail, booking, and the 24-hour confirmation call
Searches an objection library by whatever the customer just said
Tracks dials, connects, and bookings per session to separate list problems from conversation problems

Stack: HTML, CSS, vanilla JavaScript. One file, no build step, no backend. Open index.html or visit the live page.

Design principle: build the script from what the records actually contain, not from what a template assumes. When the old result is missing, that becomes the reason for the call rather than a gap to hide.
