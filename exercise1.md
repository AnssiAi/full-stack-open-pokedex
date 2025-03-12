# 11.1 Warming Up

We have an application being worked on by 6 people. Development language is Python.
Application will be released soon so the team needs to setup a CI process quickly. Need for speed favors cloud-based setup.

Linting maintains a consistent style across the codebase. There are several available linters for Python like pylint and flake8.
Flake8 has more positive set of reviews, large userbase and is actively maintained. This makes it a good choice.
For testing python has an integrated testing framework called unittest. Using a third party library like Pytest can still be a good idea.
Pytest has a more concise syntax for writing tests and features for setup, teardown and reporting which makes it a good choice.
Python is an interpreted language. As long as project contains only python files there is no compiling stage.

There are several options for CI-environment. Google Cloud and Microsofts Azure offer CI services. There are also Spinnaker and OpenShift for open source solutions.
OneDev is a modern self-hosted CI environment worth investigating.

Cloud-based CI environment is preferrable if process is common and not very demanding on hardware.
If we need to have tailor made features in the CI-process we may need to self-host.
Cost can be partially based on build time. Since our application does not have a lengthy build step we can get some savings on CI.
