echo "I'm a Jenkinsfile"
node {
stage 'Checkout different branch'
checkout changelog: false, poll: false, scm: [$class: 'GitSCM', branches: [[name: 'feature/feature1']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'git://github.com/abayer/sandbox.git']] ]
}
