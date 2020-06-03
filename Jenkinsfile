node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("aquibsiddiqui/dockerapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
