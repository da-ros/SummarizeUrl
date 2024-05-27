
# Text Article Summarizer

This project is a simple web application for summarizing text articles from URLs. It is built using Streamlit and the OpenAI API.

## Features

- Summarize articles by providing a URL.
- Select between different OpenAI chat models.
- Easy-to-use interface with Streamlit.

## Installation

### Prerequisites

- Python 3.12+
- Streamlit
- OpenAI API key

### Clone the repository

```bash
git clone https://github.com/da-ros/SummarizeUrl.git
cd SummarizeUrl
```

### Install the required packages

```bash
pip install -r requirements.txt
```

## Usage

1. Obtain your OpenAI API key from [OpenAI](https://platform.openai.com/account/api-keys).

2. Run the Streamlit app:

```bash
streamlit run streamlit_app.py
```

3. Enter your OpenAI API key in the sidebar.

4. Select the OpenAI chat model you wish to use.

5. Enter the URL of the article you want to summarize.

6. Click the "Summarize" button to get the summary.

## File Structure

- `streamlit_app.py`: Main application file.
- `requirements.txt`: List of required packages.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Streamlit](https://streamlit.io/)
- [OpenAI](https://openai.com/)

---

