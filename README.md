# NBA Game Day Status

This project provides an API for checking the NBA game day status using AWS services. The status of the game day is retrieved and updated every hour using AWS Lambda, EventBridge, SNS, and cron expressions. Notifications are sent via email and SMS to users subscribed to the respective SNS topics.

## Architecture

The project utilizes the following AWS services:

- **AWS Lambda**: Executes the Python script that checks the game day status and sends notifications.
- **Amazon EventBridge**: Schedules Lambda execution every hour using cron expressions.
- **Amazon SNS (Simple Notification Service)**: Sends notifications via email and SMS to users who subscribe to SNS topics.
- **Game Site API**: Used to retrieve the NBA game day status.

## Features

- Retrieves NBA game day status from an external API.
- Executes Lambda function every hour using EventBridge with a cron expression.
- Sends notifications (email and SMS) via SNS based on game day updates.

## Setup Instructions

### Prerequisites

- AWS account with permissions to manage Lambda, EventBridge, SNS, and IAM roles.
- Python 3.8 or higher installed.
- AWS CLI installed and configured.
- `boto3` library installed:
  ```bash
  pip install boto3



Connect with Me:
- LinkedIn: Phil Tebi
    [https://www.linkedin.com/in/phil-t-27597125a/](https://www.linkedin.com/in/phil-t-27597125a/)
