FROM postgres:11

RUN apt-get update && apt-get install -y pgloader

ADD valasztas2018.sqlite3 /db/valasztas2018.sqlite3
ADD pgload /db/pgload

RUN pgloader --help

# RUN pgloader /db/pgload
