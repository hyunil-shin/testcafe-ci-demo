
node {
    checkout scm
    sh "docker run -v '$WORKSPACE':/tests testcafe/testcafe chromium /tests/**/*.js"
}
