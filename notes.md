# re:Invent 2021 Notes

## Keynotes

- [Keynote with Adam Selipsky](https://www.youtube.com/watch?v=WGA2P_oH5Xc)
- [Keynote with Dr. Werner Vogels](https://www.youtube.com/watch?v=8_Xs8Ik0h1w)
- [Database, Analytics, and Machine Learning Keynote with Swami Sivasubramanian](https://www.youtube.com/watch?v=ue9aumC7AAk)
- [Keynote with Peter DeSantis](https://www.youtube.com/watch?v=9NEQbFLtDmg)
## Sessions

### _All Builders Welcome_

**ABW006 - Emotional intelligence to supercharge your success**

- [Attachments](https://mplay-assets.s3.amazonaws.com/sites/awsreinv21/_uploads/assets/mtekdpkyxnzwrqms_awsreinv21.pdf)


### _Architecture_

**ARC207 - The architect elevator: Connecting IT and the boardroom**

- [Attachments](https://mplay-assets.s3.amazonaws.com/sites/awsreinv21/_uploads/assets/eftwbaoydmzmmisz_awsreinv21.pdf)
- [The Software Architect Elevator: Redefining the Architect's Role in the Digital Enterprise](https://www.amazon.com/dp/1492077542/ref=cm_sw_em_r_mt_dp_M2EFWZDNS45HFNGT1MT9)


### _Artificial Intelligence and Machine Learning_

**AIM407 - Train ML models at scale with Amazon SageMaker, featuring Aurora**

- [Attachments](https://mplay-assets.s3.amazonaws.com/sites/awsreinv21/_uploads/assets/vrgrejedaopdwmbj_awsreinv21.pdf)

### _AWS Community_

**COM201 - Productizing a serverless MVP**

- [Attachments](https://mplay-assets.s3.amazonaws.com/sites/awsreinv21/_uploads/assets/ktqnirsczmpmqbgf_awsreinv21.pdf)

### _BuildOn.AWS_

**BOA306 - Twelve-Factor apps on containers, running everywhere**

- [Attachments](https://mplay-assets.s3.amazonaws.com/sites/awsreinv21/_uploads/assets/dlqtalkwopenrtga_awsreinv21.pdf)

### _Front-End Web and Mobile Development_

**FWM201 - Accelerate front-end web and mobile development with AWS Amplify**

- [Attachments](https://mplay-assets.s3.amazonaws.com/sites/awsreinv21/_uploads/assets/zizkefztgxznbgir_awsreinv21.pdf)

### _Serverless_

**SVS402 - Best practices of advanced serverless developers**

- [Attachments](https://mplay-assets.s3.amazonaws.com/sites/awsreinv21/_uploads/assets/btvyaspjqnxobxin_awsreinv21.pdf)
- Direct Service Integration
- Transform **not** Transport
- EventBridge

**SVS212 - What's new in serverless**

- [Attachments](https://mplay-assets.s3.amazonaws.com/sites/awsreinv21/_uploads/assets/rgktbxkmahyarsav_awsreinv21.pdf)
- [Serverless Land](https://serverlessland.com/)
- [Serverless Patterns Collection](https://serverlessland.com/patterns)
- IoT Core - real time updates instead of polling


## Workshops/Labs

**GPS304 - Building enterprise AI applications: No ML expertise required**

Incomplete...

- Process video and documents using AI APIs to extract their detailed data for downstream processes
- Amazon Rekognition, Amazon Transcribe, Amazon Textract

**AIM316 - AI workflow automation for document processing**

- Using OCR and NLP
- Document-processing pipeline to automate mortgage application workflows like extracting text from W2s, paystubs, and deeds; classifying documents; or using custom entity recognition to pull specific data points

See [Jupyter Notebooks](/notebooks/aim316_document_processing) linked in this repo for examples.


**AIM318 - Build an intelligent document processing solution for claims adjudication**

- Claims adjudication is a manual process performed by insurance companies under tight time pressure. The process is tedious, as claims forms have no standard template and can stretch over 100 pages.
- The _Document Understanding Solution_ for Claims automatically extracts the important information from these claims forms to help adjusters quickly adjudicate a claim and formulate a response
- The Document Understanding Solution for Claims uses Amazon Textract and Amazon Comprehend to extract important categories into a formatted template

See [Jupyter Notebooks](/notebooks/aim318_idp) linked in this repo for examples.

Additional Resources:
- [Document Understanding Solution](https://aws.amazon.com/about-aws/whats-new/2020/11/introducing-document-understanding-solution/)
- [Extract custom entities from documents with Comprehend](https://aws.amazon.com/about-aws/whats-new/2021/09/amazon-comprehend-extract-entities-native-format/)
- [SageMaker Data Labeling](https://aws.amazon.com/sagemaker/data-labeling/)
- [Automate data extraction and analysis](https://aws.amazon.com/machine-learning/ml-use-cases/document-processing/)

**SVS302 - Build a serverless web app for a theme park**

aws-serverless-workshop-innovator-island)
- Mobile app that provides thousands of users with wait times, photo opportunities, notification alerts, and language translation.
- Microservices approach
- This workshop only required minor changes to configuration files, the frontend and backend were prebuilt
- Amplify Console provides a simple, Git-based workflow for deploying and hosting fullstack serverless web applications; can be used for both frontend and backend (this workshop was only using it for the frontend)
- Amplify will be used to host static web resources like HTML, CSS, Javascript, and images which are loaded in the user's browser via S3
- Frontend:
  - existing javascript application managed with AWS Amplify that interfaces with services on the backend
- Backend:
  - Lambda, API Gateway, S3, DynamoDB, Cognito

Additional Resources:
- Virtual Workshop Tutorial:
  - [Innovator Island - Episode 1](https://www.youtube.com/watch?v=GhZpSYQ6F9M)
  - [Innovator Island - Episode 2](https://www.youtube.com/watch?v=EhgOoFbCID0)
  - [Innovator Island - Episode 3](https://www.youtube.com/watch?v=aNgmgZjzNr4)
- AWS Samples on [GitHub](https://github.com/aws-samples/aws-serverless-workshop-innovator-island)

Architecture Diagram:
![Innovator Island](/images/innovator-island-architecture.png?raw=true)