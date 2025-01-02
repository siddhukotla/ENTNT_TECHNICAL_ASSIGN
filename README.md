# ENTNT_TECHNICAL_ASSIGN
UI DESIGN
 ![image](https://github.com/user-attachments/assets/953c4ccf-d0b3-4d55-a613-28f463b80ffb)
 ![image](https://github.com/user-attachments/assets/77305263-b08e-491a-bb79-6f7285bd4815)
 ![image](https://github.com/user-attachments/assets/e42157e1-47a1-4c07-bf4a-7db0317301d8)
 ![image](https://github.com/user-attachments/assets/54d87cf3-7979-4e6d-b5fc-d2b3c60844be)
 ![image](https://github.com/user-attachments/assets/42046989-1595-4faa-9f8d-bf68c7dc24f6)
![image](https://github.com/user-attachments/assets/648987fa-5cb9-4e66-8b92-080c15e47f7e)
![image](https://github.com/user-attachments/assets/49fef5e4-c5fa-4722-b256-4dd27f4f9e9e)
![image](https://github.com/user-attachments/assets/22ed1000-982e-4951-85f1-5f1764efb425)
![image](https://github.com/user-attachments/assets/cf4ef061-45aa-4e53-ad48-b0e93939f600)
![image](https://github.com/user-attachments/assets/ed7606d8-d426-4a9f-9c77-0a1ff0665fd4)
![image](https://github.com/user-attachments/assets/41a7ff4f-365b-4585-a50c-e3dde6565b48)
![image](https://github.com/user-attachments/assets/64e60751-d9cf-4e95-a701-d7e0f7be6432)
![image](https://github.com/user-attachments/assets/a044d934-0db3-4e17-ac46-bcdc70f1fdc8)

# Objective 

As a company, we aim to maintain strong professional relationships by keeping accurate records of our interactions with other organizations. The objective of this assignment is to develop a React-based Calendar Application that enables us to efficiently track communication with companies, ensuring follow-ups are timely and consistent. This tool will provide a centralized platform to log past interactions, plan future communications, and manage the frequency of engagement based on predefined schedules.


## Features

- **Company Management**: Create, update, and delete company profiles with detailed information
- **Communication Tracking**: Log and track various communication methods (Email, LinkedIn, Phone)
- **Dashboards**:
  - Admin Dashboard: Manage companies and communication methods
  - User Dashboard: Track communications and view calendar
  - Reporting Dashboard: Analyze communication trends and effectiveness
- **Calendar Integration**: Schedule and view upcoming communications
- **Analytics**: Visualize communication patterns and engagement metrics
- **Theme Support**: colour backgroud theme 

## Setup Instructions

### Prerequisites

- Node.js (v16 or higher)
- Yarn package manager

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/communication-tracker.git
   ```
2. Navigate to the project directory:
   ```bash
   cd communication-tracker
   ```
3. Install dependencies:
   ```bash
   yarn install
   ```

### Running the Application

1. Start the development server:
   ```bash
   yarn start
   ```
2. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

### Building for Production

1. Create a production build:
   ```bash
   yarn build
   ```
2. Serve the build files using a static server:
   ```bash
   serve -s build
   ```

## Project Structure

```
src/
├── App.js                # Main application component
├── index.js              # Application entry point
├── theme.js              # Theme configuration
├── context/              # Context providers
│   └── ThemeContext.js   # Theme management context
├── modules/              # Application modules
│   ├── admin/            # Admin-specific components
│   │   ├── AdminDashboard.js
│   │   ├── CompanyManagement.js
│   │   └── CommunicationMethodManagement.js
│   ├── user/             # User-specific components
│   │   ├── UserDashboard.js
│   │   └── EnhancedCalendar.js
│   └── reporting/        # Reporting components
│       └── ReportingDashboard.js
public/                   # Static assets
```

## Known Limitations

1. **Data Persistence**: Currently uses in-memory state management. Data is lost on page refresh.
2. **Authentication**: No user authentication implemented.
3. **Form Validation**: Limited validation in company management forms.


## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/YourFeatureName`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeatureName`)
5. Create a new Pull Request

## License

MIT License

Copyright (c) 2024 Your Name

Permission is hereby granted...














