# VSCode Python Config

Creates config files with pre-defined settings for modern Python projects.  

The following files will be created in the local .vscode folder:

- settings.json: Best default settings for Python-related extensions
- launch.json: Debug config to debug the current Python file
- tasks.json: Task to run the current Python file

The following files will be created in the root directory:

- General IDE Files
  - .editorconfig: Standard file settings (line-feed, insert new-line, etc.)
  - .gitattributes: Gives attributes to pathnames
  - .gitingore: Specifies intentionally untracked files to ignore
- Python specific Files
  - .pre-commit-config.yaml: Tools to run on every git commit
  - requirements-dev.txt: List of python packages to install
  - pyproject.toml: General settings for: black, isort, mypy and ruff

**Note**: If one of these files already exists, they are overridden.

## How to use

Just run the command 'Generate Python Config Files' in VSCode's command palette.

## Settings

- ⚙️ Line Length: Max. line length for the tools (defaults to 120, Global Setting)
- ⚙️ Is Aggressive: If set to true, mypy, ruff and others will have activated most of its features (defaults to false, Global Setting)
- ⚙️ Python Target Version: Various tools can do different stuff based on the "minimal" python version for that project (defaults to 3.9)
- ⚙️ Formatting tool: The python formatter that should be used (defaults to black)

## Release Notes

Refer to the [CHANGELOG](CHANGELOG.md).

## License

Copyright (C) 2022-2023 Jan Schaffranek.  
Licensed under the [MIT License](LICENSE).

## Supporting the Work

Feel free to donate, such that I have more time to work on my VSCode extension*s*.

![PayPal QR Code](./media/QR-Code.png)

Or use the Link: <https://www.paypal.com/donate/?hosted_button_id=3WDK6ET99ZQCU>
