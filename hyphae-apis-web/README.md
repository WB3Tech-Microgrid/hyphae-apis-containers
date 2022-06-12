# Hyphae APIS Web

This containerfile is copied by the buid system when the Hyphae APIS web application is being built.

## Volumes

The following files are expected to be mounted per their correspoding locaiton within the container.  Their mount location is the working directory for the conatiner (/hyphae-apis-web)

| Filename              | Description                       | Expected Mount Location                   |
|-------------------    |-----------------------            | ------------------------                  |
| logging.properties    | Java logging properties file      | /hyphae-apis-web/logging.properties       |
| cluster.xml           | Hazelcrest Cluster configuraiton  | /hyphae-apis-web/cluster.xml              |
| config.json           | APIS Web configuraito file        | /hyphae-apis-web/config.json              |
| cert.pem              | PEM public key                    | /hyphae-apis-web/cert.pem                 |
| key.pem               | PEM private key                   | /hyphae-apis-web/key.pem                  |