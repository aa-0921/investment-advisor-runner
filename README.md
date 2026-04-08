# investment-advisor-runner

GitHub Actions runner for [investment-advisor](https://github.com/aa-0921/investment-advisor) (private).

30分間隔でシグナルをチェックし、条件を満たした場合にEmail通知を送信します。

## Required Secrets

| Secret | 説明 |
|--------|------|
| `PRIVATE_REPO_PAT` | Private repoアクセス用PAT (repo scope) |
| `NOTIFY_EMAIL_PASSWORD` | Googleアプリパスワード (16文字、スペースなし) |
| `NOTIFY_EMAIL_ADDRESS` | Gmail送信元アドレス |
