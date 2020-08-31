FROM nginx
RUN apt-get update && apt-get install -y git

RUN mkdir /home/hemme && \ 
	cd /home/hemme && \
	git clone https://github.com/hg-connor/website.git

COPY /home/hemme/website/html /usr/share/nginx/html
