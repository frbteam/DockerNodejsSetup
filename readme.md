Federal reserve bank Sample nodejs application with docker Container


Installation
    // clone the application with git clone

    // then install the npm modules using
     
    npm install

Running the application
 
    node server.js

Building docker image

    docker build -t <imagename:version>

Running docker container

// 8080 port is given since the docker file contains 8080 port
    docker run -it -d -p <outside-port-of-your-choice>:8080 <imagename:version>




