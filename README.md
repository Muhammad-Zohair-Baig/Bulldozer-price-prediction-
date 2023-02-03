<html>
  <head>
 
  </head>
  <body>
    <h1>Bulldozer Price Prediction</h1>
    <p>In this project regression is used to predict price of bulldozer using different features. Following work flow was adopted during the project:</p>
    <ol>
      <li>The data is imported and analyzed</li>
      <li>In the analysis part first we fill in the missing values (in case of number we use median as it is more robust in case of categories we fill in the most repeated one).</li>
      <li>The next thing we do is to screen out layer by plotting scatter plots we can point out fields with out lyre and deal with them accordingly (like using median for such fields).</li>
      <li>Now we convert the string into categories and encode the fields.</li>
      <li>Train the model score it on validation and tune it.</li>
      <li>Use feature dependence graph to further screen out the fields not important.</li>
      <li>Custom evaluation matrix is used RMSE as required by client (take square root of mean square log error).</li>
    </ol>
    <p>Following technologies are used in this project:</p>
    <ul>
      <li>Pickle</li>
      <li>Pandas</li>
      <li>Numpy</li>
      <li>Datetime</li>
      <li>Matplotlib</li>
      <li>SK-Learn</li>
    </ul>
    <p>Model used is:</p>
    <ul>
      <li>Random Forest Regressor</li>
    </ul>
  </body>
</html>


