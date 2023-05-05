Download Link: https://assignmentchef.com/product/solved-cse1321-lab10-classes
<br>
<strong><u>Exercise #1:</u> </strong>Design and implement class Rectangle to represent a rectangle object. The class defines the following attributes (variables) and methods:

<ol>

 <li>Two <strong>class </strong>(changed from private) variables of type double named height and width to represent the height and width of the rectangle. Set their default values to 1 <strong>in the default constructor.</strong> (Added clarification)</li>

 <li>A non-argument constructor method to create a <strong>default </strong>(Added clarification)</li>

 <li>Another constructor method<strong> (<em>Python only</em>: using classmethod decorator) </strong>(Changed since Python does not support method overloading) to create a rectangle with user-specified height and</li>

 <li>Method getArea() that returns the area.</li>

 <li>Method getPerimeter() that returns the perimeter.</li>

 <li>Method getHeight() that returns the height.</li>

 <li>Method getWidth() that returns the width.</li>

</ol>

Now design and implement a test program to create two rectangle objects: one with default height and width, and the second is 5 units high and 6 units wide. Next, test the class methods on each object to print the information as shown below.

<u>Sample run:</u>

First object:

Height:     1 unit

Width:      1 unit

Area:       1 unit

Perimeter:  4 units




Second object:

Height:     5 unit

Width:      6 unit

Area:       30 units

Perimeter:  22 units







<strong><u>Exercise #2:</u> </strong>Design and implement class Stock to represent a company’s stock. The class defines the following attributes (variables) and methods:




<ol>

 <li>A <strong>class </strong>(Changed from private) variable of type String named Symbol for the stock’s</li>

 <li>A <strong>class (</strong>Changed from private) variable of type String named Name for the stock’s</li>

 <li>A <strong>class (</strong>Changed from private) variable of type double named previousClosingPrice to store the last closing price.</li>

 <li>A <strong>class </strong>(Changed from private) variable of type double named currentPrice to store the current</li>

 <li>A constructor method to create a stock with user-specified name and</li>

 <li>Method getName() that returns the stock’s name.</li>

 <li>Method getSymbol() that returns the stock’s symbol.</li>

 <li>Method setClosingPrice() that sets the previous closing price.</li>

 <li>Method setCurrentPrice() that sets the current price.</li>

 <li>Method getChangePercent() that returns the <u>percentage changed</u> from</li>

</ol>

previousClosingPrice to currentPrice. <strong>Using the formula: </strong>

<strong>-(previousClosingPrice – currentPrice) / previousClosingPrice * 100 </strong>(Added a formula here)




<ol start="11">

 <li>Method <strong>either named </strong><strong>toString(), in Java and C#, or</strong><strong> __str__() in Python </strong>(Changed since Python calls this method a different name) to printout a <u>meaningful description</u> of a stock object when passing the object name to the print</li>

</ol>




<strong>The statement </strong><strong>PRINT yahooStock would print the string:</strong>

<strong> </strong>

<strong>Yahoo stock’s closing price is $234.54 </strong>(Changed to be grammatically correct and to use pseudo code instead of Java for no reason, also removed the Java code after this)




Now design and implement a test program to create two stock objects: one for Google with symbol GOG and the second is for Microsoft with symbol MSF. Set their closing and current prices<strong> according to the information below. Next, test the class methods on each object to print the information in a similar manner to the one shown below.</strong> (Added clarification)




<u>Sample run:</u>




Google stock:

Symbol: GOG

Closing price:   134.67

Current price:   131.98

Change percent: – 2%

Google stock closing price is $131.98




Microsoft stock:

Symbol: MSF

Closing price:   156.52

Current price:   161.22

Change percent: 3%

Microsoft stock closing price is $161.22


