# Activate Windows with PowerShell

This method demonstrates how to activate Windows using PowerShell in administrator mode.

### Steps to Activate Windows:

1. Open **PowerShell** as an administrator:
   - Press `Win + S`, type "PowerShell," then right-click on **Windows PowerShell** and select **Run as administrator**.

2. Run the following command:

   ```powershell
   irm https://get.activated.win | iex
   ```

   - `irm` is short for `Invoke-RestMethod`, which fetches the script from the given URL.
   - `iex` is short for `Invoke-Expression`, which executes the fetched script.

3. Press **1** on your keyboard to select **HWID Activation** (Permanent Windows activation).

4. Follow the on-screen instructions and wait for the process to complete.

5. Restart your PC after activation to apply the changes.

---

### Notes:

- Ensure you have a stable internet connection while running the command.
- This method requires administrative privileges to function.
- Always verify the source of scripts before executing them to ensure they are safe and trustworthy.
