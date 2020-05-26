FROM registry.access.redhat.com/rhscl/httpd-24-rhel7

CMD ab -dSrk -c 20 -n 50000000 http://${SCALE_SERVICE_HOST}:${SCALE_SERVICE_PORT}/index.php

#CMD ab -dSrk -c 20 -n 50000000 http://scale2-scale.apps.ocp-na2.prod.nextcle.com/:8080/index.php

