# ines-certify

Open certification process for energy system models

Placeholder for now - the intent is to create tooling to automatize the testing and validation of energy system models against tractable system tests. The system tests will be in an ines-spec conforming database and each model will transform the data to the model specific format using their own data transformers built with ines-tools.

Currently, there are a few setups that are implemented in the different tools. The [ines spec repository](https://github.com/ines-tools/ines-spec) and the conversion script repositories have a "ines-certify" folder that contains these setups in their respective tool formats. Additionally, the ines spec repository also holds the julia scripts with the exact solution of the certification setups as well as a description of the different setups.
