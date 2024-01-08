# coderef-python-plots
# Matplotlib
## Installation
```Shell
pip install matplotlib
```
## Basics
We import the package
```Python
import matplotlib.pyplot as plt
import matplotlib as mpl
```
We can create a simple plot as follows
```Python
fig, ax = plt.subplots()
ax.plot([1, 2, 3], [1, 4, 9])

# Show plot
plt.show()
```
# Plotly
## Plotly-Express
### Installation
We can install plotly and plotly-express as follows
```Shell
pip install plotly
```
### Basics
We can create a simple scatter plot as follows
```Python
import plotly.express as px
fig = px.scatter(x=[0, 1, 2], y=[0, 1, 4])
fig.show()
```
