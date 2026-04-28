### Setup Guide 
1. Configure secrets in settings:
    AZURE_CREDENTIALS
    AZURE_SUBSCRIPTION_ID
    POSTGRES_NAME
    POSTGRES_PASSWORD
    SSH_PUBLIC_KEY
    STORAGE_ACCOUNT_NAME (only lowercase letter)
    VM_NAME
2. Deploy
3. Enable allow public access in storage account (environment config might be set to disabled by default)
4. Give yourself storage blob data contributor permissions
5. Upload raw data from this repo in storage account in raw data folder
6. Github actions: push jobs to queue
7. Give yourself permissions (storage queue data reader) to check whether jobs landed in queue storage
