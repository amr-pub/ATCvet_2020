# ATCvet (2020)

## About
The Anatomical Therapeutic Chemical Classification System for veterinary medicinal products (ATCvet) is used to classify veterinary drugs.

According to the [WHO Collaborating Centre for Drug Statistics Methodology](https://www.whocc.no/atcvet/atcvet/):

> ATCvet is a system for the classification of substances intended for therapeutic use in veterinary medicine, and can serve as a tool for the classification of medicinal products.

> The ATCvet system provides an administrative tool for putting groups of drugs into systems according to therapeutic categories. The aim is to:

> * facilitate exchanges of data for pharmacovigilance studies;
> * improve the comparability of statistics on sales of veterinary medicinal products;
> * provide authors of scientific articles with a tool for identifying medicines; and
> * help veterinary surgeons and pharmacists in their everyday work.

> In many European countries, veterinary medicinal products are presented in accordance with the ATCvet system in drug catalogues, and the system is used as an administrative tool by the health authorities. Since many substances are used in both human and veterinary medicine, the possibility of linking the classification systems for the two areas is of considerable value. The ATCvet system is therefore being developed in close association with the ATC system.

## Data Structure

In both the ATC and the ATCvet systems, preparations are divided into groups, according to their therapeutic use. First, they are divided into 15 anatomical groups (1st level), on the basis of their main therapeutic use.


| ATC | ATCvet | Name                                                            |
|-----|--------|-----------------------------------------------------------------|
| A   | QA     | Alimentary tract and metabolism                                 |
| B   | QB     | Blood and blood forming organs                                  |
| C   | QC     | Cardiovascular system                                           |
| D   | QD     | Dermatologicals                                                 |
| G   | QG     | Genito urinary system and sex hormones                          |
| H   | QH     | Systemic hormonal preparations, excl. sex hormones and insulins |
| -   | QI     | Immunologicals                                                  |
| J   | QJ     | Antiinfectives for systemic use                                 |
| L   | QL     | Antineoplastic and immunomodulating agents                      |
| M   | QM     | Musculo-skeletal system                                         |
| N   | QN     | Nervous system                                                  |
| P   | QP     | Antiparasitic products, insecticides and repellents             |
| R   | QR     | Respiratory system                                              |
| S   | QS     | Sensory organs                                                  |
| V   | QV     | Various                                                         |

A .CSV file is provided for each anatomical group.

## Source
The ATCvet dataset was obtained by scraping the [searchable index](https://www.whocc.no/atcvet/atcvet_index/) in early 2020.

## Version
This is the 2020 edition of the ATCvet index.
