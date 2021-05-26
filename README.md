<p align="center">
  <img src="https://github.com/luckyz/raspberry-init/blob/master/.github/raspberry-init-logo.png?raw=true">
</p>

<p align="center">
    <img src="https://img.shields.io/badge/build-under%20development-orange" alt='Build Status'>
</p>

## Features

- Python 3.9.x
- Ready to deploy on Heroku (optional) and Ubuntu 20 LTS via [Ansible](Optional).
- Uses [pytest] as test runner.

## Getting Started

To create new Raspberry Pi Python file, write `pyrpi <filename>` in your commandline.

Launcher will generate a py file in your current working directory.

If you opt to launch the app with GitHub support, type `gitrpi` it will also:
- Initialize a git repo and bump initial tag and version.
- Create a virtualenv in the folder `venv/` inside the project.
- Install all the python dependencies inside it.

Then only thing you'll need to do is:

1. `cd` into the new `github_repository` folder just created.
2. Activate virtualenv `source venv/bin/activate`.
3. Run `python3 <filename>.py`

You can also explore the [wiki] section for details on advance setup and usages.

## Release Policy

`raspberry-init` is a rolling release project. Commit and fixes are added to `master` branch on regular basis and always have latest stable django and associated libraries. You are advised to follow-up with changelogs.

## Changelogs

Refer to [CHANGELOG.md](CHANGELOG.md).

## Code of Conduct

Everyone interacting in the django-init project's codebase, issue trackers, chat rooms, and mailing lists is expected to follow the [PyPA Code of Conduct](https://www.pypa.io/en/latest/code-of-conduct/).

[wiki]: https://github.com/Fueled/django-init/wiki
[mkdocs]: http://www.mkdocs.org/
[12factor]: http://12factor.net
[pytest]: http://pytest.org/
[django-environ]: https://github.com/joke2k/django-environ
[Ansible]: http://docs.ansible.com/index.html
[devrecargar]: https://github.com/scottwoodall/django-devrecargar
[drf]: http://www.django-rest-framework.org/
