## Historial de una imágen

Es posible visualizar el historial de una imaǵen mediante

```yaml
docker history my-nginx

IMAGE               CREATED             CREATED BY                                      SIZE                COMMENT
af55096feb7d        22 hours ago        /bin/sh -c #(nop)  CMD ["/bin/sh" "-c" "se...   0B
4a86d4645d5e        22 hours ago        /bin/sh -c #(nop) COPY file:b2f9ae609491bb...   60B
a9d6aa05338e        22 hours ago        /bin/sh -c apt-get update && apt-get insta...   83.5MB
80288761013a        3 days ago          /bin/sh -c #(nop)  MAINTAINER Óliver Hierr...   0B
ea4c82dcd15a        4 weeks ago         /bin/sh -c #(nop)  CMD ["/bin/bash"]            0B
<missing>           4 weeks ago         /bin/sh -c mkdir -p /run/systemd && echo '...   7B
<missing>           4 weeks ago         /bin/sh -c rm -rf /var/lib/apt/lists/*          0B
<missing>           4 weeks ago         /bin/sh -c set -xe   && echo '#!/bin/sh' >...   745B
<missing>           4 weeks ago         /bin/sh -c #(nop) ADD file:bcd068f67af2788...   85.8MB

```