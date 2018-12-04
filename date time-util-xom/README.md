# date-time-util-xom

This is just a quick example of how to add some unique logic using Java to an ODM BOM. Th datetime-util-xom.zip above here is a Java project exported from Rule Designer (eclipse) that you can import into Rule Designer and make use of using the steps below. This is just a raw example of how to add some custom Java logic to the rules. Changing the return type of the timeDifference method used would allow you to use the logic in the IF part of a rule. 

1. In the Decision Service Map, click on import XOM

<img width="250" alt="image" src="https://user-images.githubusercontent.com/18425410/49475367-e2c84e80-f7cb-11e8-95cd-af10908a0085.png">

2. Choose Java execution object model and click OK

<img width="283" alt="image" src="https://user-images.githubusercontent.com/18425410/49475471-333fac00-f7cc-11e8-9249-a989bf2b22a9.png">

3. Check date-time-util-xom and click OK

<img width="712" alt="image" src="https://user-images.githubusercontent.com/18425410/49475552-64b87780-f7cc-11e8-9eb2-d2cf835af927.png">

4. In the Decision Service Map, click on create BOM

<img width="238" alt="image" src="https://user-images.githubusercontent.com/18425410/49475621-8dd90800-f7cc-11e8-93b5-8257e130b0b5.png">

5. Pick a creative name better than model1, make sure that Create a BOM entry from a XOM is selected, and click Next

<img width="575" alt="image" src="https://user-images.githubusercontent.com/18425410/49475698-bfea6a00-f7cc-11e8-85e3-be67ea3a7993.png">

6. On the New BOM Entry dialog page, click Browse XOM, select platform:/datetime-util-xom, and click OK

<img width="880" alt="image" src="https://user-images.githubusercontent.com/18425410/49475855-35563a80-f7cd-11e8-907e-150e8350a22c.png">

7. Check the xom.demo checkbox and click Finish

<img width="273" alt="image" src="https://user-images.githubusercontent.com/18425410/49475958-7fd7b700-f7cd-11e8-8ee6-c842c84f7c63.png">

8. Open the project that contains your BOM and double click on the timeDifference(date,date)

<img width="338" alt="image" src="https://user-images.githubusercontent.com/18425410/49476076-c62d1600-f7cd-11e8-86f0-1f69f5d6968a.png">


9. Change the verbalization as seen below
<img width="802" alt="image" src="https://user-images.githubusercontent.com/18425410/49476111-ee1c7980-f7cd-11e8-9e48-04759ac67471.png">

10. Add the phrase to the action of a rule

Enj0y!
