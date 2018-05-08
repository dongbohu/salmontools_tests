This repo includes sample datasets to test SalmonTools program:
https://github.com/COMBINE-lab/SalmonTools

### Double reads test case:

1. **double_input/reads_1.fastq**:
copied from https://github.com/COMBINE-lab/SalmonTools/blob/master/sample_data/reads_1.fastq

2. **double_input/reads_2.fastq**:
copied from https://github.com/COMBINE-lab/SalmonTools/blob/master/sample_data/reads_2.fastq

3. **double_output/aux-info/unmapped_names.txt**:
copied from https://github.com/COMBINE-lab/SalmonTools/blob/master/sample_data/unmapped_random.txt

4. **expected_double_output/unmapped_by_salmon_1.fa**:
expected output file of `salmontools`, based on input files #1, #2, and #3.

5. **expected_double_output/unmapped_by_salmon_2.fa**:
another expected output file of `salmontools`, based on input files #1, #2, and #3.

### Single read test case:

1. **single_input/single_read.fastq**:
the first 10,000 lines of `SRR074262.fastq`, which is located at:
[ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR074/SRR074262/SRR074262.fastq.gz]
(ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR074/SRR074262/SRR074262.fastq.gz)

2. **single_output/aux-info/unmapped_names.txt**:
generated by `salmon quant` command, based on short index and the file #1.

3. **expected_single_output/unmapped_by_salmon.fa**:
expected output file of `salmontools`, based on input files #1 and #2.
