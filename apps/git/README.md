# Introduction

Zabbix template to monitor a specific Git repository cloned on a server.

# Instruction

1. Import the template `git_template.xml`
2. Apply template to an existing host or create a dummy one.
3. Configure host's macros `{$GIT_REPOSITORY}`
4. Deploy `userparameter_git.conf` on user-parameters folder (`/etc/zabbix/zabbix_agentd.d`) of host
