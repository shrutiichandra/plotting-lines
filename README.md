-to run plotGraph.py
in cmd, <br/>
python plotGraph.py <csv_file> <name_of_graph_to_be_generated> <br/>
<br/>

format of csv file: <br/>
x,y,c,inequalities <br/>
<br/>

x - coefficient of x variable  <br/>
y - coefficient of y variable <br/>
c - constant <br/>
inequalities - -1,0,1 depending on <,> or = [signs : 1 => greater than ; -1 = > less than, 0 => equal to] <br/>
<br/>
e.g <br/>
<br/>
if the equations of the lines to be plotted are <br/>
2x + y <= 3 and <br/>
x + 3y >= 7 <br/>
<br/>
then csv file will be <br/>

<br/>

x,y,c,inequalities <br/>
2,1,3,1 <br/>
1,3,7,0
