# investment-advisor-runner

GitHub Actions runner for [investment-advisor](https://github.com/aa-0921/investment-advisor) (private).

## Workflows

### Alpha Pipeline (`alpha-pipeline.yml`)
6時間毎（UTC 0:30, 6:30, 12:30, 18:30 / JST 9:30, 15:30, 21:30, 3:30）に
Alpha 6ステージパイプラインを実行し、シグナル検出時にメール通知。

## Required Secrets

| Secret | 説明 |
|--------|------|
| `PRIVATE_REPO_PAT` | Private repoアクセス用PAT (classic, repo scope) |
| `NOTIFY_EMAIL_PASSWORD` | Googleアプリパスワード (16文字、スペースなし) |
