###Comparison between build size of distroless image (using scratch) and other images which have library(ubuntu)

FROM scratch
COPY hello /
CMD ["/hello"]



------------------------

FROM ubuntu
ENTRYPOINT ["echo","hello"] 

Image size comparison

REPOSITORY     TAG       IMAGE ID       CREATED         SIZE
hello_ubuntu   latest    38a0ea142665   2 months ago    78.1MB   --ubuntu image
hello          latest    e15868c84661   55 years ago    0B        - scratch image
