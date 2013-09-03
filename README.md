FeatConf
========

utility class for FSL's fsf files

  works as a module and from command line:

  - python -mFeatConf.FeatConf -i design.fsf # lists feat_files
  - python -mFeatConf.FeatConf -c design.fsf # lists contrasts
  - python -mFeatConf.FeatConf -p design.fsf # should output the same as cat design.fsf, to test equivalence (used against a subset of level 1 designs with v5.98)

