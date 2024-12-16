# Visual Studio Code with GitHub Copilot Demonstration Script

This script demonstrates the capabilities of GitHub Copilot in Visual Studio Code.

## October 2024 (version 1.95)

- [October 2024 (version 1.95)](https://code.visualstudio.com/updates/v1_95)

### [Copilot Edits](https://code.visualstudio.com/updates/v1_95#_start-a-code-editing-session-with-copilot-edits)

1. Open `Copilot Edits`

![Image](https://github.com/user-attachments/assets/381f9e16-7e09-4da3-bfe8-3090aba8e338)

2. Add Owner related classes

Add the following files to working set:

- `Owner.java`
- `OwnerController.java`
- `OwnerRepository.java`

3. Input the following prompt:

```text
I want to add a attribute to Owner class which is Age. And I want to add APIs and their endpoints to operate Owner class with age as a key.
```

<details><summary>Prompt sample</summary>
<img src="https://github.com/user-attachments/assets/9b7faed3-3caf-4b23-989d-b7611cfea18b">
</details>

<details><summary>Copilot Answer sample</summary>
<video src="https://github.com/user-attachments/assets/07cdde99-167d-40d2-8189-12a9451a85ff" controls="true"></video>
</details>

### [Copilot Chat in Secondary Side Bar](https://code.visualstudio.com/updates/v1_95#_chat-in-the-secondary-side-bar)

Originally you can found the GitHub Copilot Chat view in the primary side bar. Now you can see it in the secondary side bar as a default.

![Image](https://github.com/user-attachments/assets/acdea5ea-b8cb-4945-a0d3-1d097ff60010)

#### Command Center

In the case of Command Center:

![Image](https://github.com/user-attachments/assets/030847a6-6d56-4f69-bdf4-062e3cf3cb81)

👇

![Image](https://github.com/user-attachments/assets/39541db2-4cd5-4dc5-95b2-3d1c82580acf)

👇

![Image](https://github.com/user-attachments/assets/5522eb77-2d67-44e4-a1e9-d00be46fd7d5)

#### Keyboard Shortcuts

In the case of Keyboard Shortcuts:

- `Ctrl` + `Alt` + `I` to open the Copilot Chat

### [Copilot code reviews](https://code.visualstudio.com/updates/v1_95#_copilot-code-reviews)

You can delegate code reviews to GitHub Copilot to review changes, rather than human reviewers.

- There are two ways to use Copilot code review in VS Code:
  - Review selection
    - Select the code you want to review
     `Copilot` > `Review and Comment` from the **Editor Context Menu**
    - `GitHub Copilot: Review and Comment` command from the **Command Palette**
  - Review Changes
    - Select the `Copilot Code Review button` in the **Source Control view**

1. Open `Copilot Edits`

2. Add Owner related classes

Add the following files to working set:

- `Owner.java`
- `OwnerController.java`
- `OwnerRepository.java`

3. Input the following prompt:

```text
I want to add a attribute to Owner class which is Age. And I want to add APIs and their endpoints to operate Owner class with age as a key.
```

4. Accept the Copilot suggestion

5. Select Source Control view

6. Select the `Copilot Code Review` button

![Image](https://github.com/user-attachments/assets/e15481de-d09c-4a77-987a-caa41e27ceff)

👇

![Image](https://github.com/user-attachments/assets/7e07cc5e-18a2-4521-be93-db7156ae0894)

### [Automatic chat participant detection](https://code.visualstudio.com/updates/v1_95#_automatic-chat-participant-detection)

You might have seen chat participants in the Copilot Chat, like following:

![Image](https://github.com/user-attachments/assets/acc246cb-e65c-4dff-95af-0a6c91197e27)

Originally, `Chat Participant` had to explicitly specify which one to add, but now the context is interpreted and chat participant is automatically added as needed.

1. Open `Copilot Chat`

2. Input the following prompt:

```text
How does this Spring boot application accept user requests and resond to them?
```
<details><summary>Copilot Answer sample</summary>
<img src="https://github.com/user-attachments/assets/a7160f1e-dfe5-446b-83fe-56af0d627334">
</details>

### [Control current editor context](https://code.visualstudio.com/updates/v1_95#_control-current-editor-context)

Copilot Chat has always included the currenlty opened file or your currenlt selection. But sometimes, when you ask a question that is not about your current editor, including this context might affect how the model interprets your question.

You can hide your current visible file with ![Image](https://github.com/user-attachments/assets/f886428c-e611-4e2a-8240-9e8cdfca33b6)

![Image](https://github.com/user-attachments/assets/74a72649-4923-4941-9ba7-769c8550147b)

In the case of hiding the current file:

![Image](https://github.com/user-attachments/assets/ff8c2f7a-d147-485f-a8fe-29f3bd646e0b)

In the case of not hiding the current file, you always use the current file as a context:

![Image](https://github.com/user-attachments/assets/9352d62d-97de-446e-978a-9f89f37be798)

### [Interactive workspace symbol links](https://code.visualstudio.com/updates/v1_95#_interactive-workspace-symbol-links)

Copilot Chat generates links to symbols in your workspace. You can click on these links to navigate to the symbol in the editor. And also you can drag and drop the link to the editor to insert the symbol.

1. Open `Copilot Chat`

2. Input the following prompt:

```text
@workspace Please explain ckasses and methods related to Owners.
```

3. Drag a simbol

![Image](https://github.com/user-attachments/assets/68fee647-3b5a-49d2-bfc2-9609a4e3a7b2)

4. Drop a simbol to the editor

![Image](https://github.com/user-attachments/assets/30622ebb-43da-4cc9-9cc6-cc5694616bc1)

5. Right click on a simbol

- ![Image](https://github.com/user-attachments/assets/085ff93d-2480-452e-b33d-9633c0f36930)

6. Click on a simbol

<video src="https://github.com/user-attachments/assets/42b01235-a62b-4ac8-8ffd-94902c1195a0" controls="true"></video>

### [Fix using Copilot action in the Problem hover](https://code.visualstudio.com/updates/v1_95#_fix-using-copilot-action-in-the-problem-hover)

You can use Copilot to fix problems in your code directly from the problem hover.

1. Open any file, which includes a problem. (In this case, `PetTypeFormatter.java`)

2. Hover over the problem

<video src="https://github.com/user-attachments/assets/1f149536-6b0d-45e2-ae5d-36dbaf275fde" controls="true"></video>

### [Workspace indexing](https://code.visualstudio.com/updates/v1_95#_workspace-indexing)

You can start indexing with the command `GitHub Copilot: Build Local Workspace index` from the Command Palette.

- ![Image](https://github.com/user-attachments/assets/eb7ab966-7547-4a43-9e70-c79f7444313c)

### [Sort by relevance in Semantic Search (Experimental)](https://code.visualstudio.com/updates/v1_95#_sort-by-relevance-in-semantic-search-experimental)

<video src="https://github.com/user-attachments/assets/e9dccd05-91ac-4226-9758-a9211d31cc83" controls="true"></video>

### [Copilot extensibility](https://code.visualstudio.com/updates/v1_95#_copilot-extensions-showcase)

Copilot extensions showcase

|*Extension*|*Links*|
|**GitHub Pull Requests**|[Marketplace](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)|
|**Web Search for Copilot**|[Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-websearchforcopilot), [source code](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-websearchforcopilot)|
|**MermAId diagram generation with Copilot**|[Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-vscode.copilot-mermaid-diagram)|
|**Data Analysis for Copilot**|[Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-copilot-data-analysis), [source code](https://github.com/microsoft/vscode-data-analysis-for-copilot)|
|**VS Code Commander**|[Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-commander)|
|**Vision for Copilot Preview**|[Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-copilot-vision)

#### GitHub Pull Requests


<img src="https://github.gallerycdn.vsassets.io/extensions/github/vscode-pull-request-github/0.103.2024121117/1733937976423/Microsoft.VisualStudio.Services.Icons.Default" width="200">

1. Open VS Code **Settings**

2. Find `Extensions` > `GitHub Pull Requests`

3. Enable followings:
    - **Experimental: Chat**
    - **Experimental: Notifications View**
    - **Experimental: Use Quick Chat**

![Image](https://github.com/user-attachments/assets/9d846dd8-512b-4d70-80c0-02aa8a6d41c0)

Now then you can use GitHub Pull Requests chat participant `@githubpr` to ask about issues.

4. Open `Copilot Chat`

5. Input the following prompt:

```text
@githubpr Find issues which are labeled as "demo".
```
<details><summary>Copilot Answer sample</summary>
![Image](https://github.com/user-attachments/assets/c9bbc44e-8ccf-49ba-8df0-2282e8e4e84f)
</details>

#### Web Search for Copilot

![Web Search for Copilot](https://ms-vscode.gallerycdn.vsassets.io/extensions/ms-vscode/vscode-websearchforcopilot/0.1.2024121201/1733995405382/Microsoft.VisualStudio.Services.Icons.Default)

#### MermAId diagram generation with Copilot

![MermAId diagram generation with Copilot](https://ms-vscode.gallerycdn.vsassets.io/extensions/ms-vscode/copilot-mermaid-diagram/0.0.2024121201/1733994726632/Microsoft.VisualStudio.Services.Icons.Default)

#### VS Code Commander

![VS Code Commander](https://ms-vscode.gallerycdn.vsassets.io/extensions/ms-vscode/vscode-commander/0.2.0/1730285492202/Microsoft.VisualStudio.Services.Icons.Default)


#### Vision for Copilot Preview

![Vision for Copilot Preview](https://ms-vscode.gallerycdn.vsassets.io/extensions/ms-vscode/vscode-copilot-vision/0.2.2024111316/1731516453399/Microsoft.VisualStudio.Services.Icons.Default)
