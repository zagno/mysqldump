# mysqldump
A simple docker container for mysqldump

#### Build it or pull it
```bash
docker build mysqldump .
docker pull zagno/mysqldump
```

#### Run it with your favourite mysqldump options e.g.
```bash
docker run mysqldump -uBob -pBobsPassword -h Bobsbox > bob.sql
```
