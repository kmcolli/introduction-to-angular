# Example pipeline for this application

This shows a modification of the default pipeline for this application that additionally runs tests. It requires that the OpenShift Pipelines operator is installed.

To use:

1. In the Developer perspective, choose Import From Git
2. Use https://github.com/daxelrod-rh/introduction-to-angular as the repo URL
3. Select NodeJS S2I as the build strategy
4. Check the box for creating a pipeline
5. After the app is created, run `oc apply -f pipeline.yaml -n <projectname>`
