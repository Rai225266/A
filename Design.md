​Technical Design: Jan-Setu AI
​1. Process Flow
​The application follows a streamlined voice-to-voice logic:  
​Step 1: User sends a Voice Note in a local dialect (e.g., Himachali or Punjabi).  
​Step 2: AWS Transcribe converts speech to text.  
​Step 3: Amazon Bedrock processes the query against a database of government schemes.  
​Step 4: The result is simplified and sent back as a Voice Response.  
​2. System Architecture
​The solution uses a modern, serverless cloud architecture:  
​Intelligence: Amazon Bedrock (running Claude 3) serves as the "Brain".  
​Indexing: Amazon Kendra for searching and indexing government PDFs.  
​Compute: AWS Lambda for serverless, low-cost execution.  
​Storage: Amazon S3 for secure document handling and storage.  
​Frontend: WhatsApp Business API for familiar user access.  
​3. Technology Stack
​Backend: Python utilizing asyncio for speed.  
​Cloud Platform: Amazon Web Services (AWS).  
​Language API: Bhashini for Indian language translation.  
​AI Models: Amazon Bedrock (Claude / Llama 3).  
​4. Implementation & Cost
​Development: Near-zero cost using the AWS Free Tier and Credits.  
​Scalability: A pay-as-you-go model ensures costs only grow as user impact increases.  
