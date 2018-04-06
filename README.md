# Model-evaluation-and-applicability-domains
Example KNIME workflows for the "Model evaluation and applicability domains" chapter
Please not, the instruction are for Windows, but should follow similar steps for Linux and Mac as well.

1. Download and install KNIME Analytics Platform (https://www.knime.com/downloads/download-knime)
2. Download and install R (https://cran.r-project.org/mirrors.html)
3. Within R install the e1071 package used for the SVM 
   install.packages("e1071") 
4. Download all files from the GitHub repository
5. Unzip all files to "c:\tmp\" (Can use other path as well, but the workflows will need configuring)
6. Open "Model evaluation and applicability domains.knar" to open KNIME and import all workflows
7. Enable "Stable Community Contributions" repository under File -> Preferences -> Install/Update -> Available Software Sites
8. Set the R home path under  File -> Preferences -> KNIME -> R -> Path to R Home (eg. C:\Program Files\R\R-3.3.3)
9. Open the workflows, and install the required extra extensions as KNIME prompts (with restarting KNIME as prompted)
