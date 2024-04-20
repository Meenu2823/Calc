# Ex.08 Design of a Standard Calculator
## Date:20.04.24

## AIM:
To design a web application for a standard calculator with minimum five operations.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for creating attractive colors.

### Step 4:
Write JavaScript program for implementing five different operations.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>General Calculator</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" 
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
</head>
<body style="background-color: palevioletred;">
    <h1 style="text-align: center;padding-bottom: 3%;color: darkred;"><b> General Calculator </b></h1>
    <script>
        function fn(e){
            if (e.innerHTML == '='){
                output.value = eval(output.value);
            }
            else if (e.id == 'back'){
                v = output.value;
                output.value = v.substring(0,v.length-1);
            }
            else if (e.innerHTML == 'C'){
                output.value = '';
            }
            else {
                output.value += e.innerHTML;
            }
        }
    </script>
    <div class="bg-dark mx-auto text-center text-white" style="width: 24rem;border-top-left-radius: 25px;border-top-right-radius: 25px;"><b>MEENU.S(212223230124)</b></div>
    <div class="bg-dark row mx-auto text-center" style="width: 24rem;border-bottom-left-radius: 25px;border-bottom-right-radius: 25px " >
        <div class="col-12 my-4"><input type="text" name="" id="output" style="width: 100%;height: 50px;border-radius: 25px;"></div>
        <div class="m-3 col-2 btn rounded-4" style="background-color: lightskyblue;" onclick="fn(this)">(</div>
        <div class="m-3 col-2 btn rounded-4" style="background-color: lightskyblue;" onclick="fn(this)">)</div>
        <div class="m-3 col-2 btn btn-danger rounded-4"  onclick="fn(this)">C</div>
        <div class="m-3 col-2 btn btn-danger rounded-4" onclick="fn(this)" id="back"><i class="bi bi-backspace"></i></div>
        <div class="m-3 col-2 btn rounded-4" style="background-color: lightgreen;" onclick="fn(this)">7</div>
        <div class="m-3 col-2 btn rounded-4" style="background-color: lightgreen;" onclick="fn(this)">8</div>
        <div class="m-3 col-2 btn rounded-4" style="background-color: lightgreen;" onclick="fn(this)">9</div>
        <div class="m-3 col-2 btn rounded-4" style="background-color: lightskyblue;"  onclick="fn(this)">*</div>
        <div class="m-3 col-2 btn rounded-4" style="background-color: lightgreen;" onclick="fn(this)">4</div>
        <div class="m-3 col-2 btn rounded-4" style="background-color: lightgreen;" onclick="fn(this)">5</div>
        <div class="m-3 col-2 btn rounded-4" style="background-color: lightgreen;" onclick="fn(this)">6</div>
        <div class="m-3 col-2 btn rounded-4" style="background-color: lightskyblue;" onclick="fn(this)">-</div>
        <div class="m-3 col-2 btn rounded-4" style="background-color: lightgreen;" onclick="fn(this)">1</div>
        <div class="m-3 col-2 btn rounded-4" style="background-color: lightgreen;" onclick="fn(this)">2</div>
        <div class="m-3 col-2 btn rounded-4" style="background-color: lightgreen;" onclick="fn(this)">3</div>
        <div class="m-3 col-2 btn rounded-4" style="background-color: lightskyblue;" onclick="fn(this)">+</div>
        <div class="m-3 col-2 btn rounded-4" style="background-color: lightgreen;" onclick="fn(this)">0</div>
        <div class="m-3 col-2 btn rounded-4" style="background-color: lightskyblue;" onclick="fn(this)">.</div>
        <div class="m-3 col-2 btn rounded-4" style="background-color: lightskyblue;" onclick="fn(this)">%</div>
        <div class="m-3 col-2 btn rounded-4" style="background-color: lightskyblue;" onclick="fn(this)">/</div>
        <div class="m-3 col-11 btn rounded-4" style="background-color: yellowgreen;" onclick="fn(this)">=</div>
    </div>
</body>
</html>
~~~
## OUTPUT:

![image](https://github.com/Meenu2823/Calc/assets/139416219/1e76411b-112c-4110-adf1-2f836e42b943)
![image](https://github.com/Meenu2823/Calc/assets/139416219/acbf4ccf-04f8-4e05-8c91-674110d7a9b1)

## RESULT:
The program for designing a standard calculator using HTML and CSS is executed successfully.
