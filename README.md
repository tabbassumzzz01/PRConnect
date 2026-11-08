# PRConnect — Influencer & Brand Hiring Marketplace

PRConnect is a responsive web-app prototype that helps brands discover influencer profiles, review creator bios and key metrics, post collaboration campaigns, and send hiring requests. Influencers can browse campaigns and submit applications.

## Features

- Discover sample influencer profiles
- Search by creator name, niche, platform, bio, or tags
- Filter creators by category
- View creator biography, location, platform, followers, and engagement rate
- Send a direct hiring request to a creator
- Publish brand campaigns with requirements and collaboration type
- Apply to available campaigns as a creator
- Review submitted applications and hiring requests
- Save demo campaigns and applications in browser LocalStorage
- Responsive layout for desktop and mobile browsers

## Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Browser LocalStorage (prototype persistence)

## Run Locally

### Option 1: Open directly

1. Download or clone this repository.
2. Open `index.html` in Google Chrome, Microsoft Edge, Firefox, or another modern browser.
3. Explore the Discover, Brand Campaigns, Post a Campaign, and Applications sections.

### Option 2: Run with VS Code Live Server

1. Open the `PRConnect` folder in Visual Studio Code.
2. Install the **Live Server** extension if it is not installed.
3. Right-click `index.html` and choose **Open with Live Server**.

No build step or package installation is required for this prototype.

## Project Screenshots

### Discover Influencers

![PRConnect Discover screen](screenshots/discover_screen.png)

### Post a Brand Campaign

![Campaign form](screenshots/campaign_screen.png)

### System Architecture

![System architecture](screenshots/architecture.png)

### Application Workflow

![Application workflow](screenshots/workflow.png)

## Documentation

The complete academic lab report is available here:

- [`docs/PRConnect_Lab_Report.docx`](docs/PRConnect_Lab_Report.docx)

## Important Prototype Limitations

- Influencer profiles and metrics are sample/demo data, not verified social-media data.
- Campaigns and applications are stored only in the current browser's LocalStorage.
- Data is not synchronized between different users or devices.
- There is no real authentication, cloud database, payment, chat, or notification system.
- Hiring requests and applications are demo records; they are not sent to real brands or creators.

## Future Improvements

- Add separate Brand, Influencer, and Admin accounts.
- Integrate Firebase Authentication and Firestore.
- Add creator portfolios, media kits, and verified social links.
- Add advanced search and filtering by audience, location, engagement, and budget.
- Add in-app messaging, notifications, and application status tracking.
- Add moderation, privacy controls, and secure backend validation.
- Make the web app installable as a Progressive Web App (PWA).

## Repository Structure

```text
PRConnect/
├── index.html
├── README.md
├── .gitignore
├── LICENSE
├── docs/
│   └── PRConnect_Lab_Report.docx
└── screenshots/
    ├── discover_screen.png
    ├── campaign_screen.png
    ├── architecture.png
    └── workflow.png
```

## Academic Project Note

This repository contains a student project prototype. Replace the placeholder student and course information in the lab report before submission. Test the app yourself and update the report's testing table with actual results.
