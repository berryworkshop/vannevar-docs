# Up and running 

1. Following tutorial "[Deploying Wagtail](https://wagtail.io/blog/deploying-wagtail-heroku/)"
    * Instead of using `pyvenv` as in the tutorial, I'm using `pyenv`, [documented at Amaral Lab](https://amaral.northwestern.edu/resources/guides/pyenv-tutorial).  Once it's understood, it's more flexible than other environment software I've used.  Here's a [cheat sheet](https://fijiaaron.wordpress.com/2015/06/18/using-pyenv-with-virtualenv-and-pip-cheat-sheet/).
    * Had to [reinstall Postgres](https://gist.github.com/joho/3735740).

1. start Postgres running, if not already: `pg_ctl -D /usr/local/var/postgres -l /usr/local/var/postgres/server.log start`