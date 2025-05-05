# gr5206-homework-1-solved
**TO GET THIS SOLUTION VISIT:** [GR5206 Homework 1 Solved](https://www.ankitcodinghub.com/product/gr5206-homework-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94733&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;GR5206 Homework 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Problem 1

In this assignment we’ll be studying a data set which provides information on the survival rates of passengers on the fatal voyage of the ocean liner Titanic. The dataset provides information on each passenger including, for example, economic status, sex, age, cabin, name, and survival status. This is a training dataset taken from the Kaggle competition website; for more information on Kaggle competitions, please refer to https://www.kaggle. com. Students should download the data set on Canvas. Below is a more detailed description of the variables.

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>PassengerId
Survived
Pclass
Name
</pre>
<pre>Sex
Age
SibSp
Parch
Ticket
Fare
Cabin
Embarked
</pre>
</div>
<div class="column">
Table 1: VARIABLE DESCRIPTIONS

Identification Number

Survival (0 = No; 1 = Yes)

Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)

Name

Sex

Age

Number of Siblings/Spouses Aboard

Number of Parents/Children Aboard

Ticket Number

Passenger Fare

Cabin

Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

</div>
</div>
<div class="layoutArea">
<div class="column">
Perform the following tasks:

Part 1: Importing Data into R

i. Import the titanic dataset into RStudio using read.table(). Use the argument as.is

= TRUE. The dataset should be stored in a data frame called titanic.

1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ol start="2">
<li>How many rows and columns does titanic have? (If there are not 891 rows and 12 columns something is wrong. Check part (i) to see what could have gone wrong.)</li>
<li>Create a new variable in the data frame called Survived.Word. It should read either “survived” or “died” indicating whether the passenger survived or died. This variable should be of type ‘character’.</li>
</ol>
Part 2: Exploring the Data in R

<ol>
<li>Use the apply() function to calculate the mean of the variables Survived, Age, and Fare. This will require using the apply() function on a sub-matrix of dimension 891×3. Explain what the mean of Survived tells us. One of the mean values is NA. Which variable has a mean value of NA and why is this the case?</li>
<li>Compute the proportion of female passengers who survived the titanic disaster. Round your answer to 2 decimals using the round() function. Hint ?round. Note: This is not a conditional probability.</li>
<li>Of the survivors, compute the proportion of female passengers. Round your answer to 2 decimals. This answer may take a few lines of code. One strategy would be to create a survivors matrix that only includes individuals who survived the disaster. Then using the survived matrix, calculate the proportion of females. Note: This is a conditional probability.</li>
<li>UsethefollowingcodetocreateanemptynumericvectoroflengththreecalledPclass.Survival. We will fill in the elements of Pclass.Survival with the survival rates of the three

classes.

<pre>    classes &lt;- sort(unique(titanic$Pclass))
    Pclass.Survival &lt;- vector("numeric", length = 3)
    names(Pclass.Survival) &lt;- classes
</pre>
Next use a for loop to fill in the Pclass.Survival vector with the survival rates for each class. The statements inside the loop should update the vector Pclass.Survival with the survival rate (the proportion of people who survived) for each class. Your loop should look like the following, with of course, your own code added inside the loop.

<pre>    for (i in 1:3) {
      code that fills in the Pclass.Survival vector
</pre>
}

The elements in the Pclass.Survival vector should be rounded to two decimal places.

2
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
v. Now create a Pclass.Survival2 vector that should equal the Pclass.Survival vector from the previous question, but use the tapply() function. Again, round the values to 2 decimals.

vi. Does there appear to be a relationship between survival rate and class?

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
