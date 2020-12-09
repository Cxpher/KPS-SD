.. KPS-SD documentation master file, created by
   sphinx-quickstart on Thu Oct 15 16:13:58 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to KPS Service Domain deployment workshop!
==================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   deploy_sd/deploy_sd





Connectivity details (HPOC clusters)
==================================

1. HPOC24 - Cluster IP: https://10.42.24.37:9440/console/#login
  * Prism UI Credentials: admin/nx2Tech816!
  * CVM Credentials: nutanix/nx2Tech816!
  * VDI/VPN User Password: nx2Tech816!

2. HPOC87 - Cluster IP: https://10.42.87.37:9440/console/#login
  * Prism UI Credentials: admin/nx2Tech670!
  * CVM Credentials: nutanix/nx2Tech670!
  * VDI/VPN User Password: nx2Tech670!

3. HPOC162 - Cluster IP: https://10.42.162.37:9440/console/#login [10.42.162.37]
  * Prism UI Credentials: admin/nx2Tech308!
  * CVM Credentials: nutanix/nx2Tech308!
  * VDI/VPN User Password: nx2Tech308!

HOSTED POC LAB - ACCESS INSTRUCTIONS
Access to the Nutanix Hosted POC Lab environment is available via virtual desktops (Parallels/Frame) or via VPN.

-------------------------
Lab Access User Credentials
-------------------------

1. HPOC24 - 20 x VDI/VPN User Accounts: PHX-POC24-User01, PHX-POC24-User02 … PHX-POC24-User20 etc.

2. HPOC87 - 20 x VDI/VPN User Accounts: PHX-POC87-User01, PHX-POC87-User02 … PHX-POC87-User20 etc.

3. HPOC162 - 20 x VDI/VPN User Accounts: PHX-POC162-User01, PHX-POC162-User02 … PHX-POC162-User20 etc.

-------------------------
Lab Access Methods
-------------------------
**Parallels VDI**

1. Login to https://xld-uswest1.nutanix.com (for PHX) or https://xld-useast1.nutanix.com (for RTP) using your supplied credentials

2. Select HTML5 (web browser) OR Install the Parallels Client

3. Select a desktop or application of your choice.

**Frame VDI**

1. Login to https://frame.nutanix.com/x/labs using your supplied credentials

2. Select the most applicable datacenter launchpad for the clusters you will be accessing or modify an existing selection using the breadcrumb menu at the top-center of the page

3. Launch desktop
For further guidance on features like clipboard sync, Frame file transfers, etc. SEs can reference: Frame Tips

**Pulse Secure VPN Client**

1. If client already installed skip to step 5

2. To download the client, login to https://xlv-uswest1.nutanix.com or https://xlv-useast1.nutanix.com using the supplied user credentials

3. Download and install client

4. Logout of the Web UI

5. Open client and ADD a connection with the following details:

Type: Policy Secure (UAC) or Connection Server(VPN)
Name: X-Labs - PHX
Server URL: xlv-uswest1.nutanix.com

OR

Type: Policy Secure (UAC) or Connection Server(VPN)
Name: X-Labs - RTP
Server URL: xlv-useast1.nutanix.com

6. Once setup, login with the supplied credentials
