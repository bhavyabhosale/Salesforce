# HARVEST FOOD-HELP THE NEEDY

## Project Overview
The **HARVEST FOOD-HELP THE NEEDY** project, developed in the HarvestAid app, is designed to efficiently connect surplus food sources with those in need. This initiative addresses the challenge of food waste while supporting vulnerable communities. The goal is to leverage Salesforce to streamline the collection, organization, and distribution of food donations, enhancing operational efficiency, data transparency, and user engagement.

## Objectives

### Business Goals
- Improve the process for connecting food donors with recipients by creating a seamless workflow.
- Enable efficient volunteer management, ensuring timely collection and delivery of food.
- Support non-profit organizations and communities by enhancing donation tracking and transparency.

### Specific Outcomes
- **Organization Details Dashboard**: Centralized access to reports on venues, drop-off points, and volunteer activities.
- **Automated Task Management**: For Community Volunteers, including scheduling, tracking, and reporting.
- **Real-Time Updates**: Notifications for task completions, volunteer assignments, and inventory changes.

## Salesforce Key Features and Concepts Utilized
- **Dashboards and Reports**: Custom dashboards display real-time data on food delivery points and volunteer participation.
- **Custom Profiles**: Creation of profiles like `Community_Service_User_Profile`, `NGOs Community Profile`, and `Nonprofit Engagement Profile`.
- **Data Objects**: `Community Volunteer`, `Execution Details`, `Execution Summary`, and `Activity Records`.
- **Tabs and Navigation**: Streamlined with relevant tabs such as Areas, Delivery Hubs, and Community Volunteers.

## Detailed Steps to Solution Design
- **Data Model**: Custom objects like `Community Volunteer`, `Execution Summary`, `Activity Records`, and fields for storing data on food distribution points.
- **User Interface**: Configured using Salesforce's Lightning App Builder for the Home Page, including dashboards and reports for comprehensive visibility.
- **Automation and Logic**: Custom Apex triggers for automating task assignments and notifications.

## Testing and Validation
- **Unit Testing**: Apex classes and triggers were tested for accurate task assignment and volunteer scheduling.
- **User Interface Testing**: End-to-end testing of dashboards, including data refresh functionality for real-time updates on food availability and delivery points.

## Key Scenarios Addressed
- **Volunteer Task Management**: Creation, assignment, and tracking of tasks for community volunteers.
- **Food Distribution Tracking**: Monitoring food delivery from donor locations to drop-off points.
- **Inventory and Venue Tracking**: Updates on food inventory and mapping of available venues for efficient distribution.

## Conclusion
The **HARVEST FOOD-HELP THE NEEDY** project in HarvestAid has successfully streamlined food donation management, volunteer task allocation, and real-time reporting. This initiative addresses food insecurity by facilitating an organized, transparent, and efficient food donation process.

## Installation Instructions
To set up this project in your Salesforce environment, follow these steps:
1. Clone this repository.
2. Import the necessary Salesforce components (objects, fields, flows, etc.) into your Salesforce org.
3. Configure user profiles and permissions as needed.
4. Customize any additional settings or components to fit your organization's requirements.

## Usage
1. Access the HarvestAid app in your Salesforce environment.
2. Navigate through the dashboards and reports to view organization details, volunteer tasks, and food distribution data.
3. Utilize the automated task management features for effective volunteer coordination.

## Contributing
Contributions to improve this project are welcome. Please submit issues or pull requests to enhance the functionality and usability of the app.



