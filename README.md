# ssh-server

Simple SSH server. 
By default the server will listen for connections on port 22. to change the port use flag -port 

# Install

    go get /go/src/github.com/anamanolache/ssh-server

# Docker

    docker build -t sshserver .
    docker run -p<LOCAL_PORT>:22 sshserver