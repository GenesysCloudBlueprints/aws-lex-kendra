#  Deploy the Lex-Kendra chatbot on Genesys Cloud

> View the full [Deploy the Lex-Kendra chatbot on Genesys Cloud](https://developer.mypurecloud.com/blueprints/aws-lex-kendra/) Genesys Cloud Developer Blueprint in the Genesys Cloud Developer Center.

This Genesys Cloud Developer Blueprint explains how to deploy the Lex-Kendra chatbot on Genesys Cloud. The Lex-Kendra chatbot solution, which is part of the AWS Contact Center Intelligence (CCI) accelerator, combines this basic Amazon Lex chatbot with Amazon Kendra to create a Lex-Kendra self-service chatbot. This combination enables an Amazon Lex flow to invoke an AWS Lambda function to call Amazon Kendra after a customer initiates a chat and enters a triggering question.

This integrated solution enhances the capabilities of Genesys Cloud with conversational AI capability from AWS. Both Genesys Cloud and the Lex-Kendra solution components reside natively on AWS. Genesys Cloud uses the Genesys Cloud Amazon Lex integration to provide customers with a standard Amazon Lex chatbot. Amazon Kendra uses natural language processing and machine learning abilities to process the customer's question and search an informational database stored in Amazon S3. Amazon Kendra and AWS Lambda then route the discovered answer back into the customer chat. This all occurs without live agent assistance.

![Genesys Cloud and the Lex-Kendra chatbot](blueprint/images/bpKendraOverviewMR.png)
