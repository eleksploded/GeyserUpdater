pipeline {
    agent any

    stages {
            stage ("Clone") {
                steps {
                    git url: https://github.com/YHDiamond/GeyserUpdater
                    }
                }
            }
            stage ("Build") {
                steps {
                    sh "mvn clean install"
                }
            }
        }
    }
}