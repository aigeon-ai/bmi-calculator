# BMI Calculator MCP Server

## Overview

The BMI Calculator MCP Server is designed to provide accurate and comprehensive Body Mass Index (BMI) calculations. It offers valuable insights into users' health status by considering multiple inputs, including weight, height, age, and gender. This server delivers precise BMI values along with related health metrics such as ideal weight, body surface area, and basal metabolic rate. By integrating this service, developers can empower their applications with advanced health assessment capabilities, promoting wellness and fitness among users.

## Features

### Comprehensive Health Metrics

The server processes user inputs to generate detailed health assessments, which include:

- **BMI Value**: A measure of body fat based on height and weight.
- **Ideal Weight Range**: Suggested weight range for optimal health.
- **Basal Metabolic Rate (BMR)**: The number of calories required to keep your body functioning at rest.
- **Waist-to-Hip Ratio (WHR)**: A measure of the distribution of body fat.
- **Waist-to-Height Ratio (WHtR)**: A measure to assess the distribution of body fat.

### User Inputs

The service accepts the following user inputs to generate accurate health metrics:

- **Weight**: In kilograms.
- **Height**: In centimeters.
- **Age**: In years.
- **Sex**: 'm' for male, 'f' for female.
- **Waist and Hip Measurements**: For detailed health analysis.

## How It Works

### Endpoint Request and Response

- **Endpoint**: The server processes inputs through a specific endpoint to deliver health metrics.
- **Request Format**: Users provide their weight, height, age, sex, waist, and hip measurements in a structured format.
- **Response Format**: The server responds with a comprehensive JSON object containing health metrics.

### Tools Provided

The BMI Calculator MCP Server includes the following tool:

- **Find BMI**: This tool processes user inputs to generate health metrics, including BMI, ideal weight range, basal metabolic rate, and waist-to-hip ratio.

## Usage Guide

1. **Authentication**: Obtain an access key to authenticate requests to the server.
2. **Integration**: Integrate the server into your application to provide users with detailed health assessments.
3. **Error Handling**: Gracefully handle errors by checking status codes and messages in the response.
4. **Data Privacy**: Ensure compliance with data privacy regulations while processing user health data.
5. **Support**: Reach out to our dedicated support team for any assistance or inquiries.

## Conclusion

The BMI Calculator MCP Server is a robust tool for providing users with comprehensive health assessments. By integrating this service, you can enhance your applications with valuable health insights, supporting users in achieving their wellness and fitness goals.