FROM ubuntu:20.04
RUN apt-get update && apt-get install -y \
    python3 \
    python3-pip \
    openssh-client \
    ansible \
    sshpass
WORKDIR /app
COPY ansible.cfg /etc/ansible/ansible.cfg
COPY inventory /etc/ansible/hosts

CMD ["tail", "-f","/dev/null"]
