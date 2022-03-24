# Sentiment-Analysis-on-Speech

I carried out my work on AWS services and realized an end-to-end architectural design. In this design, audio files uploaded from a front-end are uploaded to the relevant S3 bucket. Every audio file coming to the S3 bucket triggers the lambda that enables Aws trascribe to work, and thus our audio files are converted into texts. I used Aws sagemaker notebook for editing our audio files and extracting the speaker-based sentiment states. I printed this data into DynamoDB to store the data and use it when we need it. I used the PowerBI tool to visualize the work outputs. I integrated it with AWS, enabling it to be visualized and observed on a conversational and user-based basis. You can find the architecture and screenshots of the project in the file.
