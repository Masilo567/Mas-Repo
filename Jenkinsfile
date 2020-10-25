pipeline {

   agent {
        docker {
            image 'evermas/myimages:0.0.1'


        }
    }

    stages {
        stage('Test') {
            steps {
                sh "cp -r  /ui_test_poc/* /var/lib/jenkins/workspace/decl"
                sh 'behave'
        //   dir('fold/ui_test_poc') {
        //       sh 'behave'
               // chanes2

        //       }


            }

    }
    }

}
