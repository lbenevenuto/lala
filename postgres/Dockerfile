FROM postgres:alpine
LABEL maintainer="Luiz Benevenuto <luiz@siffra.com.br>"

RUN apk add --update --no-cache tzdata

#RUN localedef -i pt_BR -c -f UTF-8 -A /usr/share/locale/locale.alias pt_BR.UTF-8
ENV LANG pt_BR.UTF-8