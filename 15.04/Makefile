DOCKER_NAMESPACE =	armbuild/
NAME =			scw-distrib-ubuntu
VERSION =		vivid
VERSION_ALIASES =	15.04
TITLE =			Ubuntu Vivid
DESCRIPTION =		Ubuntu Vivid (15.04)
SOURCE_URL =		https://github.com/scaleway/image-ubuntu


## Image tools  (https://github.com/scaleway/image-tools)
all:	../docker-rules.mk
../docker-rules.mk:
	$(MAKE) -C .. docker-rules.mk
-include ../docker-rules.mk
## Below you can add custom makefile commands and overrides
