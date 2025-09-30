<general_rules>
When creating or editing a section of the Jaguar F-Type manual, please adhere to the following guidelines to ensure consistency and readability across the entire document.

### Document Structure
- **Table of Contents**: Each section file must begin with a clickable table of contents. Use descriptive names for sections and include anchor links for easy navigation.
- **Section Organization**: Group related content into logical sections using a consistent heading hierarchy (##, ###, ####). Use section dividers (---) to visually separate major sections.
- **Content Flow**: Structure the content to flow from a general overview to specific procedures, followed by safety warnings and technical specifications.

### Formatting
- **Text**: Use bold for important terms and key information, and italics for emphasis. Do not use colons in section headers.
- **Lists**: Use bullet points for general information and numbered lists for step-by-step instructions. Ensure consistent indentation and spacing.
- **Warnings**: Highlight critical safety information using bold formatting and dedicated "Warning" or "Important" sections.

### Tools
- Use a Markdown editor with a live preview to verify formatting.
- Employ Markdown linting tools to maintain consistency.
</general_rules>

<repository_structure>
The repository is structured to manage the sections of the Jaguar F-Type manual.

- **`sections/`**: This directory contains all the individual sections of the manual as Markdown files. Each file corresponds to a specific topic (e.g., `brakes.md`, `airbags.md`).
- **`extraction_summary.md`**: This file provides a summary of the status of the files in the `sections/` directory, indicating which are correctly sized, which are too large, and which are missing.
- **`formatting_improvement_guide.md`**: This is a comprehensive guide on how to format the Markdown files and is the source for the general rules.
</repository_structure>

<dependencies_and_installation>
This is a documentation-focused repository and does not have a formal dependency management system (e.g., `package.json`, `requirements.txt`). The only "dependencies" are standard Markdown editing tools.

- **Markdown Editor**: A text editor with Markdown support and live preview is recommended.
- **Markdown Linter**: A tool to enforce consistent Markdown formatting is suggested.
</dependencies_and_installation>

<testing_instructions>
Testing in this repository is a manual quality control process to ensure the documentation is accurate, consistent, and easy to navigate.

- **Link Checking**: Verify that all internal links in the table of contents and cross-references are working correctly.
- **Formatting Validation**: Ensure that the formatting of each section is consistent with the guidelines in `formatting_improvement_guide.md`.
- **User Experience Review**: Check that the table of contents is complete, navigation is intuitive, and information is easy to find.
</testing_instructions>

<pull_request_formatting>
+To ensure consistency and clarity, please follow these guidelines when submitting a pull request.
+
+### Title
+- The title should be concise and descriptive, summarizing the changes made.
+- Use a prefix to indicate the type of change, such as `feat:`, `fix:`, `docs:`, or `refactor:`.
+
+### Description
+- Provide a detailed description of the changes, including the motivation and context.
+- Use the following template:
+  - **Description**: A summary of the changes.
+  - **Related Issue**: Link to any related issues using `Closes #issue_number`.
+  - **Changes Made**: A bulleted list of the changes.
+
+### Linking to Issues
+- Use keywords in the description to automatically close related issues (e.g., `Closes #123`, `Fixes #456`).
</pull_request_formatting>
