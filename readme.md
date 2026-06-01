| Column | Description |
| --- | --- |
| ``total_bill`` | Total bill amount (USD) |
| ``tip`` | Tip amount given (USD) |
| ``sex`` | Gender of the customer (``Male``, ``Female``) |
| ``smoker`` | Whether the customer is a smoker (``Yes``, ``No``) |
| ``day`` | Day of the week (``Thur``, ``Fri``, ``Sat``, ``Sun``) |
| ``time`` | Time of day (``Lunch``, ``Dinner``) |
| ``size`` | Number of people in the dining party |




# Load tips dataset
 pd = pd,read.csv("tips_csv")
print(tips.head())





# Average total bill by gender
avg_bill_by_sex = tips.groupby("sex")["total_bill"].mean()
print(avg_bill_by_sex)




# Average total bill by gender
avg_bill_by_sex = tips.groupby("sex")["total_bill"].mean()
print(avg_bill_by_sex)
