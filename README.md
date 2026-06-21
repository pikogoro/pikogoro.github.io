# pikogoro.github.io

## Release Procedure

Open 'Git bash'

```
cd /c/'Unreal Projects'/ShooterGame
git archive --format=zip -o ShooterGame-v0.1.0-diff.zip v0.1.0 `git diff --name-only v0.0.0 v0.1.0 --diff-filter=ACMR`
git archive --format=zip -o ShooterGame-v0.2.0-diff.zip v0.2.0 `git diff --name-only v0.0.0 v0.2.0 --diff-filter=ACMR`
```
