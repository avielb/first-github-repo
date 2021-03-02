node {
    stage("checkout"){
        git 'https://github.com/avielb/first-github-repo.git'
    }
    stage("install requirements"){
        sh "pip3 install -r requirements.txt"
    }
    stage("run script"){
        sh "python3 1.py"
    }
}