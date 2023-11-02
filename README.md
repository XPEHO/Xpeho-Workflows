# Xpeho-Workflows

This repository contains GitHub workflows to automate common development tasks.

## Workflows

### General

- [Add label to Pull Request](./.github/workflows/labels.yaml): This workflow adds a label to a pull request when it is opened.
- [Changelog](./.github/workflows/changelog.yaml): This workflow check if the changelog has been updated when a pull request is merged.
- [Git checks](./.github/workflows/git_checks.yaml): This workflow runs git checks when a pull request is opened.

### Flutter

- [Coverage tests](./.github/workflows/flutter/coverage.yaml): This workflow runs coverage tests when a pull request is opened with the plugin Very Good Coverage. The min coverage is defined by your environment variables.
- [Dart checks](./.github/workflows/flutter/flutter.yaml): This workflow runs the dart format, dart analyze and dart test when a pull request is opened.

## Contributing

Contributions are welcome! If you want to add a new workflow or improve an existing workflow, please submit a pull request.

## License

This repository is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more information.