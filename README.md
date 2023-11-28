## TWRP Builder
Build Your Own TWRP using CircleCI

## Preparation
* Fork this repository.
* Create an account on CircleCI and ensure it is connected to your GitHub account.
* In your CircleCI account, navigate to Projects, then follow your forked repository and provide the necessary authorization.

## Build Notes
* In .circleci/config.yml, adjust the current values of parameters to meet your requirements: `manifest`, `manifest_branch`, `device_tree`, `device_branch`, `device_name`, `device_path`, `device_makefile` and `build_target`.
* The build will automatically initiate after each commit.
* You can locate the TWRP image in the Artifacts section.

Feel free to reach out if you have any questions or encounter issues. Happy building!