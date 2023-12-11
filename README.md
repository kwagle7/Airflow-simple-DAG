# Airflow-simple-DAG
Monitoring a DAG

# Objectives:

![image](https://github.com/kwagle7/Airflow-simple-DAG/assets/13037108/8c285112-da4b-4338-81da-aa1f9b10d525)
- Task1 does nothing but sleep for 1 second.
- Task2 sleeps for 2 seconds.
- Task3 sleeps for 3 seconds.
This DAG is scheduled to run every 1 minute.

and other objectives are:

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

# Run the command below to list out all the existing DAGs.
<pre>
  airflow dags list
</pre>

# Run the command below to list out all the tasks in dummy_dag.
<pre>
  airflow tasks list simple_dag
</pre>


