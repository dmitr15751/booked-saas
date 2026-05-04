# 🗓️ booked-saas - Simple booking for busy teams

[![Download / Visit Page](https://img.shields.io/badge/Download%20%2F%20Visit%20Page-blue?style=for-the-badge&logo=github)](https://github.com/dmitr15751/booked-saas)

## 🚀 What this is

booked-saas is a multi-tenant booking app for teams that need to manage appointments, client schedules, and bookings in one web app. It uses PHP, REST APIs, and MySQL to help you run a booking system on Windows from the project page.

Use it when you want one place for:

- Client appointments
- Team schedules
- Booking records
- Tenant-based access
- Web-based management

## 💻 Before you start

Use a Windows PC with:

- A modern web browser
- At least 4 GB of RAM
- 1 GB of free disk space
- Internet access for the first setup
- A local web stack if you plan to run it on your own machine

A typical setup for this app may include:

- PHP 8.x
- MySQL 8.x
- Apache or Nginx
- A browser such as Chrome, Edge, or Firefox

## 📥 Download

Open the project page here:

https://github.com/dmitr15751/booked-saas

From that page, you can download the source files or get the release package if one is provided. If you use the source files, you will need to place them in your web server folder before running the app.

## 🛠️ Install on Windows

1. Visit the download page:
   https://github.com/dmitr15751/booked-saas

2. Download the project files to your computer.

3. If the files come as a ZIP archive, right-click the ZIP file and choose Extract All.

4. Move the extracted folder into your web server folder. Common paths are:
   - `C:\xampp\htdocs\`
   - `C:\wamp64\www\`
   - `C:\laragon\www\`

5. Open your MySQL tool, such as phpMyAdmin, and create a new database for the app.

6. Import the SQL file that comes with the project into that database.

7. Open the config file in the project folder and enter your database name, username, and password.

8. Start Apache and MySQL in your local web stack.

9. Open your browser and go to the local address for the project, such as:
   - `http://localhost/booked-saas`
   - or the folder name you used

## ⚙️ First-time setup

After the app loads, set up the first admin account if the app asks for one. Use a strong password and save it in a safe place.

If the app shows setup screens, complete them in this order:

- Site name
- Time zone
- Database check
- Admin account
- Email settings
- Booking rules

If you plan to use it for a team, decide early how you want to separate tenants, staff, and client data.

## 🧭 How to use it

After setup, the app usually works like this:

1. Sign in as an admin or staff member.
2. Add services or booking types.
3. Set working hours and days off.
4. Create staff profiles if your team uses them.
5. Share booking links with clients.
6. Review appointments from the dashboard.
7. Update or cancel bookings when plans change.

## 📌 Main features

- Multi-tenant booking support
- Appointment scheduling
- Client booking flow
- REST API access
- PHP-based web app
- MySQL data storage
- Admin dashboard
- Staff schedule control
- Booking management
- Web browser access

## 🔐 Login and access

The app may use separate access levels for:

- Admin
- Staff
- Client
- Tenant user

Keep each account type separate so users only see the data they need. This helps protect booking data and keeps the system easy to manage.

## 🧩 Common use cases

- A salon that books client visits
- A clinic that manages appointment slots
- A service team that needs shared calendars
- A business that runs separate booking spaces for each tenant
- A web app that needs client-side scheduling

## 🧰 Troubleshooting

If the page does not open:

- Check that Apache is running
- Check that MySQL is running
- Make sure the project folder is in the correct web directory
- Confirm that the database name matches the config file

If the app cannot connect to the database:

- Recheck the database username
- Recheck the password
- Make sure the database was imported
- Confirm that the SQL file loaded without errors

If the browser shows a blank page:

- Refresh the page
- Clear the browser cache
- Check the PHP version
- Look for file names that do not match the config

If bookings do not save:

- Check database permissions
- Make sure the form fields are filled in
- Confirm that the server is writing to the correct database

## 📁 Suggested folder layout

A local Windows setup may look like this:

- `C:\xampp\htdocs\booked-saas\`
- `C:\xampp\mysql\data\`
- `C:\xampp\php\`

This helps keep the app files and database tools in one place.

## 🧪 Basic test steps

Use these steps to check that the app works:

1. Open the app in your browser.
2. Sign in to the admin area.
3. Add one booking service.
4. Create one test client.
5. Set one appointment slot.
6. Save the booking.
7. Open the schedule view and confirm that the booking appears.

## 📱 Browser tips

For the best results, use:

- Chrome
- Microsoft Edge
- Firefox

Turn on JavaScript in your browser, since the app topics include client-side scheduling and web app features.

## 🔄 REST API use

The app includes REST APIs for data access and integration. That helps when you want to connect the booking system to another site, a dashboard, or a custom client app.

Typical API uses include:

- Fetching booking data
- Sending new appointments
- Updating schedule records
- Reading tenant details
- Connecting external tools

## 🛡️ Data handling

Since this is a multi-tenant system, keep tenant data separate and use one database setup that matches your project design. Back up your database often so you can restore bookings if needed.

A simple backup plan:

- Export the database once a day
- Save a copy before updates
- Keep one backup on another drive

## 📎 Project link

https://github.com/dmitr15751/booked-saas

## 🏷️ Topics

appointments, booking, javascript, multi-tenant, mysql, php, rest-api, saas, scheduling, webapp