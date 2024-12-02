# PROMISE-Datasets

This repository contains datasets for software defect prediction. The datasets are organized into three main directories, each serving a specific purpose in the data processing workflow. Below is a detailed explanation of the content and structure:

## Contents

1. **Database**  
   - This folder contains the **original dataset**, which includes the original, unprocessed data collected for software defect prediction.  
   - The raw data serves as the starting point for all subsequent analysis and preprocessing steps.

2. **DatabaseClean**  
   - This folder contains the **cleaned dataset**, which is derived from the raw dataset after performing comprehensive data cleaning.  
   - Cleaning steps  include handling missing values, correcting inconsistencies, and removing redundant or irrelevant entries to ensure data quality.

3. **DatabasesProcess**  
   - This folder contains processed data based on the cleaned dataset.  
   - Specifically, it includes the **locations and labels of each source code file**. 

## Usage

- These datasets are intended to support research and experiments in software defect prediction.  
- Users can start with the `Database.zip`  for raw data analysis or directly use the `DatabaseClean.zip` and `DatabasesProcess.zip`  for preprocessed and structured data.

- If you use the **original dataset** (located in the `Database.zip` ), please cite the following paper:  
  **_Towards identifying software project clusters with regard to defect prediction._**

- If you use the **cleaned dataset** (`DatabaseClean.zip`) or the **processed dataset** (`DatabasesProcess.zip`), please cite **this repository**.

For questions or feedback, feel free to contact us of this project.

