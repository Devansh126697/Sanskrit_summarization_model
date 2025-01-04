# Sanskrit_summarization_model


## Sanskrit Translation and Summarization Model

This project aims to build a sophisticated pipeline for translating and summarizing Sanskrit sentences into concise English outputs. The pipeline consists of two main components:

1. **Model 1: Sanskrit to Meaning Mapping**  
   The first model focuses on extracting English meanings for individual Sanskrit words from a preprocessed dataset. It utilizes a dictionary-based approach, where each Sanskrit word is mapped to its corresponding English meaning. In cases where a word is not found, the model assigns a placeholder, ensuring that the extraction process runs smoothly.

2. **Model 2: Summarization**  
   The second model takes the extracted meanings from Model 1 and generates a coherent, concise summary. It is fine-tuned to summarize even incomplete or noisy input, ensuring that the generated output is grammatically correct and contextually relevant.

### Project Workflow:
- **Data Extraction**: The data for Sanskrit words, transliterations, and meanings was initially extracted from an encoded PDF using `pytesseract` OCR. The dataset was then manually cleaned and preprocessed to ensure accuracy and consistency.
- **Model Integration**: Both models are integrated into a seamless pipeline, where Model 1 extracts meanings for each Sanskrit word in a sentence, and Model 2 generates a summary based on those meanings.
- **Ongoing Development**: While Model 1 is completed, Model 2 is currently being fine-tuned to ensure high-quality summarization results. The project is a collaborative effort with Amit Gupta Sir.

### Features:
- Efficient extraction of Sanskrit word meanings
- Handling of incomplete or missing data using placeholders
- Summarization of extracted meanings into concise English sentences
- Flexibility to handle noisy input and produce coherent summaries

### Technologies Used:
- **pytesseract** for OCR text extraction
- **Word2Vec/GloVe** (optional) for word embedding models
- **BART/T5** for summarization
- **Python** for implementation

### Future Enhancements:
- Expand the dataset to include more Sanskrit words and meanings
- Fine-tune Model 2 with additional training data for better summary generation
- Develop a user-friendly interface for real-time translation and summarization

This project is still under development, and further updates will be made as we progress towards the final implementation.

---
