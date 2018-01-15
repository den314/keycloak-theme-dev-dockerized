FROM jboss/keycloak:latest

COPY ./config/standalone.xml /opt/jboss/keycloak/standalone/configuration/
COPY ./themes/ /opt/jboss/keycloak/themes/

EXPOSE 8080