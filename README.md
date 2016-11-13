##NOTE: You are on the archive version of this RNA-seq analysis tutorial. This version is maintained for consistency with the published materials (<a href="http://dx.doi.org/10.1371/journal.pcbi.1004393">Griffith et al. 2015. PLoS Comp Biol.</a>) and for past students wishing to review covered material. However, we strongly suggest that you visit the current version of this tutorial at www.rnaseq.wiki. 

###Informatics for RNA-seq: A web resource for analysis on the cloud
===============
An educational tutorial and working demonstration pipeline for RNA-seq analysis including an introduction to: cloud computing, next generation sequence file formats, reference genomes, gene annotation, expression analysis, differential expression analysis, alternative splicing analysis, data visualization, and interpretation.

This repository is used to store code and certain raw materials for a detailed RNA-seq tutorial.  To actually complete this tutorial, go to the <a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki">RNA-seq tutorial wiki</a>.

Citation:
Malachi Griffith\*, Jason R. Walker, Nicholas C. Spies, Benjamin J. Ainscough, Obi L. Griffith\*. 2015. <a href="http://dx.doi.org/10.1371/journal.pcbi.1004393">Informatics for RNA-seq: A web resource for analysis on the cloud</a>. PLoS Comp Biol. 11(8):e1004393.

\*To whom correspondence should be addressed: E-mail: mgriffit[AT]genome.wustl.edu, ogriffit[AT]genome.wustl.edu

===============
###Tutorial Table of Contents
<ol start="0">
  <li><strong>Module 0 - Introduction and Cloud Computing</strong></li>
  <ol start="i">
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Authors">Authors</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Citation">Citation and Supplementary Materials</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Syntax">Syntax</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Intro-to-AWS-Cloud-Computing">Intro to AWS Cloud Computing</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Logging-into-Amazon-Cloud">Logging into Amazon Cloud</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Unix-Bootcamp">Unix Bootcamp</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Environment">Environment</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Resources">Resources</a></li>
  </ol>
  <li><strong>Module 1 - Introduction to RNA sequencing</strong></li>
  <ol start="i">
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Installation">Installation</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Reference-Genome">Reference Genome</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Annotation">Annotation</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Indexing">Indexing</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/RNAseq-Data">RNA-seq Data</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/PreAlignment-QC">PreAlignment QC</a></li>
  </ol>
  <li><strong>Module 2 - RNA-seq Alignment and Visualization</strong></li>
  <ol start="i">
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Adapter-Trim">Adapter Trim</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Alignment">Alignment</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/IGV-Tutorial">IGV</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/PostAlignment-Visualization">PostAlignment Visualization</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/PostAlignment-QC">PostAlignment QC</a></li>
  </ol>
  <li><strong>Module 3 - Expression and Differential Expression</strong></li>
  <ol start="i">
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Expression">Expression</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Differential-Expression">Differential Expression</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/DE-Visualization">DE Visualization</a></li>
  </ol>
  <li><strong>Module 4 - Isoform Discovery and Alternative Expression</strong></li>
  <ol start="i">
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Reference-Guided-Transcript-Assembly">Reference Guided Transcript Assembly</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/de-novo-Transcript-Assembly">de novo Transcript Assembly</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Transcript-Assembly-Merge">Transcript Assembly Merge</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Differential-Splicing">Differential Splicing</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Transcript-Assembly-Visualization">Transcript Assembly Visualization</a></li>
  </ol>
  <li><strong>Module 5 - Reference free analysis</strong></li>
   <ol start="i">  
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Kallisto">Use of Kallisto for Abundance Estimation</a></li>
  </ol>
  <li><strong>Appendix</strong></li>
  <ol start="i">
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Abbreviations">Abbreviations</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Lectures">Lectures</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Solutions">Practical Exercise Solutions</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Integrated-Assignment">Integrated Assignment</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/Proposed-Improvements">Proposed Improvements</a></li>
   <li><a href="https://github.com/griffithlab/rnaseq_tutorial_v1/wiki/AWS-Setup">AWS Setup</a></li>
  </ol>
</ol>

