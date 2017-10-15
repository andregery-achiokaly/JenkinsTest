node {
    // Get Artifactory server instance, defined in the Artifactory Plugin administration page.
    def buildInfo

    stage('Clone sources') {
        git url: 'https://github.com/andregery-achiokaly/JenkinsTest.git'
    }

    stage('Gradle build') {
       echo "start"
       sh '/plugins/gradle build --info'
       echo "stop"
    }
}
