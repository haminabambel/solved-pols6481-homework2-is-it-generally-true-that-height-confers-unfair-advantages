Download Link: https://assignmentchef.com/product/solved-pols6481-homework2-is-it-generally-true-that-height-confers-unfair-advantages
<br>
Is it generally true that height confers unfair advantages? Conventional wisdom holds that taller candidates win presidential elections, and taller executives tend to earn higher salaries.

Download the dataset <em>HeightWage_MenWomenUS_HW.csv</em> or <em>HeightWage_MenWomenUS_HW.dta</em>. These data are drawn from the National Longitudinal Study of Youth, 1979 cohort (age 14 to 22 years old in 1979). Our dependent variable is the wages earned in 1996 (<em>wage96</em>). Here is a codebook:

<table>

 <tbody>

  <tr>

   <td width="155"><strong>Variable name</strong></td>

   <td width="469"><strong>Description</strong></td>

  </tr>

  <tr>

   <td width="155"><em>male</em></td>

   <td width="469">Male (1 = yes, 0 = no)</td>

  </tr>

  <tr>

   <td width="155"><em>white</em></td>

   <td width="469">White (1 = yes, 0 = no)</td>

  </tr>

  <tr>

   <td width="155"><em>black</em></td>

   <td width="469">Black (1 = yes, 0 = no)</td>

  </tr>

  <tr>

   <td width="155"><em>hispanic</em></td>

   <td width="469">Hispanic (1 = yes, 0 = no)</td>

  </tr>

  <tr>

   <td width="155"><em>wage96</em></td>

   <td width="469">Adult hourly wages (dollars) reported in 1996 (salary and wages in past calendar year divided by hours worked in past calendar year)</td>

  </tr>

  <tr>

   <td width="155"><em>height85</em></td>

   <td width="469">Adult height (inches), self-reported in 1985</td>

  </tr>

  <tr>

   <td width="155"><em>height81</em></td>

   <td width="469">Adolescent height (inches), self-reported in 1981</td>

  </tr>

  <tr>

   <td width="155"><em>athlets</em></td>

   <td width="469">Participation in high school athletics (1 = yes, 0 = no)</td>

  </tr>

  <tr>

   <td width="155"><em>clubnum</em></td>

   <td width="469">Number of club memberships in high school, excluding athletics, academic/honor society clubs, and vocational clubs</td>

  </tr>

  <tr>

   <td width="155"><em>momed79</em></td>

   <td width="469">Mother’s years of education</td>

  </tr>

  <tr>

   <td width="155"><em>daded79</em></td>

   <td width="469">Father’s years of education</td>

  </tr>

  <tr>

   <td width="155"><em>mompro2</em></td>

   <td width="469">Mother in a professional/managerial occupation (1 = yes, 0 = no)</td>

  </tr>

  <tr>

   <td width="155"><em>poppro2</em></td>

   <td width="469">Father in a professional/managerial occupation (1 = yes, 0 = no)</td>

  </tr>

  <tr>

   <td width="155"><em>siblings </em></td>

   <td width="469">Number of siblings</td>

  </tr>

  <tr>

   <td width="155"><em>age</em></td>

   <td width="469">Age (years) in 1996</td>

  </tr>

  <tr>

   <td width="155"><em>esteem80</em></td>

   <td width="469">Score on Rosenberg Self-Esteem Scale as an adolescent in 1980 (higher values indicate higher self-esteem)</td>

  </tr>

  <tr>

   <td width="155"><em>hgc96</em></td>

   <td width="469">Highest grade of education completed in 1996</td>

  </tr>

 </tbody>

</table>

Also download the R script titled “<em>HW2q1-4prep.R</em>” and run the script to (a) eliminate cases with missing observations – but only for the variables you care about – and (b) eliminate variables you won’t care about and (c) limit the sample to male subjects, using the <em>male</em> variable.

<ol>

 <li>Estimate the following bivariate regression model using ordinary least squares:</li>

</ol>

<ul>

 <li>What does this regression suggest about the relationships between height and wages?</li>

 <li>Can the slope coefficient, , be statistically distinguished from zero?</li>

</ul>

<ol start="2">

 <li>Estimate the following multivariate regression model using ordinary least squares, which controls for the individual’s height as an adolescent:</li>

</ol>

<ul>

 <li>How does the estimated slope coefficient from the multivariate model compare with the estimated slope coefficient  from the simple regression model?</li>

 <li>How does the standard error of from the multivariate model compare to the bivariate regression model?</li>

 <li>Is from the multivariate model statistically significant, i.e., distinguishable from zero?</li>

 <li>Use the equations from lecture to solve for the standard errors for the simple and multiple regression coefficients for <em>height85</em>. Explain how the numerator changed, then explain how and specifically why the denominator changed, relative to the simple regression model.</li>

 <li>What is the correlation between <em>height85</em> and <em>height81</em>?</li>

 <li>How much of an effect did multicollinearity have on  and/or its standard error?</li>

</ul>

The researchers were interested in whether the effect of adolescent height on wages is partly due to height encouraging participation in sports and belonging to clubs. Adding two variables to the analysis will allow you to evaluate whether taller adolescents simply had more opportunities to develop leadership and other skills (i.e., social capital).

<ol start="3">

 <li>Estimate the following regression models using ordinary least squares:</li>

</ol>

<ul>

 <li>What do these regressions suggest about how height and social capital (belonging to clubs and/or participating in athletics) affect wages?</li>

 <li>In the last regression above, which slope coefficients are “statistically significant”?</li>

 <li>In the last regression above, how does the estimated slope coefficient <sub>2</sub> compare with the estimated slope coefficients from the earlier regression models?</li>

 <li>How does the standard error of the estimated slope coefficient <sub>2</sub> from the multivariate model compare to standard errors from the earlier regression models?</li>

 <li>What is the correlation between <em>clubnum</em> and <em>athlets</em>?</li>

 <li>What is the correlation between each of these variables and <em>height81</em>?</li>

</ul>

Maybe there’s more to life than just making money. Perhaps taller people get greater social capital, which increases self-esteem. The dataset includes scores on the Rosenberg Self-Esteem Scale, taken as an adolescent in 1980; higher values indicate more self-esteem.

<ol start="4">

 <li>Estimate the following regression models using ordinary least squares:</li>

</ol>

<ul>

 <li>What do these regressions suggest about the relationship between height and self-esteem?</li>

 <li>What does the second regression suggest about the relationship between social capital (belonging to clubs and/or participating in athletics) and self-esteem?</li>

 <li>Which slope coefficients are “statistically significant”?</li>

 <li>Is multicollinearity a potential problem here? Use the casual methods described in lecture 8 to describe why it is or isn’t a problem?</li>

</ul>




Does raising education levels tend to improve economic growth? For their article, “Do Better Schools Lead to More Growth? Cognitive Skills, Economic Outcomes, and Causation,” Hanushek and Woessmann (2012) collected a dataset on economic growth of 50 countries from 1960 to 2000. Here is a codebook:




<table>

 <tbody>

  <tr>

   <td width="154"><strong>Variable name</strong></td>

   <td width="469"><strong>Description</strong></td>

  </tr>

  <tr>

   <td width="154"><em>code</em></td>

   <td width="469">Country code</td>

  </tr>

  <tr>

   <td width="154"><em>name</em></td>

   <td width="469">Country name</td>

  </tr>

  <tr>

   <td width="154"><em>open</em></td>

   <td width="469">Openness of the economy scale</td>

  </tr>

  <tr>

   <td width="154"><em>ed60</em></td>

   <td width="469">Average years of schooling in 1960</td>

  </tr>

  <tr>

   <td width="154"><em>ypc60</em></td>

   <td width="469">GDP per capita in 1960</td>

  </tr>

  <tr>

   <td width="154"><em>ypcgr</em></td>

   <td width="469">Average annual growth rate (GDP per capita), 1960–2000</td>

  </tr>

  <tr>

   <td width="154"><em>testavg</em></td>

   <td width="469">Average combined math and science standardized test scores, 1964–2003</td>

  </tr>

  <tr>

   <td width="154"><em>proprts</em></td>

   <td width="469">Security of property rights scale</td>

  </tr>

  <tr>

   <td width="154"><em>edavg</em></td>

   <td width="469">Average years of schooling, 1960–2000</td>

  </tr>

  <tr>

   <td width="154"><em>region</em></td>

   <td width="469">Region</td>

  </tr>

 </tbody>

</table>




Download the dataset <em>globaled.csv</em> or <em>globaled.dta</em> and use it to answer questions 5–8:

<ol start="5">

 <li>Estimate a regression in which <em>ypcgr</em> is the dependent variable and <em>edavg</em> is the independent variable.</li>

</ol>

<ul>

 <li>Examine the coefficient for <em>edavg</em>; what effect does education have on growth?</li>

 <li>Examine the <em>t</em> statistic and <em>p</em> value; is the estimated coefficient statistically significant (<em>p </em>&lt; .05)?</li>

 <li>How much of the variation in average economic growth is explained by average education?</li>

</ul>

5½. Optional question: estimate a regression in which <em>ypcgr</em> is the dependent variable and <em>ypc60</em> is the independent variable.

<ul>

 <li>Examine the coefficient for <em>ypc60</em>; what effect did GDP per capita in 1960 have on subsequent growth?</li>

 <li>Examine the <em>t</em> statistic and <em>p</em> value; is the estimated coefficient statistically significant (<em>p </em>&lt; .05)?</li>

</ul>

<ol start="6">

 <li>Add the <em>ypc60</em> variable to the regression estimated in 5. The stated purpose of doing this is to control for GDP per capita, given the phenomenon that countries that are wealthier have slower growth rates, since poorer countries simply have more capacity to grow. You’ll also see that countries that are wealthier tend to have higher average years of education.</li>

</ol>

<ul>

 <li>Create a scatterplot with GDP per capita in 1960 on the horizontal axis and average years of education since 1960 on the vertical axis. How, and how strongly, are these variables related?</li>

 <li>Examine the coefficients; how did <em>edavg</em> and <em>ypc60</em> impact average growth since 1960?</li>

 <li>Examine the standard errors and <em>t</em> statistics for <em>edavg</em> and <em>ypc60</em>; is either of the estimated coefficients statistically significant (<em>p </em>&lt; .05)?</li>

 <li>Examine the variance-covariance and/or correlation matrix. Why did the coefficient on <em>edavg</em> change so much between the simple regression and multiple regression?</li>

 <li>Once you control for GDP, how much does each additional year of schooling contribute to average economic growth?</li>

 <li>How much of the variation in average economic growth is explained by the combination of average education and GDP per capita in 1960?</li>

</ul>

<ol start="7">

 <li>Add another variable, <em>testavg</em>, to the regression estimated in 6. This variable average standardized test scores in math and science. Hanushek and Woessmann believed that <u>quality</u> of education would matter more than <u>quantity</u> of education.</li>

</ol>

<ul>

 <li>Create a scatterplot with average years of education on the horizontal axis and average standardized test scores on the vertical axis. How, and how strongly, are these variables related?</li>

 <li>Explain how omitting average standardized test scores (<em>testavg</em>) could have created omitted variable bias. Identify which cell of Wooldridge’s Table 3.2 this example would be classified in, treating the <em>edavg</em> variable as <em>x</em><sub>1</sub> and the <em>testavg</em> variable as <em>x</em><sub>2</sub>?</li>

 <li>Examine the coefficients for <em>edavg</em> and <em>ypc60</em> and <em>testavg</em>; what effect does each variable have on average economic growth?</li>

 <li>How has the coefficient on <em>edavg</em> changed from the regression you ran in 6.? How has the coefficient on <em>ypc60</em> changed from the regression you ran in 6.?</li>

 <li>Examine the standard errors of the coefficients and <em>t</em> statistics for <em>edavg</em> and <em>ypc60</em> and <em>testavg</em>; which estimated coefficients are statistically significant (<em>p </em>&lt; .05)?</li>

 <li>Examine both the residual standard error (<em>sigma-hat</em>) and the standard errors of the regression coefficients for the <em>edavg</em> and <em>ypc60</em> variables; how did they change when you added <em>testavg</em> to the equation?</li>

 <li>Does adding the <em>testavg</em> variable introduce a problem of multicollinearity? Use two of the “casual” methods for detecting multicollinearity and calculate Variance Inflation Factors.</li>

</ul>

<ol>

 <li></li>

 <li></li>

 <li></li>

 <li></li>

 <li></li>

 <li></li>

 <li></li>

 <li>Drop the <em>edavg</em> variable, leaving only the <em>ypc60</em> and <em>testavg</em> variables in the regression.</li>

</ol>

<ul>

 <li>Have you created an omitted variable bias problem by dropping the <em>edavg</em> variable? Provide appropriate support for your conclusion (consult Lab 3 for ideas).</li>

 <li>What happens to the coefficient, standard error, and <em>t</em> statistic for <em>testavg</em> when the <em>edavg</em> variable is dropped?</li>

 <li>How much of the variation in average economic growth is explained by all three variables (<em>edavg</em> and <em>ypc60</em> and <em>testavg</em>), and how much of the variation is explained by just the last two variables (<em>ypc60</em> and <em>testavg</em>)?</li>

</ul>