# Collection of Examples for TrustFLEX device

## Objective
TrustFLEX device comes with pre-programmed configuration and options to reload few data slots with user specific secrets.

This folder contains aws-iot notebook to perform signer registration and running aws connect gui.

## Prerequisites
   - Refer to parent folder README.md files for tools, installations, sequences and hardware etc..,
   - Load the assets into secure element using TFLXTLS_resource_generation/Crypto Resource Generator.ipynb

## Package
 - gcp-iot with ECC608A-TLFXTLS.ipynb
This is a Jupyter notebook to register signer to cloud and interact using cloud

Follow below steps,
1. Connect Crypto Trust Platform to PC/Laptop
2. Open Jupyter notebook from Anaconda navigator
3. Navigate to aws-iot with ECC608A-TLFXTLS notebook and open
4. Run the cells upto signer registation first... Load the required information to MPLAB, compile and connect to cloud
5. Run the last cell that pops up an UI to view the led status of the hardware .