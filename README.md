# Accounting Download  

1. [Download](https://github.com/yunis-ali/accounting-download/raw/main/Setup_2.0.32.0_Test.zip) and Unzip folder    
2. Install `.cer` certificate on the local machine under `Trusted Root Certification Authorities` (you have to find the store manually during installation)  
3. Install `.appxbundle` 

## Troubleshoot  

It has never loaded  
Go to `MyDocuments/HGIT-Accounting` and delete file `Accounting-latest`, a new file will be generated automatically.  
  
It loaded yesterday but not today  
Go to `MyDocuments/HGIT-Accounting` and delete file `Accounting-latest`. Delete file `Accounting-<todays date>`. Copy and paste Yesterdays file and rename it to `Accounting-latest`.

## ChangeLog

Auto generate change log  
`git log --pretty="- %s" > CHANGELOG.md`