node {
    // Get Artifactory server instance, defined in the Artifactory Plugin administration page.
    def buildInfo

    stage('Clone sources') {
        git url: 'https://git.epam.com/alexander_topilskii/test-beacons.git'
    }

    stage('Gradle build') {
       echo "start"
       sh './gradlew build'
       echo "stop"
    }
}
