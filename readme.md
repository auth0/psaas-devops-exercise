## Running the docker image

```
# Create the image
docker build -t auth0/psaas-devops-exercise .

# Run the image
docker run -p 8080:3000 -d auth0/psaas-devops-exercise
```