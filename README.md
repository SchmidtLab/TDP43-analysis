# TDP43-analysis
Source code for:<br><br>
----- Vertebrate TDP43 sequence analysis -----<br><br>
	1.) Compiling NTD, RRM and CTD databases from a collection of vertebrate TDP43 homologs (Step 1)<br>
		Input: Vertebrate TDP43.fasta<br>
		Analysis: Step1.nb<br>
		Output: NTDs.fasta, RRMs.fasta, CTDs.fasta<br><br>
	2.) Isoform filter to ensure single sequence per filter (Step 2)<br>
		Input: NTDs.fasta, RRMs.fasta, CTDs.fasta<br>
		Analysis: Step2.nb<br>
		Output: Unique species NTDs.fasta, Unique species RRMs.fasta, Unique species CTDs.fasta<br><br>
	3.) Analyzing the databases (Step 3)<br>
		Input: Unique species NTDs.fasta, Unique species RRMs.fasta, Unique species CTDs.fasta<br>
		Analysis: Step3.nb<br><br>
	4.) Subdividing the CTD database into IDR and CR databases (Step 4)<br>
		Input: Unique species CTDs.fasta<br>
		Analysis: Step4.nb<br>
		Output: IDR1 Domains.fasta, IDR2 Domains.fasta, Conserved Regions.fasta<br><br>
	5.) Analyzing the IDR and CR databases (Step 5)<br>
		Input: IDR1 Domains.fasta, IDR2 Domains.fasta, Conserved Regions.fasta<br>
		Analysis: Step5.nb<br><br>
	6.) Spacing of hydrophobic residues (Step 6)<br>
		Input: IDR1 Domains.fasta, IDR2 Domains.fasta
		Analysis: Step5.nb<br><br>
	7.) Sliding window analysis of CTD sequences (Step 7)<br>
		Input: Unique species CTDs.fasta<br>
		Analysis: Step7.nb<br><br>
	8.) Residual analysis (Step 8)<br>
		Input: IDR1 domains.fasta, IDR2 domains.fasta<br>
		Analysis: Step8.nb<br><br>
----- TDP43 splicing reporter analysis -----<br><br>	
	9.) Analysis of TDP43 splicing assay<br>
		Input: fcs files<br>
		Analysis: CSA_Gating.nb, CSA_Plotting<br><br>
----- TDP43 RRM-GFP droplet formation analysis -----<br><br>
	10.) Analysis of TDP43 reporter droplet formation<br>
		Input: image files<br>
		Analysis: Droplet_Analysis.nb<br><br>
