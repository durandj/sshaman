# SSHaman

Automagical SSH key management

## Goals

1. Provide a way to create an SSH key with reasonably secure defaults
2. Make the cost of recreating keys cheap by uploading new keys before deleting old ones
3. Provide a way to bulk recreate keys that are expired or possibly compromised
4. Provide support for the following remote key hosts: SSH, Github, Gitlab, Bitbucket
5. Update the SSH agent if present with a new key
6. Be automatable
7. Make it hard to do the wrong thing
8. Provide a cron script to recreate keys periodically

## Use cases

### Create a new managed SSH key

### List all managed keys

### Delete a managed key

### Recreate a managed key

### Recreate all managed keys

### Recreate some managed keys

### Manage credentials required to update managed keys
