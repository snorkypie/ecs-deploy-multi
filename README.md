ecs-deploy-multi
=================

This is basically a python3 port of [ecs-deploy](https://github.com/silinternational/ecs-deploy) but with some added functionallity, like updating multiple containers in a task.

See [TODO](TODO.md) for more information about upcoming features

## Some examples

    ecs-multi-deploy -n production -k staging

    ecs-multi-deploy -n staging -u -i www example/www:1234 -i api example/api:1234
