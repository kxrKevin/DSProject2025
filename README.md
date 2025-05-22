# Introduction

This repository contains the code used for 24/25 DS3000B's coursework for writing a data report on household spending on insurance for dissemination areas, with data provided by Environics.

# Set up

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd <project-directory>
   ```

3. Set up a virtual environment and `.env` file:

   ```bash
   python -m venv venv
   ```

   > Make a `.env` file and paste your absolute path to the csv file into the `.env` file: `SPENDPATH=<Insert path here>`

4. Activate the virtual environment:
   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS/Linux:

     ```bash
     source myenv/bin/activate
     ```

5. Install all necessary requirements:

   ```bash
   pip install -r requirements.txt
   ```

   > Note: whenever you update requirements and install new dependencies, make sure to run `pip freeze > requirements.txt` to update requirements

6. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

   This command will open a new tab in your default web browser, showing the Jupyter Notebook dashboard.

7. Create or open a notebook:
   - To create a new notebook, click on "New" and select "Python 3" (or another kernel if you have others installed).
   - To open an existing notebook, navigate to its location in the dashboard and click on the file name.

8. Develop your notebook:
   - Write and execute code in cells. You can also include markdown cells for documentation and explanations.
   - Use the toolbar to run cells, restart the kernel, and manage the notebook.

9. Save and export:
   - Save your work regularly using the save button or `Ctrl + S`.
   - You can export your notebook to various formats (e.g., HTML, PDF) via "File" > "Download as".

10. Shut down the notebook:
    - When you're done, you can shut down the notebook server by closing the terminal or command prompt where it's running.
    - Alternatively, you can shut down individual notebooks from the Jupyter dashboard by clicking "Shutdown" next to the notebook name.

11. Deactivate the virtual environment after using it:

    ```bash
    deactivate
    ```
