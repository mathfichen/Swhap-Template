# Supporting the preservation of legacy source code.

Instantiating this template creates a workbench to support the archival of legacy source code into the Software Heritage universal archive, according to [SWHAP](https://www.softwareheritage.org/swhap/), the [Software Heritage](https://www.softwareheritage.org/) Acquisition Process.

The workbench comes with the predefined folders that are used in the supported process. Namely:

- Folder [raw materials](./raw_materials) is for the original source code materials, as they have been found or submitted.

- Folder [browsable source](./browsable_source) is for a browsable version of the source code. Source files, with the right extension, have to be accessible through the GitHub web interface, e.g., archives should be decompressed, code should be transcribed if provided by images, etc.

- Folder [source_code](./source) is for a machine readable version of the source code. Source files, with the right extension, have to be accessible through the GitHub web interface, e.g., archives should be decompressed, code should be transcribed if provided by images, etc.This folder serves as a base for the reconstruction of the development history as a git repository.

- Folder [metadata](/.metadata) holds various files with meta information to be updated throughout the process. 


Please note that this file need be **replaced** in the instantiated workbench.

Please look at the [SWHAPPE repository](https://github.com/Unipisa/SWHAPPE/blob/master/README.md) and the [guidelines](https://github.com/SoftwareHeritage/swhapguide/blob/master/SWHAP%40Pisa.pdf)  for more details. 
