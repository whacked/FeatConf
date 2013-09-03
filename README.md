FeatConf
========

utility class for FSL's fsf files

#FeatConf class

  simple reader for .fsf files to replace repeated =grep=ing

  works as a module and from command line:

  - python -mFeatConf.FeatConf -i design.fsf # lists feat_files
  - python -mFeatConf.FeatConf -c design.fsf # lists contrasts
  - python -mFeatConf.FeatConf -p design.fsf # should output the same as cat design.fsf, to test equivalence

  simple reader for .fsf files to replace repeated =grep=ing

  works as a module and from command line:

  - python -mFeatConf.FeatConf -i design.fsf # lists feat_files
  - python -mFeatConf.FeatConf -c design.fsf # lists contrasts
  - python -mFeatConf.FeatConf -p design.fsf # should output the same as cat design.fsf, to test equivalence

##caveats

   it's dumb in that quoted strings don't get quote-stripped

