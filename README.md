# Note-for-Python
Pandas:
	
    Find a value in a Series/Dataframe:
		df[df['key'] > 0]
        
    To get the index of the return data:
		df[df['key'] > 0].index

Pandas.read_excel:
	
	Skip the first n rows: 
		skiprows = n
		
	Do Not take the first row as keys:
    	header = None
		
	Input data from specific sheet:
		sheetname = n
    
Pandas.Series:
	
	Drop the data with index of n from series S:
    	S.drop(n)
    	Note: S.drop() will keep series S unchanged and return a new, handled series. All indexs in this new series remain unchanged except index n will be removed.
		
	
