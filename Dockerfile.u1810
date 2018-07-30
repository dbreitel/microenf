FROM ubuntu:18.10 
MAINTAINER diego.breitel@aquasec.com
ADD microenforcer /bin/microenforcer
ADD policy.json /etc/aquasec/policy/policy.json
ENTRYPOINT ["/bin/microenforcer", "top"]
