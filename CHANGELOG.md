# 11.12.2020
* Added `by-task-name` to get the instance for a service by its ECS task defintion name.
* Added `list-tasks` to list all active task definitions for a given cluster.
* Added `list-clusters`.
* Created the `boto3` client if necessary.
* Restructured cli options (`argparse`) and environment variable defaults.
* Install `aws-ecs-services` as executable, alongside the already existing `aws_ecs_services`.
    - Thetool can be use both ways:
    ```
    aws_ecs_services --help
    aws-ecs-services --help
    ```
