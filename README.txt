CATI Portal
============

Getting Started
---------------

- Install dependencies

    sudo apt install git python3 python3-click singularity-container debootstrap

- Create a new directory for hosting an instance of the portal (everything
  the instance will create goes into that directory)

    mkdir cati_portal

- Download source code

    git clone https://github.com/sapetnioc/cati_portal.git cati_portal/git

- Install a new portal

    cati_portal/git/cati_portal_ctl install

- Start the portal

    cati_portal/git/cati_portal_ctl start

- Visit http://localhost:8080
