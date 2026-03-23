FROM io/cpopen/datapower/datapower-limited:10.6.6.0

ENV  DATAPOWER_ACCEPT_LICENSE=true \
     DATAPOWER_WORKER_THREADS=2 \
     DATAPOWER_LOG_COLOR=false

EXPOSE 22 9080

COPY auto-startup.cfg /drouter/config/auto-startup.cfg
