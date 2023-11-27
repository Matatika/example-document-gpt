# Document Loader

## Setup for local documents
1. Create a new workspace referencing this repository
1. Run the "Local local documents" pipeline

## Setup for remote documents
1. Upload the contents of `sample_documents` to a folder in Google Drive
1. Create a new workspace referencing this repository
1. Provide configuration for the "Load remote documents" pipeline
    1. Under the `gdrive` section, login with your Google account and authorize Matatika to access Google Drive
    1. Select the folder you uploaded the sample documents to
    1. Save the pipeline
1. Run the pipeline

---

Once the pipeline run completes, a dataset will have been created for each loaded document, with a description containing the parsed document content and tags representing the the source file path.
