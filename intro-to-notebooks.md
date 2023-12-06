# Using Jupyter Notebooks in Visual Studio Code

This guide will show you how to use Jupyter notebooks in Visual Studio Code. A Jupyter notebook is an open-source web application that allows creation and sharing of documents containing code, equations, visualizations, and narrative text.

## Steps

1. **Install the Python extension**: Install the Python extension for Visual Studio Code from the marketplace. This extension provides rich support for Python, including features such as IntelliSense, linting, debugging, code navigation, code formatting, Jupyter notebook support, refactoring, variable explorer, test explorer, snippets, and more!

2. **Open a Jupyter Notebook**: You can open a Jupyter notebook in VS Code by opening the command palette (`Ctrl+Shift+P`), then typing "Jupyter: Create New Blank Notebook". You can also open an existing notebook by navigating to the file in the Explorer and clicking on it.

3. **Choose a Kernel**: A Jupyter kernel is a set of files that point Jupyter to some means of executing code within the notebook. To choose a kernel in VS Code, you can click on the kernel status in the top right (it will say "No Kernel" when no kernel is selected), which will open the kernel picker. From there, you can select the kernel that matches the environment, language, and/or version you want.

4. **Run Cells**: In a Jupyter notebook, the unit of work is called a cell. You can run cells by clicking the "Run Cell" button at the top of each cell or by using the keyboard shortcut (`Ctrl+Enter`). The output will appear below the cell.

5. **Save and Checkpoint**: You can save your work at any time by clicking the save icon in the top left, or by using the keyboard shortcut (`Ctrl+S`). Jupyter also has a checkpoint feature that lets you save your progress and revert back to it if needed.

Note:
The ipykernel package is required for running Jupyter notebooks. This package provides the IPython kernel for Jupyter. If you select an environment on your system that does not have ipykernel installed and attempt to run the notebook, you will be prompted to install ipykernel
