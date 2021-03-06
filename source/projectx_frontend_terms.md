# projectX specific terms

- **projectX** - refers to the software.

- **Alignment** - is the process of mapping short reads on to the reference genome. The objective of alignment is determining where the fragments came from in the original genome and identifications of genetic variations. 
- **Demultiplexing** - is the process of sorting sequenced reads into separate files (fastq) for each sample in a sequenced run.
- **Pipeline** - refers to a unique set of analysis steps.
- **Backbone** - is an attribute which defines the pipeline to be triggered. Backbone is associated with a panel.
- **Panel** - is a collection of attributes including target bed(optional), padding parameter and backbone. Panel also includes other parameters. See section [] for more information.
- **Workflow** - defines a set of parameters and panel using which a sample needs to be analysed. Workflow inherits from the panel.
- **Sample sheet** - The sample sheet is a CSV file format used by Illumina for storing biological sample information and metadata associated with a given experiment.
- **Patient** - is an individual. One patient can have several samples.
- **Sample** - is an entity with an identifier; a basic unit of a run.
- **Run/Sequencing** - Run	is the group of samples mentioned in the sample sheet file ready to be analysed.
- **Sample config file** -  is the per sample json file produced from the UI having sample/panel/workflow information
- **QC metric(s)** - is/are a set of quantitative/qualitative  check(s) used to check the quality of sequencing data. QC could be per run/sample
- **Tag** - refers to a free floating text assigned to identify and search a sample. Tags can be assigned at multiple levels for example - Run level and Sample level.
- **Trimming** - refers to the process of removing bad quality bases from sequencing reads.

