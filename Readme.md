# Database monitoring
## Using ansible

- Role should run on Ubuntu Bionic
- The ultimate purpose of this task is to display database operations in a Grafana dashboard.
- Use of `shell` (and `command`) Ansible modules are prohibited
- We expect the task to be completed in a tidy manner and to be fit for production use.


1. Deploy a postgresql database in a container

2. Create a read and a write user for the database

3. Deploy an exporter providing metrics from the database

4. Deploy in a container a prometheus instance gathering the metrics

5. Deploy a grafana container with a dashboard for the database

6. Make some writing test against the database

7. Endpoints should be accessible through https _(example: https://0.0.0.0/prometheus, https://0.0.0.0/grafana)_

8. Unsecured ports should not be accessible from internet

9. All data must be persistent
