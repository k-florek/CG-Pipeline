SYNOPSIS

This is a minimized version of the CG-Pipeline to only run the readMetrics portion of the CG-Pipeline [https://github.com/lskatz/CG-Pipeline](https://github.com/lskatz/CG-Pipeline).

For more information about CG-Pipeline see below or visit [https://github.com/lskatz/CG-Pipeline](https://github.com/lskatz/CG-Pipeline).


DESCRIPTION

cg_pipeline is a computational genomics pipeline for bacterial genome sequencing projects. The pipeline provides infrastructure for automated, configurable, reproducible execution of genome assembly, feature prediction and functional annotation using algorithms from state of the art programs in each field. The package is described in detail in [1].

Installation and updating instructions can be found in the INSTALL file.

cg_pipeline is licensed under the terms of the GNU GPL license. See the LICENSE file for details.


CONFIGURATION

Key configuration parameters for cg_pipeline are stored in the file cg_pipeline/conf/cgpipelinerc. Users can override values in this file with the per-user configuration file ${HOME}/.cgpipelinerc. Descriptions of the parameters appear together with the parameters in the configuration file.


AUTHORS

Lee Katz <lkatz@cdc.gov>
Jay Humphrey <jhumphre@ebi.ac.uk>
Andrey Kislyuk

Centers for Disease Control and Prevention

The European Bioinformatics Institute

Georgia Institute of Technology:
Computational Genomics Group (http://compgenomics.biology.gatech.edu/)
Evolutionary Systems Biology Group (http://esbg.biology.gatech.edu/)
Neisseria Base (http://nbase.biology.gatech.edu/)

[1] A computational genomics pipeline for microbial sequencing projects. Kislyuk et al. Bioinformatics Advance Access June 2, 2010, DOI 10.1093/bioinformatics/btq284.
