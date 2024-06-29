# Postman Code Execution Guide

This document provides a step-by-step guide to run the Postman code available on GitHub. 

## Prerequisites

- Git Bash
- VS Code Editor
- Postman

## Steps to Run the Postman Code

### 1. Clone the Repository

1. Open Git Bash or VS Code terminal.
2. Navigate to a directory on your desktop where you want to clone the repository. You can create a new directory or use an existing one.

    ```bash
    cd ~/Desktop/your-directory
    ```

3. Clone the GitHub repository using the following command. Replace `<git-repo>` with the actual URL of the GitHub repository.

    ```bash
    git clone <git-repo>
    ```

### 2. Open the Repository in VS Code

1. If you are using Git Bash, navigate to the cloned repository directory.

    ```bash
    cd your-repo-name
    ```

2. Open the repository in VS Code by running:

    ```bash
    code .
    ```

    Alternatively, you can open VS Code, then go to `File > Open Folder` and select the cloned repository directory.

### 3. Import the JSON File into Postman

1. Open Postman.
2. Click on the `Import` button located in the top-left corner.
3. In the `Import` window, click on `Choose Files` and navigate to the cloned repository folder.
4. Select the JSON file containing the Postman collection and click `Open`.
5. The Postman collection will be imported and displayed in the `Collections` tab.

### 4. Run the Collection Runner

1. In Postman, go to the `Collections` tab.
2. Select the imported collection.
3. Click on the `Run` button located next to the collection name. This will open the Collection Runner.
4. In the Collection Runner window, you can configure the run settings such as iterations, delay, and environment.
5. Click on the `Start Run` button to execute the requests in the collection.

## Additional Tips

- Ensure that your Postman environment variables are correctly set if your collection uses any.
- Review the pre-request scripts and tests in the collection to understand their functionality.

By following these steps, you will be able to successfully run the API collection available in the GitHub repository.

## Troubleshooting

- If you encounter any issues during cloning, ensure that Git is installed and configured correctly on your machine.
- Make sure that Postman is updated to the latest version to avoid compatibility issues with the JSON file.

For any further assistance, refer to the documentation or open an issue on the GitHub repository.
