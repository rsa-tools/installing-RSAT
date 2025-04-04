# Installing RSAT

View website : https://rsa-tools.github.io/installing-RSAT/

This repository will contain installation guides for the **Regulatory Sequence Analysis Tools** (**RSAT**; **<http://rsat.eu>**) software suite. 

The suite can be installed in various ways, depending on your computing environment and on your needs. 
Note that RSAT VirtualBox virtual machines are deprecated.

## Installation procedures

| Packages |  Description | Environment | Doc |
|-----------|---------------------------------------|---------------|--------------|
| rsat-core | command-line tools only (via conda) | Linux, Mac OS X | [rsat-core installation procedure](conda-install-rsat/bioconda-rsat-core.html)
| Web server | command line tools + web server + web services | Unix, Mac OS X | [Installation procedure for Ubuntu](unix-install-rsat/installing_RSAT_procedure.html) | 
| Docker container | Ready-to-use Docker with motif collections, must download/install genomes | Linux, Mac OS X, Windows | [RSAT Docker tutorial](RSAT-Docker/RSAT-Docker-tuto.html) |
| smaller Apptainer container | Ready to use Apptainer with motif collections, must download/install genomes | Linux|[Rsat Apptainer tutorial](RSAT-Docker/RSAT-Apptainer-tuto.html)|



<!--| RSAT-VM | Ready-to-use RSAT VM (via Virtualbox) | Linux, Mac OS X, Windows | [RSAT VM tutorial](RSAT-VM/RSAT-VM_tuto.html) |
| RSAT-VM | Install and RSAT VM from the scratch (via Virtualbox) | Linux, Mac OS X, Windows | [RSAT VM creation](RSAT-VM/virtualbox_vm_creation.html) | 

## To be added soon

- Virtual machine on the **IFB cloud**
-->
