LegisPedia

This Python application is dedicated to assisting legal professionals, researchers, and those with a keen interest in legal studies.
It harnesses the power of artificial intelligence to parse, comprehend, and extract insights from complex legal documents. 




Features: Tailor your experience by selecting from multiple jurisdictions, including US Law, India Law, UK Law, and Pakistan Law, via a user-friendly interface.
Upload PDFs of legal documents. The application employs the PyPDF2 library to extract text efficiently for detailed document scrutiny.
Text Splitting: Utilize the RecursiveCharacterTextSplitter from LangChain to segment text into smaller, more manageable parts, ensuring seamless processing of extensive legal documents.
Utilize the FAISS vector store for the efficient indexing and storage of semantic embeddings, which facilitates swift retrieval of pertinent information during the question-answering phase.

Pose legal questions in everyday language. The app conducts similarity searches in the vector store to pinpoint relevant text segments and employs OpenAI's language model to craft precise responses based on the queries and identified document segments.
Navigate the application with ease, thanks to the Streamlit-based user interface designed for engaging interaction with LegisPedia.
How to Use

Select your preferred jurisdiction from the available options.
Upload the legal document you aim to analyze in PDF format.
Input questions related to the legal document using the provided text field.


