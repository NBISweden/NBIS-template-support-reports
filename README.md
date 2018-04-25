# NBIS support project templates
This Github repository contains recommended report templates for NBIS support projects. See at the bottom how to contribute.

## Suggested report structure
The following sections should be in the report:

- [cover page](#cover)
- [support request](#request)
- [practical information incl. data responsiblity and acknowledgments](#practical)
- [materials and methods](#MM)
- [results](#results)
- [support project closing procedures](#closing)

It is also recommended that these sections are included, if applicable:
- [deliverables](#deliverables)
- [summary](#summary)

### Cover page <a name="cover"></a>
Include:

- NBIS and SciLifeLab logos
- Issue number and title as seen in Redmine
- NBIS expert name and email
- Request by: name and email
- PI: name and email
- Organisation


### Support request <a name="request"></a>
_Include support request as sent by the group and as seen in Redmine (for reference purposes)_

### Practical information <a name="practical"></a>
_Include a friendly reminder where data responsiblity lies and how to acknowledge us e.g._

#### Data responsibility
- **NBIS \& Uppnex** Unfortunately, we do not have resources to keep any files associated with the support request. We kindly suggest that you store safely the results delivered by us. In addition, we kindly ask that you remove the files from UPPMAX/UPPNEX. The main storage at UPPNEX is optimized for high-speed and parallel access, which makes it expensive and not the right place for longer time archiving. Please consider others by not taking up the expensive space
- **Sensitive data** Please note that special considerations may apply to the human-derived legally considered sensitive personal data.
These should be handled according to specific laws and regulations as outlined e.g. [here](http://nbis.se/support/human-data.html)
- **Long-term backup** The responsibility for data archiving lies with universities and we recommend asking your local IT for support with long-term data archiving. Also a newly established [Data Office](https://www.scilifelab.se/data/) at SciLifeLab may be of help to discuss other options.

#### Acknowledgments
If you are presenting the results in a paper, at a workshop or conference, we kindly ask you to acknowledge us.

- **NBIS** Staff are encouraged to be co-authors when this is merited in accordance to the ethical recommendations for authorship, e.g. [ICMJE recommendations](http://www.icmje.org/recommendations/browse/roles-and-responsibilities/defining-the-role-of-authors-and-contributors.html).If applicable, please include **Name, Surname, National Bioinformatics Infrastructure Sweden, Science for Life Laboratory, Further Affliations**, as co-author. In other cases, NBIS would be grateful if support by us is acknowledged in publications according to this example: ["Support by NBIS (National Bioinformatics Infrastructure Sweden) is gratefully acknowledged"](https://bils.se/resources/support.html)

- **UPPMAX** If your project has used HPC resources we kindly asks you to acknowledge UPPMAX and SNIC. If applicable, please add: ["The computations were performed on resources provided by SNIC through Uppsala Multidisciplinary Center for Advanced Computational Science (UPPMAX) under Project SNIC XXXX/Y-ZZZ"](https://www.uppmax.uu.se/support/faq/general-miscellaneous-faq/acknowledging-uppmax--snic--and-uppnex/)

- **NGI** In publications based on data from NGI Sweden, the authors must acknowledge SciLifeLab, NGI and UPPMAX:  ["The authors would like to acknowledge support from Science for Life Laboratory, the National Genomics Infrastructure, NGI, and Uppmax for providing assistance in massive parallel sequencing and computational infrastructure."](https://ngisweden.scilifelab.se/info/faq#how-do-i-acknowledge-ngi-in-my-publication)


### Materials and Methods <a name="MM"></a>
_Include Materials and Methods as in any scientific work_

### Results <a name="results"></a>
_Include results_

### Deliverables <a name="deliverables"></a>
_**Strongly recommended, include if applicable**_ Description and location of key files delivered, e.g., main plots, list of differentially expressed genes, VCF-files, etc. Point the group to the location of the files on SNIC resources (e.g., UPPMAX) if applicable.


### Summary <a name="summary"></a>
_**Strongly recommended, include if applicable**_ A place to (in brief) summarize the results, including strengths and weaknesses of the used data and the results. This is also a good place to give recommendations on how to proceed, e.g., give recommendations of online tools that could be used to inspect the data, or point the User to tutorials to help them understand the data analyses.

### Support project closing procedures <a name="closing"></a>
_Include a note about project closing procedures e.g._

You should soon be contacted by one of our managers, Jessica Lindvall <jessica.lindvall@nbis.se> or Henrik Lantz <henrik.lantz@nbis.se>, with a request to close down the project in our internal system and for invoicing matters. If we do not hear from you within **30 days** the project will be automatically closed and invoice sent. Again, we would like to remind you about data responsibility and acknowledgements, see [Data Responsibility and Acknowledgments sections](#practical).

You are naturally more than welcome to come back to us with further data analysis request at any time via [http://nbis.se/support/support.html](http://nbis.se/support/support.html).

Thank you for using NBIS and all the best for future research.

-----------
#### How to contribute?
Follow the content README.md, suggest improvements to existing templates and add your versions for different platforms and expertise fields.

##### Github instructions
1. If first time: `git clone https://github.com/NBISweden/NBIS-templates-support-reports`
2. `cd NBIS-templates-support-reports`
3. `git checkout drafts`
4. Add your files using git, example: `git add foo.txt`
5. `git commit -m "your commit description"`
6. `git push origin drafts`
7. Create a pull request by
    - visiting [https://github.com/NBISweden/NBIS-templates-support-reports](https://github.com/NBISweden/NBIS-template-support-reports) and clicking on the `New pull request` button,
    - select the branch you want to merge into (`base: master`),
    - enter a Title and a Comment of the pull request,
    - click on the green `Create pull request` button.
8. Alert a colleague for approval!

Not comfortable with Github? Contact Olga Dethlefsen < olga.dethlefsen@nbis.se >, Agata Smialowska < agata.smialowska@nbis.se >,  or Sebastian DiLorenzo < sebastian.dilorenzo@nbis.se >
