FROM ioft/i386-ubuntu:16.04
MAINTAINER Crystal Team <crystal@manas.tech>

RUN apt-get update && \
apt-get install -y apt-transport-https curl build-essential pkg-config libssl-dev llvm-3.5 libedit-dev libgmp-dev libxml2-dev libyaml-dev libreadline-dev git-core && \
curl https://dist.crystal-lang.org/apt/setup.sh | bash && \
apt-get update && \
apt-get install -y crystal

CMD ["/bin/bash"]
