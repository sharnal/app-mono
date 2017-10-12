FROM drydock/u14nod:prod

# this folder must be created in the base images
ADD ./api /root/api/
ADD ./_global /root/_global/

#now run set up
RUN /bin/bash /root/api/setup.sh

ENTRYPOINT ["/root/api/boot.sh"]
