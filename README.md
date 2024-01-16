# EmailReminderTool

## Stages

1. **STAGE 1**: Configure Simple Email Service (SES)
2. **STAGE 2**: Add an email Lambda function to use SES to send emails for the serverless application
3. **STAGE 3**: Implement and configure the state machine, the core of the application
4. **STAGE 4**: Implement the API Gateway, API, and supporting Lambda functions
5. **STAGE 5**: Implement the static frontend application and test functionality

## Services

Serverless application using S3, API Gateway, Lambda, Step Functions, SNS & SES.

### Architecture 
 ![image](https://github.com/Yvangelion/EmailReminderTool/assets/109707734/6ad97d66-3ba0-44a0-977c-88ed8bfa53c3)

### Initail Statemachine 
![image](https://github.com/Yvangelion/EmailReminderTool/assets/109707734/bf44452d-5f3c-48e7-8a73-773e6efae50b)

### S3 Website 
![image](https://github.com/Yvangelion/EmailReminderTool/assets/109707734/5946bdf9-fccf-4245-9e76-8659c7ddfb36)
![image](https://github.com/Yvangelion/EmailReminderTool/assets/109707734/77ce9da3-393c-4f87-970e-33f8f790baaf)
![image](https://github.com/Yvangelion/EmailReminderTool/assets/109707734/a02751ff-43ec-4637-8b44-a0c61c019abf)

### Bad input
![image](https://github.com/Yvangelion/EmailReminderTool/assets/109707734/f18fa4c5-4b89-4f28-8255-3bc4f111add2)

### Correct input
![image](https://github.com/Yvangelion/EmailReminderTool/assets/109707734/7bc9c04a-3ef8-4d6a-9ad5-37ce223a7a6c)

