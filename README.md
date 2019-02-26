# VEP MEMO

★home_URL:

https://github.com/Ensembl/ensembl-vep


★install : 

git clone https://github.com/Ensembl/ensembl-vep.git


environment:

export PATH=/usr/local/bin:$PATH

import the Perl libraries via cpan（install libraryName)

1) Archive::Zip
2) DBI
3) DBD::mysql - required for database access (--database or --cache without --offline)
4) Set::IntervalTree - required for Haplosaurus, also confers speed updates to VEP </s>
5) JSON - required for writing JSON output
6) PerlIO::gzip - faster compressed file parsing
7) Bio::DB::BigFile - required for reading custom annotation data from BigWig files


cd ensembl-vep
perl INSTALL.pl



