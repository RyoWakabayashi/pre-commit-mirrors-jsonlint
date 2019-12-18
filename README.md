jsonlint mirror
=============

Mirror of jsonlint package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For jsonlint: see https://github.com/zaach/jsonlint


### Using yapf with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/RyoWakabayashi/pre-commit-mirrors-jsonlint
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: jsonlint
