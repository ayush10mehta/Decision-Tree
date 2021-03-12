# Decision-Tree

Prediction


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Iris Prediction</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/semantic-ui/2.4.1/semantic.min.css">

</head>
<body>
    <div class= "ui container">
        <br>
        <h1> IRIS SPECIES PREDICTION</h1>

<form class="ui form" method= "POST" action="/predict">
           
            <div class="field">
              <label> Sepal Length </label>
              <input name= 'sl' type="text">
            </div>
           

          
            <div class="field">
              <label> Sepal Width </label>
              <input name= 'sw' type="text">
            </div>
          

          
            <div class="field">
              <label>Petal Length</label>
              <input name= 'pl'type="text">
            </div>
          

          
            <div class="field">
              <label>Petal Width </label>
              <input name= 'pw' type="text">
            </div>
          

            <button class="ui button">
                Submit
               </button>
</form>
       


       
</body>
</html>
