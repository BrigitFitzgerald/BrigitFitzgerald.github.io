<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Create two equal columns that floats next to each other */
.column {
  float: left;
  width: 50%;
  padding: 10px;
  height: 300px; /* Should be removed. Only for demonstration */
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>


<body>
  
  <div class="row">
  <div class="column" style="background-color:#ffffff00;">
    <img src="https://i.postimg.cc/wBrSkcrx/40212635-710494179302774-6326379903797166080-o.jpg" 
      width="275" height="275" alt="Headshot" style="border:5px solid black">
  </div>
  <div class="column" style="background-color:#ffffff00;">
    <h1>Introduction</h1>
    <p>Hello! This website is under construction. Please contact me at brigitfitzgerald@gmail.com if you would like to be in touch.</p>
  </div>
</div>
 

<body>
<html>
