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

![Screenshot 2024-09-02 132514](https://github.com/user-attachments/assets/cb43ab93-740a-4ba8-a3b3-2c4498203d20)


**Donor Interface**

https://github.com/user-attachments/assets/09de63ff-640d-4280-afe5-0975955bab3b


**Admin Interface**


https://github.com/user-attachments/assets/6a7a1934-9538-410c-9736-a9f7883979d0

**Hospital Interface**
![Screenshot 2024-09-02 155812](https://github.com/user-attachments/assets/1de884f8-0931-44a2-8c37-8e5097e0f0a0)
![Screenshot 2024-09-02 155342](https://github.com/user-attachments/assets/9cf96ad1-9e23-4015-beca-6eeaa6939324)


**Organization Interface**
![Screenshot 2024-09-02 160122](https://github.com/user-attachments/assets/8068936c-ff89-4375-8091-e23591260170)

![Screenshot 2024-09-02 160104](https://github.com/user-attachments/assets/13873236-2560-4a8f-8ab3-2d5804d57576)

**Chatbot Interface**

https://github.com/user-attachments/assets/6040f5fe-2060-4348-bfa8-7dc4648f59d7



