# Azure Blob Storage File Uploader

This project demonstrates how to upload files to Azure Blob Storage using Python and the Azure SDK. Azure Blob Storage is used to store large amounts of unstructured data like images, text, or binary data.

## Features
- Connects to an Azure Blob Storage account.
- Uploads files from your local system.
- Lists files in the Blob Storage container.

## Prerequisites
- Python 3.x
- Azure Subscription (Free tier is fine)
- Azure Storage Account (you can create one during setup)
- Azure SDK for Python (`azure-storage-blob`)

## Setup Instructions
To get started with this project, follow the instructions provided in the [setup guide](setup_instructions.md).

## Usage
1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/azure-blob-storage-uploader.git
    cd azure-blob-storage-uploader
    ```

2. Install required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Update the `main.py` file with your Azure storage connection string and container name.

4. Run the script:
    ```bash
    python main.py
    ```

## License
