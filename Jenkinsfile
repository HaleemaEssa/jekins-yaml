pipeline:
  environment: DOCKERHUB_CREDENTIALS=credentials('haleema-dockerhub')
  agent: none
  stages:
    - stage: "Stage1"
      //agent: any
      steps:
        //- sh 'echo $DOCKERHUB_CREDENTIALS_PSW | docker login -u $DOCKERHUB_CREDENTIALS_USR --password-stdin'
        - sh "java -version"
        - sh "git --version"
        - sh "docker --version"
    
