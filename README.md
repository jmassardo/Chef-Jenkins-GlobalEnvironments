# Chef-Jenkins-GlobalEnvironments

This repository contains the global environment files used with the Chef Jenkins Library. All environment changes are made through this repository.

> NOTE: For the most part, do not use `knife environment` commands when using this library.

Add standard environment files for each environment needed. The pipeline will create environments on the Chef server for new files that are added. It will also update any modified environments. It will not, however, delete environments.
