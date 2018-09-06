.. _statpickmodel:

==============
Stat Model Selection
==============

.. contents:: :local:

Stat Model Cheatsheet  (from James Leeper "Choosing right Statistic")
==============

.. raw:: html

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




























































































































    



