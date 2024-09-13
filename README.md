# Affirmative action in the electoral regulations of the Legislature

Welcome to the GitHub repository of the database "Affirmative action in the electoral regulations of the Legislature," maintained by members of the Political Reform Observatory in Latin America.

## Contents

- [Summary](#summary)
- [Description](#description)
- [Citation](#citation)

## Summary

The database contains descriptive information to understand the way in which countries in Latin America implement affirmative actions that allow the integration of historically excluded groups in electoral scenarios, through the regulation of these actions in the legislative electoral regulations.
The collection of information was carried out by consulting the legislation of each country in Latin America on affirmative actions in the nomination of candidates. These affirmative actions in the legislative electoral regulations refer to national normative characteristics that establish measures so that the population that has been historically excluded from political representation can access elected positions.

The review utilizes the beginning of the third wave of democracy in Latin America as a base (Huntington, 1991).

Members of the Observatory of Political Reforms in Latin America collected and coded the information. The people responsible for collecting the data are Mauricio Lozano Massés (Faculty of Political and Social Sciences, UNAM), Yazmin Patricia Noris Contreras (Faculty of Higher Studies Acatlán, UNAM) and Arturo Peralta Oliver (Faculty of Higher Studies Aragón, UNAM) . While the person responsible for coding is Josué Godoy Jiménez (Faculty of Political and Social Sciences, UNAM).

Product was produced within the framework of Project IN302122. Project: “The resilience of democracies: elections and politics in the context of a pandemic”, of the Support Program for Research Projects in Technological Innovation of the UNAM- DGAPA, under the direction of. Flavia Freidenberg (IIJ-UNAM).

## Description

The directory `./Data/` contains the file `./Data/DD_Affirmative_Actions` where all relevant information regarding the database linked to the affirmative action in the electoral regulations of the Legislature and its reforms is located. Specifically, the database consists of the following variables:

-   `country`: name of the country in which the reform on affirmative actions in the legislative electoral regulation was carried out.

-   `cowcode`: country code according to the “Correlates of War” coding https://correlatesofwar.org/data-sets/cow-country-codes.

-   `country_abbreviation`: country acronym according to the ISO three-letter code. (ARG, MEX, SAL) http://utils.mucattu.com/iso_3166-1.html.

-   `reform_year`: corresponding calendar year to which the reform in which affirmative action was established in the legislative electoral regulation (1991-2020).

-   `consec_reform_country`: records the consecutive number of reforms to affirmative actions in electoral regulation in each Latin American country for elected positions in the national legislature. Example: Peru_1, Peru_2, Peru_3, Peru_4.

-   `norm`: indicates the legal range of the regulations where affirmative actions are established. Its values: Does not exist [0], there is no legal framework or agreements issued by the administrative or jurisdictional authorities on electoral matters that regulate affirmative actions; Judgment [1], the affirmative actions are regulated in rulings issued by the jurisdictional authorities in electoral matters; Agreement [2], affirmative actions are regulated in agreements issued by the administrative authorities on electoral matters; Law [3], the affirmative actions are regulated in electoral laws or in the relevant area; Constitution [4], affirmative actions are regulated at constitutional level.

-   `lh_women`: records the existence or nonexistence of the corresponding legislation on affirmative actions that are applied to women's candidacies to occupy a seat in the lower house of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `lh_women_mandatory`: indicates the existence or non-existence of mandatory affirmative actions for women's candidacies for the lower house. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `lh_woman_percentage`: indicates the existence or non-existence of percentages in the affirmative actions implemented in women's candidacies for the lower house. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `lh_women_seats`: indicates the percentage of seats of affirmative actions applied to women's candidacies for the lower house.

-   `lh_youth`: records the existence or nonexistence in the corresponding legislation of affirmative actions that are applied to the candidacies of young people to occupy a seat in the lower house of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `lh_youth_mandatory`: indicates the existence or non-existence of mandatory affirmative actions for the candidacies of young people to the lower house. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `lh_youth_percentage`: indicates the existence or non-existence of percentages in the affirmative actions implemented in the candidacies of young people to the lower house. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `lh_youth_seats`: indicates the percentage of seats of affirmative actions applied to the candidacies of young people to the lower house.

-   `lh_indigenous`: records the existence or nonexistence of the corresponding legislation on the affirmative actions that are applied to the candidacies of indigenous people to occupy a seat in the lower house of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `lh_indigenous_mandatory`: indicates the existence or non-existence of mandatory affirmative actions of candidacies for  indigenous people in the lower house. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `lh_indigenous_percentage`: indicates the existence or non-existence percentages of affirmative actions implemented in the candidacies of indigenous people in the lower house. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `lh_indigenous_seats`: indicates the percentage of affirmative action seats applied to the candidacies of indigenous people in the lower house.

-   `lh_afrodescendant`: records the existence or nonexistence of corresponding legislation on affirmative actions that are applied to the candidacies of people of African descent to occupy a seat in the lower house of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `lh_afrodescendent_mandatory`: indicates the existence or non-existence of mandatory affirmative actions for the candidacies of people of African descent to the lower house. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `lh_afordescendant_percentage`: indicates the existence or non-existence of percentages of affirmative actions implemented in the candidacies of people of African descent in the lower house. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `lh_afrodescendant_seats`: indicates the percentage of affirmative action seats applied to the candidacies of people of African descent in the lower house.

-   `lh_LGBTIQ`: records the existence or nonexistence on the corresponding legislation of affirmative actions that guarantee the presence of people belonging to the LGBTQI+ community in the lower house of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `lh_LGBTIQ_mandatory`: indicates the existence or non-existence of mandatory affirmative actions for the candidacies of people belonging to the LGBTIQ+ community in the lower house. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `lh_LGBTIQ_percentage`: indicates the existence or non-existence of percentages in the affirmative actions implemented in the candidacies of people belonging to the LGBTIQ+ community in the lower house. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `lh_LGBTIQ_seats`: indicates the percentage of affirmative action seats applied to the candidacies of the LGBTIQ+ community in the lower house.

-   `lh_abroad`: records the existence or non-existence in the corresponding legislation of affirmative actions that are applied to the candidacies of people residing abroad to occupy a seat in the lower house of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `lh_abroad_mandatory`: indicates the existence or non-existence of mandatory affirmative actions for the candidacies of people residing abroad in the lower house. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `lh_abroad_percentage`: indicates the existence or non-existence percentages of the affirmative actions implemented in the candidacies of people residing abroad in the lower house. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `lh_abroad_seats`: indicates the percentage of affirmative action seats applied to the candidacies of people residing abroad to the lower house.

-   `lh_disability`: records the existence or nonexistence in the corresponding legislation of affirmative actions that are applied to the candidacies of people with disabilities to occupy a seat in the lower house of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `lh_disability_mandatory`: indicates the existence or non-existence of mandatory affirmative actions for the candidacies of people with disabilities in the lower house. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `lh_disability_percentage`: indicates the existence or non-existence  percentages of the affirmative actions implemented in the candidacies of people with disabilities in the lower house. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `lh_disability_seats`: indicates the percentage of affirmative action seats applied to the candidacies of people with disabilities in the lower house.

-   `uh_women`: records the existence or nonexistence in the corresponding legislation of affirmative actions that are applied to women's candidacies to occupy a seat in the Senate (upper house) of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `uh_women_mandatory`: indicates the existence or non-existence of mandatory affirmative actions for women's candidacies in the Senate (upper house) of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `uh_women_percentage`: indicates the existence or non-existence percentages in the affirmative actions implemented in the candidacies of women in the Senate (upper house) of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `uh_women_seats`: indicates the percentage of seats of affirmative actions applied to women's candidacies in the Senate (upper house) of a country.

-   `uh_youth`: records the existence or nonexistence in the corresponding legislation of affirmative actions that are applied to the candidacies of young people to occupy a seat in the Senate (upper house) of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `uh_youth_mandatory`: indicates the existence or non-existence of mandatory affirmative actions for the candidacies of young people in the Senate (upper house) of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `uh_youth_percentage`: indicates the existence or non-existence percentages in the affirmative actions implemented in the candidacies of young people in the Senate (upper house) of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `uh_youth_seats`: indicates the percentage of seats of affirmative actions applied to the candidacies of young people in the Senate (upper house) of a country.

-   `uh_indigenous`: records the existence or nonexistence in the corresponding legislation of affirmative actions that are applied to the candidacies of indigenous people to occupy a seat in the Senate (upper house) of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `uh_indigenous_mandatory`: indicates the existence or non-existence of mandatory affirmative actions for the candidacies of indigenous people in the Senate (upper house) of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `uh_indigenous_percentage`: indicates the existence or non-existence percentages in the affirmative actions implemented in the candidacies of indigenous people in the Senate (upper house) of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `uh_indigenous_seats`: indicates the percentage of affirmative action seats applied to the candidacies of indigenous people in the Senate (upper house) of a country.

-   `uh_afrodescendant`: records the existence or nonexistence in the corresponding legislation of affirmative actions that are applied to the candidacies of people of African descent to occupy a seat in the Senate (upper house) of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `uh_afrodescendant_mandatory`: indicates the existence or non-existence of mandatory affirmative actions for the candidacies of people of African descent in the Senate (upper house) of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `uh_afrodescendant_percentage`: indicates the existence or non-existence  percentages in the affirmative actions implemented in the candidacies of people of African descent in the Senate (upper house) of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `uh_afrodescendant_seats`: indicates the percentage of affirmative action seats applied to the candidacies of people of African descent in the Senate (upper house) of a country.

-   `uh_LGBTIQ`: records the existence or non-existence in the corresponding legislation of affirmative actions that guarantee the presence of people belonging to the LGBTIQ+ community in the Senate (upper house) of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `uh_LGBTIQ_mandatory`: indicates the existence or non-existence of mandatory affirmative actions for the candidacies of people belonging to the LGBTIQ+ community in the Senate (upper house) of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `uh_LGBTIQ_percentage`: indicates the existence or non-existence percentages in the affirmative actions implemented in the candidacies of people belonging to the LGBTIQ+ community in the Senate (upper house) of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `uh_LGBTIQ_seats`: indicates the percentage of affirmative action seats applied to the candidacies of the LGBTIQ+ community in the Senate (upper house) of a country.

-   `uh_abroad`: records the existence or non-existence in the corresponding legislation of affirmative actions that are applied to the candidacies of people residing abroad to occupy a seat in the Senate (upper house) of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `uh_abroad_mandatory`: indicates the existence or non-existence of mandatory affirmative actions for the candidacies of people residing abroad in the Senate (upper house) of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `uh_abroad_percentaje`: indicates the existence or nonexistence percentages in the affirmative actions implemented in the candidacies of people residing abroad in the Senate (upper house) of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `uh_abroad_seats`: indicates the percentage of affirmative action seats applied to the candidacies of people residing abroad in the Senate (upper house) of a country.

-   `uh_disability`: records the existence or nonexistence in the corresponding legislation of affirmative actions that are applied to the candidacies of people with disabilities to occupy a seat in the Senate (upper house) of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `uh_disability_mandatory`: indicates the existence or non-existence of mandatory affirmative actions for the candidacies of people with disabilities in the Senate (upper house) of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `uh_disability_percentage`: indicates the existence or non-existence percentages in the affirmative actions implemented in the candidacies of people with disabilities in the Senate (upper house) of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `uh_disability_seats`: indicates the percentage of affirmative action seats applied to the candidacies of people with disabilities in the Senate (upper house) of a country.

-   `sc_women`: records the existence or nonexistence in the corresponding legislation of affirmative actions that are applied to women's candidacies to occupy a seat in the single chamber of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `sc_women_mandatory`: indicates the existence or non-existence of mandatory affirmative actions for women's candidacies for the single chamber. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `sc_women_percentage`: indicates the existence or non-existence percentages in the affirmative actions implemented in women's candidacies for the single chamber. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `sc_women_seats`: indicates the percentage of seats of affirmative actions applied to women's candidacies for the single chamber.

-   `sc_youth`: records the existence or nonexistence in the corresponding legislation of affirmative actions that are applied to the candidacies of young people to occupy a seat in the single chamber of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `sc_youth_mandatory`: indicates the existence or non-existence of mandatory affirmative actions for the candidacies of young people to the single chamber. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `sc_youth_percentage`: indicates the existence or non-existencenpercentages in the affirmative actions implemented in the candidacies of young people to the single chamber. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `sc_youth_seats`: indicates the percentage of seats of affirmative actions applied to the candidacies of young people to the single chamber.

-   `sc_indigenous`: records the existence or non-existence in the corresponding legislation of affirmative actions that are applied to the candidacies of indigenous people to occupy a seat in the single chamber of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `sc_indigenous_mandatory`: indicates the existence or non-existence of mandatory affirmative actions for the candidacies of indigenous people to the single chamber. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `sc_indigenous_percentage`: indicates the existence or non-existence percentages in the affirmative actions implemented in the candidacies of indigenous people to the single chamber. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `sc_indigenous_seats`: indicates the percentage of affirmative action seats applied to the candidacies of indigenous people to the single chamber.

-   `sc_afrodescendant`: records the existence or nonexistence in the corresponding legislation of affirmative actions that are applied to the candidacies of people of African descent to occupy a seat in the single chamber of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `sc_afrodescendant_mandatory`: indicates the existence or non-existence of mandatory affirmative actions for the candidacies of people of African descent to the single chamber. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `sc_afrodescendant_percentage`: indicates the existence or non-existence percentages in the affirmative actions implemented in the candidacies of people of African descent to the single chamber. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `sc_afrodescendant_seats`: indicates the percentage of affirmative action seats applied to the candidacies of people of African descent to the single chamber.

-   `sc_LGBTIQ`: records the existence or non-existence in the corresponding legislation of affirmative actions that guarantee the presence of people belonging to the LGBTIQ+ community in the single chamber of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `sc_LGBTIQ_mandatory`: indicates the existence or non-existence of mandatory affirmative actions for the candidacies of people belonging to the LGBTIQ+ community in the single chamber. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `sc_LGBTIQ_percentage`: indicates the existence or non-existence percentages in the affirmative actions implemented in the candidacies of people belonging to the LGBTIQ+ community to the single chamber. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `sc_LGBTIQ_seats`: indicates the percentage of affirmative action seats applied to the candidacies of the LGBTIQ+ community to the single chamber.

-   `sc_abroad`: records the existence or non-existence in the corresponding legislation of affirmative actions that are applied to the candidacies of people residing abroad to occupy a seat in the single chamber of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `sc_abroad_mandatory`: indicates the existence or non-existence of mandatory affirmative actions for the candidacies of people residing abroad to the single chamber. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `sc_abroad_percentage`: indicates the existence or non-existence of percentages in the affirmative actions implemented in the candidacies of people residing abroad to the single chamber. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `sc_abroad_seats`: indicates the percentage of affirmative action seats applied to the candidacies of people residing abroad to the single chamber.

-   `sc_disability`: records the existence or nonexistence in the corresponding legislation of affirmative actions that are applied to the candidacies of people with disabilities to occupy a seat in the single chamber of a country. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `sc_disability_mandatory`: indicates the existence or non-existence of mandatory affirmative actions for the candidacies of people with disabilities to the single chamber. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `sc_disability_percentage`: indicates the existence or non-existence percentages in the affirmative actions implemented in the candidacies of people with disabilities to the single chamber. It is a dichotomous variable whose values are [0] does not exist and [1] does exist.

-   `sc_disability_seats`: indicates the percentage of affirmative action seats applied to the candidacies of people with disabilities to the single chamber.

## Citation

``` r
Freidenberg, Flavia. Dir., 2023, “Affirmative actions in the legislative electoral regulations”, DOI: 10.5281/zenodo.7853670. Observatory of Political Reforms in Latin America (1978-2023). Mexico City: Legal Research Institute (IIJ-UNAM) and Washington, D.C.: Secretariat for Strengthening Democracy of the Organization of American States (SFD/OAS), V1. Available in: https://bit.ly/3T2v3eC
```