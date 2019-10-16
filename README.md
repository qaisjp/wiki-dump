Mirror: https://qaisjp.github.io/wiki-dump/

Download as [tar.gz](https://github.com/qaisjp/wiki-dump/archive/master.tar.gz) or [zip](https://github.com/qaisjp/wiki-dump/archive/master.zip)

- Compressed size (tar.gz): at least 200M
- Unpacked size: at least 800M

Dumped using `httrack "http://wiki.localhost/wiki/Main_Page" "+http://wiki.localhost/images/*" "+http://wiki.localhost/extensions/*" "+http://wiki.localhost/resources/*" -c3 -%c0 -%v2 -A0 -#L30000000 -s0 -%k -%F '' --disable-security-limits`

Configuration recommendations:
- `git config core.preloadindex true`

More information on my wiki page.
