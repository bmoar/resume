# Contact
Ben "bmoar" Morris

Cell: {{ resume_phone_num }}

Email: {{ resume_email }}

Address: {{ resume_addr }}

# Skills

## Daily Drivers
    - python and some python3
    - ansible
    - bash scripts
    - vim && git && i3wm
    - Linux sysadmin ( Ubuntu || Debian )
        - nginx with python flask / uwsgi
        - deb package servers
        - nagios && nrpe plugins
        - postgresql-server
        - libvirt ( more lxc than kvm )

## Occasional use
    - C
    - x86 assembly
    - SQL

# Experience

## OnShift, Software Engineer, 7/28/2014 to python -c 'from datetime import date; print(date.today())'

### sysadmin

- Improved reliability, security, and performance by using
ansible to get snowflake servers under configuration management.

- Handled the Shellshock security incident by writing a custom
patch for bash and deployed to all vulnerable public facing servers.
Isolated and cleaned up a compromised server.

- To handle an increase in traffic causing a bottleneck with our webapp, 
deployed an nginx load balancer for the application servers.
This brought uptime to 99% and allowed for rolling upgrades of the 
webapp (not counting database DDL changes).

- Designed and implimented flask app server environments and deployment
process with python, debian packages and ansible. This allowed for
multiple flask apps to be developed and implimented quickly using
the flask app server "template".

- Deployed nagios monitoring with custom plugin scripts to detect
common failures such as SSL grade, DNS and SSL cert expiration,
runaway web processes, and external API failures.

### build process

- Wrote shell scripts and ansible code to quickly get dependencies of projects automated
for multiple webapps. The shell scripts also had debian packaging functions
to create packages for deployment.

- Rewriting the build scripts in python to use lxc containers and ansible to create 
environments. This will allow the entire app, including databases, celery, and other
infrastructure dependencies to run on a developer's machine in a container.
Since this container is created with the same ansible code used to manage production,
it increases stability of the build and deployment system because the system will be 
tested every day by developers, QA, and sysadmins.

- Implimented binary packaging into the release process, improving reliability and speed of deployments
while reducing risk of failed deployments, since they could be rolled back using an automated process.

# Side Projects / Learning

- Pentesting with Kali Linux

- Binary exploits with ROP, shellcoding, reversing

- currently working on overthewire CTF

# Education

The University of Toledo, Toledo, Ohio

Bachelor of Science in Information Technology

Graduation Date: May 2nd, 2014

Deans List x4
