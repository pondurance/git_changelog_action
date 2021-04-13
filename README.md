# git_changelog_action

GitHub Action to help generate a changelog for a project based on [aldrin/git-changelog](https://github.com/aldrin/git-changelog).

# Usage

```yaml
- name: Changelog
  uses: pondurance/git_changelog_action@v2
  id: changelog
```

This Action supports the following inputs:

| Property       | Default | Description |
| -------------- | ------- | ----------- |
| `url`          | `https://github.com/aldrin/git-changelog/releases/download/v0.3.1/git-changelog-v0.3.1-linux.tar.gz` | The url for the release to use |


The Action also expects the repository to include a configuration file for the changelog generation tool, see [git-changelog - Customization](https://github.com/aldrin/git-changelog#customization) for more details.

