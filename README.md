# pandas-challenge
Resources:

Xpert Learning Assistant
 (Naming Index in the per_school_summary dataframe. per_school_summary.index.name = None)
Xpert Learning Assistant
 (Binning with strings and integers error.) school_spending_df["Per Student Budget"] = school_spending_df["Per Student Budget"].str.replace('$', '').astype(float).astype(int).astype(str)
school_spending_df["Spending Ranges (Per Student)"] = pd.cut(school_spending_df["Per Student Budget"], bins=spending_bins, labels=labels)
school_spending_df["Per Student Budget"] = "$" + school_spending_df["Per Student Budget"].astype(str)
school_spending_df
