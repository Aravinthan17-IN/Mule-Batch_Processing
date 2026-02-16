# Mule-Batch_Processing
This Repository contains the mule code of batch processing with huge number of data pushing into salesforce.

The Usecase of this project is to performs data importing into Salesforce from CSV file. 
For this we use database On new or Updated file listener to listens the directory path. Salesforce credentials are configured in SF connector.

Mapping the fields to store the incoming data into salesforce database. Since we are using salesforce native connector the default batch size is 200.
