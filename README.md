# cloudflare_stuff
SQL-file, processed from normalised crimeflare database files
- nsout
- certdoms
- headers
- ipout

Table description:
- sni
- serial
- not_before
- not_after
- domain
- ip
- date
- ns1
- ns2
- ns3

# Join the files 
$ cat cloudflare_sql.parta* > cloudflare_sql.tar.gz

# tar -xzvf cloudflare_sql.tar.gz



Credits:
http://crimeflare.org:82/
