---
title: International Club Event Tool
date: 2025-07-25
categories: [Python, Streamlit, Web App]
tags: [google-api, automation, portfolio]
pin: true # This pins the post to the top of your homepage
---

An all-in-one Streamlit application designed to automate and simplify the entire event management workflow for the International Club at the University of Applied Sciences Munich.

![Screenshot of the Event Tool](/assets/img/eventtool-screenshot.png)  
*(Upload a screenshot of your app to the `/assets/img/` folder and name it `eventtool-screenshot.png`)*

### The Problem
Organizing events for the International Club was a manual, time-consuming, and error-prone process, spanning from registration and participant lists to financial settlement.

### My Solution
I developed a centralized web application that digitizes the entire workflow:
- **Automated Form Creation:** Instantly generates Google Forms for event sign-ups with a single click.
- **Digital Signatures:** Allows participants to digitally sign in at events via a QR code.
- **PDF Generation:** Automatically creates professionally formatted participant lists.
- **AI-Powered Reports:** Leverages a local LLM to generate experience reports from brief notes.

**Technologies Used:** Python, Streamlit, Pandas, Google APIs (Forms, Drive, Sheets), OAuth 2.0, FPDF, Git.

---

### Links

<div class="d-flex justify-content-between">
    <a href="https://internationalclubeventmanagementtool.streamlit.app" class="btn btn-primary" target="_blank" role="button">
        <i class="fas fa-rocket"></i> View Live Demo
    </a>
    <a href="https://github.com/IsaSmt/InternationalClubEventmanagementtool" class="btn btn-dark" target="_blank" role="button">
        <i class="fab fa-github"></i> View Code on GitHub
    </a>
</div>