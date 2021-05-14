# genome-randomisation-survey

* A survey comparing different genome randomisation methods.


## Files:

* README.md: this readme file

* LICENSE: software licence 

* bin: directory of software scripts

* data: data directory

* docs: documents, including draft manuscript

## Work flow:

1. Fetch sequences for testing different tools (these cover a range of lengths, C+G contents, "complexities" (genes, repeats, etc).

2. Run & time different randomisation methods

* shuffle methods

 * EASEL  esl-shuffle -m|d (-w)

 * SQUID  shuffle -m|d (-w) 

 * EMBOSS shuffleseq 

* Markov methods & simulated evolution

 * EASEL esl-shuffle -0|1 (-w) 

 * SQUID shuffle -0|1 (-w) 

 * ROSE

 * INDELible
 
* Monte-Carlo methods

 * D-Tailor, BiDAS

3. Evaluate shuffled sequences

 * similarity with input sequence

 * C+G content and shared k-mers

 * shared ORFs, ncRNAs, domains, ...

4. Generate figure(s)

5. Write manuscript






 






