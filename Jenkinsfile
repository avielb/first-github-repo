node {
    stage("checkout"){
        git 'https://github.com/avielb/first-github-repo.git'
    }
    stage("install requirements"){
        sh "pip install -r requirements.txt"
    }
    stage("run script"){
        sh "python 1.py"
    }
}
