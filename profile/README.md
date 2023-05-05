# GVSU Apache Airflow Scheduler

Airflow is a platform to programmatically author, schedule, and monitor workflows.

When workflows are defined as code, they become more maintainable, versionable, testable, and collaborative.

----

## Useage
Each workflow (job) must be created as a repository within the IT - Apache Airflow Scheduler
GitHub Organization (https://github.com/GVSU-Apache-Airflow)

Template repositories have been created as a started point. Be sure to copy all branches when
creating a new repository from a template. This will ensure that the automated deployment workflows are run correctly.

DAGs are the acronym for the jobs code which is written in Python. DAGs are deployed to the Airflow server when you merge
code to the "test" branch of the repository. Please develop the DAG in the "development" branch of the repository before 
migrating it to the server via a pull request.

## Helpful Resources
Intro to Apache Airflow: https://docs.astronomer.io/learn/intro-to-airflow

Apache Airflow Docs: https://airflow.apache.org/docs/apache-airflow/stable/index.html

Third Party Airflow Docs and Tutorials: https://docs.astronomer.io/learn/category/airflow-concepts
