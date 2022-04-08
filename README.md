# exchange-rate-app

Project containing the reference to the frontend and backend project of the application.

# Software architecture document
In the **docs** folder is included the software architecture document

# Cloning

Execute `git clone --recursive` to clone this project and submodules

# Running application

```
docker-compose up -d
```

Require docker compose to run frontend backend and database. Application will run on http://localhost:4600

# Perfomance and Load Testing
```
jmeter -n -t ExchangeRate.jmx -l out.jtl
```
