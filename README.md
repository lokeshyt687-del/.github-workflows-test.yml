# .github-workflows-test.yml
name: YouTube Automation Test  on:   workflow_dispatch:  jobs:   test:     runs-on: ubuntu-latest     steps:       - name: Check automation         run: echo "YouTube automation system is running!"
