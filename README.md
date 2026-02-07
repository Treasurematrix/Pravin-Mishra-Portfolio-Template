# DMI Portfolio Website (Static HTML/CSS)

This repository contains a clean, professional-looking **static portfolio website** used in **DevOps Micro Internship (DMI)** Week 1 to practice:
- Linux basics
- Nginx hosting
- Deployment proof / ownership
- Production-style checks

✅ Students deploy this website on an Ubuntu VM using Nginx and keep it live for 24 hours.

---

## Who is this for?
- DMI students (beginner → intermediate)
- Anyone learning how to host a static site with Nginx on Linux

---

## What you will build
A portfolio-style website hosted on:
- **Ubuntu VM**
- **Nginx**
- Accessible via: `http://<public-ip>`

---

## Mandatory Ownership Proof (DMI Rule)
Before you deploy, you MUST edit the footer and add your details:

Original:

```html
<p>Crafted with <span>cloud</span> excellence by Pravin Mishra</p>
```

Add this line (example):

```html
<p><strong>Deployed by:</strong> DMI Cohort 2 | Rahul Sharma | Group 4 | Week 1 | 16-01-2026</p>
```
## What I did
Footer requirement:
 I added these text: Pravin Mishra Portfolio v1.0 — Deployed on 05 feb 2026 — By CHIOMA MARGARET NWOSU
 and also replace the date with a span id 'deployDate'

How date is generated: Using ChatGPT to generate a JS code snippet for 'deployDate'
<script>
const dateElement = document.getElementById('deployDate');
const now = new Date();
const options = { day: '2-digit', month: 'short', year: 'numeric' };

const formattedDate = now.toLocaleDateString('en-US', options);
dateElement.textContent = formattedDate;

</script>

A small code snippet (footer section + JS if used): 

✅ This proof must be visible in your browser screenshot submission.