echo "I'm a Jenkinsfile"
node {
stage 'Checkout different branch'
git branch: 'master', changelog: false, poll: false, url: 'git://github.com/jenkinsci/pipeline-model-definition.git'
}
