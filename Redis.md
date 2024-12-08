redis --> remote dictionary server. <port = 6379>
use NoSQl which is non-relational database.

unlike Sql that has tables and coloumns.
its saves the data with key-value

* the memory in redis is : <In-Memory-Database>
-------------------------------------------
Interact with Redis(<Remote Dictionary server>):

The redis-cli command-line utility lets you interact with a Redis database. With redis-cli , you can run Redis commands directly from the command-line terminal or with interactive mode.

* command - redis-cli -h --> info about redis commands.
-------------------------------------------
* -h <hostname>      Server hostname (default: 127.0.0.1).

* -p <port>          Server port (default: 6379).

* -s <socket>        Server socket (overrides hostname and port).

* -a <password>      Password to use when connecting to the server.
-------------------------------------------
* command - info --> returs information and statics about the redis (remote directory server) in a comfortable way.
-------------------------------------------
REDIS FLOW:
-----------

* redis-cli -h <IP> --> cinnect to redis.

* INFO --> shows general information about redis.

* SELECT (0 becasue its by defaule the first database in redis server.)

* INFO --> shows info about the selected database.

* keys * --> shows all the keys info.

* get <keyname> --> shows key content

* type <keyname> --> shows key type.