# Frequency and Phase Correction of MRS signals Using Cross-Correlation

The algorithm is based on the "Automatic frequency and phase alignment of in vivo J-difference-edited MR spectra by frequency domain correlation" paper. The authors of the paper find the maximum using manual grid search. But here, the problem is converted to a non-linear minimization problem which can be solved by direct search or Newton family methods.

FPCcorr(refrence signal, data(number of points, number of signals), method("fminunc" or "fminsearch"), range(in points, e.g: 1:1:1000), dwelltime, visus(true or false) )

## This project was supported by:
European Union's Horizon 2020 research and innovation program under the Marie Sklodowska-Curie grant agreement No 813120 (INSPiRE-MED)

The software was developed by Amir Shamaei.
Copyright (c) 2021 Ústav přístrojové techniky AV ČR, v. v. i.
