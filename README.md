# Golang Project Template

> Consider changing the name of the repository ownership

This repository contains a simple template for golang projects. It has been configured with asdf to use the latest version of golang (currently v1.19), but any version >=1.13 of golang installed on your local machine can be used instead. The included Taskfile is an optional utility that can be used as an alternative to makefile, but any other build tool can be used as well.

## Inspiration

This project was created as a starting point for golang projects, to save time and effort when setting up a new project from scratch. It is intended to be a basic template that can be easily customized and expanded as needed, and can be used as a reference or starting point for other projects.

## Usage

To use this template, clone the repository and start building your project.

```bash
git clone https://github.com/ruslanguns/golang-template.git
cd golang-template
```

### Building

To build the project, you can use either of the following commands:

```bash
task build

# or

go build cmd/main.go
```

### Running

To start the project, use either of the following commands:

```bash
task run

# or

go run cmd/main.go
```

### Contributing

To contribute to this template, fork the repository and create a pull request with your changes.

## Contributions

The Golang Project Template is an open-source project, and we welcome contributions from the community. If you have suggestions for improving the template, or if you have found a bug or an issue, you can open an issue on the GitHub repository for the project.

We also welcome pull requests from users who want to contribute code or other changes to the template. If you want to submit a pull request, please make sure to follow the guidelines and conventions used in the project, and to include tests for your changes. This will help us review and merge your changes more efficiently, and ensure that the template remains stable and reliable.

Thank you for your interest in contributing to the Golang Project Template, and we look forward to your feedback and contributions.

## Author

- Ruslan Gonzalez
- Twitter: [@ruslangonzalez](https://twitter.com/ruslangonzalez)
