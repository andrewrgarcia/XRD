# X-Ray Diffraction (XRD) analysis with Python
> ### Andrew Garcia, 2018

## XRD.py [and XRD_functions.py]
XRD.py integrates the XRD_functions.py script in order to do the following:

* Take XRD data expressed as *.csv* files:

* Perform background subtraction algorithms on XRD data

* Data smoothing (with an n-point moving average) [if desired]

* Plot one main graph with all XRD spectra in interest and 3 additional smaller graphs serving as a comparison to the first graph (can be customized by changing the size of the *for loops*)

* Calculate crystallite size for each of the XRD spectrum
using the Scherrer equation and displays them on the shell.

* Find location of emission peaks corresponding to secondary radiation sources (with K_alpha peak as a reference)

## XRDsingle.py

* Takes a single XRD file expressed as *.csv* files:

* Performs a background subtraction algorithm on XRD data

* Plots subtracted and non-subtracted XRD data in Python

* Creates *.csv* file of background-subtracted version of XRD data, which can be open and edited in Excel (if Excel is your thing)

## indexing.py

* Calculates interplanar spacing

* ~~If your a b c lattice parameters are known, can be used to find the Miller indices of your XRD data at a certain 2-theta peak~~

* Adding capabilities to determine hkl indices and lattice parameters for powder patterns - in progress

## LICENSE file excerpt -see: LICENSE file in this repository-

   Copyright 2018 Andrew R Garcia

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
