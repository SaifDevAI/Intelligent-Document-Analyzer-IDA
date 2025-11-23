Intelligent PDF Analyzer (IPA)
==============================

A lightweight yet powerful PDF analysis tool designed to break down large documents using **semantic sentence-based chunking** and extract meaningful summaries using the **Gemini 2.5 Flash API**. Built to handle long PDFs while keeping the final output natural, readable, and non-AI sounding.

✨ Key Features
--------------

*   **Sentence-Aware Chunking:** Uses NLTK to split the document _only at sentence boundaries_, ensuring the flow of ideas stays intact.
    
*   **Chunk-Based AI Analysis:** Each chunk is summarized with Gemini 2.5 Flash using a structured, human-friendly prompt.
    
*   **Merged Final Summary:** All chunk summaries are combined and refined into one smooth, coherent final document.
    
*   **Clean Output:** Summaries include simple explanations, bullet notes, key terms, and helpful insights.
    
*   **No Image Extraction:** Pure text-based PDF analysis for clean and reliable results.
    
*   **Colab-Ready:** Fully optimized to run in Google Colab with file upload support.
    

🛠 Requirements
---------------

*   Google Colab (recommended)
    
*   Gemini API Key
    
*   Python libraries:
    
    *   NLTK
        
    *   PyPDF2
        
    *   google-genai
        

🚀 How It Works
---------------

1.  Upload a PDF file.
    
2.  Extract all text from the PDF.
    
3.  Automatically break the text into semantic chunks.
    
4.  Send each chunk to Gemini 2.5 Flash for analysis.
    
5.  Collect and merge all summaries into a final, polished output.
    
6.  Display the full summary in a human-friendly format.
    

📦 What This Project Solves
---------------------------

*   Handles long PDFs beyond LLM token limits
    
*   Prevents mid-sentence cuts using smart chunking
    
*   Produces structured, easy-to-read summaries
    
*   Ensures natural writing instead of robotic AI tone
    

📚 Use Cases
------------

*   Academic notes
    
*   Research paper analysis
    
*   Business document summaries
    
*   Book breakdowns
    
*   Report simplification
    

🔒 Security Note
----------------

Your API key is not stored inside the notebook when shared — **only you must enter it manually** for every new session.

📘 License
----------

MIT License — free to use and modify.
