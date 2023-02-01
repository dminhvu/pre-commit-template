# Pre-Commit Template for Python

This repository contains a pre-commit template for Python projects. It is intended to provide a framework for developers to quickly and easily establish a pre-commit hook to help ensure their code is properly formatted and free of easily preventable errors.


## Usage

This template uses **black** to format the Python code according to PEP 8. Additionally, **flake8** is used to detect errors related to bad coding style and potential bugs. Also, **isort** is an automated Python code formatter and allows you to sort your imports alphabetically and automatically. The pre-commit hook is set up to run these tools on all Python files in the repository.


To use this template, simply copy the `.pre-commit-config.yaml` file into your project's repository, and run the command pre-commit install. This will automatically set up the pre-commit hook for your repository.


## Customization

The pre-commit hook can be modified and customized by editing the `.pre-commit-config.yaml` file. The following parameters can be changed:



`exclude` - A list of file patterns to exclude from the pre-commit hook.

`args` - A list of arguments to pass to the black and flake8 commands.


## Conclusion

This pre-commit template provides an easy way to quickly set up a pre-commit hook in your Python project. It ensures that your code is properly formatted and free of easily preventable errors.