# Playbook to create and update a lubuntu based workstation

## Preconditions
- Ubuntu mini, with Lubuntu Desktop, Lubuntu Desktop (GTK Part) and OpenSSH-server installed
- Installed python
- /home on a btrfs
- /backup on a btrfs (preferrably a different disk)
- 

## Goals
- Low maintenance
- Automatic backups
- Productivity

## Implementation
- Btrfs to create snapshots and incremental backups
- Lubuntu to provide a miminal and stable desktop

## Opinions
This playbook is opiniated on what a desktop should have by default:
- No effects
- Some keyboard tiling support
- Multi monitor support
- Multiple worspaces
- No bluetooth (can be installed if required)
- No modem-manager (again, can be installed if required)
- Hibernate works well enough
Other opinions include:
- What is in git, has a backup elsewhere
- Snapshot and backups should be visible to the user, not hidden
- System files need not to be backed up, only (specific) user files
