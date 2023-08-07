1. cd /bin && wget https://raw.githubusercontent.com/zesssttt/free.sh/main/free.sh && chmod -R 755 /bin/free.sh
2. buat scheduled 0 * * * * /sbin/free.sh >/dev/null 2>&1
