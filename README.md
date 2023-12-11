# Airflow-simple-DAG
Monitoring a DAG

# Objectives:

![image](https://github.com/kwagle7/Airflow-simple-DAG/assets/13037108/8c285112-da4b-4338-81da-aa1f9b10d525)
- Task1 does nothing but sleep for 1 second.
- Task2 sleeps for 2 seconds.
- Task3 sleeps for 3 seconds.
This DAG is scheduled to run every 1 minute.

Following are some  of the basic things we can see/perform (some are given in the images at the end)

- Search for a DAG
- Pause/Unpause a DAG
- Get the Details of a DAG
- Explore grid view of a DAG
- Explore graph view of a DAG
- Explore Calendar view of a DAG
- Explore Task Duration view of a DAG
- Explore Details view of a DAG
- View the source code of a DAG
- Delete a DAG

# Start Apache Airflow
<pre>
start_airflow
</pre>

![image](https://github.com/kwagle7/Airflow-simple-DAG/assets/13037108/79cac458-c4f9-41b7-88d6-b5afc62e76ff)

# Copy the file simple_dag.py to the location specified by the variable `$AIRFLOW_home/dags`
<pre>
  cp simple_dag.py $AIRFLOW_HOME/dags
</pre>
- cp: This is the command for copying files or directories in Unix-like operating systems.

- simple_dag.py: This is the name of the file being copied.

- $AIRFLOW_home/dags: This seems to be a variable indicating a directory path. Variables in shell scripting are denoted by the $ sign followed by the variable name.

# Run the command below to list out all the existing DAGs.
<pre>
  airflow dags list
</pre>

# Run the command below to list out all the tasks in simple_dag.
<pre>
  airflow tasks list simple_dag
</pre>
![image](https://github.com/kwagle7/Airflow-simple-DAG/assets/13037108/86a0bacd-572e-49fd-aa66-a5c146c39e7c)

![image](https://github.com/kwagle7/Airflow-simple-DAG/assets/13037108/f58fa16d-4606-4269-a6bd-194a3f087027)

![image](https://github.com/kwagle7/Airflow-simple-DAG/assets/13037108/db7cbf47-a17c-4651-bb31-1d091e155ab5)
![image](https://github.com/kwagle7/Airflow-simple-DAG/assets/13037108/24be5a15-268c-473f-9a40-0012b445c811)
