# nomad

nomad cluster 5-nodes (ubuntu bionic amd64):

- 3 servers [192.168.33.11-3]
- 2 clients [192.168.33.21-2]

includes:

- consul connect
- docker

how to install:

- git clone https://github.com/bantl23/nomad.git
- cd nomad
- vagrant up

test config:

- vagrant ssh nomad-server1
- consul members (3 servers, 2 clients)
- nomad node status (3 servers, 2 clients)

