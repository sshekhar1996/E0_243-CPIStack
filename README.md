Obtaining CPI Stack using Performance Monitoring Counters and Linear Regression

# Installing python packages

Use 
```
$ virtualenv venv
$ source venv/bin/activate
$ pip3 install -r requirements.txt

```

# Downloading datasets

The datasets assigned to us were 

```
$ 525.x264_r
$ 531.deepsjeng_r
$ 521.wrf_r
$ 526.blender_r
```
We used an online text to csv converter and created 4 data files.

```
$ 521.csv
$ 531.csv
$ 526_data_pointsN.csv
$ 525_1310.csv
```
The CSV files can be found in the zipped folder.

# Running the code 

```python3 521_f.py```

This will generate the output (CPI stack, statistical values, plots etc) that was used in our report.
In case the plots are not rendered, please consider running this code on Google Colab as we tested our code there. We have also included the .ipynb files for reference which can be uploaded (along with the corresponding .csv file) and run directly.

