### pandas
(1) df.drop(['B', 'C'], axis=1)
(2) df.drop(columns=['B', 'C'])
(3) df.drop([0, 1])
(4) df.drop([df.columns[0]], axis=1, inplace=True) 
