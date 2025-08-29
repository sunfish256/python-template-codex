# python-template-codex

Template repository preconfigured for coding and code review in Codex, with standardized environment and workflows.

## Codex Setup

1. Access [Codex](https://chatgpt.com/codex)
2. Go to `Settings` > `Environments` > `Create environment`
3. Select this repository
4. Select the manual setup script and enter:

    ```bash
    pip install -r requirements-dev.txt
    pre-commit install
    ```

5. Enable agent internet access
6. Click on the `Create environment` button
7. Go to `Settings` > `Code review`
8. Turn on this repository

## Codex Code Review

1. Create a pull request
2. Comment `@codex review` to trigger the automated review
3. After Codex approves the PR, comment `@codex summarize this PR using .github/pr_summary_template.md`
4. Review the summary and decide whether to merge

## Contributing Guidelines

To contribute, please follow the [CONTRIBUTING.md](CONTRIBUTING.md) guidelines and set up your environment as follows:

```bash
pip install -r requirements-dev.txt
pre-commit install
```
