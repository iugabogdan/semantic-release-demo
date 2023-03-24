## Semantic-Release-Demo

This is a sample repository that demonstrates the use of semantic-release for automated versioning and releases based on commit messages. Semantic-release is a powerful tool that can help streamline the release process and improve the quality of software releases by automating the versioning and publishing of releases based on the content of commit messages.

### Getting Started
To get started with semantic-release-demo, simply clone the repository and install the necessary dependencies:

```
git clone https://github.com/iugabogdan/semantic-release-demo.git
cd semantic-release-demo
npm install
```

Once the dependencies have been installed, you can run semantic-release by running the following command:

```
npm run release
```

This will initiate the semantic-release process, which will automatically determine the next version number based on the content of your commit messages, create a new tag, and publish the release to GitHub.

Or simply push into main and a workflow will be triggered.

### Usage
Semantic-release works by analyzing the content of commit messages to determine the type of release that should be created (major, minor, or patch), as well as the version number. To create a release using semantic-release, you simply need to follow a few simple rules when writing commit messages:

- To trigger a major release, include the phrase "BREAKING CHANGE" (in all caps) somewhere in the commit message.
- To trigger a minor release, include the word "feat" (short for "feature") somewhere in the commit message.
- To trigger a patch release, use any other type of commit message.

Here's an example of a commit message that would trigger a minor release:

```
feat: add support for new feature
```

And here's an example of a commit message that would trigger a patch release:

```
fix: resolve issue with login page
```

### Contributing
If you find a bug or have a feature request, please open an issue or submit a pull request. We welcome contributions from anyone who is interested in improving this project.