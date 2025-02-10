# Mathable numbers recognision

## Libraries Required to Run the Project

- **Python version**: 3.9.13  
- **Jupyter version**: 1.1.1  
- **numpy**: 1.26.4  
- **opencv-python**: 4.10.0.84  
- **os** and **copy**: These libraries have the same version as Python.  

---

## How to Run the Project

1. **Main Notebook**:  
   - Open the `task_1_2_3.ipynb` file.  
   - In the last cell, you will find the logic for generating the solution file:  
     - On **line 13**, there is a variable `fisier_date`. Replace this with the path to the input data file.  
     - On **line 14**, there is a variable `game_numbers`. Replace this with the number of games (default is 4).  

2. **Execution**:  
   - Running the entire `task_1_2_3.ipynb` file will execute all tasks (1, 2, and 3).  
   - The predictions and scores will be saved in a folder named `351_Pirvulescu_Daria`.  

3. **Important Notes**:  
   - If the project is run more than once, ensure that the `351_Pirvulescu_Daria` folder is deleted before running it again. This is because the score file is created by appending, and running the project multiple times without deleting the folder will result in duplicate entries.  

---

## Additional Files

- **templates.ipynb**:  
   - This file does not need to be executed. It serves as proof of the preprocessing of the templates attached in the `templates` folder.  

---

## Summary

To run the project:  
1. Open `task_1_2_3.ipynb`.  
2. Modify the `fisier_date` and `game_numbers` variables in the last cell.  
3. Run the entire notebook.  
4. Ensure the `351_Pirvulescu_Daria` folder is deleted before re-running the project.  

For more details, refer to the [documentation](https://github.com/dariapirvulescu18/ML-Mathable-game/blob/main/documentatie.pdf).
