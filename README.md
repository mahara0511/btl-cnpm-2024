# HCMUT STUDENT SMART PRINTING SERVICE

This repository contains the codebase for a **Printing Service** system. The service enables users to upload files, configure printing preferences, manage print queues, and track print history. Designed with scalability, efficiency, and ease of use in mind, the printing service includes various components to ensure smooth operation and meet both functional and non-functional requirements.

## Features
- **Login**: Authenticate with HCMUTSSO.
- **File Upload**: Allows users to upload documents for printing.
- **Print Configuration**: Supports customization options such as color, paper size, and orientation.
- **Print History Tracking**: Records job details for future reference, including job timestamps, document names, and print configurations.

## System Architecture

The printing service follows a modular architecture for maintainability and scalability, with key components outlined below:

1. **User Interface (UI)**: The front-end interface that enables users to interact with the printing service.
2. **API Gateway**: Manages communication between the UI and backend components, handling user requests and responses.
3. **Backend Microservices**: Includes services responsible for file handling, job processing, and print configuration management.
4. **Database**: Stores information on print jobs, configurations, and user history for tracking and reporting.

This separation allows each component to scale independently and maintain smooth interactions even under heavy load.

## System Models

To support clear and effective system development, various models are used to define requirements and interactions:

- **Use Case Diagrams**: Illustrate user interactions, including file upload, print configuration, and history tracking.
- **Sequence Diagrams**: Define the workflow of a print job from upload to completion.
- **Acitvity Diagrams**: Describe the step-by-step flow of activities involved in the printing process, including file selection, configuration setup, job submission, and completion notification.
- **Class Diagrams**: 

## Getting Started

### Prerequisites

- **Reactjs**, **npm**: For setting up and running the frontend services.
- **Python**: For setting up and running the backend services
  
### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mahara0511/btl-cnpm-2024.git
   
2. Install dependencies:
   npm i

3. Start the application:
   npm start
