# Cotiviti_Intern
1. **Content Summarization with Custom Clinical Policy** (`content_summarization_poc1.ipynb`):
   - This notebook demonstrates the use of a custom clinical policy document to generate summaries using the BART model. The model has been tailored to handle the specific content structure and language of clinical policies.

2. **Content Summarization with Pre-defined Dataset** (`content_summarization_poc2.ipynb`):
   - In this notebook, the `guidelines` dataset from the Hugging Face library is utilized. The `facebook/bart-base` model is employed for conditional text generation. Additionally, the TF-IDF (Term Frequency-Inverse Document Frequency) method is used for summary generation, providing a comparison between deep learning-based and traditional summarization techniques.

3. **Content Comparison and Similarity Analysis** (`content_comparison.ipynb`):
   - This notebook focuses on extracting text data from clinical policy PDFs using the PyPDF library. The extracted text is then analyzed for similarities between documents using cosine similarity metrics, enabling a quantitative comparison of content across different policies.
