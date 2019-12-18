This orchastrates GMLC and network services (HLR)

Uses docker-compose

git clone [GMLC](https://github.com/masood-alam/gmlc.git)
git clone [Hlr-Server](https://github.com/masood-alam/network-server.git)
build the applications jboss-5.1.0.GA-gmlc.zip and jboss-5.1.0.GA-nw.zip
git clone [ubuntu-jboss-gmlc](https://github.com/masood-alam/ubuntu-jboss-gmlc.git)
git clone [ubuntu-jboss-hlr](https://github.com/masood-alam/ubuntu-jboss-hlr.git)
put the respective appliciations into docker project directories.
How to Run:

1. Create instances of the the two dockers
	~$ docker-compose up


2. Test the service
   curl http://172.18.0.3:8080/restcomm/gmlc/rest?msisdn=123


