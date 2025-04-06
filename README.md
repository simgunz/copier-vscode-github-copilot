# GitHub Copilot Prompts for VSCode

A [Copier](https://copier.readthedocs.io/) template to quickly set up GitHub Copilot prompts for your VSCode Python projects. This template provides a set of predefined GitHub Copilot prompts optimized for Python development in Visual Studio Code, helping you get more relevant and accurate suggestions from GitHub Copilot.

## Requirements

- [Copier](https://copier.readthedocs.io/) (install with `pip install copier` or `uv tool install copier`)
- Visual Studio Code with GitHub Copilot extension

## Usage

To use this template, run the following command in your project directory:

```bash
copier copy https://github.com/simgunz/copier-vscode-github-copilot .
```

After initializing your project, please read the README.md file in the `.github/` directory for instructions on setting up the project plan prompts for your project.

## Updating the Template

If you've already generated a project using this template and want to update it with the latest changes from the template, you can use the following command:

```bash
copier update -a .copier-answers.prompts.yml
```

This will update your project with any new or modified files from the template while preserving your customizations. Copier will ask you to confirm any changes before applying them.

## License

See [LICENSE](LICENSE) file for details.

