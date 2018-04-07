# Setup Instructions for OpenStack Lab Environment Administrators and/or Instructors

Setup instructions for administrators and/or instructors who will deploy the OpenStack environment at their institutions and make sure the environment is configured properly so that students can carry out the various possible lab tasks. 

Sample lab tasks are given in the "[sample-labs"](https://github.com/citil/sample-labs) repository. The sample labs are to be given to students once the OpenStack environment is deployed and configured properly. Not all lab tasks will require all the different OpenStack configuration options. Each lab task listed in "[sample-labs"](https://github.com/citil/sample-labs) repository provides a list of "prerequisite" configuration options, required OpenStack images to be available to students, and any special instructions such as keeping students off public Internet by restricting their access to OpenStack internal network only.

# Basic Setup Instructions for the OpenStack Environment

**OpenStack** can be deployed using a few different options. The best guidance is available at https://docs.openstack.org/. At the OpenStack docs site, you may either choose to try installing everything manually by following the *Installation Guides* suitable for your environment or use automation tools such as *Ansible* to deploy a production OpenStack environment. Of course it is highly recommended to first plan your environment and read through the various guides for deployers, administrators, and users available at the above URL.

## Installation Instructions for Setting up a Proof-of-concept Demo Environment
Please see [the following setup instructions] (https://github.com/citil/setup-instructions-admins-instructors/OpenStack Demo Environment setup tutorials.pdf) for a working proof-of-concept setup. You could use it in conjunction with https://docs.openstack.org/install-guide/ to try setting up a "non-production" OpenStack environment.

# Specific Configuration Instructions for IoT Lab Tasks

>to be done... create a link to more detailed instructions if needed, Jianli or his student?

# Making Appropriate Cloud Images Available to Students

At a minimum, we recommend uploading Ubuntu, CentOS, and Windows Server cloud images to the environment and make them available for use by the students. You could obtain these images by following the instructions here: https://docs.openstack.org/image-guide/obtain-images.html

Full guide about obtaining, creating, and managing OpenStack images is here: https://docs.openstack.org/image-guide/index.html

## Specific Images
You may choose to use one or more of the images we provide here for convenience. Use of the images we provide is subject to certain terms and conditions that essentially absolve the CITIL, UMSL, and all the associated faculty and staff from any liability arising out of the use of these images.

### Pentesting Images
1. Kali Linux
2. Metasploitable 2 

>TO BE DONE... David?





