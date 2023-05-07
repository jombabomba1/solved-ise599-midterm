Download Link: https://assignmentchef.com/product/solved-ise599-midterm
<br>



<ol>

 <li>The OJ data set from the ISLR library contains 1070 purchases where the customer either purchased Citrus Hill or Minute Maid Orange Juice (Use ?OJ for more details). It is of interest to predict Purchase using all other variables. Use seed(1,sample.kind=”Rounding”) to create a training set containing a random sample of 800 observations, and a test set containing the remaining observations.</li>

</ol>

Fit a classification tree to the training data to answer questions (a) to (c).

<ol>

 <li>Plot the tree. What is the training error rate? What is the test error rate?</li>

 <li>Use seed(2) and cross-validation to find the best number of terminal nodes. Which tree size corresponds to the lowest cross-validated classification error rate?</li>

 <li>Plot a pruned tree with five terminal nodes. What is the test error rate?</li>

</ol>

For the following question, fit a RF to the training set using all predictors.

<ol>

 <li> Which predictors are the most important? What is the test error rate?</li>

</ol>

When fitting a boosted tree the number of trees, depth of trees, shrinkage, should be carefully selected. If a tuning grid is defined, the train function can be used to tune these parameters (see p217, handout).

<ol>

 <li> Fit a boosted tree selecting the best parameter values. What is the test error rate?</li>

</ol>

<ol start="2">

 <li>In segmenting the market, a breakfast cereal manufacturer uses health and diet consciousness as thesegmentation variable. Four segments are developed:

  <ul>

   <li>= Concerned about eating healthy foods</li>

   <li>= Concerned primarily about weight</li>

   <li>= Concerned about health because of illness</li>

   <li>= Unconcerned</li>

  </ul></li>

</ol>

To distinguish between groups, a survey is conducted (see cereal.csv). In the survey, people are categorized as belonging to one of these groups. The most recent census reveals that 234,564,000 Americans are 18 and older.

<ol>

 <li> Use the test function to find a 95% Confidence interval for the true proportion of American adults who are concerned about eating healthy foods. Then use it to estimate how many American adults belong to group 1.</li>

 <li>Each respondent was also asked the amount spent on breakfast cereal in an averagemonth. The company would like to know whether on average the market segment <em>concerned about eating healthy foods </em>outspends the other market segments.</li>

 <li> The following table is a sample of the dataframe Hitters from library ISLR. It shows the data of nine baseball players chosen at random. Select the rownumber equal to the first digit of your USC ID. Then use the data in that row and the regression tree shown below to predict the salary (in 000s of dollars) of the selected player.</li>

</ol>

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/456.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/456.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>




<ol>

 <li><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/305.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/305.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript></li>

</ol>





