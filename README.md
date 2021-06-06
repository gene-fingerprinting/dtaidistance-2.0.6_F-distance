# F-distance support based on dtaidistance-2.0.6

Implementation of F-distance[1] based on dtaidistance-2.0.6.

Support C-Extensions for Python to accelerate calculation.

[1] S. Feghhi and D. J. Leith, "A Web Traffic Analysis Attack Using Only Timing Information," in IEEE Transactions on Information Forensics and Security, vol. 11, no. 8, pp. 1747-1759, Aug. 2016, doi: 10.1109/TIFS.2016.2551203.

## Installation

    $ python setup.py build_ext --inplace
    $ python setup.py install

## Modified Files

1. dtaidistance\dtw.py
2. dtaidistance\dtw_cc.pyx
3. dtaidistance\dtaidistancec_dtw.pxd
4. dtaidistance\lib\DTAIDistanceC\DTAIDistanceC\dd_dtw.h
5. dtaidistance\lib\DTAIDistanceC\DTAIDistanceC\dd_dtw.c

## Original README

Please see README-original.md
