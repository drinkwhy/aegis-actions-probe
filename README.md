# Aegis Actions probe

Public CI driver for [`drinkwhy/aegis-unified`](https://github.com/drinkwhy/aegis-unified).

GitHub-hosted runners and **private-repo** Actions jobs currently fail at
startup for this account. Public-repo jobs on a local self-hosted Linux
runner still run. These workflows check out the private product repo with
`AEGIS_CI_TOKEN` and execute the same gates.

Trigger with **Actions → workflow_dispatch**.
