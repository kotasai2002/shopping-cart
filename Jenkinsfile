pipeline {
    agent any

    environment {
        GITHUB_REPO_URL = 'https://github.com/kotasai2002/shopping-cart.git' // Your repo URL
       // SBOM_TOOL = 'ghcr.io/cdxgen/cdxgen'  // cdxgen tool Docker image
       // SCA_TOOL = 'ghcr.io/osv-scanner/osv-scanner'  // OSV scanner Docker image
    }

    stages {
        stage('Checkout Repository') {
            steps {
                // Checkout the GitHub repository
              //  sh 'systemctl restart jenkins'
                git url: "${GITHUB_REPO_URL}"

            }
        }


    }
}
