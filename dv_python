import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

# Read data from the Excel file
excel_file = 'data.xlsx'
df = pd.read_excel(excel_file)

# Extract data from the DataFrame using NumPy
x = df['X'].to_numpy()
y = df['Y'].to_numpy()

# Create a Matplotlib plot
plt.figure(figsize=(8, 6))
plt.plot(x, y, label='Data from Excel', color='b', marker='o')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Data from Excel Plot')
plt.legend()
plt.grid(True)
plt.show()
