## Do I already have pip?

First, let's check whether you already have pip installed:

- Open a command prompt by typing `cmd` into the search bar in the Start menu, and then clicking on **Command Prompt**:

    ![Open a command prompt](images/cmd-prompt.png)

    If you are **not** using your own computer at home (for example, if you are using a computer on a school network), you may not see **Command Prompt** appear in the menu, or you may not be allowed to open it because you don't have administrator privileges. In that case, please speak to your network manager about whether your network allows the use of the command prompt to install Python software. If you are not permitted to use the command prompt, pass this guide to your network manager so they can install Python modules on your behalf.

- Type the following command into the command prompt and press <kbd>Enter</kbd> to see if pip is already installed:

    ```bash
    pip --version
    ```

- If pip is installed and working, you will see a version number like this:

    ![Open a command prompt](images/pip-working.png)

- If you do, you're ready to use pip to install any Python module you like by typing the following into a command prompt (replace `name-of-module` with the name of your module):

    ```bash
    pip install name-of-module
    ```

- If you don't see a version number and instead get an error message, continue working through this guide.
