node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'DockerID') {

        def customImage = docker.build("gsunilkumar2509/repo2")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
