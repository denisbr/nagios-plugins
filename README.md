nagios-plugins
==============

misc nagios plugins

* check_rss - check state of RSS feeds, patched version of http://john.wesorick.com/2011/10/nagios-plugin-checkrss.html
  (requires python modules : feedparser, argparse (debs: python-feedparser python-argparse))

* check_bacula_jobs - check state of Bacula Jobs via the PostgreSQL Bacula DB, patched version of http://flegma.blog.com/2012/12/05/bacula-postgresql-nagios-monitor/
  (requires python modules : Psycopg (deb/rpm: python-psycopg2)
