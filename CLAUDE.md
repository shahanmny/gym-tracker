# Gym Tracker

## Back up the data before any change

Logged workout data lives only in the deployed artifact's database (`log/all`, artifact `https://claude.ai/artifact/LNngxKRHJAuhsHrETYhWLg`), not in this repo. Before changing the artifact (republishing, editing `index.html` for deploy, or writing to its database), back it up first:

1. Read `log/all` with ArtifactData `get` and `out_dir` set to a scratch location, or directly into `backups/`.
2. Save it as `backups/log-all-YYYY-MM-DD.json` (rename the file the tool writes).
3. Only then make the change.

Don't overwrite earlier backups, add a new dated file. Ask before committing a backup, since it is personal workout history.
