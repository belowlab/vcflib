% VCFENTROPY(1) vcfentropy (vcflib) | vcfentropy (VCF unknown)
% Erik Garrison and vcflib contributors

# NAME

vcfentropy

# SYNOPSIS

usage: ./build/vcfentropy [options] <vcf file>

# DESCRIPTION

options: -f, --fasta-reference FASTA reference file to use to obtain flanking sequences -w, --window-size Size of the window over which to calculate entropy

# OPTIONS

```


Anotates the output VCF file with, for each record, EntropyLeft, EntropyRight,
EntropyCenter, which are the entropies of the sequence of the given window size to the
left, right, and center  of the record.  Also adds EntropyRef and EntropyAlt for each alt.

```

# EXIT VALUES

**0**
: Success

**not 0**
: Failure

# OTHER

## Source code

[vcfentropy.cpp](https://github.com/vcflib/vcflib/blob/master/src/vcfentropy.cpp)

# LICENSE

Copyright 2011-2020 (C) Erik Garrison and vcflib contributors. MIT licensed.

<!--
  Created with ./scripts/bin2md.rb scripts/bin2md-template.erb
-->