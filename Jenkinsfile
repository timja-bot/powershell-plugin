#!/usr/bin/env groovy

/* `buildPlugin` step provided by: https://github.com/jenkins-infra/pipeline-library */
buildPlugin(
  useContainerAgent: false,
  configurations: [
    [platform: 'linux', jdk: 17],
    [platform: 'windows', jdk: 11],
  ]
)