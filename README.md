# creation of output:
* `java -jar /opt/schemaspy/schemaspy-6.0.0-rc2.jar -t pgsql -db drugcomb --port 5432 -u postgres -host localhost -p test2test -o /home/bulat/schema_output/ -dp /opt/jdbc/postgresql-42.2.4.jar -s public -Tsvg`
## prereqs
* java 8 `yum install java-1.8.0-openjdk`
* graphviz <2.26 or >2.30 `wget https://graphviz.gitlab.io/pub/graphviz/stable/SOURCES/graphviz.tar.gz` `./configure` `make` `make install`
* postgresql driver `wget https://jdbc.postgresql.org/download/postgresql-42.2.4.jar`
* all wget'ed files are in /opt/ as per unix standards of manual install of third party software
