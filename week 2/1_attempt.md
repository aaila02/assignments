

1. Problem: 1 blank cell in price
code: df.isna().sum()
planned decision: correct

2. Problem: 1 duplicated record
code: df.duplicated().sum()
planned decision: flag

3. Problem: Date's data type is set to string
code: df.info()
planned decision: correct

4. Problem : Price is set to string
code: df.info()
planned decision: correct

5. Problem: There is a invalid value in item named oil b
code: df['item'].value_counts()
planned decision: correct
