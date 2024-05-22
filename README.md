# Dual Causality Models
This repo walks through the statistical models I created to test dual causality factors between regime type and armed conflict in Africa during the course of my undergraduate studies.

**Files:** The following files are included in this repo:
* An Rmd file containing the code used to clean and create datasets, write and execute statistical models, and output effects plots;
* The five original datasets that I used to create a bespoke dataframe for the purposes of my analysis;
* Word documents with a sample and the complete text of the final paper I submitted for my undergraduate senior seminar in African conflict; and
* A PowerPoint presentation sumamrizing the research project's methodology and key findings.

## Background
In the spring of 2020, I completed a senior seminar in African conflict as part of my major in government. Throughout the semester, I completed a mixed-methods research project, applying my skills in statistical modeling and R to analyze the dual causality between African regime type and armed conflict. Dr. Laura Seay, my advisor and ultimate guide through my undergraduate studies, taught this course and offered tremendous support as I ventured into the quantitative realm – a generally untapped option within the Colby government department. 

## Abstract
This paper examines the relationship between African states’ regime types and intrastate conflict onset, severity, duration and outcome. A robust body of literature on regime type and conflict focuses largely on global trends of a one-way directionality, using regime type to explain conflict. I expect a causal mechanism to operate in both directions between the two: civil wars can affect the kind of regime that emerges post-conflict and an African state’s regime type can influence the onset, severity, duration, and outcome of an internal conflict. I rely on logistic regression, multiple linear regression, and ordinary least squares regression models to test these associations, drawing on indicators from the Varieties of Democracy, Armed Conflict, and World Development Indicators datasets. The data indicate that more autocratic regimes experience more, longer, and more severe conflicts, but fewer relapses than democratic regimes; as well, longer conflicts are significantly associated with more autocratic regimes. These findings also suggest that the causal mechanism in question is stronger when regime type is used to predict conflict rather than in the opposite direction, in which really only conflict duration plays a significant role.

## Dataset Bibliography

* Coppedge, Michael, John Gerring, Carl Henrik Knutsen, Staffan I. Lindberg, Jan Teorell, David Altman, Michael Bernhard, M. Steven Fish, Adam Glynn, Allen Hicken, Anna Lührmann, Kyle L. Marquardt, Kelly McMann, Pamela Paxton, Daniel Pemstein, Brigitte Seim, Rachel Sigman, Svend-Erik Skaaning, Jeffrey Staton, Steven Wilson, Agnes Cornell, Lisa Gastaldi, Haakon Gjerløw, Nina Ilchenko, Joshua Krusell, Laura Maxwell, Valeriya Mechkova, Juraj Medzihorsky, Josefine Pernes, Johannes von Römer, Natalia Stepanova, Aksel Sundström, Eitan Tzelgov, Yi-ting Wang, Tore Wig, and Daniel Ziblatt. “V-Dem [CountryYear/Country-Date] Dataset v9.” *Varieties of Democracy (V-Dem) Project.* (2019). Retrieved from https://doi.org/10.23696/vdemcy19.
* Gleditsch, Nils Petter, Peter Wallensteen, Mikael Eriksson, Margareta Sollenberg & Håvard Strand. Armed Conflict 1946-2001: A New Dataset. *Journal of Peace Research 39,* no. 5. (2002). Retrieved from https://ucdp.uu.se/downloads/index.html#armedconflict
* Lührmann, Anna, Staffan I. Lindberg, and Marcus Tannenberg. “Regimes in the World (RIW): A Robust Regime Type Measure Based on V-Dem.” *V-Dem Working Paper 2017,* no. 47. (2017). Retrieved from https://ssrn.com/abstract=2971869.
* Pettersson, Therese. UCDP/PRIO Armed Conflict Dataset Codebook v 19.1. *Uppsala Conflict Data Program.* (2019). Retrieved from https://ucdp.uu.se/downloads/.
* Ross, Michael and Paasha Madhavi. *Oil and gas data, 1932-2014.* Harvard Dataverse, 2015. https://doi.org/10.7910/DVN/ZTPW0Y*  2015.
* World Bank, and World Bank Group. *World Development Indicators.* Washington, D.C.: World Bank, 2019.

## License
BSD 3-Clause License

Copyright (c) 2024, Sam Kane

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its
   contributors may be used to endorse or promote products derived from
   this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
