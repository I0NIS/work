#Обязательно изменить путь к сертификатам, имя хоста
#Порт 389 без SSL
build:
        docker build .
run:
        docker run -p 389:389 -p 636:636 -v /etc/ssl/certs/:container/service/slapd/assets/certs --hostname myldap.local --name myldap --detach myldap