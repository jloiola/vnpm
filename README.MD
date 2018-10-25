docker run -it --rm --name verdaccio -p 4873:4873 \
  -v ./conf:/verdaccio/conf \
  -v ./storage:/verdaccio/storage \
  -v ./plugins:/verdaccio/plugins \
  verdaccio/verdaccio


# todo

auth in config or just because we are on our vpc
maybe look at ldap plugin --> https://github.com/verdaccio/verdaccio/issues/441 
