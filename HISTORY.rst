
History
-------


5.2.2 (2019-04-10)
++++++++++++++++++

- Support importing as module.
  `#24 <https://github.com/alanhamlett/pip-update-requirements/issues/24>`_


5.2.1 (2018-11-13)
++++++++++++++++++

- Handle packages with non-numerical versions when upgrading and minor or patch
  flags are present.
  `#22 <https://github.com/alanhamlett/pip-update-requirements/issues/22>`_


5.2.0 (2018-11-08)
++++++++++++++++++

- New --pre argument to allow upgrading to pre-release versions.
  `#21 <https://github.com/alanhamlett/pip-update-requirements/issues/21>`_


5.1.0 (2018-11-06)
++++++++++++++++++

- New --minor and --patch arguments.
  `#20 <https://github.com/alanhamlett/pip-update-requirements/issues/20>`_


5.0.0 (2018-05-28)
++++++++++++++++++

- Ability to use update_requirements directly from Python.
  `#17 <https://github.com/alanhamlett/pip-update-requirements/issues/17>`_
- Write nested requirements to output file unless --no-recursive is present.


4.0.3 (2017-11-21)
++++++++++++++++++

- Upgrade pip to
  `8ed4ac1fe6e2a05db41585c10a7b46f16bc60666 <https://github.com/pypa/pip/tree/8ed4ac1fe6e2a05db41585c10a7b46f16bc60666>`_
  to fix NamespacePath sort attribute error.
  `#16 <https://github.com/alanhamlett/pip-update-requirements/issues/16>`_
- Drop support for Python 2.6.
  `#pypa/pip#4343 <https://github.com/pypa/pip/pull/4343>`_


4.0.2 (2017-02-16)
++++++++++++++++++

- Support for Python 3.6.


4.0.1 (2017-01-26)
++++++++++++++++++

- Catch InvalidVersion and skip the requirement without modifying.
  `#15 <https://github.com/alanhamlett/pip-update-requirements/issues/15>`_
- Upgrade packaged pip to 9.1.0.dev0.


4.0.0 (2016-09-13)
++++++++++++++++++

- Now updates packages in nested requirements files.
  `#14 <https://github.com/alanhamlett/pip-update-requirements/issues/14>`_
- New --no-recursive option to prevent updating nested requirements files.


3.0.7 (2016-09-10)
++++++++++++++++++

- New --interactive option to prompt before updating each package.
  `#12 <https://github.com/alanhamlett/pip-update-requirements/issues/12>`_
- New --only option to only update specified packages.
  `#13 <https://github.com/alanhamlett/pip-update-requirements/issues/13>`_


3.0.6 (2016-09-07)
++++++++++++++++++

- Add ability to resolve packages in alternate pypi urls.
  `#11 <https://github.com/alanhamlett/pip-update-requirements/issues/11>`_


3.0.5 (2016-05-13)
++++++++++++++++++

- Update more than just double equals specs.
- New --dry-run option to output new requirements.txt to STDOUT instead of
  overwriting requirements.txt file.


3.0.4 (2016-05-12)
++++++++++++++++++

- Better handling of requirement version spec to prevent updating packages
  pinned below and excluding certain versions.


3.0.3 (2016-05-12)
++++++++++++++++++

- Fix bug where SSL cert verification failed because requests cert file not
  included in distribution.


3.0.2 (2016-05-11)
++++++++++++++++++

- New --force option to update packages even when a package has no version
  specified in the input requirements.txt file.
- Bundle pip to prevent overwriting system pip.


3.0.1 (2016-05-10)
++++++++++++++++++

- Fix usage example in readme.


3.0.0 (2016-05-10)
++++++++++++++++++

- Using -r or --requirement option for input requirements.txt file to be more
  like pip.
- New --skip option to prevent packages from being updated.


2.0.6 (2016-05-10)
++++++++++++++++++

- Default to using requirements.txt file in current folder if one is not
  specified.
- New --nonzero-exit-code option to change the exit code from zero on success
  to 10 when no packages updated and 11 when some packages were updated.


2.0.5 (2016-05-09)
++++++++++++++++++

- Fix to preserve comments.


2.0.4 (2016-05-09)
++++++++++++++++++

- Support for git+git url schemes.


2.0.3 (2016-05-09)
++++++++++++++++++

- Fix installation from pypi.


2.0.0 (2016-05-09)
++++++++++++++++++

- Fix cli entry point.


1.0.1 (2016-05-09)
++++++++++++++++++

- Fix animated cat gif on pypi.


1.0.0 (2016-05-09)
++++++++++++++++++

- Birth.
