"# Penda Med Data Analytics Project 2022" 

This is a description of the project and the dataset: 

Table Name: 
1. Visit Table
-This table contains information and details for medical visits at Penda Health
Columns: VisitCode (A unique ID assigned to each clinical visit), PatientCode (A unique ID assigned to each patient), VisitDateTime (Date on which the visit occurred), MedicalCenter(The medical centre at which the visit occurred), VisitCategory (The nature of visit whether in person or vitual), Payor(The name of the payor for the visit. "Cash" means the patient paid for themselves, while Insurance means the bill was paid by an Insurance company) NPS Score(Score provided by patient that rates their satisfaction level with the visit. Score range is 0-10)

2. Invoice Tbl - This table contains information about the total billed amount for each visit. Note: Multiple invoices can be issued against one visit
Columns: amount (The total amount invoiced for the visit)

3. Diagnosis Tbl - This table contains information about the diagnosis for each visit. Note: One visit can have multiple diagnoses
Columns: Diagnosis (The nature of illness recorded for each visit)

Rules:

1. All results were ROUNDed DOWN to the nearest INTEGER.
2. For purposes of this project, the least possible invoice amount for any insurance visit was 100. Any amount less than 100 was overriden to 100. This cleaning part of my analysis is detailed in the code.

## Installation

- Step 1: Clone the repository.
- Step 2: Install the required dependencies.
- Step 3: Run the project.

## Usage

To use this project and analyze the dataset, you may follow the steps below:

### Prerequisites

- Python 3.6.x or later installed on your computer
- Jupyter Notebook or JupyterLab installed (I have Anaconda installed and found it useful and hassle-free since all the analytics IDEs are there)

### Dataset

1. Clone my repository to your local machine using the following command: git clone https://github.com/JosephMurage/Penda-Health-Analytics-Project-2022.git

2. Navigate to the project directory: cd project-directory

3. Download the dataset file here:
 - Dataset File: 

You can download the dataset files by clicking on the links above and saving them to the `dataset` directory in your project.

### Analyzing the Data

1. Launch Jupyter Notebook or JupyterLab.

2. Open the `Penda Health Patient Data Analytics 2022.ipynb` notebook in Jupyter.

3. Follow through and see how I analyzed the dataset. The notebook includes examples of various data analysis tasks, such as exploration, filtering, aggregations, visualizations, etc.

4. Feel free to modify the code or add additional analysis as needed.

### Dependencies

- The project uses Python libraries such as Pandas and PrettyTables. Ensure that these dependencies are installed before running the code.

