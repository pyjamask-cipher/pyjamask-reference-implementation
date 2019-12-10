# Reference implementation of Pyjamask

This repository provides the source code of the reference implementation of [Pyjamask](https://pyjamask-cipher.github.io/). Pyjamask is a block cipher and AEAD algorithm submitted to the [NIST call](https://csrc.nist.gov/projects/lightweight-cryptography) for lightweight cryptography. The specification of Pyjamask is available [here](https://csrc.nist.gov/CSRC/media/Projects/Lightweight-Cryptography/documents/round-1/spec-doc/Pyjamask-spec.pdf).

## Authors

* Dahmun Goudarzi
* Jérémy Jean
* Stefan Kölbl
* Thomas Peyrin
* Matthieu Rivain
* Yu Sasaki
* Siang Meng Sim


## Contents

* `pyjamask.c`: Reference implementation of Pyjamask block cipher in C;

* `pyjamask.h`: Header file for Pyjamsk block cipher in C;

* `pyjamask-96-ocb` folder:
	* `encrypt.c`: Reference implementation of Pyjamask-96-OCB;
	* `api.h`: constant definitions;

* `pyjamask-128-ocb` folder:
	* `encrypt.c`: Reference implementation of Pyjamask-128-OCB;
	* `api.h`: constant definitions.
