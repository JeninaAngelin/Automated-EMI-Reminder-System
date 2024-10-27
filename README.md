# EMI Reminder System

## Project Overview

The **EMI Reminder System** is an automated application developed using UiPath that helps users manage and track their Equated Monthly Installments (EMIs) efficiently. This system sends timely reminders to users about upcoming EMI payments, helping them avoid late fees and maintain a good credit score.

## Features

- **Automated Reminders**: Sends automated email or SMS reminders to users before their EMI due dates.
- **User-Friendly Dashboard**: A simple UI to add, update, and track EMI details for various loans.
- **Notification System**: Notifies users of payment confirmations and changes in EMI amounts or due dates.
- **Historical Data Tracking**: Maintains a history of past EMIs and payments for user reference.
- **Multi-Loan Support**: Allows users to manage multiple loans from different financial institutions.
- **Configurable Notification Settings**: Users can customize reminder settings (e.g., reminder days before due date).

## Technologies Used

- **UiPath**: For automating the reminder process and managing workflows.
- **Excel/CSV**: To store user EMI data and loan details.
- **Email/SMS Service**: To send notifications to users (e.g., SMTP for emails, Twilio for SMS).
- **Database**: Optional integration with a database for persistent storage of EMI records.

## Installation

1. Clone the repository
   ```bash
   git clone https://github.com/username/emi-reminder-system.git
   cd emi-reminder-system

2. Installation

1. Open the UiPath project in UiPath Studio.
2. Configure the necessary email/SMS settings in the workflow.
3. Ensure the Excel/CSV file with EMI data is properly formatted and located in the project directory.
4. Run the main workflow to initiate the reminder system.

3. Usage

1. Open the UiPath project in UiPath Studio.
2. Update the `EMI_Data.xlsx` file with your loan details (Loan Amount, EMI Amount, Due Date, etc.).
3. Run the workflow to start sending reminders based on the configured settings.
4. Check the logs for reminder statuses and any issues encountered.
5. Test using UI Path Assitant and move the template to UI Path Orchestrator to deploy.

## Tools:

- [UiPath](https://www.uipath.com/) for providing a powerful automation platform.
- [Excel](https://www.microsoft.com/en-us/microsoft-365/excel) for managing EMI data.

## Contact

For inquiries or feedback, please reach out to [jeninaangelind@gmail.com](mailto:jeninaangelind@gmail.com).

