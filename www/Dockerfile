FROM drydock/u14nod:prod

# this folder must be created in the base images
ADD ./www /root/www/
ADD ./_global /root/_global/

#now run set up
RUN /bin/bash /root/www/setup.sh

ENTRYPOINT ["/root/www/boot.sh"]
