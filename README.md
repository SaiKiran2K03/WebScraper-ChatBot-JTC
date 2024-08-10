# Web Scraping Chatbot for Josh Technologies Group

## Overview

This project implements a chatbot that utilizes web scraping and OpenAI's language model to provide accurate information to users. The chatbot is designed to enhance communication within the Josh Technologies Group by offering quick and interactive responses based on data gathered from various online sources.

## Files

- **WebScrapingChatBotJTC.ipynb**: Jupyter notebook containing the main code for the chatbot, including web scraping and model integration.
- **cleaned_website_words.txt**: A text file containing processed and cleaned words extracted from the scraped websites.
- **ngrams.txt**: A file containing n-grams derived from the website content to help improve the chatbot's understanding and response generation.
- **website_words.txt**: The raw text file with words obtained from the initial web scraping process.

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Install Dependencies**:
   Make sure you have Python installed, then install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:
   Open the Jupyter notebook:
   ```bash
   jupyter notebook WebScrapingChatBotJTC.ipynb
   ```
   Follow the instructions within the notebook to run the chatbot.

## Usage

Once the chatbot is running, you can interact with it by asking questions related to the information scraped from the websites. The chatbot will respond based on the data processed from the scraped content.

## Contributing

Feel free to submit issues or pull requests if you have suggestions for improvements or new features!

## License

This project is licensed under the MIT License - see the LICENSE file for details.
