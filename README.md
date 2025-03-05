# ASPX Gh0st Executor

ASPX Gh0st Executor is a powerful web-based tool that allows administrators to execute system commands, read and delete files, and navigate directories through an ASPX interface. This tool is secured with password authentication.

## 🚀 Features

- **Command Execution**: Run system commands directly from the browser.
- **File Deletion**: Delete specific files or folders within the current working directory.
- **File Reading**: View the content of any file in the active directory.
- **Directory Navigation**: Change the working directory and list contents.
- **Password Protection**: Requires an authentication parameter (`exec=ghost`) to access.

## 🔧 Installation

1. **Download the `gh0st.aspx` file**.
2. **Upload it to your web server** (e.g., `/inetpub/wwwroot/` or any accessible directory).

## 📖 Usage

### **Accessing the Tool**
Go to: http://yourwebsite.com/gh0st.aspx?exec=ghost

Replace `ghost` with the correct password set in the script.

### **Running Commands**
1. Enter a system command in the **command input field**.
2. Click **"Execute"** to run the command.
3. The output will be displayed in a **textarea**.

### **Security Features**
- Unauthorized users attempting to access without the correct password will see a **404 Not Found** error.
- The tool runs under the **IIS worker process**, which may have restricted privileges. If a command fails, check permissions.

## ⚠️ **Warnings & Disclaimer**
- **Use this tool for legal and authorized purposes only.**
- Running commands can be **dangerous** if misused. **Only use it if you know what you're doing**.
- The author is **not responsible** for any **misuse or damage** caused by this tool.
- Ensure that your **server is secured** to prevent **unauthorized access**.

