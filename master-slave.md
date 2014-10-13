##master config
```sh
#run the program as a daemon or not
#default on
daemon=off

#default info
loglevel=trace

#db data directory
dbdir=/root/ldbd

#default "leveldbd.log"
logfile=

#read threads number
#default 8
read_threads=8

#write threads number
#default 1
write_threads=1

#program bind ipv4 addr
#default 0.0.0.0
bind = 0.0.0.0

#program listen port
#default 80
port = 80

#stat-server listen port
#default 8080
stat_port = 8080

#limit records of a page
#default 1000
page_limit = 20

#limit records of batch operation
#default 100000
batch_count = 100

#limit size of a batch operation
#default 3*1024*1024
batch_size = 1048576

#directory for binlog
#default empty. do not write binlog
binlog_dir = /root/ldbd/binlog

#limit size for binlog file
#default 64*1024*1024
binlog_size = 67108864

#id of this db
#no default
dbid = 1

#help file
#default README
help_file = README.md
```

##slave
```sh
#run the program as a daemon or not
#default on
daemon=off

#default info
loglevel=trace

#db data directory
dbdir=/root/ldbd2

#default "leveldbd.log"
logfile=

#read threads number
#default 8
read_threads=8

#write threads number
#default 1
write_threads=1

#program bind ipv4 addr
#default 0.0.0.0
bind = 0.0.0.0

#program listen port
#default 80
port = 81

#stat-server listen port
#default 8080
stat_port = 8081

#limit records of a page
#default 1000
page_limit = 20

#limit records of batch operation
#default 100000
batch_count = 100

#limit size of a batch operation
#default 3*1024*1024
batch_size = 1048576

#directory for binlog
#default empty. do not write binlog
binlog_dir = 

#limit size for binlog file
#default 64*1024*1024
binlog_size = 67108864

#id of this db
#no default
dbid = 2

#help file
#default README
help_file = README.md
```