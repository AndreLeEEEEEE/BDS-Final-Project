# BDS-Final-Project

How to execute the project's program:

1. Download the dataset in Excel form from this website, https://www.energyinst.org/statistical-review/resources-and-data-downloads. Look for the Excel file under the "Key reports" section.

2. In the same directory you placed main.ipynb and requirements.txt in, create a folder called "data". Within the "data" folder, create a folder called "dataset".

3. Put the downloaded Excel file into the "dataset" folder.

4. Your current directory should look like this.


```
├── main.ipynb
├── README.md
├── requirements.txt
└── data
    └── dataset
        └── Statistical Review of World Energy Data.xlsx
```

5. The project dependencies are found in requirements.txt. They can be installed by entering `pip install -r requirements.txt` into Command Prompt on Windows. Speaking of which, please try to run this project on Windows, I haven't tested this project on Mac. This project was made and executed using Python 3.10.6. This project was made and executed on Visual Studio Code. main.ipynb could be executed on any IDE that can run .ipynb files.

6. To execute the program, run all cells in main.ipynb sequentially. Essentially, run cells from top to bottom.
