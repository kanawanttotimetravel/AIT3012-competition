# AIT3012: Competition
## Our members
- 22022537 Do Minh Nhat 
- 22022549 Khong Ngoc Anh 
- 22022500 Nguyen Quy Dang 
- 22022504 Nguyen Duc Anh

## Disclaimer 
Due to the time constraint, we haven't been able to derive a functional pipeline. Our codebase is purely run on Jupyter notebook (`ipynb` files), and hosted on Kaggle, a cloud-based site for Jupyter notebook. As such, most of the code are hard-coded, and likely unable to run without specific editing. The file `eegnet-features-full-pipeline.ipynb` contain the whole pipeline, and can be run with the conda configuration

## How to run 
To run the `eegnet-features-full-pipeline.ipynb` file, we assumed the dataset is like this:
- `folder/`
    - `raw_files/`
        - all the `.fif` files
    - `y_test.csv` contain id and age the 40 test subjects
    - `y_train.csv` contain the id and age of the remaining subjects