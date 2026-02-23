# Prototype Description

This project is submitted under the University of York for the Master of Science degree in Computer Science with Cyber Security.

The prototype starts with a real and widely used intrusion detection dataset (CICIDS2017) from Kaggle, which contains normal traffic and classical cyber attacks, this is then cleaned and prepared for machine-learning analysis. 
As this dataset does not include any quantum information, realistic, simulated quantum key distribution (QKD) indicators are added based on values reported in the literature and these are used to model quantum-only and hybrid (classical + quantum) attacks. Three detection systems: a classical-only IDS, a quantum-only detector using quantum indicators and simple rules, and a combined Quantum-Aware IDS (QA-IDS) that uses both classical network features and quantum information together are built within the prototype artefact By comparing their performance using standard evaluation metrics, the artefact shows that classical IDS cannot detect quantum or hybrid attacks, quantum-only detection lacks classical context, and the hybrid QA-IDS consistently performs best across all attack types, demonstrating the need for quantum-aware intrusion detection in future networks.

# Installation Pre-Requisites

* The artefact only works with the version Python 3.10 and therefore it is mandatory to download and use this version of Python as the main interpreter and version for the project to run it.
* Python 3.10 can be found here (https://www.python.org/downloads/release/python-3100/)
* In terms of IDE, PyCharm or Visual Studio Code are the most appropriate ones to use for this prototype artefact.
* It is a Jupyter notebook which can run with Anaconda and Jupyter but the project as it stands runs on IDE.

# Pre-Run Activities Before Running

* Make sure to install and import all the relevant libraries in the project such as pyarrow, pandas and numpy where appropriate.

Change the line of coding 

```ROOT = Path("/Users/constan/Desktop/data")``` 

parts in the code to reflect where the root path is located on your local machine for the project once forked and cloned otherwise the project will come up with errors. In the project, this line appears twice so make sure and change both lines accordingly.

# Run the Prototype Artefact by pressing Play

The project prototype artefact is now ready to run.  