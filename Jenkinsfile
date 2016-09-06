echo "I'm a Jenkinsfile"
node {
stage 'Checkout different branch'
git branch: 'just-one', changelog: false, poll: false, url: 'git://github.com/abayer/sandbox.git'
}
