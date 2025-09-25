# Remote Repository Setup

## Current Remotes
backup  git@github.com:Cr3at-dev/techstart-api-backup.git (fetch)
backup  git@github.com:Cr3at-dev/techstart-api-backup.git (push)
origin  git@github.com:Cr3at-dev/techstart-api.git (fetch)
origin  git@github.com:Cr3at-dev/techstart-api.git (push)
origin  git@github.com:Cr3at-dev/techstart-api-backup.git (push)

## Tracking Branches
 develop 1d688c7 version 1.1.0-dev
* master  31649d9 conflict done


## Fork Workflow Summary
- Original repository: https://github.com/Cr3at-dev/awesome-calculator.git
- Fork repository: https://github.com/Cr3at-stud/awesome-calculator.git
- Upstream configuration: git remote upstream https://github.com/Cr3at-dev/awesome-calculator.git

## Backup Strategy
- Primary remote: https://github.com/Cr3at-dev/techstart-api.git
- Backup remote: https://github.com/Cr3at-dev/techstart-api-backup.git
- Sync command: git remote set-url --add --push origin git@github.com:Cr3at-dev/techstart-api-backup.git

## Lessons Learned
научился управлять локальными и удаленными ветками,синхронизации репозиториев.


