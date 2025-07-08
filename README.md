import pandas as pd

csv_file_Path = "C:\Users\User\Desktop\ML_Projects\sample_dta.csv"
excel_file_Path = "C:\Users\User\Desktop\ML_Projects\sample_dta.xlsx"

data_csv=pd.read_csv(csv_file_path)
print("CSV File Data:")
print(data_csv)

data_excel=pd.read_excel(excel_file_path)
print("\nExcel File Data:")
print(data_excel)

print("\nData Description:")
print("CSV Data Description:")
print(data_csv.describe())

print("\nExcel Data Description:")
print(data_excel.describe())
