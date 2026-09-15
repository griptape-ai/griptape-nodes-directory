# Contributing to the Griptape Nodes Directory

Thank you for your interest in to the Griptape Nodes Directory! This document provides guidelines and instructions for contributing.

## Types of Contributions

### 1. New Nodes

This repository contains a list of nodes contributed by the team here at Griptape, and we would love to add community contributed nodes to the directory too. We accept pull requests to the [README.md](README.md) for adding reference to your nodes.

Please keep lists in alphabetical order to minimize merge conflicts when adding new items.

* Check the Node Development Documentation (coming soon)
* Ensure your nodes don't duplicate existing functionality
* Consider whether your nodes would be generally useful to others
* Follow security best practices from the Node Development Documentation (coming soon)
* Create a PR adding a link to your nodes to the [README.md](README.md).

### 2. Documentation
Documentation improvements are always welcome:

- Fixing typos or unclear descriptions
- Adding additional resources that might be valuable for node developers such as:
    - reference or example nodes
    - additional documentation
    - troubleshooting guides

## Getting Started

1. Fork the repository
2. Clone your fork:
   ```bash
   git clone https://github.com/your-username/gripape-nodes-directory.git
   ```
3. Add the upstream remote:
   ```bash
   git remote add upstream https://github.com/griptape-ai/griptape-nodes-directory.git
   ```
4. Create a branch:
   ```bash
   git checkout -b my-feature
   ```

## Development Guidelines

### Style
- Follow the existing style in the repository

#### Add to Griptape Nodes button

Each entry ends with a button that installs the library. Copy it and replace the
git URL with your repository:

```html
<p align="right"><a href="https://app.nodes.griptape.ai/open#library-management?git=https://github.com/your-username/your-library"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>
```

The `/open` path hands the link to Griptape Nodes Desktop when it is installed,
and otherwise offers the download or the web editor. Use `app.nodes.griptape.ai`:
`nodes.griptape.ai` redirects there and drops the path, which turns the link back
into a web-only one.

### Documentation
- Include a detailed README.md in your node repository
- Document all configuration options
- Provide setup instructions, such as secrets that need to be provided
- Include usage examples

### Security
- Follow security best practices
- Implement proper input validation
- Handle errors appropriately
- Document security considerations

## Submitting Changes

1. Commit your changes:
   ```bash
   git add .
   git commit -m "Description of changes"
   ```
2. Push to your fork:
   ```bash
   git push origin my-feature
   ```
3. Create a Pull Request through GitHub

### Pull Request Guidelines

- Thoroughly review your changes
- Fill out the pull request template completely
- Link any related issues
- Provide clear description of changes
- Include any necessary documentation updates

## Community

- Participate in discussions on the [Griptape Discord](https://discord.gg/griptape) 

## Questions?

- Check the documentation (coming soon)
- Ask in the [#nodes-development](https://discord.com/channels/1096466116672487547/1377978843092226148) channel on the [Griptape Discord](https://discord.gg/griptape)

Thank you for contributing to Griptape Nodes!