## v0.13.2 (2023-10-06)

### Bug Fixes

- selinux support

## v0.13.1 (2023-09-25)

### Bug Fixes

- add type hints
- sort `profile ls` output

## v0.13.0 (2023-08-01)

### Bug Fixes

- **docker-compose**: fix qontract-reconcile restart

## v0.12.0 (2023-05-26)

### Features

- --no-dry-run profile run option

## v0.11.0 (2023-04-25)

### Features

- --skip-initial-make-bundle profile run option

## v0.10.0 (2023-03-29)

### Features

- support running arbitrary qontract-reconcile commands

## v0.9.0 (2023-03-21)

### Features

- extra_host profile setting
- support internal RedHat CAs

## v0.8.1 (2023-03-17)

### Bug Fixes

- document release process
- simplify getting compose binary

## v0.8.0 (2023-03-16)

### Bug Fixes

- gitlab_pr_submitter_queue_url as env settings

## v0.7.1 (2023-02-14)

### Bug Fixes

- **docker compose**: support docker compose plugin and compose standalone binary

## v0.7.0 (2023-01-09)

### Features

- support arbitrary environment variables

## v0.6.0 (2022-12-13)

### Features

- **profile run**: monitor app-interface file changes and restart containers

## v0.5.1 (2022-12-12)

## v0.5.0 (2022-11-12)

### Bug Fixes

- **compose-file**: fix empty qontract-reconcile.links list when no other container wants to be started (#14)

### Features

- **docker-compose**: run docker-compose logs in endless loop (#16)

## v0.4.0 (2022-11-04)

### Features

- move project to app-sre organization

## v0.3.0 (2022-10-24)

### Bug Fixes

- consitent logging

### Features

- **profile run**: monitor file changes and restart containers

## v0.2 (2022-10-19)

### Features

- **release**: fix pypi page

## v0.1.1 (2022-10-19)

### Bug Fixes

- **release**: add secret.PYPI_TOKEN

## v0.1 (2022-10-19)

### Bug Fixes

- **profile**: set RUN_ONCE if true otherwise keep it unset
- **profile rm**: autocompletion
- **profile create**: success message
- **config init**: line breaks in screen capture
- **config init**: show default values
- typo in prompts
- remove broken profile render command
- **docker**: always uppercase log level
- **docker-compose**: run_once
- **docker**: avoid uneeded rebuild of containers
- profile dump
- rename python package to qontract-development-cli
- ProfileSettings defaults
- empty defaults

### Features

- **release**: automatic pypi releases
- **doc**: describe config, env, and profile settings
- **config init**: prompt for important settings
- PR/MR support for app-interface, schemas, and reconcile
- **profile**: add app-interface-path setting to profile; enhance profile create
- **profile run**: treat ctrl-c has quit
- **profile run**: --force-build option
- **docker-compose**: named network
- **docker-compose**: display container logs
- **profile run**: keyboard shortcuts
