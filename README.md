# Build Your Own Chatbot
   - Can be used to for Twitter - Charles the AI - https://twitter.com/Charles_the_AI?lang=en

## Demo of prebuilt chatbot

## Build custom chatbot
  1. Download Dataset
  2. Python code to build a chatbot database, tables, & columns (parent id, comments, parent data, body, subredit, created_utc, score)
  3. Clean data - Format/remove quotes, spaces, unessecary characters
  4. Find out if comments are acceptable (grab data with upvoted comments)
  5. Insert data - Browse/View results
  
## Create training data
  1. Create two data files train.from and train.to (Parent comment and child reply)

## Run Model - Tensorflow NMT - Nueral Machine Translation
  1. Prepare GPU VM or Desktop 
     - Install Python 3.6, Tensorflow GPU 1.4, Cuda 8.0 Toolkit, cuDNN
     - Paperspace provides provised ML-in-a-Box for $10 (Versions have been updated)
  2. Clone NMT github project
  3. Install requirements
  4. Copy database to new_data (train.from, train.to)
  5. Run prepare data
  7. Run training - Tokenize data - BNN Birdirectional Neural Network
  
## View Data in Tensorboard
  1. Show Blue Score & Epochs
  2. Show word vector projector
  
## Deploy 
  1. View training data in output.dev
  2. Run python inference
  3. Chat with your bot
  
  
  
  

  
