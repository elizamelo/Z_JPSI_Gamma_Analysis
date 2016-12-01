# Z_JPSI_Gamma_Analysis

```
setenv SCRAM_ARCH slc6_amd64_gcc530
cmsrel CMSSW_8_1_0_pre16
cd CMSSW_8_1_0_pre16/src
cmsenv

git cms-addpkg PhysicsTools/FWLite

```
```
FWLiteHistogramsBestByPt inputFiles=file:RootFiles/FakeZToJPsiGammaToMuMuGamma_pythia8.root outputFile=analyzeFWLite.root maxEvents=-1 outputEvery=20
````
