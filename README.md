# OPMS – Sales Target Management Dashboard

### Shakti Power Solutions Pvt. Ltd.

## Overview

OPMS (Operations Performance Management System) is a web-based Sales Target Management and Executive Analytics Dashboard developed for Shakti Power Solutions Pvt. Ltd.

The application helps management assign sales targets, monitor revenue performance, track quantity-wise achievements, analyze pending targets, and evaluate individual sales representatives through an interactive dashboard.

It provides separate interfaces for Super Admin and Sales Representatives, ensuring a structured approach to sales performance monitoring and target management.

## Features

### 1. Role-Based Dashboard
- Super Admin Dashboard
- Sales Representative Dashboard
- Interactive role switching
- Dynamic dashboard content based on selected role
- Individual sales representative performance view

### 2. Sales Target Management
- Assign targets to sales representatives.
- Create Monthly, Quarterly, and Yearly targets.
- Set targets using two performance metrics:
  - Volume Wise – Revenue (₹)
  - Quantity Wise – Units
- Assign targets according to product categories.
- Prevent duplicate target allocations.

### 3. Target Matrix

A centralized Target Matrix provides a consolidated view of sales targets and achievements.

**Key Metrics:**
- Volume Target
- Volume Achieved
- Volume Pending
- Quantity Target
- Quantity Achieved
- Quantity Pending

**Additional Functionality:**
- Editable target values using pencil icons.
- Super Admin can edit target values.
- Sales Representatives have read-only access.
- Dedicated Sales Person filter.
- Monthly, Quarterly, and Yearly target comparison.
- Volume-wise and Quantity-wise filters.
- Automatic calculation of achieved and pending targets.

### 4. Performance Analytics
- Target vs. Realized Performance Chart.
- Volume-wise performance analysis.
- Quantity-wise performance analysis.
- Product Category Breakdown.
- Top-performing product category identification.
- Interactive Chart.js visualizations.

### 5. KPI Dashboard

The dashboard displays three major performance indicators:

**Total Assigned Target**
- Total assigned revenue target.
- Total assigned quantity target.

**Target Achieved**
- Total revenue achieved.
- Total quantity achieved.
- Achievement percentage.
- Visual progress indicators.

**Pending Quota Gap**
- Remaining revenue target.
- Remaining quantity target.

### 6. Achievement Tracking
- Log additional sales achievements.
- Update existing target progress.
- Automatically recalculate pending targets.
- Refresh dashboard analytics after updates.

### 7. Team Announcements
- Prepare team-wide target announcements.
- Create sales-related updates.
- Interactive announcement modal.

*Actual announcement delivery requires integration with a notification service.*

### 8. User Interface
- Modern enterprise dashboard design.
- Dark Mode and Light Mode.
- Responsive layout.
- Mobile sidebar navigation.
- Interactive modals.
- Toast notifications.
- Professional typography and icons.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure |
| CSS3 | Styling |
| Tailwind CSS | Responsive UI |
| JavaScript | Functionality and logic |
| Chart.js | Data visualization |
| Font Awesome 6 | Icons |
| Google Fonts | Typography |

## Target Management Structure

The application supports three target periods:

| Period | Description |
|---|---|
| Monthly | Monthly sales targets |
| Quarterly | Quarterly sales targets |
| Yearly | Annual sales targets |

Each period supports two performance metrics:

| Metric | Measurement |
|---|---|
| Volume Wise | Revenue (₹) |
| Quantity Wise | Units |

## Installation & Setup

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Navigate to the Project Directory

```bash
cd OPMS
```

### Step 3: Run the Application

Open the following file in your browser:

```text
OPMS_SPSPL_Sales_Target_Page.html
```

Alternatively, use the Live Server extension in Visual Studio Code.

**Requirements:**
- Modern web browser.
- Internet connection to load external CDN libraries and Google Fonts.
- No additional installation is required.

## Demo Data

The current version includes sample sales target records for demonstration purposes.

Sample data includes:
- Sales representatives.
- Monthly sales targets.
- Quarterly sales targets.
- Yearly sales targets.
- Revenue-wise achievements.
- Quantity-wise achievements.
- Product category information.

## Current Implementation

This version is a frontend prototype developed using HTML, CSS, JavaScript, and Chart.js.

- Target records are maintained in JavaScript memory.
- Changes are not permanently stored in a database.
- Role switching is a frontend demonstration.
- Authentication is not connected to a backend.
- Team announcements are simulated.
- Database and backend integration are not included.

## Future Enhancements

- Backend development using Python Django / Flask or Node.js.
- MySQL database integration.
- Secure login and authentication.
- Database-driven target allocation.
- Permanent sales achievement records.
- Automated sales performance reports.
- Excel and PDF report generation.
- Email and WhatsApp notifications.
- Advanced analytics and sales forecasting.
- Real-time dashboard synchronization.

## Project Information

**Project:** Operations Performance Management System (OPMS)

**Organization:** Shakti Power Solutions Pvt. Ltd.

**Module:** Sales Target Management & Executive Analytics

**Version:** 3.0

---

*OPMS – Simplifying Sales Target Management, Performance Tracking, and Business Analytics.*
