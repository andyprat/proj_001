# proj_001
# Read Excel to Python
 ## read excel ##

# import pandas as pd
# from pathlib import Path
# Path('C:/Users/Cray.xp/Desktop')
# file = pd.ExcelFile('TT_n2.xls')
#file.sheet_names
# df1 = file.parse("n1")

 


# from pathlib import Path
# Path('C:/Users/Cray.xp/Desktop')

## import warnings; warnings.simplefilter("ignore")
## import matplotlib.pyplot as plt
## import seaborn as SNS
## import numpy as np
## import pandas

import pandas as pd
file = pd.ExcelFile('TT_n2.xls')
file.sheet_names
df1 = file.parse('n')
