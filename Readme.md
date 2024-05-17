Business needs

    The organization is looking for a solution to predict data in student study performance.
    https://www.kaggle.com/datasets/bhavikjikadara/student-study-performance
    
Requirements

    python 3.7

    numpy==1.17.3
    pandas==1.1.5
    sklearn==1.0.0

Running:

    To run the demo, execute:
        python predict.py 

    After running the script in that folder will be generated <prediction_results.csv> 

    The input is expected  csv file in the same folder with a name <predict.csv>. The file shoul have all features columns. 

Training a Model:

    Before you run the training script for the first time, you will need to create dataset. The file <train.csv> should contain all features columns and target for prediction math_score.
    After running the script train_model.ipynb  "finalized_model.sav" will be created.
    Run the training script:
        python train.py

    There is no fraud check.