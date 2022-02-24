<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IV Sem Time Table</title>
    <style>
        h2{
            padding-left: 30%;
        }
        table{
            width: 70%;
            height: 300px;
            background-color: rgb(177, 231, 156);
            color: rgb(39, 41, 35);
            border-collapse: collapse;
            text-align: center;
        }
        table,th,td{
            border: 2px solid;
        }
        th{
            background-color: rgb(138, 236, 175);
            height: 40px;
        }
        #lab{
            border-bottom: 0px;
        }
        #lab1{
            border-top: 0px;
        }
    </style>
</head>
<body>
    <h2>Time Table</h2>
    <table>
        <thead>
            <tr>
                <th>Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
        </thead>
        <tbody>
           <tr>
               <td>10:00</td>
               <td>Cyber Sec.</td>
               <td>Cyber Sec.</td>
               <td>------</td>
               <td>------</td>
               <td>DMS</td>
               <td>OS</td>
           </tr>
           <tr>
               <td>10:50</td>
               <td id="lab">SE Lab</td>
               <td>DMS</td>
               <td>------</td>
               <td>OB</td>
               <td id="lab">SE RRS</td>
               <td>OS</td>
           </tr>
           <tr>
               <td>11:40</td>
               <td id="lab1">Lab-6</td>
               <td>WT.</td>
               <td>PPL</td>
               <td>WT</td>
               <td id="lab1">CS-Hall</td>
               <td>OB</td>
           </tr>
           <tr>
               <td>12:30</td>
               <td>DMS</td>
               <td>PPL</td>
               <td>DMS</td>
               <td>OS</td>
               <td>WT</td>
               <td>------</td>
           </tr>
           <tr>
               <td>13:20</td>
               <td>Lunch</td>
               <td>Lunch</td>
               <td>Lunch</td>
               <td>Lunch</td>
               <td>Lunch</td>
               <td>Lunch</td>
           </tr>
           <tr>
               <td>14:20</td>
               <td id="lab">WT Lab</td>
               <td id="lab">SE RRS</td>
               <td>OB</td>
               <td>PPL</td>
               <td>------</td>
               <td>------</td>
           </tr>
           <tr>
               <td>15:10</td>
               <td id="lab1">Lab-1</td>
               <td id="lab1">CS-Hall</td>
               <td>------</td>
               <td>------</td>
               <td>------</td>
               <td>------</td>
           </tr>
        </tbody>
    </table>
</body>
</html>
