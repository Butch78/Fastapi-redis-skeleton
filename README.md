# Fastapi + Redis Skeleton

A Fastapi Backend that will communicate inbetween Fastapi & Redis


"""
Integration with FastAPI.
=========================

To test, first, start the server:

    $ docker-compose up

After the Docker build is complete you can view the Swagger documentation here:

    http://localhost:8000/docs


You can then create customers in the Swagger UI with the following JSON object:

    {
        "first_name": "Matthew",
        "last_name": "Aylward",
        "email": "user@example.com",
        "join_date": "2022-03-19",
        "age": 0,
        "bio": "string"
    }

    You can remove the pk fields from the JSON object (Unless you want to create one yourself) as it is generated by the server.

You can list all of the created customers at the following URL:

    http://localhost:8000/customers

You can find a specific customer at the following URL, you will have to get the pk of the customer you want to find from the list of customers.


    http://localhost:8000/customers/{pk}


You can view the info about the redis database here:

    http://localhost:8001/

You might need to enter the following info:

    host: redis 
    port: 6379

