##Introduction

The Grassroots system running at the Earlham Institute (EI) is being used to gather and catalogue the Field Trial information generated within the Designing Future Wheat (DFW) programme. 
Typically this information is collected within spreadsheets and Work Package 4 (WP4) has been working with field managers and biologists to standardise these spreadsheets and collection mechanisms.
The standards we have produced follow the same concepts as the [Breeding API (BrAPI)](https://brapi.org/), a technical solution to use these standards to make genotyping, phenotyping and trial data interoperable and reusable.

The top level of the BrAPI hierarchy is a **Programme** which, initially for us, is the DFW programme. 
We can store non-DFW data and create the relevant Programmes for such data, however our initial focus is on DFW data.

Each Programme can contain one or more **Trials**, which BrAPI defines as the equivalent of an 
"investigation" in the [Minimal Information about a Plant Phenotyping Experiment (MIAPPE)](https://www.miappe.org/) standard.

Trials can consist of one or more experiments where seeds are sown and phenotypic information is gathered and each of these is called a **Study**. 
These contain a variety of data, such as weather information, experimental design notes and each Study takes place at a **Location**. 
To add a Study to the system you need to define both the Field Trial that it is part of and the Location where it
took place.

For each Study, you can specify the set of phenotypes that will be measured and these are called **Measured Phenotype Variables**. Each of these consist of unique *triples* (three distinct pieces of information) that define:

 1. A phenotype
 2. How it has been measured 
 3. Which units have been used

When you have specified the phenotypes to use, these are submitted as **Plots**, along with the details of how the experiment has been laid out in the field. 
Plots contain various details such as width, length, position in field, phenotypic data, *etc.*

All of the uploaded data is available in our field trial search portal which allows you to search across all Studies and view individual Studies in more detail.

The various services are described in more detail below, however for easy access, the links to each of the services are:

### Registering an ORCID

To submit data into the DFW Field Trial system, you need to have an ORCID - a unique identifier that can be used to record your institution, affiliations, funding, publications, *etc.* ORCIDs are becoming favoured by funders, journals, and services like Grassroots because it allows: 

 * science outputs to be attributable to an individual even if they move employment and 
 * the use of ORCIDs as an authentication mechanism to identify people who are able to use specific services. 

In this case, we can attribute your field trials to you as collectors of this information within DFW, but also control who is able to submit data thus preventing people from gaining access to the system. 

Registering for an ORCID takes a couple of minutes and will not expose any personal information about you. You can follow the [instructions for getting an ORCID](https://grassroots.tools/docs/user/services/field_trial/orcid.md).

### Submitting data:

 * [Submitting a Programme](https://grassroots.tools/docs/user/services/field_trial/submit_programme.md)
 * [Submitting a Trial](https://grassroots.tools/docs/user/services/field_trial/submit_trial.md)
 * [Submitting a Location](https://grassroots.tools/docs/user/services/field_trial/submit_location.md)
 * [Submitting a Study](https://grassroots.tools/docs/user/services/field_trial/submit_study.md)
 * [Submitting Plots](https://grassroots.tools/docs/user/services/field_trial/submit_plots.md)

### Searching the system:

* [Field Trial Search Portal](https://grassroots.tools/docs/user/services/field_trial/search_portal.md)
* [Search Measured Phenotype Variables](https://grassroots.tools/docs/user/services/field_trial/search_measured_variables.md)
* [Search Treatments](https://grassroots.tools/docs/user/services/field_trial/search_treatments.md)

        
