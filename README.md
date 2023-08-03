# PDF Upload and Display

This is a simple web application that allows users to upload a PDF file and display its pages as images. Users can select a page from the uploaded PDF and view its content as text.

## Deploy

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)


## Installation

Clone the repository to your local machine.
Install the required packages using `pip install -r requirements.txt`.

Run the app using streamlit run app.py.

## Usage

- Upload a PDF file using the file uploader.
- Select a page from the uploaded PDF using the selectbox.
- The selected page will be displayed as an image in the first column.
- The content of the selected page will be displayed as text in the second column.

## Dependencies

- streamlit
- pdf2image
- PyPDF2
- Pillow

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

This project was inspired by the Streamlit Gallery and the PyPDF2 documentation.
Thanks to the developers of the streamlit and pdf2image packages for making this project possible.
