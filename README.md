# bash-utilities

**ztail** and **zhead** show the tail and the head of a compressed file, respectively.
 <br />
usage : 
 <br />
 <br />
`ztail myfile.gz`
 <br />
by default shows the last 5 lines.
 <br />
 <br />
`ztail myfile.gz 10`
 <br />
the second argument specifies the number of rows.
 <br />
 <br />
 <br />
Got an error at line 127?
 <br />
**tline** shows exactly **that line**, where the error occurred.
 <br />
usage:
 <br />
 <br />
`tline myfile 3`
<br />
It does work also for gzipped files.
 <br />
 <br />
**getinfo** from an uncompressed vcf, for a specific sample, using chr and pos.
 <br />
usage:
 <br />
 <br />
`getinfo <myvcf> <samplename> <chr> <pos>`


