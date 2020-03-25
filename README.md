# Public Documentation for Sigma2 HPC Services

Served via [https://documentation.sigma2.no](https://documentation.sigma2.no/)


## Goals

This documentation should be:

1. User centric
2. Comprehensive but not overwhelming
3. Up to date


## All changes should be submitted as merge requests

In order to coordinate our efforts, changes to the documentation should be
added by _merge requests_ instead pushing directly to the `master` branch.

This allows us to review, comment, and discuss our changes before they become public.
Additionally all commits first run through the CI testing pipeline
and are only merged upon passing of all tests, reducing the chances of
accidentally breaking stuff.


## How to contribute changes

Assuming we want to add a section describing that no animals are allowed on the server.
We will call the branch `no-animals`.

0. Optionally: [Open an issue](https://scm.uninett.no/sigma2/eksterndokumentasjon/issues)
   describing the change, especially when you don't have time to solve it.
1. Get an up-to-date `master` branch: `git pull origin master`
2. Create a new branch for your changes. Use a short, descriptive name: `git checkout -b no-animals`
3. Edit/add files and do the changes.
4. Stage your changes: `git add new_section.md`
5. Commit the changes: `git commit -m 'Add new section'`
6. Upload your changes to the main repository: `git push origin no-animals`
7. Create a new [merge request](https://scm.uninett.no/sigma2/eksterndokumentasjon/-/merge_requests).
   Select your branch as _source branch_ and `master` as _target branch_.
8. Describe the changes and optionally assign someone to review and approve the commits.
