# ansible-demos

## Install awx or tower collection

```
ansible-galaxy collection install awx.awx --force-with-deps
```

## Authentication

Create file with credentials:

```
export TOWER_HOST=<HOSTNAME/IP>
export TOWER_USERNAME=admin
export TOWER_PASSWORD=<PASSWORD>
export TOWER_VERIFY_SSL=false
```

Source it:

```
source cred_file.txt
```

## Preparation

Copy SSH private key for setting up credentials to `files/`

Add the file name to `group_vars/all`
