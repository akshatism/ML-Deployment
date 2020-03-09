
Run ```docker run -p 80:80 app-iris``` to run the docker container on the EC2 instance.
Use the below command in terminal to query the flask server
    ```
        curl -X POST \
        0.0.0.0:80/predict \
        -H 'Content-Type: application/json' \
        -d '[5.9,3.0,5.1,1.8]'
    ```
