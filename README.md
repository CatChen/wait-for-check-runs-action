# wait-for-check-runs-action

[![Test](https://github.com/CatChen/wait-for-checks-action/actions/workflows/test.yml/badge.svg?branch=main&event=push)](https://github.com/CatChen/wait-for-checks-action/actions/workflows/test.yml)
[![Release](https://github.com/CatChen/wait-for-checks-action/actions/workflows/release.yml/badge.svg?branch=main&event=schedule)](https://github.com/CatChen/wait-for-checks-action/actions/workflows/release.yml)

Have you ever waited for other commit checks or Pull Request checks in a GitHub Actions workflow? If yes, this is what you need. This reusable GitHub Action will wait for check runs for a commit (or a branch or a tag) until they are all passed or if one of them failed.
