project wedgiewuzzle 
started: 18.09.2012
objective: 
To create a boilerplate for website design using SASS responsive grid
Compatibility targets: EI7+ Moz, Chrome, Safari (to degrade nicely for IE6)
To provide modular bolt-ons for common website widgets etc

19.09.12 - current issues:
PIE.htc - no rounded corners in ie?
tried to use var on scss compile for gradient ie filter but compile wont recognise variable so have to hard code colours at CSS level
for ie7 last column needs class 'last' with margin 0 to avoid ie rounding issue - can this be written into the scss grid function? 