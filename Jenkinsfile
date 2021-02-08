node {

    checkout scm

    docker.withRegistry('https://hub.docker.com/repository/docker/gsunilkkumar63', 'Sunil*63') {

        def customImage = docker.build("gsunilkumar2509/repo2")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
