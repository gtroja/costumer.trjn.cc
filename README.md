trjn Costumers app
==================
See [requirements](requirements.md) for the system description (it's in portuguese)
I'm planning in using lisp for the backend (with hunchentoot framework), mariaDB and react for the front-end. I'm gonna try to use tailwindcss in the front. I'll describe de rest api in openapi. I'm gonna try to deploy it with git (having a upstream in the server maybe? with all those git hooks and only deploying after the tests passes etc..)wish me luck.

RoadMap
-------
I already have in mind how the user gonna use the system, so I'm gonna start by making the crude frontend.
I'll start by:

    - a login page:
        -user and password field
        -login and create a user button
    
    - a new user page:
        -name, user, password input box
        -create new user button

    - a main page:
        - Clients list
        - a report button
        - new client button
    
    - a client modal:

    - a new client modal:

    - a new/edit contact modal:

I plan to use the react router. After having those with mock data, I'll model the REST API and I'll describe it using OpenAPI; After that I'll implement and publish a mock server and implement the frontend services. Having those ready, I'll architect the backend. well well