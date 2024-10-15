                                                          FITNESS CAMP 
THIS IS A C PROGRAM FOR A FITNESS CAMP ORGANIZED FOR DIFFERENT AGE GROUP PEOPLES AND TO ENCOURAGE YOUTH TOWARDS LEADING A HEALTHY LIFESTYLE

PROBLEM STATEMENT:
To develop a c-program to calculate the average marks and grade of each student in the first year
BTech.
Program based on the marks obtained in the 1 st semester.
The program should prompt the user to input the marks of each student for subjects such as
Mathematics, Chemistry, Physics, English and Computer Science using control structure such as
loops and conditional statement, the program should calculate the average marks and assign grades
to each student according to pre-defined criteria.
Finally, the program should display the average marks and grade of each student.

IDEATE / INNOVATION BY THE GROUP:
We can use this concept in real-life based application.
The topic selected by our group is ‘FITNESS CAMP’.
REFERNCES:
https://www.who.int/news-room/fact-sheets/detail/physical-activity
https://www.lenovo.com/in/en/glossary/fiteness-
tracker/?orgRef=https%253A%252F%252Fwww.google.com%252F&amp;srsltid=AfmBOortue8MwQEu0Fg
T9qqXY90LFki9FXm0mDBPp9NQgy112o_AUQju
https://www.moontechnolabs.com/blog/features-for-fitness-app/
https://canyon.eu/blog/what-is-a-fitness-tracker-and-how-does-it-work/
https://www.physio-pedia.com/Harvard_Step_Test

CODE DEVELOPMENT:

The code is developed by our group using Microsoft’s-VSCode for coding. The programming
language chosen is C Language.
The elements of control structure used are majorly Conditional statements like if and else statement
The code is written below
#include &lt;stdio.h&gt;
int main () {
int price , i , a , b ;
float w;
printf(&quot;\nTHE ACTIVITIES YOU CAN PERFORM ARE \n&quot;);
printf(&quot;\n1 - RUNNING ~~&gt; 100Rs/Hr\n &quot;);
printf(&quot;\n2 - OUTDOOR GAMES ~~&gt; 200Rs/Hr\n&quot;);
printf(&quot;\n3 - SWIMMING ~~&gt; 400Rs/Hr\n&quot;);
printf(&quot;\n4 - YOGA ~~&gt; 150Rs/Hr\n &quot;);
printf(&quot;\n5 - MEDITATION ~~&gt; 200Rs/Hr\n &quot;);
printf(&quot; \nENTER YOUR AGE :  &quot;);
scanf(&quot;%d&quot;,&amp;i );
printf(&quot; \nENTER YOUR WEIGHT :  &quot;);
scanf(&quot;%f&quot;,&amp;w);
 if (i&gt;70 ){
    printf(&quot; \nSORRY YOU CANNOT PERFORM ANY ACTIVITY &quot;);
}else if (i&gt;10 &amp;&amp; w &lt;= 40 ){
    printf(&quot; \nYOU CAN PERFORM ALL THE ACTIVITIES &quot;);
}else if (i&gt;10 &amp;&amp; w &lt;= 70){
        printf(&quot; \nYOU CAN PERFORM ACTIVITY 3,4,5&quot;);
}else if (i&gt;10 &amp;&amp; w &gt; 70){
        printf(&quot; \nSORRY YOU CANNOT PERFORM ANY ACTIVITY &quot;);
}else if (i&gt;20 &amp;&amp; w &lt;= 60 ){
    printf(&quot; \nYOU CAN PERFORM ALL THE ACTIVITIES &quot;);
}else if (i&gt;20 &amp;&amp;  w &lt;= 80){
        printf(&quot; \nYOU CAN PERFORM ACTIVITY 3,4,5&quot;);
}else if ( i&gt;20 &amp;&amp; w &gt; 90){
        printf(&quot; \nSORRY YOU CANNOT PERFORM ANY ACTIVITY&quot;);
}else if (i&gt;30 &amp;&amp; w &lt;= 70 ){
    printf(&quot; \nYOU CAN PERFORM ACTIVITY 3,4,5 &quot;);
}else if (i&gt;30 &amp;&amp; w &lt;= 90){
        printf(&quot; \nYOU CAN PERFORM ACTIVITY 4,5&quot;);
}else if (i&gt;30 &amp;&amp; w &gt; 90){
        printf(&quot; \nSORRY YOU CANNOT PERFORM ANY ACTIVITY &quot;);

}else if (i&gt;40 &amp;&amp; w &lt;= 80 ){
    printf(&quot; \nYOU CAN PERFORM ACTIVITY 3,4,5 &quot;);
}else if (i&gt;40 &amp;&amp; w &lt;= 90){
        printf(&quot; \nYOU CAN PERFORM ACTIVITY 4,5&quot;);
}else if (i&gt;40 &amp;&amp; w &gt; 90){
        printf(&quot; \nSORRY YOU CANNOT PERFORM ANY ACTIVITYY &quot;);
}else if (i&gt;70 ){
    printf(&quot; \nSORRY YOU CANNOT PERFORM ANY ACTIVITY &quot;);
}
printf(&quot; \nENTER THE ACTIVITY YOU WANT TO PERFORM : \n &quot;);
scanf(&quot;%d&quot; ,&amp;a);
printf(&quot; \nENTER THE NO OF HOURS YOU WANT TO PERFORM THE ACTIVITY :  \n&quot;);
scanf(&quot;%d&quot; , &amp;b);
if(a == 1){
    price = b * 100;
    printf(&quot;\nTHE COST OF PERFORMING ACTIVITY 1 IS %d&quot;, price);
} else if(a == 2){
    price = b * 200;
    printf(&quot;\nTHE COST OF PERFORMING ACTIVITY 2 IS %d&quot;, price);
} else if(a == 3){
    price = b * 400;
    printf(&quot;\nTHE COST OF PERFORMING ACTIVITY 3 IS %d&quot;, price);
} else if(a == 4){
    price = b * 150;
    printf(&quot;\nTHE COST OF PERFORMING ACTIVITY 4 IS %d&quot;, price);
} else if(a == 5){
    price = b * 200;
    printf(&quot;\nTHE COST OF PERFORMING ACTIVITY 5 IS %d&quot;, price);
}
return 0;
}

MOTIVE:
To encourage the youth towards leading a healthy lifestyle, where most of the youth is busy in their
schedules and routine of sitting at one place for hours and hours can deteriorate their health in the
long run.
The main objective of our project is to promote exercise and initiate a sense of awareness about
moving our body and taking out some time from work and work for ourselves as well.
The target community is majorly students and office goers.
While we also would like to promote it for the homemakers and senior citizens as maintaining health
is also Important.

Features:
a. Training: Fitness camps typically include a combination of strength training,
bodyweight training, and functional training. Exercises are designed to burn calories
quickly and improve strength and fitness
b. Location: Fitness camps can take place in a gym, outdoors, or both. Some
camps are held off-site and include extracurricular activities. 
c. Group dynamic: Fitness camps are often group-based, which can help
motivate participants. 
d. Mental health: Regular aerobic exercise can help reduce stress and high blood
pressure, and release endorphins to improve mood. Some camps offer mental
coaching to help participants stay motivated.
e. Intensity: Fitness camps are intense and efficient, with the goal of pushing
participants&#39; limits. 
f. Flexibility: Fitness camps can be flexible for beginners and advanced
participants. 
g. Fun: Fitness camp workouts can be fun and motivating


TESTING AND RESULTS:
SYSTEM TESTING-
Evaluated the complete system’s compliance with the code.
The code was run without any errors and debugs were checked and rectified.

CONCLUSION:
The project successfully demonstrates the capabilities of the C programming language. The project
met its objectives, provided valuable insights and inculcates a health-conscious community.

DOCUMENTATION:
The code has been published on the GITHUB website.
Link for the same is given below:
https://github.com/computerojan/-fitness-camp

THANK YOU
