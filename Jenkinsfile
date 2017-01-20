node {

    currentBuild.result = "SUCCESS"

    try {
       stage('Hello World') {
            echo 'Hello world'
       }
   }
    catch (err) {
        echo 'failure :('
        currentBuild.result = "FAILURE"
        throw err
    }
}
