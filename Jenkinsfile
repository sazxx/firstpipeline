pipleline {
    agent any

   stages{ 

        stage("build"){

            steps{
                    echo'building the app'

            }
        }
       stage{
    
        stage("test"){
            when {
                expression {
                    BRANCH_NAME == main
                }
            }

            steps{

                echo'testing'
            }
        }
    stage{

        stage("deploy"){

            steps{

                echo'deploying'
            }
        }
    }
}
