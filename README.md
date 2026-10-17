# GitHub & VS Code Setup Guide

1. [Extensions & GitHub Auth](#extensions--github-authentication)
2. [Workflow](#workflow)

## Extensions & GitHub Authentication

### Required Extensions

Before starting, make sure you have installed the following extensions in Visual Studio Code:

*   **Remote Repositories**
*   **GitHub Pull Requests and Issues**
*   **GitHub Repositories**

### GitHub Authentication

To authenticate your GitHub account in VS Code:

1. Click the **`> <`** icon in the bottom-left corner of VS Code.
2. Select **Open Remote Repository**.
3. Follow the on-screen prompts to complete authentication.

## Workflow

### Templates

You can connect any repository you prefer. To follow this specific workflow:

1. Create your template repository on GitHub.
2. Generate a new repository from your template by clicking **Use this template** > **Create a new repository**.
3. When selecting which repository to link in VS Code, choose the newly created repository.

### Connecting a Local Folder to an Existing Repository

1. Open the local folder in VS Code and mark it as a **Trusted Folder** when prompted.
2. Open the **Source Control** view from the left sidebar (or via `View` > `Source Control`).
3. Click **Initialize Repository**.
4. In the Source Control panel, navigate to `Repositories` > `[Folder Name]` > `...` (More Actions) > `Remote` > `Add Remote...` > `From GitHub`.
5. Select your target repository (see 3. in Templates) and name the remote `origin`.

If the repository was **empty**

6. Commit and push your changes (the default branch will be set to `main`).

Otherwise

6. Fetch and Pull.

