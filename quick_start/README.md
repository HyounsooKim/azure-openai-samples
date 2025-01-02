# Hands-On Practice with Prompt Engineering Code

## Choosing a Development Environment for Practice
To ensure a smooth experience for these hands-on exercises, a `.devcontainer` environment is provided. If you prefer not to install Docker or an IDE on your PC, we recommend using `CodeSpace`.  
- If `Docker` is installed on your local PC, you can use VS Code to reopen in the DevContainer. This will create a container image in Docker that automatically installs the runtime and packages needed for the practice environment.  
- By leveraging GitHub’s `CodeSpace`, a container will run on a remote VM provided by CodeSpace, and you can begin development immediately via the browser-based VS Code interface provided by CodeSpace.  
- The testing has been verified with Python kernel version 3.11.4.

Note: `CodeSpace` provides free access to 15GB of storage and up to 120 hours/core of VM usage per month for individual GitHub accounts.  
- [CodeSpace Pricing](https://docs.github.com/en/billing/managing-billing-for-github-codespaces/about-billing-for-github-codespaces)

#### 1️⃣ Setting Up the .env File

Copy the `.env.sample` file to create a `.env` file, then save your Azure OpenAI, AI Search, and related resource API Key values before proceeding.  
If you modify the content of the `.env` file during practice, make sure to `restart` the kernel of that file or close and reopen the file before continuing.

#### 2️⃣ Practice Steps

The `01_Create_resource` step is pre-configured by the infrastructure administrator.  

As a developer, you can proceed with the code execution from step 02 to 15.  
For the hands-on practices, the verified Python kernel version is 3.11.4. Press `Shift + Enter` to execute the code.