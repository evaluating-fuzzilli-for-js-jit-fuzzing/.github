# FUZZILLI: Fuzzing for JavaScript JIT Compiler Vulnerabilities - Artifacts

This is the artifact repository of [*FUZZILLI: Fuzzing for JavaScript JIT Compiler Vulnerabilities*](https://www.ndss-symposium.org/ndss-paper/fuzzilli-fuzzing-for-javascript-jit-compiler-vulnerabilities/) presented at NDSS'23.

``` 
@inproceedings{ndss.2023.24290,
author = {Groß, Samuel and Koch, Simon and Bernhard, Lukas and Holtz, Thorsten and Johns, Martin},
title = {Fuzzilli: Fuzzing for JavaScript JIT Compiler Vulnerabilities},
year = {2023},
booktitle = {Network and Distributed Systems Security (NDSS) Symposium 2023},
doi={\url{https://dx.doi.org/10.14722/ndss.2023.24290}}
}
```

## Structure

We evaluated [Fuzzilli](https://github.com/googleprojectzero/fuzzilli) and [Superion](https://github.com/zhunki/Superion) and compared their code coverage in general and concerning JIT compiler related code in particular. As Superion requires an input corpus we opted to use the open dataset provided by DIE. Our artifacts concerning intial coverage and a reduced input corpus is [here](https://github.com/evaluating-fuzzilli-for-js-jit-fuzzing/SuperionInputCorpus).

This org contains the artifacts required for reproducability, i.e., the input corpus we used for Superion.

If there are any questions feel free to contact us.


