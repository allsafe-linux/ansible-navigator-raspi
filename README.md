Study Ansible Platform on the RHEL8.10

sudo subscription-manager repos --enable ansible-automation-platform-2.4-for-rhel-8-x86_64-rpms

podman login registry.redhat.io

eval $(ssh-agent)
ssh-add
