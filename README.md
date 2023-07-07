# DNA

This is my DNA download from [Ancestry](https://www.ancestry.com/)

Let me know if you find any bugs. Thanks.

Data was collected using AncestryDNA array version V2.0 and was formatted using AncestryDNA converter version V1.0.

## Format

DNA Data is provided in a tab delimited text file. This file contains a header describing the data and five columns of information. Each line corresponds to one single nucleotide polymorphism (SNP) or indel. A SNP is a single site in the genome that is known to vary across individuals. An indel is either an insertion or a deletion site. The possible observations are A for adenine, C for cytosine, G for guanine, T for thymine, I for insertion, D for deletion, and 0 for missing data. Column one provides the identifier (including the #rsID where possible). Columns two and three contain the chromosome and base pair position of the variant using human reference genome GRCh37 coordinates. Columns four and five contain the two alleles observed at this variant (genotype). The specific letters present are called alleles and the pair of alleles observed at a given location is called the genotype. For example, if a variant contains either C (cytosine) or A (adenine), then the possible genotypes are C C, A A, or A C (allele order is irrelevant so C A is the same as A C). Each chromosome is composed of two complementary strands, often called forward and reverse, and alleles may be reported on either strand. For example, a SNP genotype that is G G on the forward strand will be C C on the reverse strand. Likewise G A on the forward strand is C T on the reverse strand.

## License

Copyright (c) 2023 Jordan Millett

Permission is hereby granted, free of charge, to any person obtaining a copy of this DNA and associated documentation files (the "DNA"), to deal in the DNA without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the DNA, and to permit persons to whom the DNA is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the DNA.

THE DNA IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE DNA OR THE USE OR OTHER DEALINGS IN THE DNA.
