# Solution of npm `Execution Policy Error`

After installing *node.js* if you run *npm (Node Package Manager)* you may can see this error message

![Error!!!](/GitHubImages/npmExecutionPolicyError.png)

This npm execution policy error occurs because Windows PowerShell has a security feature called **Execution Policies** that blocks scripts from running by default to prevent malicious activity.

When you try to run npm, PowerShell attempts to load the npm.ps1 script, but if your policy is set to *Restricted* (the default on many systems), it blocks this action.

## How to fix it

To fix it follow these steps:

1. Open PowerShell as Administrator
2. Check the Current Execution Policy

    **command : `Get-ExecutionPolicy`**

    If the result is *Restricted*, it means script execution is disabled on your system.

3. Set the Execution Policy to RemoteSigned

   **command : `Set-ExecutionPolicy RemoteSigned`**

   You might be prompted to confirm the change. *Type Y* and press Enter to confirm.

4. Repeat Step-2 to Verify the New Execution Policy

     **command : `Get-ExecutionPolicy`**, it will show: *RemoteSigned*.

## Result

After completing these steps close Administrator and open terminal and run this **command : `npm -v`**, if it's shows the current version of npm, then the *Execution Policies* is change to *RemoteSigned*.

### **Resources**

- [Resolving npm Execution Policy Error in PowerShell: A Step-by-Step Guide for Developers](https://dev.to/jackfd120/resolving-npm-execution-policy-error-in-powershell-a-step-by-step-guide-for-developers-32ip) by JAKER HOSSAIN on dev.to
