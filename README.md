-to run plotGraph.py
in cmd,
python plotGraph.py <csv_file> <name_of_graph_to_be_generated>

format of csv file:
x,y,c,inequalities

x - coefficient of x variable 
y - coefficient of y variable
c - constant
inequalities - -1,0,1 depending on <,> or = [signs : 0 => greater than ; 1 => less than, -1 => equal to]

e.g

if the equations of the lines to be plotted are
2x + y <= 3 and
x + 3y >= 7

then csv file will be

x,y,c,inequalities
2,1,3,1
1,3,7,0