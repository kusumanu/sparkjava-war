pipeline {                           // 1  Defines the start of the Jenkins pipeline block
    agent any                        // 2  Specifies the pipeline can run on any available agent

    environment {                    // 3  Defines environment variables for the pipeline
        PATH = "/opt/maven/bin:$PATH" // 4 Adds Maven's path to the system's PATH variable
    }                                 // 5 Ends the environment block

    stages {                          // 6 Defines the stages block where multiple stages are declared

            }                         // 10 Ends the steps block for 'git clone' stage
        }                             // 11 Ends the 'git clone' stage

        stage('build') {              // 12 Creates a stage named 'build'
            steps {                   // 13 Defines the steps that will be executed in this stage
                sh 'mvn clean install' // 14 Runs the Maven clean install command to build the project
            }                          // 15 Ends the steps block for 'build' stage
        }                              // 16 Ends the 'build' stage
    }                                  // 17 Ends the stages block
}
