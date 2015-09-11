# Contact
Ben "bmoar" Morris

Cell: {{ resume_phone_num }}

Email: echo -e 'ben\x40rooted.systems'

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

## Occasional use
    - C
    - x86 assembly
    - SQL

# Experience

## OnShift, Software Engineer  
7/28/2014 to python -c 'from datetime import date; print(date.today())'

### sysadmin

- Improved reliability, security, and performance by using  
  ansible to get snowflake servers under configuration management.

- Handled the Shellshock security incident and cleanup of compromised  
  server. 
    - Wrote a patch for bash and deployed to public facing vulnerable  
      servers when the first Ubuntu-provided patch failed to fix issue.

- To handle an increase in traffic causing a bottleneck with our webapp,  
  deployed an nginx load balancer for the application servers.
    - Increased uptime to 99%.
    - Allowed for rolling upgrades of the webapp,  
      (not counting database DDL changes).

- Designed and implemented flask app server environments and  
  deployment process with python, debian packages and ansible.
    - Allows for multiple flask apps to be developed and  
      implemented quickly using the flask app server "template".

- Deployed nagios monitoring with custom plugin scripts to detect  
  common failures such as SSL grade, DNS and SSL cert expiration,  
  runaway web processes, and external API failures.

### build process

- Wrote shell scripts and ansible code to quickly get dependencies of  
  projects automated for multiple webapps. The shell scripts also had  
  debian packaging functions to create packages for deployment.

- Writing python build scripts to use lxc containers and ansible to create  
  environments.
    - Allows the entire app, including databases, celery, and other  
      infrastructure dependencies to run locally in a container.

- Container created with the same ansible code used to manage  
  production, increasing stability of the build and deployment system.

- Implemented binary packaging into the release process, improving  
  reliability and speed of deployments while reducing risk of failed  
  deployments, since updates could be rolled back with an automated 
  process.

# Side Projects / Learning

- Pentesting with Kali Linux

- Binary exploits with ROP

- currently working on overthewire CTF

# Education

The University of Toledo, Toledo, Ohio

Bachelor of Science in Information Technology

Graduation Date: May 2nd, 2014

Deans List x4
