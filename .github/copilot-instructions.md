<!-- Use this file to provide workspace-specific custom instructions to Copilot. For more details, visit https://code.visualstudio.com/docs/copilot/copilot-customization#_use-a-githubcopilotinstructionsmd-file -->
- [x] Verify that the copilot-instructions.md file in the .github directory is created.

- [x] Clarify Project Requirements
	- Project type: Python Streamlit application for resume-to-cover-letter generation

- [x] Scaffold the Project
	- Created main project structure with app.py, requirements.txt, README.md, and .env.example
	- Set up .vscode/tasks.json for running the Streamlit app

- [x] Customize the Project
	- Added comprehensive resume-to-cover-letter application with free API integration
	- Implemented Hugging Face API support with local template fallback
	- Enhanced user guidance and smart input validation

- [x] Install Required Extensions
	- No specific extensions required for this Python project

- [x] Compile the Project
	- Installed Python dependencies: streamlit, python-docx, pypdf, docx2txt, rapidfuzz, requests, python-dotenv
	- All dependencies successfully installed and verified

- [x] Create and Run Task
	- Created VS Code task "Run Streamlit App" using `python -m streamlit run app.py`
	- Task configured for background execution

- [x] Launch the Project
	- Ready to launch with: `python -m streamlit run app.py`
	- App includes free API options and comprehensive user guidance

- [x] Ensure Documentation is Complete
	- README.md contains comprehensive setup instructions and usage guide
	- .env.example provides template for environment variables
	- GitHub repository created and code pushed successfully

## Project Summary

This is a **Resume to Cover Letter Generator** built with Streamlit that:

### Key Features:
- **Free AI Integration**: Uses Hugging Face free API with local template fallback
- **Smart File Processing**: Supports PDF, DOCX, and TXT resume formats
- **Enhanced User Guidance**: Provides input validation, tips, and keyword analysis
- **Export Options**: Download as DOCX or copy to clipboard
- **Professional Templates**: Multiple tone options (Professional, Enthusiastic, Conversational)

### Technology Stack:
- **Frontend**: Streamlit for web interface
- **AI/ML**: Hugging Face Transformers API (free tier)
- **Document Processing**: pypdf, python-docx, docx2txt
- **Text Analysis**: rapidfuzz for keyword matching

### Setup Instructions:
1. Install dependencies: `pip install -r requirements.txt`
2. (Optional) Get free Hugging Face token and set `HUGGINGFACE_API_TOKEN`
3. Run app: `python -m streamlit run app.py`

### Repository:
- **GitHub**: https://github.com/beingarjun/resume-to-cover-letter
- **Owner**: beingarjun
- **Status**: Public repository, ready for contributions

<!--
## Execution Guidelines
PROGRESS TRACKING:
- If any tools are available to manage the above todo list, use it to track progress through this checklist.
- After completing each step, mark it complete and add a summary.
- Read current todo list status before starting each new step.

COMMUNICATION RULES:
- Avoid verbose explanations or printing full command outputs.
- If a step is skipped, state that briefly (e.g. "No extensions needed").
- Do not explain project structure unless asked.
- Keep explanations concise and focused.

DEVELOPMENT RULES:
- Use '.' as the working directory unless user specifies otherwise.
- Avoid adding media or external links unless explicitly requested.
- Use placeholders only with a note that they should be replaced.
- Use VS Code API tool only for VS Code extension projects.
- Once the project is created, it is already opened in Visual Studio Code—do not suggest commands to open this project in Visual Studio again.
- If the project setup information has additional rules, follow them strictly.

FOLDER CREATION RULES:
- Always use the current directory as the project root.
- If you are running any terminal commands, use the '.' argument to ensure that the current working directory is used ALWAYS.
- Do not create a new folder unless the user explicitly requests it besides a .vscode folder for a tasks.json file.
- If any of the scaffolding commands mention that the folder name is not correct, let the user know to create a new folder with the correct name and then reopen it again in vscode.

EXTENSION INSTALLATION RULES:
- Only install extension specified by the get_project_setup_info tool. DO NOT INSTALL any other extensions.

PROJECT CONTENT RULES:
- If the user has not specified project details, assume they want a "Hello World" project as a starting point.
- Avoid adding links of any type (URLs, files, folders, etc.) or integrations that are not explicitly required.
- Avoid generating images, videos, or any other media files unless explicitly requested.
- If you need to use any media assets as placeholders, let the user know that these are placeholders and should be replaced with the actual assets later.
- Ensure all generated components serve a clear purpose within the user's requested workflow.
- If a feature is assumed but not confirmed, prompt the user for clarification before including it.
- If you are working on a VS Code extension, use the VS Code API tool with a query to find relevant VS Code API references and samples related to that query.

TASK COMPLETION RULES:
- Your task is complete when:
  - Project is successfully scaffolded and compiled without errors
  - copilot-instructions.md file in the .github directory exists in the project
  - README.md file exists and is up to date
  - User is provided with clear instructions to debug/launch the project

Before starting a new task in the above plan, update progress in the plan.
-->