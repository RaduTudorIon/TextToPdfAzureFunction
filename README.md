# PdfConversion# Azure Function: TextToPdf

This Azure Function converts text to a PDF document.

## Functionality

The `TextToPdf` function takes a `text` parameter and generates a PDF document with the provided text. The PDF document is then returned as a downloadable file.

## Usage

To use this function, send a GET or POST request to the function endpoint with the `text` parameter set to the desired text. The function will generate a PDF document with the text and return it as a downloadable file.

Example request:
## Dependencies

This function requires the following dependencies:

- Syncfusion.Pdf
- Syncfusion.Pdf.Graphics
- Syncfusion.Drawing

Make sure to include these dependencies in your project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
