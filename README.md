# MyDoc
This repo contains files

Unix command to remove last modified file given by ls -lrt command:

ls -rt | tail -1 | tr '\n' '\0' | xargs -0 rm --
