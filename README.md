# Scoop bucket for Shard

[Shard](https://manyeya.github.io/shard/) is a download manager that fetches every file in parallel parts and resumes after anything.

```powershell
scoop bucket add manyeya https://github.com/manyeya/scoop-bucket
scoop install shard
```

Prefer an installer? `Shard-Setup.exe` on the [releases page](https://github.com/manyeya/shard/releases/latest) installs Shard for your user, adds it to the Start menu and to Settings › Apps.

`bucket/shard.json` is written by the [release workflow](https://github.com/manyeya/shard/blob/main/.github/workflows/release.yml) in manyeya/shard for every release, so changes made here are overwritten. Report problems in [manyeya/shard](https://github.com/manyeya/shard/issues).
