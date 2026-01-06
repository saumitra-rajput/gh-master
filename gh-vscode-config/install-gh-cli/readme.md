# GitHub CLI (gh) Installation

Note: The command is gh, not git gh.

## Steps:
- Install: Run in terminal.
    ```
    winget install --id GitHub.cli
    ```
    - Login: Run to connect your account via the browser. Make sure you set the global config username/mail
    
    
    ```
    gh auth login
    ``` 
### IMP
- To check global config
   
    First-Time Configuration
    Before you can start committing code, you must set your identity:
    >git config --global user.name "Your Name"


    >git config --global user.email "you@example.com" 

    run: 
    ```
    git config --list
    ```
    > list of global config
    ```
    git config --list | grep user
    ```
    > output table of username/mail

1.  Set your Identity
Uncomment the lines (remove the #) and enter your details so they look like this:
    ```
    ini
    [user]
            name = Saumitra Rajput
            email = example@mail.com

    ```
    > Use code with caution.

    > (Note: Use your keyboard arrows to move the cursor and delete the # characters.)

2. Save and Exit 

    (The "Nano" way)
    You might be inside the nano editor, use these shortcuts:


    Press Ctrl + O (Write Out) and press Enter to save the file.


    Press Ctrl + X to exit the editor and return to the command prompt.

3. ### Alternative (The Terminal way)
   ### Easy and safe way

    If editing the file is frustrating, you can just exit nano (Ctrl + X) and run these two commands in the terminal instead. 

    They do the exact same thing automatically:

    ```
    git config --global user.name "Saumitra Rajput"

    git config --global user.email "example@mail.com"
    ```

    >Use code with caution.


- How to verify it worked:
    Type to see your saved settings.
    ```
    git config --list
    ```
    List of global config
    ```
    git config --list | grep user
    ```
    output table of username/mail

- VS Code Tip: 

    Use the GitHub Pull Requests and Issues extension for a visual experience.