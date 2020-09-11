#  AWS Lex-Kendra Chatbot on Genesys Cloud Blueprint

> View the full [AWS Lex-Kendra Chatbot Blueprint article](https://developer.mypurecloud.com/blueprints/aws-lex-kendra/) on the Genesys Cloud Developer Center.

This Genesys Blueprint provides instructions for deploying the Lex-Kendra chatbot on Genesys Cloud. The Lex-Kendra chatbot is part of the AWS Contact Center Intelligence (CCI) accelerator. This integrated solution enhances the capabilities of Genesys Cloud with a conversational AI capability from AWS. Both Genesys Cloud and the Lex-Kendra solution components reside natively on AWS Cloud.

Genesys Cloud uses the Genesys Cloud Lex integration to provide customers with a standard Amazon Lex chatbot. The Lex-Kendra chatbot solution combines this basic Lex chatbot with Amazon Kendra to create a Lex-Kendra self-service chatbot. This combination enables an Amazon Lex flow to invoke an AWS Lambda function to call Amazon Kendra after a customer initiates a chat and enters a triggering question. Amazon Kendra uses natural language processing and machine learning abilities to process the customer's question and search an informational database stored in Amazon S3. Amazon Kendra and AWS Lambda then route the discovered answer back into the customer chat. All of this occurs without live agent assistance.

![Genesys Cloud and the Lex-Kendra Chatbot](blueprint/images/bpKendraOverviewMR.png)
