# -fitness-camp
#include <stdio.h>
int main () {
int price , i , a , b ;
float w;

printf("\nTHE ACTIVITIES YOU CAN PERFORM ARE \n");
printf("\n1 - RUNNING ~~> 100Rs/Hr\n ");
printf("\n2 - OUTDOOR GAMES ~~> 200Rs/Hr\n");
printf("\n3 - SWIMMING ~~> 400Rs/Hr\n");
printf("\n4 - YOGA ~~> 150Rs/Hr\n ");
printf("\n5 - MEDITATION ~~> 200Rs/Hr\n ");
printf(" \nENTER YOUR AGE :  ");
scanf("%d",&i );
printf(" \nENTER YOUR WEIGHT :  ");
scanf("%f",&w);

 if (i>70 ){
    printf(" \nSORRY YOU CANNOT PERFORM ANY ACTIVITY ");
}else if (i>10 && w <= 40 ){
    printf(" \nYOU CAN PERFORM ALL THE ACTIVITIES ");
}else if (i>10 && w <= 70){
        printf(" \nYOU CAN PERFORM ACTIVITY 3,4,5");
}else if (i>10 && w > 70){
        printf(" \nSORRY YOU CANNOT PERFORM ANY ACTIVITY ");
}else if (i>20 && w <= 60 ){
    printf(" \nYOU CAN PERFORM ALL THE ACTIVITIES ");
}else if (i>20 &&  w <= 80){
        printf(" \nYOU CAN PERFORM ACTIVITY 3,4,5");
}else if ( i>20 && w > 90){
        printf(" \nSORRY YOU CANNOT PERFORM ANY ACTIVITY");
}else if (i>30 && w <= 70 ){
    printf(" \nYOU CAN PERFORM ACTIVITY 3,4,5 ");
}else if (i>30 && w <= 90){
        printf(" \nYOU CAN PERFORM ACTIVITY 4,5");
}else if (i>30 && w > 90){
        printf(" \nSORRY YOU CANNOT PERFORM ANY ACTIVITY ");
}else if (i>40 && w <= 80 ){
    printf(" \nYOU CAN PERFORM ACTIVITY 3,4,5 ");
}else if (i>40 && w <= 90){
        printf(" \nYOU CAN PERFORM ACTIVITY 4,5");
}else if (i>40 && w > 90){
        printf(" \nSORRY YOU CANNOT PERFORM ANY ACTIVITYY ");
}else if (i>70 ){
    printf(" \nSORRY YOU CANNOT PERFORM ANY ACTIVITY ");
}

printf(" \nENTER THE ACTIVITY YOU WANT TO PERFORM : \n ");
scanf("%d" ,&a);

printf(" \nENTER THE NO OF HOURS YOU WANT TO PERFORM THE ACTIVITY :  \n");
scanf("%d" , &b);

if(a == 1){
    price = b * 100;
    printf("\nTHE COST OF PERFORMING ACTIVITY 1 IS %d", price);
} else if(a == 2){
    price = b * 200;
    printf("\nTHE COST OF PERFORMING ACTIVITY 2 IS %d", price);
} else if(a == 3){
    price = b * 400;
    printf("\nTHE COST OF PERFORMING ACTIVITY 3 IS %d", price);
} else if(a == 4){
    price = b * 150;
    printf("\nTHE COST OF PERFORMING ACTIVITY 4 IS %d", price);
} else if(a == 5){
    price = b * 200;
    printf("\nTHE COST OF PERFORMING ACTIVITY 5 IS %d", price);
}

return 0;
}
