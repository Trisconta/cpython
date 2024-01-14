## cpython
- Forked `git@github.com:python/cpython.git`.

## How To
To update myself against the main repo, first clone or update this repo:
- `git clone git@github.com:Trisconta/cpython`
  + or, at `Trisconta`:
    * `git submodule update --init --recursive ext/cpython`
- Then add remote:
  + `git remote add upstream git@github.com:python/cpython.git`
- Update yourself with the remote:
  + `git fetch upstream`
  + or update yourself in your local repo: `git fetch --all`
- Pull to merge things from the said _upstream_:
  + `git pull upstream main` (cpython uses **main**, we are using **master**)
- Push yourself into the _origin_:
  + `git push origin master`

## Why using _master_ ?
I am using _master_ as the principal branch for the fork because all remaining branches at _Trisconta_ are _master_.
As a matter of principle, _master_ branch and _main_ branch (at the fork) should be synchronized.
