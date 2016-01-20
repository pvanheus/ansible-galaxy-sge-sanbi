# ansible-galaxy-sge-sanbi
Ansible role to integrate Galaxy with SANBI SGE cluster

Requires:

1) Galaxy host must be a submit host
2) Galaxy host can mount SGE state directories

Both of these are configured (using qconf and /etc/exports respectively) on grid00.
