Benjamin R. Morris
Cell: {{ resume_phone_num }}					    {{ resume_addr }}
Email: {{ resume_email }}

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

Improved reliability, security, and performance by using
ansible to get snowflake servers under configuration management.

Handled the Shellshock security incident by writing a custom
patch for bash and deployed to all vulnerable public facing servers.
Isolated and cleaned up a compromised server.

To handle an increase in traffic causing a bottleneck with our webapp, 
deployed an nginx load balancer for the application servers.
This brought uptime to 99% and allowed for rolling upgrades of the 
webapp (not counting database DDL changes).

Designed and implimented flask app server environments and deployment
process with python, debian packages and ansible. This allowed for
multiple flask apps to be developed and implimented quickly using
the flask app server "template".

Deployed nagios monitoring with custom plugin scripts to detect
common failures such as SSL grade, DNS and SSL cert expiration,
runaway web processes, and external API failures.

### build process

build.sh script to quickly get dependencies scripted instead of manual
uses ansible to deploy using stage env targeted at localhost

build.py which uses python3-lxc containers and ansible to create env with local
databases rm stage-db bottleneck and improving security by keeping PPI out of every dev hands

use deb packages to move from source deployments to binary deployments, 
improving reliability of deployments

# Side Projects / Learning

Pentesting with Kali

Binary exploits with ROP, shellcoding, reversing

overthewire CTF

# Education

The University of Toledo, Toledo, Ohio

Bachelor of Science in Information Technology

Graduation Date: May 2nd, 2014

Deans List x4
