# L1TauProducerPhase2_Old


# From my fork area


cmsrel CMSSW_10_6_1_patch2

cd CMSSW_10_6_1_patch2/src

cmsenv

git cms-init



git remote add sandeepbhowmik1 https://github.com/sandeepbhowmik1/cmssw

git fetch sandeepbhowmik1 from-CMSSW_10_6_1_patch2

git cms-merge-topic -u sandeepbhowmik1:Phase2_L1HPSPFTau_v8

scram b -j 8





# From original area

https://twiki.cern.ch/twiki/bin/view/CMSPublic/SWGuideL1TPhase2Instructions#CMSSW_10_6_1_patch2


cmsrel CMSSW_10_6_1_patch2

cd CMSSW_10_6_1_patch2/src

cmsenv

git cms-init

git remote add cms-l1t-offline https://github.com/cms-l1t-offline/cmssw.git

git fetch cms-l1t-offline phase2-l1t-integration-CMSSW_10_6_1_patch2

git cms-merge-topic -u cms-l1t-offline:l1t-phase2-v2.37.2

scram b -j 8
