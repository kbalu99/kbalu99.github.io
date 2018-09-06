.. _statpickmodel:

==============
Stat Model Selection
==============

.. contents:: :local:

Stat Model Cheatsheet  (from James Leeper "Choosing right Statistic")
==============

.. raw:: html

   <article class="post-882 page type-page status-publish entry" itemscope="" itemtype="https://schema.org/CreativeWork">
   <header class="entry-header">
      <h1 class="entry-title" itemprop="headline">Choosing the Correct Statistical Test in SAS, Stata, SPSS and R</h1>
   </header>
   <div class="entry-content" itemprop="text">
      <p>The following table shows general guidelines for choosing a statistical
         analysis. We emphasize that these are general guidelines and should not be
         construed as hard and fast rules. Usually your data could be analyzed in
         multiple ways, each of which could yield legitimate answers. The table below
         covers a number of common analyses and helps you choose among them based on the
         number of dependent variables (sometimes referred to as outcome variables), the
         nature of your independent variables (sometimes referred to as
         predictors). You also want to consider the nature of your dependent
         variable, namely whether it is an interval variable, ordinal or categorical
         variable, and whether it is normally distributed (see <a href="https://stats.idre.ucla.edu/other/mult-pkg/whatstat/what-is-the-difference-between-categorical-ordinal-and-interval-variables/">What is the difference between categorical, ordinal and interval variables?</a>
         for more information on this). The table then shows one or more
         statistical tests commonly used given these types of variables (but not
         necessarily the only type of test that could be used) and links showing how to
         do such tests using SAS, Stata and SPSS.
      </p>
      <table>
         <tbody>
            <tr>
               <th>Number of Dependent Variables</th>
               <th>Nature of Independent Variables</th>
               <th><a href="https://stats.idre.ucla.edu/other/mult-pkg/whatstat/what-is-the-difference-between-categorical-ordinal-and-interval-variables/">Nature of Dependent Variable(s)</a></th>
               <th>Test(s)</th>
               <th>How to SAS</th>
               <th>How to Stata</th>
               <th>How to SPSS</th>
               <th>How to R</th>
            </tr>
            <tr>
               <th rowspan="28">1</th>
               <th rowspan="4">0 IVs (1 population)</th>
               <td>interval &amp; normal</td>
               <td>one-sample t-test</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#1sampt">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#1sampt">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#1sampt">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#1sampt">R</a></td>
            </tr>
            <tr>
               <td>ordinal or interval</td>
               <td>one-sample median</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#1sampm">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#1sampm">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#1sampm">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#1sampm">R</a></td>
            </tr>
            <tr>
               <td>categorical (2 categories)</td>
               <td>binomial test</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#bitest">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#bitest">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#bitest">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#bitest">R</a></td>
            </tr>
            <tr>
               <td>categorical</td>
               <td>Chi-square goodness-of-fit</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#chifit">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#chifit">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#chifit">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#chifit">R</a></td>
            </tr>
            <tr>
               <th rowspan="4">1 IV with 2 levels (independent groups)</th>
               <td>interval &amp; normal</td>
               <td>2 independent sample t-test</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#2ittest">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#2ittest">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#2ittest">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#2ittest">R</a></td>
            </tr>
            <tr>
               <td>ordinal or interval</td>
               <td>Wilcoxon-Mann Whitney test</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#wilc">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#wilc">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#wilc">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#wilc">R</a></td>
            </tr>
            <tr>
               <th rowspan="2">categorical</th>
               <td>Chi-square test</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#chisq">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#chisq">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#chisq">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#chisq">R</a></td>
            </tr>
            <tr>
               <td>Fisher’s exact test</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#exact">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#exact">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#exact">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#exact">R</a></td>
            </tr>
            <tr>
               <th rowspan="3">1 IV with 2 or more levels (independent groups)</th>
               <td>interval &amp; normal</td>
               <td>one-way ANOVA</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#1anova">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#1anova">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#1anova">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#1anova">R</a></td>
            </tr>
            <tr>
               <td>ordinal or interval</td>
               <td>Kruskal Wallis</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#kw">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#kw">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#kw">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#kw">R</a></td>
            </tr>
            <tr>
               <td>categorical</td>
               <td>Chi-square test</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#chisq">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#chisq">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#chisq">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#chisq">R</a></td>
            </tr>
            <tr>
               <th rowspan="3">1 IV with 2 levels (dependent/matched groups)</th>
               <td>interval &amp; normal</td>
               <td>paired t-test</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#pairt">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#pairt">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#pairt">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#pairt">R</a></td>
            </tr>
            <tr>
               <td>ordinal or interval</td>
               <td>Wilcoxon signed ranks test</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#wilcsign">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#wilcsign">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#wilcsign">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#wilcsign">R</a></td>
            </tr>
            <tr>
               <td>categorical</td>
               <td>McNemar</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#Mcnemar">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#Mcnemar">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#Mcnemar">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#Mcnemar">R</a></td>
            </tr>
            <tr>
               <th rowspan="3">1 IV with 2 or more levels (dependent/matched groups)</th>
               <td>interval &amp; normal</td>
               <td>one-way repeated measures ANOVA</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#1repanova">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#1repanova">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#1repanova">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#1repanovA">R</a></td>
            </tr>
            <tr>
               <td>ordinal or interval</td>
               <td>Friedman test</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#fried">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#fried">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#fried">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#fried">R</a></td>
            </tr>
            <tr>
               <td>categorical (2 categories)</td>
               <td>repeated measures logistic regression</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#1replog">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#1replog">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#1replog">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#1replog">R</a></td>
            </tr>
            <tr>
               <th rowspan="3">2 or more IVs (independent groups)</th>
               <td>interval &amp; normal</td>
               <td>factorial ANOVA</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#factanov">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#factanov">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#factanov">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#factanov">R</a></td>
            </tr>
            <tr>
               <td>ordinal or interval</td>
               <td>ordered logistic regression</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#orderedlogistic">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#orderedlogistic">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#orderedlogistic">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#orderedlOgistic">R</a></td>
            </tr>
            <tr>
               <td>categorical (2 categories)</td>
               <td>factorial logistic regression</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#faclogistic">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#faclogistic">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#faclogistic">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#faclogisTic">R</a></td>
            </tr>
            <tr>
               <th rowspan="4">1 interval IV</th>
               <td>interval &amp; normal</td>
               <td>correlation</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#corr">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#corr">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#corr">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#corr">R</a></td>
            </tr>
            <tr>
               <td>interval &amp; normal</td>
               <td>simple linear regression</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#simpreg">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#simpreg">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#simpreg">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#simpreg">R</a></td>
            </tr>
            <tr>
               <td>ordinal or interval</td>
               <td>non-parametric correlation</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#nonparr">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#nonparr">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#nonparr">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#nonparr">R</a></td>
            </tr>
            <tr>
               <td>categorical</td>
               <td>simple logistic regression</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#simplog">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#simplog">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#simplog">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#simplog">R</a></td>
            </tr>
            <tr>
               <th rowspan="4">1 or more interval IVs and/or 1 or more categorical IVs</th>
               <th rowspan="2">interval &amp; normal</th>
               <td>multiple regression</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#multreg">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#multreg">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#multreg">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#multreg">R</a></td>
            </tr>
            <tr>
               <td>analysis of covariance</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#ancova">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#ancova">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#ancova">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#ancova">R</a></td>
            </tr>
            <tr>
               <th rowspan="2">categorical</th>
               <td>multiple logistic regression</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#logistic">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#logistic">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#logistic">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#logistic">R</a></td>
            </tr>
            <tr>
               <td>discriminant analysis</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#discrim">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#discrim">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#discrim">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#discrim">R</a></td>
            </tr>
            <tr>
               <th rowspan="3">2+</th>
               <th>1 IV with 2 or more levels (independent groups)</th>
               <td>interval &amp; normal</td>
               <td>one-way MANOVA</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#manova">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#manova">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#manova">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#manova">R</a></td>
            </tr>
            <tr>
               <th>2+</th>
               <td>interval &amp; normal</td>
               <td>multivariate multiple linear regression</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#mmreg">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#mmreg">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#mmreg">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#mmreg">R</a></td>
            </tr>
            <tr>
               <th>0</th>
               <td>interval &amp; normal</td>
               <td>factor analysis</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#factor">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#factor">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#factor">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#factor">R</a></td>
            </tr>
            <tr>
               <th>2 sets of 2+</th>
               <th>0</th>
               <td>interval &amp; normal</td>
               <td>canonical correlation</td>
               <td><a href="https://stats.idre.ucla.edu/sas/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-sas/#cancor">SAS</a></td>
               <td><a href="https://stats.idre.ucla.edu/stata/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-stata/#cancor">Stata</a></td>
               <td><a href="https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/#cancor">SPSS</a></td>
               <td><a href="https://stats.idre.ucla.edu/r/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-r/#cancor">R</a></td>
            </tr>
            <tr>
               <th></th>
               <th></th>
               <th></th>
               <th></th>
               <th></th>
               <th></th>
               <th></th>
               <th></th>
            </tr>
         </tbody>
      </table>
      <p>This page was adapted from <em>Choosing&nbsp;the Correct Statistic</em> developed by James D. Leeper, Ph.D.&nbsp; We thank Professor
         Leeper for permission to adapt and distribute this page from our site.
      </p>
      <p>&nbsp;</p>
      <p>&nbsp;</p>
    </div>
    </article> 


    <center>
   <table width="100%" border="1" style="border-collapse: collapse" bordercolor="#111111" cellpadding="0" cellspacing="0">
      <tbody>
         <tr bgcolor="#ff0000">
            <td align="middle">
               <font size="+1" color="#000000">Number</font> 
               <center>
                  <p><font size="+1" color="#000000">of</font> <br>
                     <font size="+1" color="#000000"><a href="#outcome">Dependent*</a></font> <br>
                     <font size="+1" color="#000000">Variables</font>
                  </p>
               </center>
            </td>
            <td>
               <center>
                  <p><font size="+1" color="#000000">Number</font> <br>
                     <font size="+1" color="#000000">of</font> <br>
                     <font size="+1" color="#000000"><a href="#predictor">Independent**</a></font>
                     <br>
                     <font size="+1" color="#000000">Variables</font>
                  </p>
               </center>
            </td>
            <td>
               <center>
                  <p><font size="+1" color="#000000">Type</font> <br>
                     <font size="+1" color="#000000">of</font> <br>
                     <font size="+1" color="#000000">Dependent</font> <br>
                     <font size="+1" color="#000000">Variable(s)</font>
                  </p>
               </center>
            </td>
            <td>
               <center>
                  <p><font size="+1" color="#000000">Type</font> <br>
                     <font size="+1" color="#000000">of</font> <br>
                     <font size="+1" color="#000000">Independent</font> <br>
                     <font size="+1" color="#000000">Variable(s)</font>
                  </p>
               </center>
            </td>
            <td align="middle"><font size="+1" color="#000000">&nbsp;Measure</font></td>
            <td>
               <center>
                  <p><font size="+1" color="#000000">Test(s)</font></p>
               </center>
            </td>
         </tr>
         <tr bgcolor="#ffcccc">
            <td valign="top" bgcolor="#ffcccc" rowspan="26">
               <center>
                  <p><font size="+1">1</font></p>
               </center>
            </td>
            <td valign="center" rowspan="3">
               <center>
                  <p>&nbsp;0 <br>
                     (1 population)
                  </p>
               </center>
            </td>
            <td>
               <center>
                  <p>continuous normal</p>
               </center>
            </td>
            <td rowspan="3">
               <center>
                  <p>not applicable&nbsp; <br>
                     (none)
                  </p>
               </center>
            </td>
            <td>
               <center>
                  <p>&nbsp;mean</p>
               </center>
            </td>
            <td>
               <center>
                  <p>one-sample t-test</p>
               </center>
            </td>
         </tr>
         <tr>
            <td bgcolor="#ffcccc">
               <center>
                  <p>&nbsp;continuous non-normal</p>
               </center>
            </td>
            <td bgcolor="#ffcccc">
               <center>
                  <p>&nbsp;median</p>
               </center>
            </td>
            <td bgcolor="#ffcccc">
               <center>
                  <p>one-sample median</p>
               </center>
            </td>
         </tr>
         <tr bgcolor="#ffcccc">
            <td>
               <center>
                  <p>&nbsp;categorical</p>
               </center>
            </td>
            <td>
               <center>
                  <p>&nbsp;proportions</p>
               </center>
            </td>
            <td>
               <center>
                  <p>&nbsp;Chi Square goodness-of-fit, binomial test</p>
               </center>
            </td>
         </tr>
         <tr>
            <td valign="center" rowspan="3">
               <center>
                  <p>&nbsp;1 <br>
                     (2 independent populations)
                  </p>
               </center>
            </td>
            <td>
               <center>
                  <p>normal</p>
               </center>
            </td>
            <td rowspan="3">
               <center>
                  <p>&nbsp;2 categories</p>
               </center>
            </td>
            <td>
               <center>
                  <p>&nbsp;mean</p>
               </center>
            </td>
            <td>
               <center>
                  <p>2 independent sample t-test</p>
               </center>
            </td>
         </tr>
         <tr bgcolor="#ffcccc">
            <td bgcolor="#ffffff">
               <center>
                  <p>&nbsp;non-normal</p>
               </center>
            </td>
            <td bgcolor="#ffffff">
               <center>
                  <p>medians</p>
               </center>
            </td>
            <td bgcolor="#ffffff">
               <center>
                  <p>&nbsp;Mann Whitney, <br>
                     Wilcoxon rank sum test
                  </p>
               </center>
            </td>
         </tr>
         <tr>
            <td>
               <center>
                  <p>&nbsp;categorical</p>
               </center>
            </td>
            <td>
               <center>
                  <p>&nbsp;proportions</p>
               </center>
            </td>
            <td>
               <center>
                  <p>&nbsp;Chi square test <br>
                     Fisher's Exact test
                  </p>
               </center>
            </td>
         </tr>
         <tr bgcolor="#ffcccc">
            <td valign="center" rowspan="3">
               <center>
                  <p>0 <br>
                     (1 population measured twice) <br>
                     <b><i>or</i></b> <br>
                     1 <br>
                     (2 matched populations)
                  </p>
               </center>
            </td>
            <td>
               <center>
                  <p>normal</p>
               </center>
            </td>
            <td rowspan="3">
               <center>
                  <p>&nbsp;not applicable/ <br>
                     categorical
                  </p>
               </center>
            </td>
            <td>
               <center>
                  <p>means</p>
               </center>
            </td>
            <td>
               <center>
                  <p>paired t-test&nbsp;</p>
               </center>
            </td>
         </tr>
         <tr bgcolor="#ffcccc">
            <td bgcolor="#ffcccc">
               <center>
                  <p>&nbsp;non-normal</p>
               </center>
            </td>
            <td bgcolor="#ffcccc">
               <center>
                  <p>&nbsp;medians</p>
               </center>
            </td>
            <td bgcolor="#ffcccc">
               <center>
                  <p>Wilcoxon signed ranks test&nbsp;</p>
               </center>
            </td>
         </tr>
         <tr>
            <td bgcolor="#ffcccc">
               <center>
                  <p>&nbsp;categorical</p>
               </center>
            </td>
            <td bgcolor="#ffcccc">
               <center>
                  <p>&nbsp;proportions</p>
               </center>
            </td>
            <td bgcolor="#ffcccc">
               <center>
                  <p>McNemar, Chi-square test</p>
               </center>
            </td>
         </tr>
         <tr bgcolor="#ffffff">
            <td valign="center" rowspan="3">
               <center>
                  <p>1 <br>
                     (3 or more populations)
                  </p>
               </center>
            </td>
            <td>
               <center>
                  <p>normal</p>
               </center>
            </td>
            <td valign="center" rowspan="3">
               <center>
                  <p>categorical</p>
               </center>
            </td>
            <td>
               <center>
                  <p>means</p>
               </center>
            </td>
            <td>
               <center>
                  <p>one-way ANOVA</p>
               </center>
            </td>
         </tr>
         <tr>
            <td bgcolor="#ffffff">
               <center>
                  <p>non-normal</p>
               </center>
            </td>
            <td bgcolor="#ffffff">
               <center>
                  <p>medians</p>
               </center>
            </td>
            <td bgcolor="#ffffff">
               <center>
                  <p>Kruskal Wallis</p>
               </center>
            </td>
         </tr>
         <tr bgcolor="#ffffff">
            <td>
               <center>
                  <p>categorical</p>
               </center>
            </td>
            <td>
               <center>
                  <p>proportions</p>
               </center>
            </td>
            <td>
               <center>
                  <p>Chi square test</p>
               </center>
            </td>
         </tr>
         <tr bgcolor="#ffcccc">
            <td valign="center" rowspan="3">
               <center>
                  <p>2 or more <br>
                     (e.g., 2-way ANOVA)
                  </p>
               </center>
            </td>
            <td>
               <center>
                  <p>normal</p>
               </center>
            </td>
            <td valign="center" rowspan="3">
               <center>
                  <p>categorical</p>
               </center>
            </td>
            <td>
               <center>
                  <p>means</p>
               </center>
            </td>
            <td>
               <center>
                  <p>Factorial ANOVA</p>
               </center>
            </td>
         </tr>
         <tr bgcolor="#ffffff">
            <td bgcolor="#ffcccc">
               <center>
                  <p>non-normal</p>
               </center>
            </td>
            <td bgcolor="#ffcccc">
               <center>
                  <p>medians</p>
               </center>
            </td>
            <td bgcolor="#ffcccc">
               <center>
                  <p>Friedman test</p>
               </center>
            </td>
         </tr>
         <tr bgcolor="#ffcccc">
            <td>
               <center>
                  <p>categorical</p>
               </center>
            </td>
            <td>
               <center>
                  <p>proportions</p>
               </center>
            </td>
            <td>
               <center>
                  <p>log-linear, logistic regression</p>
               </center>
            </td>
         </tr>
         <tr bgcolor="#ffffff">
            <td>
               <center>
                  <p>0 <br>
                     (1 population measured&nbsp; <br>
                     3 or more times)
                  </p>
               </center>
            </td>
            <td>
               <center>
                  <p>normal</p>
               </center>
            </td>
            <td>
               <center>
                  <p>not applicable</p>
               </center>
            </td>
            <td>
               <center>
                  <p>means</p>
               </center>
            </td>
            <td>
               <center>
                  <p>Repeated measures ANOVA</p>
               </center>
            </td>
         </tr>
         <tr bgcolor="#ffcccc">
            <td rowspan="4">
               <center>
                  <p>1</p>
               </center>
            </td>
            <td>
               <center>
                  <p>normal</p>
               </center>
            </td>
            <td valign="center" align="middle" colspan="2" rowspan="2">continuous</td>
            <td>
               <center>
                  <p>correlation <br>
                     simple linear regression
                  </p>
               </center>
            </td>
         </tr>
         <tr bgcolor="#ffffff">
            <td bgcolor="#ffcccc">
               <center>
                  <p>non-normal</p>
               </center>
            </td>
            <td bgcolor="#ffcccc">
               <center>
                  <p>&nbsp;non-parametric correlation</p>
               </center>
            </td>
         </tr>
         <tr>
            <td valign="center" align="middle" bgcolor="#ffcccc" rowspan="2">
               <center>
                  <p>categorical</p>
               </center>
            </td>
            <td bgcolor="#ffcccc" colspan="2">
               <center>
                  <p>categorical or continuous</p>
               </center>
            </td>
            <td bgcolor="#ffcccc">
               <center>
                  <p>logistic regression</p>
               </center>
            </td>
         </tr>
         <tr>
            <td bgcolor="#ffcccc" colspan="2">
               <center>
                  <p>continuous</p>
               </center>
            </td>
            <td bgcolor="#ffcccc">
               <center>
                  <p>discriminant analysis</p>
               </center>
            </td>
         </tr>
         <tr bgcolor="#ffffff">
            <td valign="center" align="middle" rowspan="6">
               <center>
                  <p>&nbsp;2 or more</p>
               </center>
            </td>
            <td bgcolor="#ffffff">
               <center>
                  <p>&nbsp;normal</p>
               </center>
            </td>
            <td valign="center" align="middle" colspan="2" rowspan="3">
               <center>
                  <p>continuous</p>
               </center>
            </td>
            <td bgcolor="#ffffff">
               <center>
                  <p>multiple linear regression&nbsp;</p>
               </center>
            </td>
         </tr>
         <tr>
            <td>
               <center>
                  <p>&nbsp;non-normal</p>
               </center>
            </td>
            <td>
               <center>
                  <p>&nbsp;</p>
               </center>
            </td>
         </tr>
         <tr bgcolor="#ffcccc">
            <td bgcolor="#ffffff">
               <center>
                  <p>categorical</p>
               </center>
            </td>
            <td bgcolor="#ffffff">
               <center>
                  <p>logistic regression</p>
               </center>
            </td>
         </tr>
         <tr bgcolor="#ffcccc">
            <td>
               <center>
                  <p>normal</p>
               </center>
            </td>
            <td colspan="2" rowspan="3">
               <center>
                  <p>mixed categorical and continuous</p>
               </center>
            </td>
            <td>
               <center>
                  <p>Analysis of Covariance <br>
                     General Linear Models (regression)
                  </p>
               </center>
            </td>
         </tr>
         <tr bgcolor="#ffcccc">
            <td>
               <center>
                  <p>&nbsp;non-normal</p>
               </center>
            </td>
            <td>&nbsp;</td>
         </tr>
         <tr bgcolor="#ffcccc">
            <td>
               <center>
                  <p>categorical</p>
               </center>
            </td>
            <td>
               <center>
                  <p>logistic regression</p>
               </center>
            </td>
         </tr>
         <tr bgcolor="#e8e8e8">
            <td>
               <center>
                  <p>2</p>
               </center>
            </td>
            <td>
               <center>
                  <p>2 or more</p>
               </center>
            </td>
            <td bgcolor="#e8e8e8">
               <center>
                  <p>normal</p>
               </center>
            </td>
            <td colspan="2">
               <center>
                  <p>categorical</p>
               </center>
            </td>
            <td>
               <center>
                  <p>MANOVA</p>
               </center>
            </td>
         </tr>
         <tr bgcolor="#ffcccc">
            <td>
               <center>
                  <p>2 or more</p>
               </center>
            </td>
            <td>
               <center>
                  <p>2 or more</p>
               </center>
            </td>
            <td>
               <center>
                  <p>normal</p>
               </center>
            </td>
            <td colspan="2">
               <center>
                  <p>continuous</p>
               </center>
            </td>
            <td>
               <center>
                  <p>multivariate multiple linear regression</p>
               </center>
            </td>
         </tr>
         <tr bgcolor="#ebebeb">
            <td>
               <center>
                  <p>2 sets of&nbsp; <br>
                     2 or more
                  </p>
               </center>
            </td>
            <td bgcolor="#e8e8e8">
               <center>
                  <p>0</p>
               </center>
            </td>
            <td>
               <center>
                  <p>normal</p>
               </center>
            </td>
            <td colspan="2">
               <center>
                  <p>not applicable</p>
               </center>
            </td>
            <td>
               <center>
                  <p>canonical correlation</p>
               </center>
            </td>
         </tr>
         <tr bgcolor="#ffcccc">
            <td>
               <center>
                  <p>2 or more</p>
               </center>
            </td>
            <td>
               <center>
                  <p>0</p>
               </center>
            </td>
            <td>
               <center>
                  <p>normal</p>
               </center>
            </td>
            <td colspan="2">
               <center>
                  <p>not applicable</p>
               </center>
            </td>
            <td>
               <center>
                  <p>factor analysis</p>
               </center>
            </td>
         </tr>
      </tbody>
    </table>
    </center>




























































































































    



