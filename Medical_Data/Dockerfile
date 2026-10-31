# Dockerfile - MySQL client container to connect to remote pre-existing MySQL server
FROM mysql:latest

# Connection details for the pre-existing remote MySQL server
ENV DB_HOST=18.136.157.135
ENV DB_PORT=3306
ENV DB_USER=dm_team4
ENV DB_NAME=project_medical_data_history

# Launch the MySQL interactive client, connecting to the remote server
CMD ["sh", "-c", "mysql -h $DB_HOST -P $DB_PORT -u $DB_USER -p $DB_NAME"]
