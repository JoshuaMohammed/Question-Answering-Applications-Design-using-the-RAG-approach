# Question-Answering-Applications-Design-using-the-RAG-approach


This study focuses on developing a question-answering application using the
Retrieval-Augmented Generation (RAG) approach. This hybrid system combines
retrieval and generation strategies to leverage pre-trained natural language processing
models, enhancing the accuracy of answers by retrieving relevant texts and generating
contextually rich responses. The approach utilizes the BM25 algorithm to improve the
search process for relevant documents and applies the BERT question-answering model
to identify appropriate answers from the retrieved texts.
The system was applied to a dataset consisting of texts extracted from a book in PDF
format using the Fitz library. The data was then organized using the Pandas library. The
system employs a BERT model from the Transformers library to analyze the texts and
retrieve accurate answers. Additionally, the system was integrated with a Telegram bot
API to allow users to ask questions and receive immediate answers.
The system is characterized by its ability to handle complex or open-ended questions
that require access to multiple sources for comprehensive information. Such systems
can be applied in various fields to improve data retrieval, enhance user interaction,
generate content, and facilitate scientific research. The system also stands out for its
flexibility in usage and the capability to integrate with social media platforms, enabling
seamless integration with different applications to provide an improved user experience.


You can get the book from this link:
https://drive.google.com/file/d/1FYKhEq9sgFCOjGxb169VkcOS-JEWKdrh/view?usp=sharing

In the future, I am planning to find a way to make it suitable for any pdf file user can upload.
The telegram bot link: https://t.me/Hands_on_ML_bot
The bot need to run the code on a device or platform connected to internet.
