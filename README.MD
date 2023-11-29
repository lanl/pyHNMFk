# pyHNMFk

The identification of sources of advection-diffusion transport is based usually on solving complex ill-posed inverse models against the available state-variable data records. However, if there are several sources with different locations and strengths, the data records represent mixtures rather than the separate influences of the original sources. Importantly, the number of these original release sources is typically unknown, which hinders the reliability of the classical inverse-model analyses. To address this challenge, we present here a novel hybrid method for the identification of the unknown number of release sources. Our hybrid method, called HNMF, couples unsupervised learning based on Nonnegative Matrix Factorization (NMF) and inverse-analysis of Green's functions method. HNMF synergistically performs decomposition of the recorded mixtures, finds the number of the unknown sources and uses the Green's function of advection-diffusion equation to identify their characteristics. In the paper, we introduce the method and demonstrate that it is capable of identifying the advection velocity and dispersivity of the medium as well as the unknown number, locations, and properties of various sets of synthetic release sources with different space and time dependencies, based only on the recorded data. HNMF can be applied directly to any problem controlled by a partial-differential parabolic equation where mixtures of an unknown number of sources are measured at multiple locations.

## Citation
[Vangara, R., Rasmussen, K. Ø., Petsev, D. N., Bel, G., & Alexandrov, B. S. (2020). Identification of anomalous diffusion sources by unsupervised learning. Physical Review Research, 2(2), 023248.](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.2.023248)

## Authors
- Vesselin Grantcharov
- Raviteja Vangara
- Boian S. Alexandrov

## Copyright Notice
Copyright 2016. Los Alamos National Security, LLC. This software was produced under U.S. Government contract DE-AC52-06NA25396 for Los Alamos National Laboratory (LANL), which is operated by Los Alamos National Security, LLC for the U.S. Department of Energy. The U.S. Government has rights to use, reproduce, and distribute this software.  NEITHER THE GOVERNMENT NOR LOS ALAMOS NATIONAL SECURITY, LLC MAKES ANY WARRANTY, EXPRESS OR IMPLIED, OR ASSUMES ANY LIABILITY FOR THE USE OF THIS SOFTWARE.  If software is modified to produce derivative works, such modified software should be clearly marked, so as not to confuse it with the version available from LANL.
 
Additionally, redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:
·         Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
·         Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
·         Neither the name of Los Alamos National Security, LLC, Los Alamos National Laboratory, LANL, the U.S. Government, nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.
THIS SOFTWARE IS PROVIDED BY LOS ALAMOS NATIONAL SECURITY, LLC AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL LOS ALAMOS NATIONAL SECURITY, LLC OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

**LANL C Number: C16097**
