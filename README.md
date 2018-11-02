# PrognosTILs application

## Purpose

Using pooled individual data of 9 studies (n=2148 patients), we have developed an integrated survival prediction model for early stage triple negative breast cancer patients, based on standard clinicopathological factors and stromal tumour infiltrating lymphocytes (TILs). The model has been shown to have satisficatory discrimination and calibration across studies (see Loi et al 2018). This tool has been designed to facilitate the use of this predictive model.

The application is available using the *Prognosis tool for triple negative breast cancer (TNBC)* button of <https://www.tilsinbreastcancer.org/>, or directly using the link <https://cesp-proxy.vjf.inserm.fr/shiny/prognosTILs/>.

A tutorial is available in the pdf file of this repository.

## Outcome prediction

### Available outcomes

This tool has been designed to calculate different indicators for a given time:

* Survival probability
* Cumulative incidence (event probability before the given time)

Different survival event may be considered:
*Invasive disease-free survival (iDFS)
*Distant disease-free survival (D-DFS)
*Overall survival (OS)

### Patient profiles

This app allows to compare the desired indicators for different patient profiles, according their clinical factors (age, number of positive nodes, tumor size, tumor histological grade and treatment) and their value of TILs. The indicators can also be compared for the same profile.

## App features

Users can export the results in a report document using different formats (pdf, docx or html). Different patient profiles can be created and compare them using the graphical illustration of their prediction according to the TILs value. Predictions for specific values of TILs can be obtained, which will be reported in tables in the final document. Users can save particular comparisons to report them in the final document. Add descriptions (which will be reported in the final document) to facilitate your final choice.

## References

Loi S, Drubay D, Adams S, Pruneri G, Francis PA, Lacroix-Triki M, Joensuu H, Dieci MV, Badve S, Demaria S, Gray R, Colleoni MA, Lemonnier J, Sotiriou C, Piccart MJ, Kellokumpu-Lehtinen PL, Andre F, Denkert C, Salgado R, Michiels S. Tumor infiltrating lymphocytes and prognosis: a pooled individual patient analysis of 2148 early-stage triple negative breast cancers. (Accepted in Journal of Clinical Oncology)

## Disclaimer

The survival prediction tool is not intended to replace medical decisions made by health professionals. The authors of this prediction tool will not be liable for any interpretation or decision based on the survival predictions made by this tool.



**Some issues with this app?**
Please contact Damien Drubay: <damien.drubay@gustaveroussy.fr>
