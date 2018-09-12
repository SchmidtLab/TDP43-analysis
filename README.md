# TDP43-analysis
Source code for:<br>
	1.) Compiling NTD, RRM and CTD databases from a collection of vertebrate TDP43 homologs (Step 1)
		Input: Vertebrate TDP43.fasta
		Analysis: Step1.nb
		Output: NTDs.fasta, RRMs.fasta, CTDs.fasta
	2.) Isoform filter to ensure single sequence per filter (Step 2)
		Input: NTDs.fasta, RRMs.fasta, CTDs.fasta
		Analysis: Step2.nb
		Output: Unique species NTDs.fasta, Unique species RRMs.fasta, Unique species CTDs.fasta
	3.) Analyzing the databases (Step 3)
		Input: Unique species NTDs.fasta, Unique species RRMs.fasta, Unique species CTDs.fasta
		Analysis: Step3.nb
	4.) Subdividing the CTD database into IDR and CR databases (Step 4)
		Input: Unique species CTDs.fasta
		Analysis: Step4.nb
		Output: True IDR Domains without CRs.fasta, Conserved Regions.fasta
	5.) Analyzing the IDR and CR databases (Step 5)
		Input: True IDR Domains without CRs.fasta, Conserved Regions.fasta
		Analysis: Step5.nb
	6.) Sliding window analysis of CTD sequences (Step 6)
		Input: Unique species CTDs.fasta
		Analysis: Step6.nb
	7.) Analysis of TDP43 splicing assay (Step 7)
		Input: fcs files
		Analysis: Step7.nb
	8.) Analysis of TDP43 reporter droplet formation (Step 8)
		Input: image files
		Analysis: Step8.nb
