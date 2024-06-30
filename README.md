# Android GitHub Actions Playground

[![actionlint](https://github.com/okuzawats/android-github-actions-playground/actions/workflows/actionlint.yml/badge.svg?branch=main)](https://github.com/okuzawats/android-github-actions-playground/actions/workflows/actionlint.yml)
[![yamllint](https://github.com/okuzawats/android-github-actions-playground/actions/workflows/yamllint.yml/badge.svg?branch=main)](https://github.com/okuzawats/android-github-actions-playground/actions/workflows/yamllint.yml)

Androidアプリ開発に関するGitHub Actionsの実験場

## ワークフローの説明

### yamllint

[adrienverge/yamllint: A linter for YAML files.](https://github.com/adrienverge/yamllint)、および[reviewdog/action-yamllint: Run yamllint with reviewdog](https://github.com/reviewdog/action-yamllint)を用いた、YAMLファイルのlintを実行するワークフロー。

YAMLのフォーマットは[.yamllint](./.yamllint)に定義する。

### actionlint

[rhysd/actionlint: :octocat: Static checker for GitHub Actions workflow files](https://github.com/rhysd/actionlint)、および[reviewdog/action-actionlint: run actionlint with reviewdog](https://github.com/reviewdog/action-actionlint)を用いた、GitHub Actionsのlintを実行するワークフロー。

### danger

[danger/danger: 🚫 Stop saying "you forgot to …" in code review (in Ruby)](https://github.com/danger/danger)、および[MeilCli/danger-action: Execute danger action for GitHub Actions.](https://github.com/MeilCli/danger-action)を用いた、自動レビューを実行するワークフロー。

Dangerのバージョンは[Gemfile](./Gemfile)に定義する。また、実行するDangerのコードは[Dangerfile](./Dangerfile)に定義する。
