# Install git on vsCode
This file can be used as reference to install git on vsCode.
Also to configure your vs code to work on git locally.


## Git: Installation & Environment Path

- Install via Terminal: Open PowerShell/CMD as Admin and run:

  ```winget install Git.Git.```

- OR Manual Install: Download from git-scm.com.
- Adding to Path (Manual):

  -  Search for "Edit the system environment variables" in Windows.
  - Click Environment Variables > Select Path > Edit.
  -  Add: C:\Program Files\Git\cmd and C:\Program Files\Git\bin.
- Verification: 

    Type in terminal.

    ```git --version```
    
     Restart VS Code after installation.


