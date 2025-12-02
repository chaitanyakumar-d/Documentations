# KAT Tech Systems - Timesheet Application
## User Manual

---

## Table of Contents
1. [Introduction](#introduction)
2. [Accessing the Application](#accessing-the-application)
3. [Employee Registration](#employee-registration)
4. [Employee Login](#employee-login)
5. [Employee Dashboard](#employee-dashboard)
6. [Submitting Timesheets](#submitting-timesheets)
7. [Admin Login](#admin-login)
8. [Admin Dashboard](#admin-dashboard)
9. [Team Lead Approval](#team-lead-approval)
10. [Troubleshooting](#troubleshooting)

---

## 1. Introduction

The **KAT Tech Systems Timesheet Application** is a web-based system for managing employee work hours and timesheet approvals. It provides:

- **Employee Self-Registration** with email verification
- **Role-based Access Control** (Admin, Team Lead, Employee)
- **Timesheet Submission** with project tracking
- **Multi-level Approval System**
- **Admin Management Panel**

---

## 2. Accessing the Application

### URL
Access the application at: **http://timesheet.kattechsystems.in**

### Browser Requirements
- Modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- Cookies enabled

---

## 3. Employee Registration

### Step 1: Navigate to Registration Page
- Click **"Click here to register"** on the login page
- Or go directly to: http://timesheet.kattechsystems.in/register.html

### Step 2: Fill Registration Form
1. **Full Name**: Enter your complete name
2. **Company Email**: Enter your @kattechsystems.com or @kattechsystems.in email
3. **Role**: Select your job role from the dropdown
4. **Password**: Create a password (minimum 6 characters)
5. **Confirm Password**: Re-enter the same password

### Step 3: Email Verification
1. Click **"Send OTP to Email"** button
2. Check your email inbox for the OTP code
3. Enter the 6-digit OTP in the form
4. Click **"Register Account"**

### Step 4: Wait for Admin Approval
- Your account will be created in **"Pending"** status
- Admin must approve your account before you can log in
- You will receive an email notification once approved

---

## 4. Employee Login

### Step 1: Go to Login Page
Navigate to: http://timesheet.kattechsystems.in/login

### Step 2: Enter Credentials
- **Email**: Your @kattechsystems.com or .in email
- **Password**: The password you created during registration

### Step 3: Click Login
- You will be redirected to the Employee Dashboard

### Forgot Password?
- Click **"Forgot Password?"** link
- Enter your email
- Follow the reset instructions sent to your email

---

## 5. Employee Dashboard

### Overview Tab
View your timesheet statistics:
- **Total Timesheets Submitted**
- **Approved Timesheets**
- **Pending Approval**
- **Rejected Timesheets**

### Quick Actions
- Submit new timesheet
- View recent submissions
- Check approval status

---

## 6. Submitting Timesheets

### Step 1: Open Timesheet Tab
Click on **"Timesheet"** in the navigation menu

### Step 2: Fill Timesheet Details

**Work Date**
- Select the date you worked

**Project**
- Enter the project name or code you worked on

**Task Description**
- Describe the work you completed
- Be specific and detailed

**Hours Worked**
- Enter the number of hours (e.g., 8, 8.5)
- Must be a positive number

**Status**
- Will automatically be set to "Pending"

### Step 3: Submit Timesheet
- Click **"Submit Timesheet"** button
- You'll see a success message
- The timesheet appears in your submission list

### Step 4: Track Status
Your timesheet will go through approval stages:
1. **Pending** - Waiting for Team Lead approval
2. **Team Lead Approved** - Waiting for Admin approval
3. **Approved** - Fully approved by Admin
4. **Rejected** - Rejected (check rejection reason)

### Editing Timesheets
- You can only edit timesheets in **"Pending"** status
- Click the **Edit** button next to the timesheet
- Update the details and click **"Update"**

### Deleting Timesheets
- You can only delete timesheets in **"Pending"** status
- Click the **Delete** button and confirm

---

## 7. Admin Login

### Admin Credentials
- **Email**: Provided by system administrator
- **Password**: Set during admin account creation

### Access
- Navigate to: http://timesheet.kattechsystems.in/login
- Enter admin email and password
- You will be redirected to the Admin Dashboard

---

## 8. Admin Dashboard

### Overview Tab
View system-wide statistics:
- **Total Employees**
- **Total Timesheets**
- **Pending Approvals**
- **Approved Timesheets**

### Employees Tab
Manage employee accounts:
- **View All Employees**
- **Approve Pending Registrations**
- **Update Employee Roles**
- **Delete Employee Accounts**

**Approving New Employees:**
1. Click on **"Employees"** tab
2. Find employees with **"Pending"** status
3. Click **"Approve"** button
4. Employee can now log in

### Timesheets Tab
View and manage all timesheets:
- See all employee timesheets
- Filter by status
- Approve or reject timesheets
- Export reports

**Approving Timesheets:**
1. Click **"Approve Timesheets"** button
2. Review timesheets pending admin approval
3. Click **"Approve"** for each timesheet
4. Or **"Reject"** with a reason

### Roles Tab
Manage system roles:
- **View All Roles**
- **Create New Roles**
- **Edit Role Names**
- **Delete Roles**

**Note:** Employees assigned to a deleted role will be automatically reassigned to "Employee" role.

---

## 9. Team Lead Approval

### Team Lead Role
Team Leads have special permissions:
- View team member timesheets
- Approve timesheets (first level approval)
- Cannot access admin functions

### Approving Team Timesheets
1. Log in with Team Lead credentials
2. Navigate to **"Timesheet"** tab
3. Review pending timesheets
4. Click **"Approve"** or **"Reject"**
5. Approved timesheets move to Admin for final approval

---

## 10. Troubleshooting

### Cannot Register
**Problem:** Email validation error
- **Solution:** Ensure you're using @kattechsystems.com or @kattechsystems.in email

**Problem:** OTP not received
- **Solution:** Check spam folder, wait 1-2 minutes, or request a new OTP

### Cannot Login
**Problem:** "Invalid credentials"
- **Solution:** Verify email and password are correct
- **Solution:** Use "Forgot Password" to reset

**Problem:** "Account pending approval"
- **Solution:** Wait for admin to approve your registration

### Timesheet Issues
**Problem:** Cannot submit timesheet
- **Solution:** Ensure all fields are filled correctly
- **Solution:** Check that hours worked is a positive number

**Problem:** Cannot edit timesheet
- **Solution:** You can only edit timesheets in "Pending" status
- **Solution:** Once approved/rejected, timesheets cannot be edited

### General Issues
**Problem:** Page not loading
- **Solution:** Clear browser cache and refresh
- **Solution:** Try a different browser
- **Solution:** Check internet connection

**Problem:** Changes not showing
- **Solution:** Refresh the page (Ctrl+F5 or Cmd+R)
- **Solution:** Log out and log back in

---

## Support

For technical support or questions:
- **Email:** chaitanyad@kattechsystems.in
- **Report Issues:** Contact your system administrator

---

## System Information

- **Application URL:** http://timesheet.kattechsystems.in
- **Version:** 1.0
- **Last Updated:** October 2025
