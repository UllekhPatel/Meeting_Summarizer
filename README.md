# Meeting Summarizer

This project provides a solution for summarizing meeting transcripts using Natural Language Processing (NLP) techniques. The system processes meeting transcripts to generate concise summaries, offering both extractive and abstractive methods.

## Features

- **Transcription Handling**: The system can handle meeting transcripts in various formats.
- **Text Preprocessing**: Includes steps such as tokenization, stop-word removal, and stemming.
- **Summarization Techniques**:
  - **Extractive Summarization**: Identifies and extracts the most important sentences from the transcript.
  - **Abstractive Summarization**: Generates new sentences that capture the main points of the transcript.
- **Evaluation**: Uses the ROUGE metric to evaluate the quality of the summaries against reference summaries.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Meeting_Summarizer.git
   cd Meeting_Summarizer
   ```

2. Install the required Python packages:

   The project uses a few key libraries, including:

   ```bash
   pip install nltk rouge
   ```

   *(Note: Adjust this command if you add more dependencies or specific versions.)*

## Usage

1. Run the Jupyter notebook:

   ```bash
   jupyter notebook Meeting_Summarizer.ipynb
   ```

2. Follow the instructions in the notebook to input a meeting transcript and generate a summary.

## Functions

- **`preprocess_text(text)`**: Preprocesses the text by tokenizing, removing stop words, and stemming.
- **`extractive_summarization(text)`**: Generates a summary by extracting key sentences from the input text.
- **`abstractive_summarization(text)`**: Generates a summary by rephrasing the main ideas in the text.
- **`evaluate_summary(summary, reference_summary)`**: Uses the ROUGE metric to evaluate the generated summary against a reference summary.

## Example

Given a meeting transcript, the system produces a concise summary highlighting the key points discussed during the meeting.

```plaintext
Original Transcript: [Insert example text here]
Generated Summary: [Insert example summary here]
```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.
