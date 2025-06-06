## 🔁 Switching GitHub Accounts in VS Code

Follow these steps to remove old GitHub credentials and configure a new GitHub account in Visual Studio Code.

### 1. 🗑️ Remove Existing GitHub Credentials
- Open **Credential Manager** on Windows.
- Go to **Windows Credentials** tab.
- Locate and **remove** any entries related to `git:https://github.com`.

### 2. 🚪 Sign Out from VS Code GitHub Account
- Open **Visual Studio Code**.
- Click on the **Account icon** in the lower-left corner.
- Select **"Sign Out"** from the GitHub account listed.

### 3. 🔐 Sign In with a New GitHub Account
- Click on the **Account icon** again.
- Select **"Sign in with GitHub"**.
- Complete the authentication process in the browser.

### 4. ⚙️ Set Git Commit Author Info
Configure Git with your new account details (this only affects commit metadata, not authentication):

```bash
git config --global user.name "your-github-username"
git config --global user.email "your-email@example.com"
```


### 5. when new commit `login using browser`