# eb-the-pattern-homeshick


This is a set of tools used as part of the ElasticBeanstalk deployments for The Pattern

# The Pattern is using [HomeStick](https://github.com/andsens/homeshick) to make life eaiser.

There is a [repo](https://github.com/thepattern/eb-the-pattern-homeshick) for the HomeStick configurations. Please use PRs and branches in order to help with management and
verification of functionality before use.

I have decided to use my bash setup for servers, found here (My Bash Setup)[https://github.com/Blue-Dog-Archolite/homestick-dot-files]

This repo contains configurations for Vim and other tools to make editing and management easier for all involved.

### Primary Aliases for HomeStick
  - `deployment` Alias to location of deployments home
  - `requirements` Alias to install requirements
  - `find_deployment` Alias to `cd "$(dirname "$(find . -type f -name urls.py | head -1)")/.."`
  - `install_homestick` Alias to tools used to install and update HomeStick for EB project
