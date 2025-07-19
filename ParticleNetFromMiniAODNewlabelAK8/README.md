# ParticleNetFromMiniAODAK8

This folder contains the ONNX models for the `ParticleNetFromMiniAODNewlabelAK8` network, which performs jet tagging for heavy resonances with merged decay products
(bb, cc, tautau vs. QCD). The training sample consists of about 14M jets, sampled uniformly in resonance/softdrop mass and pT,
from a large mix of physics processes including ggH, Z+jets, and QCD from Run2UL2018 MC samples. The output classes of the DNN can be found in the `preprocess.json` file.

Enhancements to the `ParticleNetFromMiniAODAK8` training now incorporate `SingleTau` and pure leptonic tau decay channels in the tagging categories, alongside a 50% reduction in training sample size.