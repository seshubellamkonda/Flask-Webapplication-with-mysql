node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'docker') {

        def customImage = docker.build("seshubellamkonda/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
