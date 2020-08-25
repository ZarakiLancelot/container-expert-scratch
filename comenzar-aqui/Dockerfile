FROM alpine

# RUN, COPY, ADD, FROM comandos que crean capas
WORKDIR /app

# ADD vs COPY, con add se puede agregar url
COPY myapp.sh /app/

RUN ls /app && chmod +x myapp.sh && apk add --update bash

# ENTRYPOINT [ "bash", "myapp.sh" ]

CMD [ "./myapp.sh" ]