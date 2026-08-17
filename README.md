# Project Name

**React Tools And Agents**

## How to Run

Follow the steps below to run this project successfully.

### 1. Open the Project

Open the project folder in **Jupyter Notebook** or **VS Code**.

### 2. Create the `keys` Folder

Create a folder named:

```text
keys
```

inside the same directory as the Jupyter Notebook.

The folder structure should look like:

```text
Project Folder/
│
├── react_tools_and_agent_participants_copy.ipynb
│
└── keys/
    ├── .groq_api_key.txt
    └── .langsmith_api_key.txt
```

### 3. Add the Groq API Key

Create the following file inside the `keys` folder:

```text
.groq_api_key.txt
```

Paste your **Groq API key** inside this file.

### 4. Add the LangSmith API Key

Create the following file inside the `keys` folder:

```text
.langsmith_api_key.txt
```

Paste your **LangSmith API key** inside this file.

### 5. Install Required Packages

Open the Jupyter Notebook and look for the commented package installation commands, such as:

```python
# !pip install langchain
```

Uncomment the required `pip install` commands and run them to install the necessary dependencies.

For example:

```python
!pip install langchain
```

Install all the required packages mentioned in the notebook before running the project.

### 6. Run the Notebook

You can run the project using either:

* **Jupyter Notebook**
* **VS Code**

Open the `.ipynb` file and **run each cell sequentially from top to bottom**.

Make sure the required packages are installed and the API keys are correctly placed in the `keys` folder before running the complete notebook.

## Important

* Do **not** share or upload your API keys publicly.
* Do **not** commit the `keys` folder to GitHub if it contains real API keys.
* Make sure the API key files are present locally before running the notebook.
