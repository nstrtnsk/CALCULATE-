<!DOCTYPE html>
<html>
<head>
   <title>Калькулятор</title>
   <style>
     .as{
 
 border-style: solid;
 border-color: black;
 border-width: 1px;

 }
</style>
</head>
<body>
    <H1 ALIGN=CENTER><I><big>Калькулятор</H1></I>
    <H4 ALIGN=LEFT>Струтинська Анастасія</H4>  
  <table class="as" >
    <div>
   <tr>
   
        <ol>
            <form name="formcalc1">
       <td><input type ="text" name ="txtnum1"> +
       <td><input type ="text" name ="txtnum2"> =
       <td><input type ="text" name ="txtres"> 
   
      <td><input type ="button" value ="Розрахувати" onClick="sumValues()"> </tr></td>
  </form>

  <script type="text/javascript">


    function sumValues()
    {
      var num1,num1,res;
      num1=Number(document.formcalc1.txtnum1.value);
      num2=Number(document.formcalc1.txtnum2.value);
      res=num1+num2;
      document.formcalc1.txtres.value=res;
    }
  </script>

      <tr>
  <form name="formcalc2">
     <td>  <input type ="text" name ="txtnum1"> -
     <td>  <input type ="text" name ="txtnum2"> =
     <td>  <input type ="text" name ="txtres"> 
      <td>  <input type ="button" value ="Розрахувати" onClick="minValues()"> </tr></td>
  </form>
  <script type="text/javascript">

    function minValues()
    {
      var num1,num1,res;
      num1=Number(document.formcalc2.txtnum1.value);
      num2=Number(document.formcalc2.txtnum2.value);
      res=num1-num2;
      document.formcalc2.txtres.value=res;
    }
  </script>

    <tr>
      <form name="formcalc3">
     <td>  <input type ="text" name ="txtnum1"> *
     <td>  <input type ="text" name ="txtnum2"> =
     <td>  <input type ="text" name ="txtres"> 
     <td>   <input type ="button" value ="Розрахувати" onClick="multiplicationValues()"></tr></td> 
  </form>
  <script type="text/javascript">

    function multiplicationValues()
    {
      var num1,num1,res;
      num1=Number(document.formcalc3.txtnum1.value);
      num2=Number(document.formcalc3.txtnum2.value);
      res=num1*num2;
      document.formcalc3.txtres.value=res;
    }
  </script>

<tr>
  <form name="formcalc4">
     <td>  <input type ="text" name ="txtnum1"> /
     <td>  <input type ="text" name ="txtnum2"> =
     <td>  <input type ="text" name ="txtres"> 
     <td>   <input type ="button" value ="Розрахувати" onClick="divisionValues()"> </td></tr>
  </form>
  <script type="text/javascript">

    function divisionValues()
    {
      var num1,num1,res;
      num1=Number(document.formcalc4.txtnum1.value);
      num2=Number(document.formcalc4.txtnum2.value);
      res=num1/num2;
      document.formcalc4.txtres.value=res;
    }
  </script>

<tr>
  <form name="formcalc5">
       <td><input type ="text" name ="txtnum1"> ^
       <td><input type ="text" name ="txtnum2"> =
       <td><input type ="text" name ="txtres"> 
        <td><input type ="button" value ="Розрахувати" onClick="degreeValues()"> </tr></td>
  </form>
  <script type="text/javascript">

    function degreeValues()
    {
      var num1,num1,res;
      num1=Number(document.formcalc5.txtnum1.value);
      num2=Number(document.formcalc5.txtnum2.value);
      res=Math.pow(num1,num2);
      document.formcalc5.txtres.value=res;
    }
  </script>
</ol>
    </td>
 

</body>
</html>
