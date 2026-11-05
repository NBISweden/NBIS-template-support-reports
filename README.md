# NBIS support project templates
This Github repository contains Quarto report template, `NBIS_Quarto_Report.qmd` and `_extensions` for NBIS support projects.

## Install Quarto

To use the template you will need to have Quarto installed. Install from [the Quarto homepage](https://quarto.org/docs/get-started/) or a package manager, for example `brew install quarto`.

## What is included in the template?

Some sections are default and some need to be filled in by you. The sections where you need to add information are in _italic_.

### General \& Contact

- _Your name_
- _Issue number and title as seen in Redmine_
- _Main contact: name and email_
- _PI: name and email_
- _NBIS expert name and email_

### Request
_Include support request as sent by the group and as seen in Redmine (for reference purposes)_

### Practical information

#### Data responsibility
**NBIS and HPC resources**
Unfortunately, we do not have resources to keep any files associated with the support request. We suggest that you safely store the results delivered by us. In addition, we ask that you remove the files from HPC resources after analysis is completed. The main storage at HPC resources is optimized for high-speed and parallel access, which makes it expensive and not the right place for long time archiving.

**Sensitive data** Please note that special considerations may apply to the human-derived sensitive personal data. These should be handled according to [specific laws and regulations](https://data-guidelines.scilifelab.se/topics/research-involving-human-data/).

**Long-term backup** The responsibility for data archiving lies with universities and we recommend asking your local IT for support about long-term data archiving. Additionally the [Data Center](https://www.scilifelab.se/data-ai/) at SciLifeLab may be of help to discuss other options.

#### Acknowledgments
If you are presenting the results in a paper, at a workshop or conference, we kindly ask you to acknowledge us.

**NBIS** Staff are encouraged to be co-authors when this is merited in accordance to the ethical recommendations for authorship, e.g. [ICMJE recommendations](http://www.icmje.org/recommendations/). If applicable, please include _YOUR NAME_, National Bioinformatics Infrastructure Sweden, Science for Life Laboratory, _YOUR_ University, Department of _YOUR DEPARTMENT_ as co-author. In other cases, NBIS would be grateful if support by us is acknowledged in publications according to this example:"Support by NBIS (National Bioinformatics Infrastructure Sweden) is gratefully acknowledged."

For computations, please see the following pages for the respective acknowledgment recommendations:

| Site      | Request                                                                 |
|-----------|-------------------------------------------------------------------------|
| NAISS/NSC (arrhenius, triolith) | [NAISS acknowledgment inforamation](https://www.naiss.se/policies/acknowledge/) |
| UPPMAX (bianca, rackham, snowy, pelle, maja) | [UPPMAX acknowledgement information](https://www.uu.se/en/centre/uppmax/get-started/acknowledge-naiss-uppmax) |
| PDC/KTH (Dardel) | [PDC acknowledgment suggestions](https://www.pdc.kth.se/research/acknowledgement-of-using-resources-at-pdc-for-research-1.918148) |
| LUNARC |  [LUNARC acknowledgment information](https://www.lunarc.lu.se/getting-access/how-get-access/how-acknowledge-lunarc) |
| C3SE | [C3SE acknowledgment information](https://www.c3se.chalmers.se/#acknowledgement-suggestion)|
| HPC2N | [HPC2N acknowledgement information](https://docs.hpc2n.umu.se/documentation/accounts-rules/#acknowledgment) |

### Summary
_A short summary of the work performed by NBIS in the project._

### Deliverables
_Description and location of key files delivered, e.g., main plots, list of differentially expressed genes, VCF-files, etc. Point the group to the location of the files on HPC resources if applicable._

### Materials and Methods
_Include Materials and Methods as in any scientific work. Recommended to include software and versions._

### Data
_A description of data. Can be data used as resources during the project, such as reference data or annotation data, as well._

### Other Methods
_Other methods, such as custom scripts or commandline tools to adjust the data for example._

### Results
_The results of the project. Can be plots, tables etc._


-----------
#### How to contribute?
Follow the content README.md, suggest improvements to existing templates and add your versions for different platforms and expertise fields.

##### Github instructions
1. Fork the repository.
2. Make your changes.
3. Create a pull request.

