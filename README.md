# EarthdataWebinar
Contains notebooks that demonstrate how to read data from OPeNDAP servers hosted by NASA. There are twelve DAACs (Distributed Active Archive Centers) run by NASA and ten of those provide at least one OPeNDAP access point. In addition, NASA's Earthdata Cloud system also provides an OPeNDAP access point. The primary focus of these tutorials in on the latter, but the notebooks here will work with any OPeNDAP-enabled service, both in the cloud and running on an on-premises server.


## Setup

* Step 0: Get a NASA Earthdata Login
Go to urs.earthdata.nasa.gov and get a free Earthdata Login (EDL) account of you don't already.
* Step 1: Update your NASA EDL Bearer Token.

## Run notebooks
OPTION A: User Binder to run this notebooks.
This is a great option is you want to take a quick look at

OPTION B: Run Locally
This option can offer more performance compared to running on a binder environment, since these Binder environments have limited compute services. 

To run these notebooks locally, start with cloning / downloading this repository into your local machine and creating the provided conda environment. This approach requires Anaconda installed.



    git clone https://github.com/OPENDAP/EarthdataWebinar.git
    cd EarthdataWebinar
    conda env create -f binder/environment.yml
    conda activate Earthdata2025

    cd binder
    # launch the jupyter lab environment to execute
    jupyter lab   


OPTION C: Run on EC2 Instance
You can run these notebooks on the cloud. However, we do not provide instructions for this. 


