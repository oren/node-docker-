# Using Docker for Node.js development

    docker build -t my-nodejs-app .
    run -it --rm -v $(pwd):/root --name my-running-app node /bin/bash
    cd && node server.js
    open localhost:3000
