FROM postgres:16.2

# Set the environment variables
ENV POSTGRES_USER=postgres
ENV POSTGRES_PASSWORD=postgres
ENV POSTGRES_DB=postgres

# Copy the SQL file to the container 
COPY ./init.sql /docker-entrypoint-initdb.d/

# Copy the data to the container


# Expose the port
EXPOSE 5432

# Start the server and run the shell
CMD ["postgres"]
