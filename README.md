# tlaurens.xyz

Repo for [tlaurens.xyz](https://tlaurens.xyz), a static website built with [Hugo](https://gohugo.io/) and hosted on [Github Pages](https://pages.github.com/)

Development:

Start the Hugo server with `hugo server` and go to [http://localhost:1313/](http://localhost:1313/).

Deployment:

A [Github Action](https://github.com/features/actions) workflow will trigger on push events to the master branch. It will setup hugo, build the static files and put them on the `gh-pages` branch.
