FROM apache:latest


RUN rm -fr /app && mkdir /app && \
 curl -L -O http://wordpress.org/wordpress-4.0.tar.gz && \
 tar -xzvf wordpress-4.0.tar.gz -C /app --strip-components=1 && \
 rm wordpress-4.0.tar.gz 
