# Replication: Figure 1
# Is There a Replication Crisis in Finance?

## Step 1 — Download Data
Put these files in /Data:
- hml.csv
- cmp.csv
- market_returns.csv
(Due to memory limitations, please download these data from the Google Drive Link:
https://drive.google.com/drive/folders/1fRIFZftpYRrlJGDkhKzv3m1lsKYJMw7C?usp=drive_link)

Put these files in the root folder (same level as main.R):
- Factor Details.xlsx
- Country Classification.xlsx

## Step 2 — Run
Open main.R and run it. Everything else runs automatically.
(In order to save running time, please download the RDS file in advance from the following link:
https://drive.google.com/drive/folders/1w7zysdLKU-8JFo1LDnLZRv49pTAzj0ZM?usp=sharing)

## Step 3 — Output
Figure 1 is saved in /Figures as fig1.eps
(The file for the first run is stored in the following file, and the png version of figure1 is additionally saved:
https://drive.google.com/drive/folders/1AiQqOnikGJ9Q8WaIMrVMK8vF7sTQ3vpO?usp=sharing)

Please notice that in "main.R":
"update_sim <- F             
update_post_over_time <- F
update_post_is <- F
update_harvey_baseline <- F  
update_harvey_worstcase <- F"
If you want to recalculate without using objects, please change all F to T
