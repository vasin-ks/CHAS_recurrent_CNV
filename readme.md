Script name: Unique-CNV-catcher

Description and tasks: This script is written to work with CNV (deletions, duplications)  from Chromosome Analysis Suite 4.3 (ChAS 4.3).

This script aims to identify unique and non-unique CNVs in subjects.

 I use PyCharm in work.

1-You need your (personal/laboratory) CNV base to use it. 
  We have a file with CNV coordinates called DataForComparison. It should not be used. 
  It contains data and databases of non-pathogenic genomic variations as an example "http://dgv.tcag.ca/dgv/app/downloads?ref=GRCh37/hg19". It needs to be replaced!
  
2-I wrote the code in PyCharm. Need to install #install python-docx.
  This package is needed to generate a doc file and highlight text with color.	

3-First you enter how much CNV there is in the your program. We usually have 100-200 CNV per patient. 
  Write out the number from the program: 124

4-Next, you will copy all the data for this CNV Columns from the CHAS program should be copied 15.

   1:Name_off_pattient	2:2.3608007	3:GainMosaic	4:3	5:22268030	6:32989956	7:10721.927	8:9647	9:1111	10:p24.3	11:p22.3	12:5	13:2	14:UBE2E2-AS1, UBE2E2, UBE2E1-AS1, UBE2E1, NKIRAS1, 15:UBE2E2 (602163), UBE2E1 (602916)")
   1:PatientName 2:CN_State 3:Type 4:Chromosome 5:Min 6:Max 7:Size 8:M.Count 9:M.M.Dis 10:Cyto.Start 11:Cyto.End 12:Gene.Count 13:Omim.G.Count 14:Genes 15:Omim.Genes
  Correct order matters!

5-The script will return the results, and each CNV will have a designation for its uniqueness. A short entry will also be generated:
  Xp22.33(1511714_1569114)x3.11q11(55609009_55653792)x1.
  Unfortunately for the CNV mosaicism, the short record is generated incorrectly. Be careful about this.
  Can't wright Xp22.33(1511714_1569114)2~3

6-The program will finish its work by generating a document!
  You need to write a convenient place for you to generate this file.
  My file is saved to the desktop and is called CNV-catcher-result.doc and generated on the desktop


	Thank you all for your attention. 

	With you was 
	# Vasin Kirill Sergeevich, MD., Phd. 
	My contacts:

	drvasinks@gmail.com

	telegram @DrKvasin

	https://www.linkedin.com/in/kirill-vasin-ba654a104/
