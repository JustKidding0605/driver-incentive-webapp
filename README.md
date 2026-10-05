# Driver Incentive Program

A multi-role web application that connects trucking companies with their drivers through a performance-based rewards system. Sponsors issue points for safe driving and on-time delivery; drivers redeem them in a catalog storefront.

Built as a Senior Design capstone (Clemson University, CPSC 4910, Spring 2026) over 15 weeks with a team 5 students

<img width="1440" height="683" alt="Screenshot 2026-10-05 at 7 25 46 PM" src="https://github.com/user-attachments/assets/b8cf1ec2-0817-4c16-83b3-0c327f6ed053" />

## What it does

Trucking companies run driver incentive programs to reward safe, reliable drivers, but managing them manually across spreadsheets and email is painful. This app centralizes the whole loop:

- **Drivers** log in, see their point balance, browse a rewards catalog, and redeem points for merchandise.
- **Sponsors** (trucking company admins) add drivers, award or deduct points with a reason attached, curate their rewards catalog, and audit all activity.
- **System administrators** manage the platform itself — creating sponsor organizations, moderating users, and handling impersonation for support.

Every action is logged for audit, and all data flows respect role-based boundaries so drivers never see each other's data and sponsors only see their own drivers.

## Features

- Role-based access control across three distinct user types (driver, sponsor, admin)
- Point-ledger system with full transaction history
- Rewards catalog with product browsing and redemption workflow
- Impersonation flow so support staff can troubleshoot as another user without password sharing
- Application pipeline for drivers to join sponsor programs
- Audit log for every point change and administrative action

## My role

I worked on the frontend development of the website focusing on connecting the populated backend data to display on the web pages

- Made sure the all data related to users were displayed correctly and updated accordingly(username, password, email, etc)
- Made sure website headings, buttons, titles, etc. were displayed in an orderly and uncluttered manner to make user experience simple and understandable
- Ensured users were able to add items to their cart in an orderly and efficent manner to ensure user experience was not complicated or bugged

## Team

- [Justin Kang]
- [Joseph Laudati]
- [Gabriel Walker]
- [James Kluttz]
- [Liam Nats]

Advised by [Roger Van Scoy], CPSC 4910, Clemson University.
