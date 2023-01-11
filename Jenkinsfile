pipeline {
    agent any {
        stages {
            stage ("SCM") {
                steps {
                    echo "Pulling code from SCM"
                }
            }

            stage ("Build") {
                steps {
                    echo "Building the code"
                }

            }

            stage ("Release") {
                steps {
                    echo "Release state "
                }
                
            }

            stage ("Deploy") {
                steps {
                    echo "Deployment"
                }
            }
        }
    }
}