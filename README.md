# SWOTein
Here there are some files related to our paper "SWOTein: A structure-based approach to predict stability Strengths and Weaknesses of prOTEINs". More in details there are three files corresponding to three statistical potentials used in the paper: acc.en is the solvent accessibility statistical potentials (Eq.5), tor.en is the torsion angle domain statistical potential (Eq.6) and sds.en is the distance statistical potentials.  

Parameter used<br /> 
>> acc.en: windows along the sequence considered 5, number of solvent accessibility bins = 5 (0-5%, 5-15%, 15-30%, 30-50%, 50-100%).<br /> 
>> tor.en: windows along the sequence considered 7, number of torsion angle domain = 7 (α-helix A, 3-10-helix C, β-stand B, extende conformation P, positive ϕ G, positive ϕ E, cis-conformation O).<br /> 
>> sds.en: windows along the sequence considered 7, number of distance bins of 0.2 Å = 25 from 3.0 to 8.0 width one additional bin for d<3.0 Å and one for d>8.0 Å
