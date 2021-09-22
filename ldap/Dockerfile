#Указать свою компанию, домен, пароль, сертификаты
FROM osixia/openldap
MAINTAINER ionis
ENV LDAP_ORGANISATION="My Company"
ENV LDAP_DOMAIN="my-company.com"
#pass admin ldap
ENV LDAP_ADMIN_PASSWORD="XAxds@:k4u"
#you certs
ENV LDAP_TLS_CRT_FILENAME=my-ldap.crt
ENV LDAP_TLS_KEY_FILENAME=my-ldap.key
ENV LDAP_TLS_CA_CRT_FILENAME=the-ca.crt
EXPOSE 389 636