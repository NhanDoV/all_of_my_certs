## Week 1. Quiz 1 [4 questions]

#### Q1. Which statement is true for all uses of machine learning?
- [x] Uses algorithms to learn and improve from training data.
- [ ] Uses multilayer networks to build models that are inspired by the human brain
- [ ] Uses algorithms that are suited to only one purpose
- [ ] Requires a human to perform inferences or estimates from a trained model

#### Q2. A software engineer wants to process a collection of images to find all the images that contain a copyrighted logo. Which Amazon Rekognition API operation would help with this project?
- [ ] DetectLabels
- [ ] DetectFaces
- [x] DetectCustomLabels
- [ ] DetectModerationLabels

#### Q3. A software engineering team was supplied with scans of store receipts. The team wants populate a database with all the details of the line items that appear on the receipts. Which Amazon Textract API operation would be best suited to this task?
- [ ] AnalyzeDocument
- [x] AnalyzeExpense
- [ ] AnalyzeID
- [ ] GetDocumentText

#### Q4. A software engineer needs to determine the dominant language of a large set of documents. The documents are currently stored in an Amazon Simple Storage Service (Amazon S3) bucket. Which steps should the software engineer follow to determine the dominant language of each document?
- [x] Write a script to load the contents of each file, and use an Amazon Comprehend API operation to determine the dominant language.
- [ ] Write a script to use the Amazon Comprehend API, and pass the location of each file in Amazon S3 as a parameter.
- [ ] Write a script to load the contents of each file, and use an Amazon Translate API operation to determine the dominant language.
- [ ] Write a script to use the Amazon Translate API, and pass the location of each file in Amazon S3 as a parameter.

## Week 2. Quiz 2 [3 questions]

#### Q1. A team is processing call-center transcriptions with Amazon Transcribe. They are concerned that transcripts might contain sensitive data that will create a requirement for compliance. The team wants to configure the transcription so that sensitive data—such as name, address, and credit card numbers—do not appear in the transcripts. Which feature of Amazon Transcribe can be used to meet this requirement?
- [ ] Custom vocalbularies
- [ ] Custom language models
- [ ] Custom filters
- [x] Custom redaction

#### Q2. A software engineer has purchased an Amazon SageMaker model for license-plate detection and recognition from the AWS Marketplace. The model will be used to control entry and exit from a parking garage by recognizing license plates. To open and close the parking-garage gates, the results from the model inferences must be returned as quickly as possible. Which SageMaker resource will the engineer need to create to perform inferences with the model?
- [ ] A notebook instance
- [ ] A training job
- [x] An endpoint
- [ ] A batch transform job

#### Q3. A team is using Amazon Translate for automated language translation. The team was told that the translated text contains profanity that needs to be removed. Which option can they use to remove profanity in the output text?
- [ ] Create a custom terminology that contains the profane words and an acceptable translation.
- [x] Perform the translation with setting Profanity = MASK.
- [ ] Perform the translation with setting Formality = FORMAL.
- [ ] Write an AWS Lambda function to process the translated text and replace all profane words.
