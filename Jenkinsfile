echo "I'm a Jenkinsfile"
node {
stage 'Checkout different branch'
checkout changelog: true, poll: true, scm: [$class: 'GitSCM', branches: [[name: 'just-one']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'git://github.com/abayer/sandbox.git']] ]
}
