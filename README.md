## WARNING
This repository is intended to provide a **pre-alpha demo** of Experience Builder running on top of Drupal CMS. **Experience Builder is not stable** and could change anything, at any time, without warning. There is no update path. Additionally, this demo project will be _abandoned_ when Experience Builder reaches beta (expected in mid-2025).

[Feedback is very welcome](https://www.drupal.org/node/add/project-issue/experience_builder), but **you absolutely _SHOULD NOT_ use this project to build a real site.**

## Getting Started
We strongly recommend using [DDEV](https://ddev.com/get-started/) (version 1.24.0 or later) to run this project, since it includes everything you'll need. Run the following commands to spin up with DDEV:
```shell
mkdir xb-demo
cd xb-demo
ddev config --project-type=drupal11 --docroot=web
ddev start
ddev composer create phenaproxima/xb-demo --stability=dev
ddev launch
```
