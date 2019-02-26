# VEP

★論文 :

https://genomemedicine.biomedcentral.com/articles/10.1186/gm543#Sec2

http://blog.goldenhelix.com/goldenadmin/the-sate-of-variant-annotation-a-comparison-of-annovar-snpeff-and-vep/


★home_URL:

https://github.com/Ensembl/ensembl-vep


★install : 
git clone https://github.com/Ensembl/ensembl-vep.git

cd ensembl-vep
perl INSTALL.pl

export PATH=/usr/local/bin:$PATH
cpan経由で、Perl librariesを入れた （install libraryName)
1) Archive::Zip
2) DBI
3) DBD::mysql - required for database access (--database or --cache without --offline)

<s> Set::IntervalTree - required for Haplosaurus, also confers speed updates to VEP </s>

4) JSON - required for writing JSON output
5) PerlIO::gzip - faster compressed file parsing
6) Bio::DB::BigFile - required for reading custom annotation data from BigWig files




