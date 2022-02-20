# AngularCalculation

# Web Page for Mathematical Calculations using Angular

## AIM:
To design a dynamic website to perform mathematical calculations using Angular Framwork

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS in component.html file.

### Step 3:

Write typescript to perform the calculations.

### Step 4:

Validate the layout in various browsers.

### Step 5:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
### app.component.html
~~~
<body>
<div class="container">
<div class="content">
<Rectanglr-Area></Rectanglr-Area>
<br>
</div>
<div class="content">
<Cone-Volume></Cone-Volume>
<br>
</div>
</div>
</body>
~~~

### app.component.css
~~~
* {
    box-sizing:border-box;
    font-family: Arial, Helvetica, sans-serif;
  }
 
  .container {
    width:1080px;
    margin-left: auto;
    margin-right: auto;
    padding-top: 20px ;
    padding-left: 300px;
    max-height:max-content;
    background-color:black;
    padding-bottom: 45px; ;
  }
  .content {
    display:block;
    width: 500px;
    background-color:whitesmoke;
    min-height: 150px;
    font-size: 20px;
    position:relative;
    
  }
  h1{
    text-align: center;
    color:black;
  }

~~~

### cone.component.html
~~~
<h2>Volume of a Cone</h2>
<div class="formelement">
Radius=<input type="text" [(ngModel)]="radius"> Meters <br/>
</div>
<div class="formelement">
Height=<input type="text" [(ngModel)]="height"> Meters <br/>
</div>
<div class="formelement">
    <input type="button" (click)="onCalculate()" value="Calculate Volume"> <br/>
</div>
<div class="formelement">
Volume=<input type="text" [value]="volume"> Meters<sup>3</sup>
</div>
~~~

### cone.component.css
~~~
* {
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
  }
  h2{
      text-align: center;
      padding-top: 25px;
  }
  .formelement{
      text-align: center;
      margin-top: 5px;
      margin-bottom: 5px;
  }
~~~

### rectangle.component.html
~~~
<h2>Area of a Rectangle</h2>
    <div class="formelement">
    Length=<input type="text" [(ngModel)]="length"> Meters <br/>
    </div>
    <div class="formelement">
    Breadth=<input type="text" [(ngModel)]="breadth"> Meters <br/>
    </div>
    <div class="formelement">
        <input type="button" (click)="onCalculate()" value="Calculate Area"> <br/>
    </div>
    <div class="formelement">
    Area=<input type="text" [value]="area"> Meters<sup>2</sup>
    </div>
~~~

### rectangle.component.css
~~~
* {
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
  }
  .container {
    width: 1080px;
    margin-left: auto;
    margin-right: auto;
    padding-top: 30px;
    padding-left: 300px;
    padding-bottom: 500px;
  }
  .content {
    display:block;
    width: 500px;
    background-color:white;
    min-height: 150px;
    font-size: 20px;
  }
  h2{
      text-align: center;
      padding-top: 25px;
  }
  .formelement{
      text-align: center;
      margin-top: 5px;
      margin-bottom: 5px;
  }
~~~

## OUTPUT:

![git](angular_calculation(1).png)


## Result:
A math calculations website has been designed using angular framework.
