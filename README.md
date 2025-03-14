# Invoice Extraction with OCR

**License:** MIT  
**Platform:** UiPath RPA

This repository provides an UiPath automation solution to solve the Invoice Extraction challenge. It leverages Optical Character Recognition (OCR) to capture essential information from invoices and save it into a CSV file.

## Prerequisites

- UiPath Studio
- UiPath Assistant
- UiPath Automation Cloud (optional for deployment)

### Challenge Details

The objective of this challenge is to develop a workflow that processes each row of the invoice table, downloads the corresponding invoices, and extracts the following critical data:

- **Invoice Number**
- **Invoice Date**
- **Company Name**
- **Total Due**

The extracted data will be saved in a CSV file, which should include the invoice ID and Due Date from the table, for invoices where the Due Date is today or overdue. The CSV file format must match exactly as in the provided sample with no discrepancies in the order, formatting, or data.

### Workflow Process

1. Use OCR to extract important details (Invoice Number, Date, Company Name, Total Due) from each invoice.
2. Only process invoices where the Due Date is today or in the past.
3. Create a CSV file containing the extracted data along with the table ID and Due Date, maintaining the specified format.
4. Upload the CSV file once the extraction is complete.

**Note:** The countdown for this challenge starts once the *Start* button is clicked and finishes once the CSV is uploaded. You may experiment with the table before starting the process without any penalties.

### Sample CSV Format

Ensure your output CSV file matches the format shown in the sample. Invoices will follow a fixed layout, and the CSV should not deviate from the sample in any way.

For a demonstration of the solution, check the video below:

- [Watch the RPA Invoice Extraction Demo](https://youtu.be/6FqmYb5xFcM)

> **Important:** As of 12 April 2024, the server for rpachallenge.com is not functioning properly and will always show a failure status, regardless of the correctness of the uploaded file. You may ignore the scoring provided by the challenge website.

---

## Installation

Make sure your system fulfills the requirements for UiPath software as outlined in the official [UiPath documentation](https://docs.uipath.com).

### UiPath Tools Required

- **UiPath Studio**
- **UiPath Assistant**
- **UiPath Automation Cloud** (optional for deployment)

### Steps for UiPath Studio Installation:

1. Download and install UiPath Studio from [here](https://www.uipath.com/start-trial).
2. Follow the instructions in the [UiPath Studio Documentation](https://docs.uipath.com/studio/docs).

### How to Connect to UiPath Automation Cloud:

1. Sign in to your UiPath Automation Cloud account.
2. Link your local machine to the cloud for workflow deployment.

---
## Usage

To execute the RPA workflow locally, follow these steps:

1. Download or clone this repository.
2. Open **UiPath Studio**.
3. Open the `Main.xaml` file from the downloaded repository.
4. Click **Run** to initiate the automation.

---

## Acknowledgements

A big thank you to the UiPath community for providing resources, tutorials, and a collaborative platform for learning and growing in the field of RPA.

---

## License

This project is licensed under the **MIT License**, which allows you to freely modify, distribute, and use the code for your own projects.

--- 
