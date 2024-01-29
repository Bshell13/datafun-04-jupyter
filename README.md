# datafun-04-jupyter

## How to Install and Run the Project
```shell
py -m venv .venv
.venv\Scripts\activate
py -m pip install jupyterlab numpy pandas mayplotlib seaborn scipy
py -m pip freeze > requirements.txt
```

## About the Project
In this project, I will demonstrate the use of jupyter notebooks while eploring a common dataset, iris.csv.
The 'iris.csv' dataset is stored in the Seaborn library.

plt.show() was not working so I imported as follows to help with this
<div class="plt.show() not working">
<b>Tip:</b> If plt.show() is not working, import the following from matplotlib.
`import matplotlib.pyplot as plt`
</div>
