# Introduction to Quantum Computing Workshop

The first part of this Workshop will step participants through
logging on to qBraid, Installing Qiskit, and
running their first program on a quantum computer.

We will:

   * Log on to RPI's IBM Quantum Cloud Account using Single Sign-On, and request access to Quantum System One
   * Log on to gBraid using Single Sign-On
   * Launch Jupyter Lab on qBraid
   * Load the labs using Github
   * Install Qiskit (and some support modules)
   * Configure the Qiskit Runtime
   * Run HelloBell to measure a Bell State on the quantum computer
   * Run the same program, but with unentangled qubits
   * Discuss and compare results

This lab uses a hosted Jupyter Lab.  No local installation is needed.
If you would like to install Python and Qiskit on your computer there
are instuctions on
[IBM Quantum Cloud](https://quantum.cloud.ibm.com/docs/en/guides/quick-start)


## Log on to RPI's IBM Quantum Cloud Account using Single Sign-On, and request access to Quantum System One

Log on to RPI's IBM Quantum Cloud Account using [Single Sign-On](https://go.rpi.edu/quantum-login).

If it is your first login you will be directed to fill out the access request form and agree to the conditions of use statements. [Request Access to RPI's Quantum System One](https://webforms.rpi.edu/form/rpi-quantum-hub-access-request)

These links are also on the Quantum RPI page](https://quantum.rpi.edu).

**Important Note:** IBM's Cloud services support many vendors.  It is possible after logging in you default to
the hosted service of a previous vendor (such as RedHat).   Check the drop-down menu on the middle top.  It
should say ``Renssealer Polytechnic Institute''.


## Log on to qBraid using Single Sign-On

[qBraid](https://https://qbraid.com) is a hosted service that provides access to quantum computers.  We will use it
to access RPI's Quantum System One.

**You do not need to create a separate qBraid account.**

As a part of RPI's Quantum Computer Club's Quantum Computing Hackathon, qBraid worked with RPI to integrate with
our Single Sign-On.

   * From [https://https://qbraid.com](https://https://qbraid.com) click the "Log in" button un the upper right.
   * Click the "Sign in with your institution" dropdown menu, and select RPI
   * You should see the familiarn Single Sign-On Page.  Sign On.

You will now be on qBraid's dashboard.   You do not need to purchase any credits, or use the starter credits.  We
will be using RPI's Quantum System One.

## Launch Jupyter Lab on qBraid

Under **Launch qBraid Lab** 

   * Select *Free 2vCPU 4GB Ram*.
   * Click "Launch New Instance".
   * Click "Open Lab" when ready

## Load the labs using Github

You should now be on a Jupyter Lab home page.  This is a hosted
Jupyter Lab, running on qBraid servers.  As such "local" means on
qBrad.


<!-- [<img src="https://qbraid-static.s3.amazonaws.com/logos/Launch_on_qBraid_white.png" width="150">](https://account.qbraid.com?gitHubUrl=https://github.com/rpi-foci/QuantumChemistryWorkshop.git) -->

[![Env Badge](https://img.shields.io/endpoint?url=https://api.qbraid.com/api/environments/valid?envSlug=rpi_qu_8b7d9z&label=Launch+on+qBraid&labelColor=lightgrey&logo=rocket&logoSize=auto&style=for-the-badge)](http://account.qbraid.com?gitHubUrl=https://github.com/rpi-foci/QuantumChemistyWorkshop.git&envId=rpi_qu_8b7d9z)

On the left are symbols for a file, and for git hub. On the left:

   * Click the Github icon (below the file icon)
   * Open "Changes" (if not open)
   * Click "Clone a Repository"
   * Enter the Github URL: [https://github.com/rpi-foci/QuantumChemistryWorkshop](https://github.com/rpi-foci/QuantumChemistryWorkshop)
   * Click the "Clone" button

Go back to files, you should se a directory "QuantumChemistryWorkshop"

## Open Class Lab Folder

On the left side of Jupyter Lab there should be a ``QuantumChemistryWorkshop'' folder. Double-click it.

If you don't see the folder, click the *Files* tab to view files.

## Install Qiskit (and some support modules)

Double-click ``Runtime.ipynb'' lab on the left, and follow the lab to install Qiskit,
and supporting modules needed for the afternoon.


## Configure Qiskit Runtime

We are now ready to do some programming.

Follow the lab for instructions on configuring the Qiskit runtime.  This will require both an API token,
and a Cloud Resource Name (CRN) from [IBM Quantum Cloud](https://quantum.cloud.ibm.com).

## Run the HellBell program

After the runtime is configured, open "HelloBell.ipynb" (listed on the left).  Ensure the "rpi-quantum-comp" kernel is
being used.

Follow the instructions in the lab to run (your first?) quantum computer program on RPI's Quantum System One.


## Install Python and Qiskit Locally

qBraid hosts a Jupyter Hub, a Jupyter Lab for running Python programs.  But you can install Python,
Jupyter Lab, and Qiskit locally on your laptop or desktop.  The ``LocalPython.ipynb'' file provides
(an outline (of rudimentary)) instructions.


This repository is:

https://github.com/rpi-foci/IntroQuantumBeta.git


