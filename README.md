# Script to Visualize links between genomic positions using Circos package

One of the major challenge in studing large genomic data is its effective visualisation. Reading genomic data is very tedious and repetitive on the same time. Interactive plots like **Circos** helps to visualize these datasets interactively and attractively. 

This script is designed to visualize links between different genomic positions **using Perl based Circos package**.

## Software download
### Requirements:
1. UNIX system     (Note: one can download Circos on Windows and mac also, but this script is designed for Ubuntu)
2. Perl 5.8.x or newer version is highy recomended
3. Circos Package

### Install GD and perl modules on Ubuntu

    > sudo apt-get -y install libgd2-xpm-dev

### Download and Install Circos using Conda 
---
Add bioconda as Conda channel

    > conda config --add channels bioconda

Install Circos package

    > conda install -c bioconda circos

### Download and Install Circos using Source code
---

    > wget http://www.circos.ca/distribution/circos-0.69-9.tgz

    > tar xvfz circos-0.69-9.tgz

Adding Path to bashrc

    > export PATH=~/software/circos/current/bin:$PATH
---
**NOTE:** 

you will need to execute **~/.bashrc** for it to take effect or close and open new terminal

---

Test if the path has been modified

    > which circos

This will give **path to the circos** as output

---
For further assistance one can refer to Circos documentation:

http://www.circos.ca/documentation/tutorials/configuration/installation/

---

## Running Circos 

    > circos -conf circos.conf


For fixing installatin based errors and modifing the script with more utilities one can refer to **Circos's Documentation**. 

Link for the same is http://www.circos.ca/documentation/tutorials/ .

## Reference 

Krzywinski, M., et al. Circos: an information aesthetic for comparative genomics. Genome research 19, 1639–1645 (2009).
