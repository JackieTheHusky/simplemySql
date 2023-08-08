# WHAT IS IN THIS?
The contenting code is very base level and not made with thoughts of it being used by anybody else. 

That being said, I will document my progress and bring up things that a beginner(like myself) may also find helpful.
(it can also be used to hopefully show my growth and cause amusement for later)

# WHAT DOES THIS HAVE?
<h3>MySql code</h3>
<ol> 
<li>How to make certain tables</li>

<li>Stored Procedures for the following ideas: 
<ul>
  <li>Calling data when given a first and last initial</li>
  <li>Calling data that uses multiple join statements</li>
</ul> </li>
<li>Funtion to call the difference of dates</li>
</ol>

# HOW TO USE?


# WHAT I'VE LEARNED
<ol>
  <li>'JOIN' need to be used carefully as they can have LEFT JOIN and RIGHT JOIN</li>
  <li>'IF' needs a condition to work, and that condition is most likely not going to work if you are trying to compare something within a column</li>
  <dd>-This was important when trying to compare a VARCHAR of a name to a column from a table</dd>
  <li>TEMP tables still exist even if it is not shown, thus it is always best to 'DROP TABLE [table name]' which is important especially when testing/troubleshooting</li>
  <li>Funtions are not like STORED PROCEDURE, the most important is that you will not be able to recall tables, and the "RETURN" is necessary for Funtions</li>
  <li>'IN' is something that the STORED PROCEDURE will call(ie 'IN first_name VARCHAR(smallint)' will make it so anytime 'first_name' is used it will use the string presented when starting the funtion</li>
  <li>'OUT' seems to what we get out from the STORED PROCEDURE and thus you will have to name it a @ or a variable which can be called if it needs to be viewed</li>
</ol>

# MORE THING I NEED TO LOOK MORE INTO
<ol>
  <li>In Stored Procedures, if you wish to get a table as an output the 'OUT' is not a viable strategy</li>
  <li>What 'IN', 'OUT', and 'INOUT' do exactly</li>
  </ol>
