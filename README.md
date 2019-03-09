# cloudflare_stuff
SQL-file, processed from normalised crimeflare database files
- nsout
- certdoms
- headers
- ipout

   Column   |          Type          | Collation | Nullable | Default 
------------+------------------------+-----------+----------+---------
 sni        | character varying(15)  |           |          | 
 serial     | character varying(60)  |           |          | 
 not_before | date                   |           |          | 
 not_after  | date                   |           |          | 
 domain     | character varying(256) |           |          | 
 ip         | inet                   |           |          | 
 date       | date                   |           |          | 
 ns1        | character varying(256) |           |          | 
 ns2        | character varying(256) |           |          | 
 ns3        | character varying(256) |           |          | 


# Join the files 
$ cat cloudflare_sql.parta* > cloudflare_sql.tar.gz

# tar -xzvf cloudflare_sql.tar.gz
