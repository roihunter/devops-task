# Database monitoring
## Using ansible

1. Deploy a postgresql database in a container
2. Create a read and a write user for the database
3. deploy an exporter providing metrics from the database
4. deploy in a container a prometheus instance gathering the metrics
5. deploy a grafana container with a dashboard for the database
6. make some writing test against the database
7. endpoints should be accessible through https
8. unsecured ports should not be accessible from internet
9. all data must be persistent
