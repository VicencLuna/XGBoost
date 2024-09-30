This is a script to predict house sale prices. The input files are provided by the Kaggle competition: House Prices - Advanced Regression Techniques.
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/code

The data directory is currently set to Kaggle; you should change it to your local computer:
                dir_Input='/kaggle/input/house-prices-advanced-regression-techniques/'
                dir_Output='/kaggle/working/'
                file='train.csv'
                output='temp.csv'
                df_train = pd.read_csv(dir_Input+file)  # Sustit#uye por tu dataset


