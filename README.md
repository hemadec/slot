# Ex03 - Time Table

## Date:15.03.2024

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM

```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <html>
<title>Ragavn E time table</title>
<body>
<center>
  <img src="logo.png"height="100" width="800" >
      <table border="1" cellspacing=4" cellpadding="15" bgcolor="black">
<caption> <h2>Slot Jayasree time table(23013456)</h2></caption>
<tr>
<th bgcolor="deeppink">Days/Timings</th>
<th bgcolor="blue">8-10</th>
<th bgcolor="blue">10-12</th>
<th bgcolor="blue">12-1</th>
<th bgcolor="blue">1-3</th>
<th bgcolor="blue">3-5</th>     
</tr>
<tr>
<th bgcolor="pink">MONDAY</th>
<th bgcolor="cyan">19EE305</th>
<th bgcolor="cyan">    </th>
<th bgcolor="cyan">    </th>
<th bgcolor="cyan">    </th>
<th bgcolor="cyan">19AI305</th>
 </tr>
   <tr>
<th bgcolor="pink">TUESDAY</th>
<th bgcolor="cyan">    </th>
<th bgcolor="cyan">19AM508</th>
<th bgcolor="cyan">    </th>
<th bgcolor="cyan">19EE404</th>
<th bgcolor="cyan">19AI414</th>
</tr>
<tr>
<th bgcolor="pink">WEDNESDAY</th>
<th bgcolor="cyan">19AI301</th>
<th bgcolor="cyan">19CS406</th>
<th bgcolor="cyan">    </th>
<th bgcolor="cyan">19EY702</th>
<th bgcolor="cyan">19AI305</th>
</tr>
<tr>
<th bgcolor="pink">THURSDAY</th>
<th bgcolor="cyan">19AI414</th>
<th bgcolor="cyan">19MA222</th>
<th bgcolor="cyan">Mentor Meet</th>
<th bgcolor="cyan">19AM508</th>
<th bgcolor="cyan">    </th>
</tr>
<tr>
<th bgcolor="pink">FRIDAY</th>
<th bgcolor="cyan">19AI414</th>
<th bgcolor="cyan">19EE404</th>
<th bgcolor="cyan">    </th>
<th bgcolor="cyan">    </th>
<th bgcolor="cyan">    </th>
</tr>
<tr>
<th bgcolor="pink">SATURDAY</th>
<th bgcolor="cyan">19MA222</th>
<th bgcolor="cyan">19CS406</th>
<th bgcolor="cyan">    </th>
<th bgcolor="cyan">19EE305</th>
<th bgcolor="cyan">19AI301</th>
</tr>
<table border="1" cellspacing="4" cellpadding="10"  >
  <tr>
  <th>S.no</th>
  <h2><th>COURSE CODE</th></h2>
  <h2><th>COURSE TITTLE</th></h2>
  </tr>
  <tr>
  <th>1.</th>.
  <th>19AI305</th>
  <th>Advanced C Programming</th>
  </tr>
  <tr>
  <th>2.</th>
  <th>19AI414</th>
  <th>Fundamentals of Web Applications</th>
  </tr>
  <tr>
  <th>3.</th>
  <th>19AI301</th>
  <th>Python Programming</th>
  </tr>
  <tr>
  <th>4.</th>
  <th>19EE305</th>
  <th>Basic Electrical,Electrical and Measurement Engineering</th>
  </tr>
  <tr>
  <th>5.</th>
  <th>19EY702</th>
  <th>Creative Skills For Communication</th>
  </tr>
  <tr>
  <th>6.</th>
  <th>19MA222</th>
  <th>Probability And Queueing Models</th>
  </tr>
  <tr>
  <th>7.</th>
  <th>19EE404</th>
  <th>Digital Electronics</th>
  </tr>
  <tr>
  <th>8.</th>
  <th>19CS406</th>
  <th>Computer Networks</th>
  </tr>
    </center>
    </body>
    </html>  
</body>
</html>

```


## OUTPUT

![alt text](<Screenshot 2024-04-04 231741.png>)

![alt text](<Screenshot 2024-04-04 231748.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
