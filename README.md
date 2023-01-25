## Freshchat Android SDK

## How to publish?
We host this library internally using [GitHub Packages](https://github.com/features/packages)

#### 1. Setup variables for GitHub Packages

To connect with GitHub Packages, you need to add these properties in `local.properties` as follows:
```
gpr.user=YOUR_GITHUB_USERNAME
gpr.key=YOUR_PERSONAL_ACCESS_TOKEN
```
Please make sure your personal access token has `write:packages` access.

#### 2. Run the following command
`./gradlew assembleRelease publish`

#### 3. Check the artifact
The new artifact will be published in [our main repository](https://github.com/orgs/pomelofashion/packages?repo_name=mobile-android)