# ExportPDFusingWORD_COM
Export the content from the web page to PDF using Microsoft word components.

There are roughly two ways to export PDF from the website.

1. Using the iTextSharp library method has the advantage of very flexible deployment of content.

2. To use Microsoft WORD components for conversion, you need to export the content into a doc file first, and then convert it into a PDF for download.

Assuming that your original content is already a formatted HTML file, it is strongly recommended to use the second method.

Note: However, WORD must be installed on the server before components can be used, and please pay attention to the permissions for component calls.
