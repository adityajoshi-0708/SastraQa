# ShastraQA: Multilingual Question Generation from PDF Texts using Advanced NLP Models

**ShastraQA** is a project designed to generate contextually relevant questions in multiple languages, including Hindi, English, and Sanskrit, from text extracted from PDFs. The system leverages advanced Natural Language Processing (NLP) techniques to streamline question generation for educational and research purposes.

## Features
- Extracts text from PDFs efficiently.
- Supports multilingual question generation (Hindi, English, Sanskrit).
- Integrates advanced NLP models for contextual question generation.
- Provides highly accurate and coherent questions using AI models like Meta LLaMA.
- Easy-to-use system for educators and researchers.

## Tools and Technologies
- **Python**: Main programming language.
- **pdfplumber**: For extracting text from PDFs.
- **LangChain**: For managing LLaMA model integration.
- **Google Translator API**: For multilingual support and translation.
- **Hugging Face Transformers**: For NLP-based question generation.
- **Scikit-learn**: For cosine similarity calculations.
- **NVIDIA LLaMA Models**: For robust and advanced language modeling.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ShastraQA.git
   cd ShastraQA
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure you have API keys for:
   - **Google Translator** (for translation)
   - **NVIDIA AI endpoints** (for question generation).

## Usage

1. Place your PDF files in the appropriate directory (e.g., `input/`).
2. Run the main script:
   ```bash
   python generate_questions.py
   ```
3. Follow the prompts to:
   - Select the PDF file.
   - Choose the desired language for question generation.
4. View the output questions saved in the `output/` folder.

## How It Works
1. **PDF Text Extraction**: Extracts clean text from the PDF using `pdfplumber`.
2. **Text Translation**: Converts non-English text into English using the Google Translator API.
3. **AI-Based Question Generation**: Processes the text with LLaMA or Hugging Face T5 models to create contextually relevant questions.
4. **Multilingual Output**: Translates generated questions into Hindi and Sanskrit for broader accessibility.

## Example

- **Input**: PDF containing excerpts from a Hindi book.
- **Output**: Contextually relevant questions in:
  - Hindi
  - English
  - Sanskrit

## Project Structure
```
ShastraQA/
│
├── input/               # Directory for input PDF files
├── output/              # Directory for generated questions
├── generate_questions.py # Main script for question generation
├── requirements.txt     # List of dependencies
└── README.md            # Project documentation
```

## Future Enhancements
- Adding support for more languages.
- Improved contextual understanding for complex texts.
- Interactive web interface for question generation.

## License
This project is licensed under the MIT License.

## Acknowledgments
- **Meta LLaMA Models** for advanced NLP capabilities.
- **Google Translator** for seamless multilingual translation.
- **Hugging Face** and **LangChain** for providing robust NLP pipelines.
```
