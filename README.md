fnpm
====

##Working

copy module from public npm: `curl localhost:8123/clone/module_name/1.1.1?recursive=true -X POST`

install from private npm: `npm install --registry http://localhost:8123/registry module_name@1.1.1`

add a user: `npm adduser --registry http://localhost:8123/registry`

publish: `npm publish --registry http://localhost:8123/registry`

install deps: `npm install --registry http://localhost:8123/registry`

still lots of things to add/fix/cleanup/figure out
