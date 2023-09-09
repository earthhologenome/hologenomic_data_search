# hologenomic_data_search
Search for available paired vertebrate genomic and metagenomic datasets

###

ENA data types
https://www.ebi.ac.uk/ena/portal/api/results?dataPortal=ena


### Study search

Display search fields for "study"
https://www.ebi.ac.uk/ena/portal/api/returnFields?result=study

#### Metagenome search

Search based on fields:
- description
- study_title
- study_name
- study_alias
- project_name
- keywords

Search based on keyword combinations:
- "*metagenome*" + "*gut*"
- "*microbiome*" + "*gut*"
- "*metagenome*" + "*gut*"
- "*metagenome*" + "*intestin*"
- "*microbiome*" + "*intestin*"
- "*metagenome*" + "*intestin*"
- "*metagenome*" + "*fecal*"
- "*microbiome*" + "*fecal*"
- "*metagenome*" + "*fecal*"
- "*metagenome*" + "*faecal*"
- "*microbiome*" + "*faecal*"
- "*metagenome*" + "*faecal*"

Metagenome search (replace line breaks with nothing before submitting)
https://www.ebi.ac.uk/ena/portal/api/search?result=study&query=
(description="*gut*" AND description="*metagenome*") OR
(description="*gut*" AND description="*microbiome*") OR
(description="*gut*" AND description="*microbiota*") OR
(study_title="*gut*" AND study_title="*metagenome*") OR
(study_title="*gut*" AND study_title="*microbiome*") OR
(study_title="*gut*" AND study_title="*microbiota*") OR
(study_name="*gut*" AND study_name="*metagenome*") OR
(study_name="*gut*" AND study_name="*microbiome*") OR
(study_name="*gut*" AND study_name="*microbiota*") OR
(study_alias="*gut*" AND study_alias="*metagenome*") OR
(study_alias="*gut*" AND study_alias="*microbiome*") OR
(study_alias="*gut*" AND study_alias="*microbiota*") OR
(description="*fecal*" AND description="*metagenome*") OR
(description="*fecal*" AND description="*microbiome*") OR
(description="*fecal*" AND description="*microbiota*") OR
(study_title="*fecal*" AND study_title="*metagenome*") OR
(study_title="*fecal*" AND study_title="*microbiome*") OR
(study_title="*fecal*" AND study_title="*microbiota*") OR
(study_name="*fecal*" AND study_name="*metagenome*") OR
(study_name="*fecal*" AND study_name="*microbiome*") OR
(study_name="*fecal*" AND study_name="*microbiota*") OR
(study_alias="*fecal*" AND study_alias="*metagenome*") OR
(study_alias="*fecal*" AND study_alias="*microbiome*") OR
(study_alias="*fecal*" AND study_alias="*microbiota*") OR
(description="*faecal*" AND description="*metagenome*") OR
(description="*faecal*" AND description="*microbiome*") OR
(description="*faecal*" AND description="*microbiota*") OR
(study_title="*faecal*" AND study_title="*metagenome*") OR
(study_title="*faecal*" AND study_title="*microbiome*") OR
(study_title="*faecal*" AND study_title="*microbiota*") OR
(study_name="*faecal*" AND study_name="*metagenome*") OR
(study_name="*faecal*" AND study_name="*microbiome*") OR
(study_name="*faecal*" AND study_name="*microbiota*") OR
(study_alias="*faecal*" AND study_alias="*metagenome*") OR
(study_alias="*faecal*" AND study_alias="*microbiome*") OR
(study_alias="*faecal*" AND study_alias="*microbiota*") OR
(description="*intestin*" AND description="*metagenome*") OR
(description="*intestin*" AND description="*microbiome*") OR
(description="*intestin*" AND description="*microbiota*") OR
(study_title="*intestin*" AND study_title="*metagenome*") OR
(study_title="*intestin*" AND study_title="*microbiome*") OR
(study_title="*intestin*" AND study_title="*microbiota*") OR
(study_name="*intestin*" AND study_name="*metagenome*") OR
(study_name="*intestin*" AND study_name="*microbiome*") OR
(study_name="*intestin*" AND study_name="*microbiota*") OR
(study_alias="*intestin*" AND study_alias="*metagenome*") OR
(study_alias="*intestin*" AND study_alias="*microbiome*") OR
(study_alias="*intestin*" AND study_alias="*microbiota*") OR
(description="*caec*" AND description="*metagenome*") OR
(description="*caec*" AND description="*microbiome*") OR
(description="*caec*" AND description="*microbiota*") OR
(study_title="*caec*" AND study_title="*metagenome*") OR
(study_title="*caec*" AND study_title="*microbiome*") OR
(study_title="*caec*" AND study_title="*microbiota*") OR
(study_name="*caec*" AND study_name="*metagenome*") OR
(study_name="*caec*" AND study_name="*microbiome*") OR
(study_name="*caec*" AND study_name="*microbiota*") OR
(study_alias="*caec*" AND study_alias="*metagenome*") OR
(study_alias="*caec*" AND study_alias="*microbiome*") OR
(study_alias="*caec*" AND study_alias="*microbiota*") OR
(description="*colon*" AND description="*metagenome*") OR
(description="*colon*" AND description="*microbiome*") OR
(description="*colon*" AND description="*microbiota*") OR
(study_title="*colon*" AND study_title="*metagenome*") OR
(study_title="*colon*" AND study_title="*microbiome*") OR
(study_title="*colon*" AND study_title="*microbiota*") OR
(study_name="*colon*" AND study_name="*metagenome*") OR
(study_name="*colon*" AND study_name="*microbiome*") OR
(study_name="*colon*" AND study_name="*microbiota*") OR
(study_alias="*colon*" AND study_alias="*metagenome*") OR
(study_alias="*colon*" AND study_alias="*microbiome*") OR
(study_alias="*colon*" AND study_alias="*microbiota*") OR
(description="* git *" AND description="*metagenome*") OR
(description="* git *" AND description="*microbiome*") OR
(description="* git *" AND description="*microbiota*") OR
(study_title="* git *" AND study_title="*metagenome*") OR
(study_title="* git *" AND study_title="*microbiome*") OR
(study_title="* git *" AND study_title="*microbiota*") OR
(study_name="* git *" AND study_name="*metagenome*") OR
(study_name="* git *" AND study_name="*microbiome*") OR
(study_name="* git *" AND study_name="*microbiota*") OR
(study_alias="* git *" AND study_alias="*metagenome*") OR
(study_alias="* git *" AND study_alias="*microbiome*") OR
(study_alias="* git *" AND study_alias="*microbiota*")
&fields=study_accession,parent_study_accession,tax_id

to: metagenome_studies.tsv

#### Genome search

Search based on fields:
- description
- study_title
- study_name
- study_alias
- project_name
- keywords

Search based on keyword combinations:

- "* genom*" | "Genome*"

Genome search (replace line breaks with nothing before submitting)
https://www.ebi.ac.uk/ena/portal/api/search?result=study&query=
(description="* genom*") OR
(description="Genom*") OR
(study_title="* genom*") OR
(study_title="Genom*") OR
(study_name="* genom*") OR
(study_name="Genom*") OR
(study_alias="* genom*") OR
(study_alias="Genom*")
&fields=study_accession,parent_study_accession,tax_id

to: genome_studies.tsv
