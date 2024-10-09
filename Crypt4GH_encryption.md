# Crypt4GH Encryption


------------------------
## Quick Step Overview

1. Import bash script and public key
2. (If Applicable) - Make the script executable 
3. Run the bash script and enter the input and ouptut directory paths

------------------------

## Step 1. Import bash script and public key

Make sure to import the *encrypt_all.sh* script and the corresponding public key for your encryption (ingestion.pubkey.pub).

## Step 2. (If Applicable) - Make the script executable

If the bash script is not running properly, make it executable by running: 

```bash

   chmod +x encrypt_all.sh
```

## Step 3. Run the bash script and enter the input and ouptut directory paths

Indicate the input directory with the files that need to be encrypted and the output directory where you want the encrypted files to be placed. For the public key, please ONLY use the ingestion.pubkey.pub file. This file contains the public key used by EGA to be able to decrypt and ingest the files during the submission process.

![screenshot](images/Prompts.png)
