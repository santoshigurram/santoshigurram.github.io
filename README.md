<!DOCTYPE html>
<html>
    <head>
        <title>areaOfCube</title>
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css">
        <script>
            function area(){
                var n = document.getElementById("num").value;
                console.log(n);
                document.getElementById("resv").innerHTML= n*n*n;
                document.getElementById("resd").innerHTML= 1.732*n;
                document.getElementById("resa").innerHTML = 6*n*n;
            }
        </script>
        <style>
            table td{
                padding: 20px,90px;
                font-size: 15px;
                padding-bottom:30px;
                padding-right:20px;
                padding-left:10px;
            }
            .container{
                border: 3px solid black;
                align-content:centre;
                padding-bottom:20px;
                padding-top:15px;
                padding-right:30px;
                width:500px;
            }
            body{
              font-family: Arial, Helvetica, sans-serif;
            }
        </style>
    </head>
    <body>
        <div class="container">
            <h4 style="text-align:center;">CUBE </h4>
            <center><table border="1" width="200px" >
                <tr>
                    <td>volume&nbsp;</td>
                    <td id="resv">x</td>
                </tr>
                <tr>
                    <td>Space diagonal&nbsp;</td>
                    <td id="resd">x</td>
                </tr>
                <tr>
                    <td>Area&nbsp;</td>
                    <td id="resa">x</td>
                </tr>
            </table>
            </center>
            <br>
            <table>
            <tr>
                <td>Edge length :</td>
                <td ><input type ='number' id="num" size="10"></td>
                <td><select>
                    <option>ft</option>
                    <option>cm</option>
                    <option>km</option>
                    <option>yd</option>
                    <option>mile</option>
                    <option>meter</option>
                    <option>in</option>
                    <option>ft</option>
                </select> </td>
            </tr>
            </table>
            <button class="btn btn-primary" onclick ="area()" style="margin-left:170px">calculate</button>
            <button class="btn btn-danger" >clear</button>
            <br>
            <center><img src="https://d39460vivz6red.cloudfront.net/questions/M-BB-NCERT6-CH11-EX11P2-Q3/images/1_1592316795443.jpeg" width="50px" height="50px"></center>
        </div>
    </body>
</html>
