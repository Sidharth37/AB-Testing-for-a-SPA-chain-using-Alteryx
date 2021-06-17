# AB-Testing-for-a-Local-SPA-using-Alteryx
<br>
We are part of a team, looking to increase the gross margin for a chain of spas. We have decided to discount the price of facials, to see its effect on the gross margin. Currently the store offers facials at $98.99, and we decide to run 2 promotional campaigns, one of them would lead to a group of stores offering facials at $76.99 and another group offering facials at $87.99.<br><br>

<b>The project compromises of 3 parts</b><br>
1. Select treatment and control unit
2. Prepare & run the test
3. Analyze the result


<b>Selection of treatment and control units -</b><br>
For our experiment, our we have selected the treatment units, and all the other stores(control units) will continue to offer facials at the same old price of $98.99.
We will match these treatment units to control units based on both continuous variables and discreet variables, but the process of matching them will differ.
For the selection of variables to used for matching, we start by looking at the list of all the variables present. They are as follows - <br>
a. Invoice Number<br>
b. Invoice Date <br>
c. SKU<br>
d. SKU Category<br>
e. Gross margin<br>
f. Sales<br>
g. Store id<br>
h. Region<br>

We start by matching the discreet variables. You cannot match discreet variables directly like continuous variables. You need to match stores which have the same common value of the discreet variable. In our case, we can match stores which belong to the same region. This is backed up the assumption that customer behavior varies by region.<br
