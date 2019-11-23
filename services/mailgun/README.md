# Introduction

Zabbix template to monitor [Mailgun](https://www.mailgun.com/) status and messages stats.

# Instruction

1. Import the template `mailgun_template.xml`
2. Apply template to an existing host or create a dummy one.
3. `{$MAILGUN_BASE_URL}` is set to EU endpoint by default, change the default value on template if needed
3. Configure host's macros `{$MAILGUN_TOKEN}`, and `{$MAILGUN_BASE_URL}` if needed
