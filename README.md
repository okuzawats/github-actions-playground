# Android GitHub Actions Playground

Androidアプリ開発に関するGitHub Actionsの実験場

## ワークフローの説明

### yamllint

[adrienverge/yamllint: A linter for YAML files.](https://github.com/adrienverge/yamllint)、および[reviewdog/action-yamllint: Run yamllint with reviewdog](https://github.com/reviewdog/action-yamllint)を用いた、YAMLファイルのlintを実行するワークフロー。

YAMLのフォーマットは `.yamllint` に定義する。

### actionlint

[rhysd/actionlint: :octocat: Static checker for GitHub Actions workflow files](https://github.com/rhysd/actionlint)、および[reviewdog/action-actionlint: run actionlint with reviewdog](https://github.com/reviewdog/action-actionlint)を用いた、GitHub Actionsのlintを実行するワークフロー。
