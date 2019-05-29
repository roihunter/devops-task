# Database monitoring
## Using ansible

1. Deploy a postgresql database in a container

2. Create a read and a write user for the database

3. Deploy an exporter providing metrics from the database

4. Deploy in a container a prometheus instance gathering the metrics

5. Deploy a grafana container with a dashboard for the database

6. Make some writing test against the database

7. Endpoints should be accessible through https

8. Unsecured ports should not be accessible from internet

9. All data must be persistent
