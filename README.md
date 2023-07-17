# Project Name

React Mapbox Project with AWS Lambda, DynamoDB, and API Gateway Backend

## Description

This repository contains a React Mapbox project that utilizes AWS Lambda, DynamoDB, and API Gateway as the backend infrastructure. The project allows users to interact with the Mapbox API to display and manage map data.

## Features

- Displaying interactive maps using the Mapbox API.
- Implementing search functionality to find specific locations on the map.
- Storing map data and user preferences in a DynamoDB database.
- Leveraging AWS Lambda functions to handle backend logic and data processing.
- Utilizing API Gateway to manage API endpoints and facilitate communication between the frontend and backend.

## Installation

To run the project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/ashir1234/react-mapbox.git`
2. Navigate to the project directory: `cd repository-name`
3. Install dependencies: `npm install`
4. Configure AWS credentials: Set up your AWS credentials in the AWS CLI or provide them through environment variables.
5. Start the development server: `npm run dev`
6. Open the project in your browser at `http://localhost:5173`.

## Configuration

Before running the project, make sure to configure the necessary environment variables and AWS services:

1. Create a Mapbox account and obtain an API key.
2. Set up an AWS account and configure AWS credentials with appropriate permissions.
3. Create a DynamoDB table to store map data and configure the table name in the backend code.
4. Create AWS Lambda functions to handle backend logic and data processing. Configure the function names and API Gateway integration in the frontend code.

## Usage

- Upon opening the project in the browser, the map will be displayed with default settings.
- Use the search functionality to find specific locations and update the map display accordingly.
- Interact with the map and explore various features and options available.
- Data will be stored in DynamoDB and processed by the AWS Lambda functions.

## Contributing

Contributions to this project are welcome. To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any inquiries or questions, please contact [Your Name](mailto:ashirharoon15@gmail.com).
