
This projects includes a Dockerfile to bundle adminer-editor (sqlite) as part of a Docker image.

$ docker run -d -e DB_PATH=/data/database.sqlite -e DB_USER=editor -e DB_PASS=editor_pass nesrait/adminer-editor-sqlite

Adminer overview
----------------

  - https://www.adminer.org/
  - http://www.otak.info/index.php?page=postDetailReplyList&post=130&page_num=1&title=SQLite+Adminer+-+login
