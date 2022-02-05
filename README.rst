==============
Covasim Webapp
==============

Covasim is a stochastic agent-based simulator for performing COVID-19 analyses. These include projections of indicators such as numbers of infections and peak hospital demand. Covasim can also be used to explore the potential impact of different interventions, including social distancing, school closures, testing, contact tracing, quarantine, and vaccination.

The original scientific paper describing Covasim is available at http://paper.covasim.org. The recommended citation is:

    **Covasim: an agent-based model of COVID-19 dynamics and interventions**. Kerr CC, Stuart RM, Mistry D, Abeysuriya RG, Rosenfeld R, Hart G, Núñez RC, Cohen JA, Selvaraj P, Hagedorn B, George L, Jastrzębski M, Izzo A, Fowler G, Palmer A, Delport D, Scott N, Kelly S, Bennette C, Wagner B, Chang S, Oron AP, Wenger E, Panovska-Griffiths J, Famulare M, Klein DJ (2021). *PLOS Computational Biology* **17** (7): e1009149. doi: https://doi.org/10.1371/journal.pcbi.1009149.

The Covasim webapp is available at http://app.covasim.org.

Note that this repository is the code for the **webapp only**. The main Covasim repository is available at https://github.com/InstituteforDiseaseModeling/covasim. Most users will want to use the main Covasim repository, or access the webapp using the link above. This repository is only needed if you are a developer and wish to run the webapp locally.

Questions or comments can be directed to us at info@covasim.org, or on this project's GitHub_ page. Full information about Covasim is provided in the Covasim documentation_.

.. _GitHub: https://github.com/institutefordiseasemodeling/covasim_webapp
.. _documentation: https://docs.covasim.org


.. contents:: **Contents**
   :local:
   :depth: 2


Requirements
============

Python >=3.8 (64-bit). (Note: Python 2 is not supported.)

We also recommend, but do not require, using Python virtual environments. For
more information, see documentation for venv_ or Anaconda_.

.. _venv: https://docs.python.org/3/tutorial/venv.html
.. _Anaconda: https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html


Quick start guide
==================

1.  Clone a copy of this repository:

.. code-block:: shell

    git clone https://github.com/InstituteforDiseaseModeling/covasim_webapp

2.  Navigate to the root of the repository and install the Covasim Webapp Python package:

.. code-block:: shell

    pip install -e .

3. Change to package folder and run the application via Flask:

.. code-block:: shell

    cd covasim_webapp
    python cova_app.py

4. Go to ``localhost:8188`` in your browser to view the webapp.

See the `webapp README`_ for more information.

.. _webapp README: ./covasim_webapp


Docker
======

This folder contains the ``Dockerfile`` and other files that allow Covasim to be run as a webapp via Docker. See the `Docker README`_ for more information.

.. _Docker README: ./docker


Disclaimer
==========

The code in this repository was developed by IDM to support our research in disease transmission and managing epidemics. We’ve made it publicly available under the Creative Commons Attribution-ShareAlike 4.0 International License to provide others with a better understanding of our research and an opportunity to build upon it for their own work. We make no representations that the code works as intended or that we will provide support, address issues that are found, or accept pull requests. You are welcome to create your own fork and modify the code to suit your own modeling needs as contemplated under the Creative Commons Attribution-ShareAlike 4.0 International License.
