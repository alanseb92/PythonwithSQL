# PythonwithSQL

In the SQL Server Management Studio, the ease of using external procedure sp_execute_external_script has been (and still will be) discussed many times. But the reason for this work is the fact that, changing Python environments using Conda package/module management within Microsoft SQL Server (Services), is literally impossible. Scenarios, where you want to build  a larger set of modules (packages) but are impossible to be compatible with your SQL Server or Conda, then you would need to set up a new virtual environment and start using Python from there.

Communicating with database to load the data into different python environment should not be a problem. Python Pandas module is an easy way to store dataset in a table-like format, called dataframe. Pandas is very powerful python package for handling data structures and doing data analysis.
