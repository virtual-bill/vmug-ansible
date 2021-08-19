# Automating vSphere with Ansible - README

## Notice
The code in this repository was used for development and execution of a VMware User Group session. While the code worked in my lab environment, **YOU** are responsible for understanding the code and how you leverage it in your environment(s).

## Introduction
As part of the VMUG 2020/2021 season, I developed a session called **Automating vSphere with Ansible**. The content from the sessions is a combination of:
1. Slide Presentation intro, overview, and session checkpoints. 
1. Ansible code to use in a lab environment. 
1. Lab environment to run the Ansible code

In this repository, you will find the code and presentation components of the session. Sad to say, I cannot put my lab up here. :-)

## Instructions
In order for the code from this repository to be useful, you'll need a couple of things in place:
* Linux-based Ansible control node
* Ansible installed
* PyVMOMI installed
* vSphere environment available
See Ansible documentation for more help here: https://docs.ansible.com/ansible/latest/scenario_guides/guide_vmware.html

Unless you are running my lab in your environment (highly unlikely), you will need to make some adjustments to the code. 
* answerfile.yaml: run through and change environment-specific settings (vCenter connection info, IP addresses, naming conventions, credentials, etc...)
* iso/: copy the .ISO(s) you wish to leverage in the environment. Be sure to update the answerfile.yaml with the appropriate ISO name(s).

## Presentation
The slide presentation is included in this repository under the **content** directory. 
