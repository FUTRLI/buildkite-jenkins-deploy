# Buildkite Jenkins Deploy

## Example

```yml
steps:
  - name: ":shipit: Deploy!!!!"
    plugins:
      https://github.com/FUTRLI/buildkite-jenkins-deploy.git#1.0:
        lambda: JenkinsDeployer
        job: deploy-my-service
        iam-role: iam::abc...
```
