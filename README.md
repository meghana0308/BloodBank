## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Configuration](#configuration)
7. [Contact](#contact)
8. [Output](#output)

## Introduction

Welcome to **RedReserve**, the Blood Bank Management System! This web-based application is designed to streamline the blood donation process by connecting donors, hospitals, and blood banks. It features an AI-powered chatbot for enhanced user support, aiming to optimize the availability and distribution of blood supplies efficiently.

## Features

- **Donor Management**: Register donors, view donation history, and manage donor profiles.
- **Hospital Inventory Management**: Track blood type availability, manage incoming and outgoing inventory, and ensure efficient use of resources.
- **Organization Coordination**: Facilitate communication and coordination between different blood banks to maintain optimal blood supply levels.
- **Chatbot Integration**: Developed using Dialogflow, the chatbot assists users with inquiries, provides guidance, and improves engagement.
- **User Roles**: Distinct roles for donors, hospitals, and administrators to manage their respective functionalities.
- **Real-Time Data**: Provides real-time updates on blood availability, donation history, and inventory management.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Chatbot**: Dialogflow
- **State Management**: Redux
- **Styling**: CSS, Bootstrap

## Installation

Follow these steps to get a local copy up and running.

### Prerequisites

- Node.js (v14.x or higher)
- npm (v6.x or higher)
- MongoDB

### Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/meghana0308/blood-bank.git
   cd blood-bank-system
2. **Install dependencies:**

   ```bash
   npm install
   cd client
   npm install
3. **Set up environment variables:**
   Create a `.env` file in the root directory and add the following:

   ```env
   NODE_ENV=development
   PORT=8000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   DIALOGFLOW_CLIENT_EMAIL=your_dialogflow_client_email
   DIALOGFLOW_PRIVATE_KEY=your_dialogflow_private_key
4. **Run the application:**

   ```bash
   npm run dev
5. **Access the application:**
   Open your browser and go to `http://localhost:8000`

## Usage

Once the application is running, you can:

- Register as a donor, hospital, or blood bank organization.
- Manage blood inventory and donor records.
- Use the chatbot for assistance and queries.
- Administrators can manage users, blood inventory, and handle communication between different organizations.

## Configuration

Additional configuration options can be managed through the `.env` file and other configuration files within the project. Ensure you have correctly set up Dialogflow integration for the chatbot to function properly.

## Contact

For any questions, please contact: [meghanavjiet@gmail.com](mailto:meghanavjiet@gmail.com)

## Output

Here are some screenshots showcasing the different aspects of the **RedReserve** Blood Bank Management System:

**Login/Register**

![Screenshot 2024-09-02 132514](https://github.com/user-attachments/assets/df5eb535-e24d-4831-99d4-74ee7cdb5905)


**Donor Interface**


https://github.com/user-attachments/assets/1960b3f8-0d0a-43f2-90b7-ba69efbf13fa




**Admin Interface**



https://github.com/user-attachments/assets/9e992808-fc0a-4b48-9b78-f36095a59ef3


**Hospital Interface**

![Screenshot 2024-09-02 155812](https://github.com/user-attachments/assets/34519966-e760-445b-b115-1ae6491e7826)

![Screenshot 2024-09-02 155342](https://github.com/user-attachments/assets/fa8e7e3c-fd89-4d27-a69d-4d93d4faa8fa)

**Organization Interface**

![Screenshot 2024-09-02 160122](https://github.com/user-attachments/assets/0623670a-c8ea-4288-9227-7ebfd64028fd)

![Screenshot 2024-09-02 160104](https://github.com/user-attachments/assets/60e8e9b5-2a13-412b-a6b7-c448449e3a87)

**Chatbot Interface**


https://github.com/user-attachments/assets/4aacbcff-0f7e-496d-81eb-c925787ceabc

