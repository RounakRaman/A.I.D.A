# A.I.D.A - Artificial Intelligence and Data Analytics System

Welcome to the A.I.D.A (Artificial Intelligence and Data Analytics) project! A.I.D.A is an advanced chatbot system built using the GPT-3.5 architecture developed by OpenAI. This chatbot leverages the power of artificial intelligence and data analytics to provide intelligent responses and perform various tasks.

## Features

1. **Infinite Memory**: Unlike the previous versions, A.I.D.A now has the capability to store an infinite number of messages. This is made possible by utilizing Pinecone Vectorized Databases, which enable efficient storage and retrieval of message vectors.

2. **Improved Cognitive Architecture**: A.I.D.A's cognitive architecture has been enhanced to provide better semantic search capabilities. This enables the chatbot to understand the context of user queries and generate more accurate and relevant responses.

3. **Integration with Pinecone API**: In addition to the OpenAI API key, A.I.D.A now requires a Pinecone API key to initialize the index and store the messages in vector format. Pinecone's vector search engine powers the infinite memory feature and allows for efficient querying of the stored messages.

## Usage

To use A.I.D.A and interact with the chatbot, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies using the provided `requirements.txt` file.
3. Obtain the necessary API keys:
   - OpenAI API Key: Visit the OpenAI website (https://openai.com) to obtain an API key.
   - Pinecone API Key: Sign up on the Pinecone website (https://www.pinecone.io) to get an API key.
4. Configure the API keys in the `config.py` file.
5. Run the chatbot by executing the `chatbot.py` script.
6. Interact with the chatbot by entering your queries and receiving responses.

## Differences from Previous Version

A.I.D.A with infinite memory and Pinecone integration offers several improvements over the previous version:

1. **Infinite Memory**: The previous version had a limited capacity to store messages, which restricted the chatbot's ability to recall past interactions. The current version overcomes this limitation by using Pinecone Vectorized Databases, enabling storage of an unlimited number of messages.

2. **Semantic Search**: A.I.D.A's cognitive architecture has been enhanced to improve semantic search capabilities. This allows the chatbot to understand the context of user queries more effectively, resulting in more accurate and relevant responses.

3. **Pinecone Integration**: The integration of Pinecone API adds vector storage functionality to the chatbot. Each message is converted into a vector and stored in the virtual cloud environment provided by Pinecone. This allows for efficient storage, retrieval, and searching of messages, enhancing the chatbot's memory and overall performance.

By combining these advancements, A.I.D.A becomes a more powerful and intelligent chatbot, providing enhanced conversational experiences and knowledge recall.

## Contributing

We welcome contributions from the community to improve and enhance A.I.D.A. If you would like to contribute, please follow these guidelines:

- Fork the repository and create a new branch for your feature or bug fix.
- Ensure your code is well-documented and follows the coding style of the project.
- Create a pull request, describing your changes and the motivation behind them.



## Acknowledgements

We would like to express our gratitude to OpenAI for their powerful GPT-3.5 architecture and to Pinecone for their vectorized databases and search engine.


We hope

 you enjoy using A.I.D.A and find it helpful in your endeavors!

