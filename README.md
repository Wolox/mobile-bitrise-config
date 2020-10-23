# Bitrise Configuration

In order to add Bitrise support with metrics configuration to your Wolox project, you must add the `bitrise.yml` file added in this repository. You must modify it in order to enable CI metrics. The following keys should be changed:

- GIT_URL: Repository url
- PROJECT_NAME: Project name
- PROJECT_TYPE: react_native, android or iOS
- KEYSTORE_NAME: Keystore name
- PRETTY_TITLE: A display name
- ENV_TEMPLATE_NAME: Development env file name (e.g. .dev.env)
- ENV_TEMPLATE: Base64 string from a file which contains the same keys as the env file but without the real keys
- GOOGLE_SERVICES_NAME: Firebase Google Services file (.json)
