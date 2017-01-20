node {

    currentBuild.result = "SUCCESS"

    try {
       stage('Hello World') {
            echo 'Hello world'
       }
   }
    catch (err) {
        currentBuild.result = "FAILURE"
        throw err
    }
}
