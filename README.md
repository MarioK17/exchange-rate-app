# exchange-rate-app

Project containing the reference to the frontend and backend project of the application.

# Software architecture document
In the **docs** folder is included the software architecture document

# Cloning

Execute `git clone --recursive` to clone this project and submodules

# Login, Users and Roles

The application by default creates 2 users and 2 roles, one role for each one.

| username | password | roles
| --- | --- | --- |
| admin | admin | ADMIN
| user | user | USER


# Running application

```
docker-compose up -d
```

Require docker compose to run frontend backend and database. Application will run on http://localhost:4600

# Perfomance and Load Testing
```
jmeter -n -t ExchangeRate.jmx -l out.jtl
```
