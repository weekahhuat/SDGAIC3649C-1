# Spark Jobs Folder

Write your PySpark programs in this folder.

Each program should connect to either MySQL or MongoDB, read data using Spark, and perform some transformations (e.g., filter, groupBy, aggregation).

You may name your scripts as:
- read_mysql.py
- read_mongodb.py
- etl_assignment.py

Use this command to run your job from the terminal:

```bash
spark-submit /opt/spark-jobs/read_mysql.py
```

If you are using Jupyter notebooks instead of scripts, put them in the `notebooks/` folder.
