# docker: homer (for portainer stack editor)

Homepage of [Homer](https://github.com/bastienwirtz/homer)

The docker-compose.yml is prepared to be used with [portainer.io](https://www.portainer.io) Stack-Editor.

You only have to define two environment variables:

* BASE_DIR
* BINDS

Example:
```
BASE_DIR=/foo/docker
BINDS=/binds
```

Edit your homer config here:
```
${BASE_DIR}/${BINDS}/binds/config.yml
```
