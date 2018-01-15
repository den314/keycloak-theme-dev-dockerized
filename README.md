# Custom Keycloak theme dev with docker

## Build and Run
docker build docker/. -t keycloak_theme_dev && docker run -d -p 18080:8080 --env KEYCLOAK_USER=admin --env KEYCLOAK_PASSWORD=password keycloak_theme_dev

### Steps to apply custom theme
- run image as above
- go to realm settings -> theme tab
- choose theme from the list
 
 #### What is Keycloak?
 More info: http://www.keycloak.org/