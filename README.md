# My notes

### Database and Spring Data JPA
![img](/statics/images/databases_and_spring_data_jpa_overview.png "overview")

1. How to create database (PostgreSQL with docker)
```text
- In terminal, run following commands:
    1. docker exec -it postgres bash
        (postgres: name of running postgres container)
    2. psql -U amigoscode
        (amigoscode: database user name)
    3. CREATE DATABASE customer;
        (customer: database name)
```
