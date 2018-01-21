# keycloak-spring-security-rest-demo

It's necessary to get a token from the Auth server in order to invoke this service:

    curl -X POST \
        -H "Authorization: Basic c2ItYXBwOmEyY2ViZmI2LTBjMzgtNDNiNS1hMDAwLThhYmUzYjU5YjJiMQ==" \
        -H "Content-Type: application/x-www-form-urlencoded" \
        -d 'username=jainigo&password=jainigo&grant_type=password' \
        "http://localhost:8080/auth/realms/SampleRealm/protocol/openid-connect/token"
