#include<iostream>
using namespace std;

int main(){

    char category,catA, catB, catC,catD; //category
    char difficulty;
    char a1,a2,a3,a4,a5; //category A, EASY
    char am1, am2, am3, am4, am5; //category A MEDIUM
    char ah1, ah2, ah3, ah4, ah5;//category A HARD
    char b1,b2,b3,b4,b5,bm1,bm2,bm3,bm4,bm5,bh1,bh2,bh3,bh4,bh5; // questions category B EASY,MEDIUM,HARD
    char c1, c2, c3, c4, c5,cm1,cm2,cm3,cm4,cm5,ch1,ch2,ch3,ch4,ch5; // questions C EASY,MEDIUM,HARD
    char d1, d2, d3, d4, d5; // questions D Easy
    char answer;
    int score=0,scoreA2=0,scoreA3=0,scoreB1=0,scoreB2=0,scoreB3=0,scoreC1=0,scoreC2=0,scoreC3=0,scoreD1=0;
    

    cout << "\n         ================================\n";
    cout << " \n        ¦          MIND GAMES\n         ¦\n";     
    cout << "\n         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~";
    cout << " \n ";
    cout << " \n________________________________________________________________________________\n";
    cout << " \n Welcome to mind games,a game solely created to test out your basic knowledge.";
    cout << " This game contains 4 categories with 3 levels of Difficulty. Each one has 5 questions";
    cout << " for you to answer\n";
    cout << " \n";
    cout << " Mechanics: Just type the correct letter of your answer and get 1 point each. ";
    cout << " \n";
    cout << " \n";
    cout << " \n Here are the categories: \n";
    cout << " \n     A. Random Trivia Questions  \n";
    cout << " \n     B. Human Body\n";
    cout << " \n     C. Geography \n";
    cout << " \n     D. Psychology \n";
    cout << " \n";
    cout << " \n Levels of Difficulty: \n";
    cout << " \n     A. Easy  \n";
    cout << " \n     B. Medium \n";
    cout << " \n     C. Hard \n";
    cout << " \n";
    cout << " \n ";
    cout<<"\n Do you want to begin? Y/N: ";
    cin>>answer;
    
    
    if(answer=='Y' || answer=='y'){
    cout << "\n Enter the letter of your Category: ";
    cin>>category;
    cout << "\n Enter the letter of your Difficulty: ";
    cin>>difficulty;
    
     }
     
    else{
    cout << " \n Stop fooling around child\n";
    cout << " \n       <( `ε´ )>  \n";
    }
    system("cls");

    
   
   
   if((category=='A' && difficulty =='A') || (category=='a' && difficulty =='a')){
    cout<< "\n";
    cout<< "\n____________________________________________________";
    cout<< "\n           WELCOME TO CATEGORY A!\n ";
    cout<< "\n          R A N D O M  T R I V I A \n";
    cout<< "\n           - e a s y   l e v e l -\n";
    cout<< "\n              Now let's begin!\n";
    cout<< "\n ";
    cout<< "\n";
    
   
    
    cout<< "1. Meteorology is the study of what? \n ";
    cout<< "\n       A. Cosmo \n";
    cout<< "\n       B. Weather \n";
    cout<< "\n       C. Meteors \n";
    cout<< "\n       D. Stars \n";
    cout<< "\n Answer: ";
    cin>>a1;

    
    if (a1=='B' || a1=='b'){
    score++;
    
    }
    
    cout<< "\n 2. What plant has similar DNA to humans?\n ";
    cout<< "\n       A. Ginger \n";
    cout<< "\n       B. Banana \n";
    cout<< "\n       C. Flower \n";
    cout<< "\n       D. Grass \n";
    cout<< "\n Answer: ";
    cin>>a2;
    
    
    if (a2=='B' || a2=='b'){
    score++;
    
    }
    
    cout<< "\n 3. What is the body's largest external organ called? \n ";
    cout<< "\n       A. Liver \n";
    cout<< "\n       B. Lungs \n";
    cout<< "\n       C. Skin \n";
    cout<< "\n       D. Brain \n";
    cout<< "\n Answer: ";
    cin>>a3;
    
    
    if (a3=='C' || a3=='c'){
    score++;
    
    }
    
    cout<< "\n 4. Which is the only body part that is fully grown from birth? \n ";
    cout<< "\n       A. Lips \n";
    cout<< "\n       B. Gums \n";
    cout<< "\n       C. Eyeball \n";
    cout<< "\n       D. Belly Button \n";
    cout<< "\n Answer: ";
    cin>>a4;
    
    
    if (a4=='C' || a4=='c'){
    score++;
    
    }
    
    cout<< "\n 5. Where is the heart of a shrimp located in its body ? \n ";
    cout<< "\n       A. Tail \n";
    cout<< "\n       B. Center \n";
    cout<< "\n       C. Head \n";
    cout<< "\n       D. Abdomen \n";
    cout<< "\n Answer: ";
    cin>>a5;
    
    
    if (a5=='C' || a5=='c'){
    score++;
    
    }
    
    cout << " \n Ready for your score? \n";
    cout << " \n";
    cout << "\n | You got "<<score<<"/5 |\n";
    cout << " \n \n";
    
    if (score==5){
    cout<<"\nYou are definitely smarter than an 8th grader\n";
    cout<<"\nPerfect!\n";
    
    }
     
   
   }
   else if((category=='A' && difficulty =='B') || (category=='a' && difficulty =='b')){
    cout<< "\n          WELCOME TO CATEGORY A!\n ";
    cout<< "\n          R A N D O M  T R I V I A \n";
    cout<< "\n            m e d i u m   l e v e l\n";
    cout<< "\n             Now let's begin!\n";
    cout<< "\n";
    cout<< "\n";
    
   
    
    cout<< "1. what is a group of crows called? \n ";
    cout<< "\n       A. A mischief \n";
    cout<< "\n       B. An asylum \n";
    cout<< "\n       C. A murder\n";
    cout<< "\n       D. A spiral\n";
    cout<< "\n Answer: ";
    cin>>am1;

    
    if (am1=='C' || am1=='c'){
    scoreA2++;
    
    }
    
    cout<< "\n 2. What was the name of the greek god of war?\n";
    cout<< "\n       A. Zeus \n";
    cout<< "\n       B. Apollo \n";
    cout<< "\n       C. Ares \n";
    cout<< "\n       D. Poseidon \n";
    cout<< "\n Answer: ";
    cin>>am2;
    
    
    if (am2=='C' || am2=='c'){
    scoreA2++;
    
    }
    
    cout<< "\n 3. Which color represents envy? \n ";
    cout<< "\n       A. Red \n";
    cout<< "\n       B. Purple \n";
    cout<< "\n       C. Black \n";
    cout<< "\n       D. Green \n";
    cout<< "\n Answer: ";
    cin>>am3;
    
    
    if (am3=='D' || am3=='d'){
    scoreA2++;
    
    }
    
    cout<< "\n 4. What was the first fruit that was eaten on the moon? \n ";
    cout<< "\n       A. Apple \n";
    cout<< "\n       B. Tangerine \n";
    cout<< "\n       C. Peach \n";
    cout<< "\n       D. Corn \n";
    cout<< "\n Answer: ";
    cin>>am4;
    
    
    if (am4=='C' || am4=='c'){
    scoreA2++;
    
    }
    
    cout<< "\n 5. Which sport was called the 'american pasttime'?";
    cout<< "\n      A. Baseball \n";
    cout<< "\n      B. Hockey \n";
    cout<< "\n      C. Basketball \n";
    cout<< "\n      D. Soccer \n";
    cout<< "\n Answer: ";
    cin>>am5;
    
    
    if (am5=='A' || am5=='a'){
    scoreA2++;
    
    }
    
    cout << " \n Ready for your score? \n";
    cout << " \n You got "<<scoreA2<<"/5 \n";
   
   
   
   
   
   }
   else if((category=='A' && difficulty =='C') || (category=='a' && difficulty =='c')){
    cout<< "\n           WELCOME TO CATEGORY A!\n ";
    cout<< "\n          R A N D O M  T R I V I A \n";
    cout<< "\n             h a r d    l e v e l\n";
    cout<< "\n               Now let's begin!\n";
    cout<< "\n";
    cout<< "\n";
    
   
    
    cout<< "1. Where on the human body is the zygomatic bone found ? \n ";
    cout<< "\n       A. Facial Cheek\n";
    cout<< "\n       B. Pelvis \n";
    cout<< "\n       C. Backbone\n";
    cout<< "\n       D. Ribs\n";
    cout<< "\n Answer: ";
    cin>>ah1;

    
    if (ah1=='A' || ah1=='a'){
    scoreA3++;
    
    }
    
    cout<< "\n 2. When held to ultraviolet light, what animal’s urine glows in the dark?\n";
    cout<< "\n       A. Dog \n";
    cout<< "\n       B. Horse \n";
    cout<< "\n       C. Cat \n";
    cout<< "\n       D. Rabbit \n";
    cout<< "\n Answer: ";
    cin>>ah2;
    
    
    if (ah2=='C' || ah2=='c'){
    scoreA3++;
    
    }
    
    cout<< "\n 3. Mageirocophobia is the fear of what?? \n ";
    cout<< "\n       A. Eye contact \n";
    cout<< "\n       B. Man \n";
    cout<< "\n       C. Cooking \n";
    cout<< "\n       D. Transportation\n";
    cout<< "\n Answer: ";
    cin>>ah3;
    
    
    if (ah3=='C' || ah3=='c'){
    scoreA3++;
    
    }
    
    cout<< "\n 4. What was the original name of the search engine 'Google' ? \n ";
    cout<< "\n       A. Backrub \n";
    cout<< "\n       B. FindLauncher \n";
    cout<< "\n       C. GrowRadar \n";
    cout<< "\n       D. Glegool \n";
    cout<< "\n Answer: ";
    cin>>ah4;
    
    
    if (ah4=='A' || ah4=='a'){
    scoreA3++;
    
    }
    
    cout<< "\n 5. Which of the following languages does NOT use gender as a part of its grammar? \n";
    cout<< "\n       A. Dutch \n";
    cout<< "\n       B. Filipino \n";
    cout<< "\n       C. Japanese \n";
    cout<< "\n       D. Turkish \n";
    cout<< "\n Answer: ";
    cin>>ah5;
    
    
    if (ah5=='D' || ah5=='d'){
    scoreA3++;
    
    }
    
    cout << " \n Ready for your score? \n";
    cout << " \n You got "<<scoreA3<<"/5 \n";
   
   
   
   
   }
   else if ((category=='B' && difficulty=='a') || (category=='b' && difficulty=='a')){
   
    cout<<"\n ";
    cout<<"\n";
    cout<< "\n          Welcome to Category C!\n ";
    cout<<"\n         T H E  H U M A N  B O D Y \n";
    cout<<"\n              e a s y  l e v e l\n";
    cout<< "\n            Now let's begin!\n";
    cout<< "\n";
    cout<< "\n";
     
    cout<< "\n1. What is the hardest substance in the human body? \n";
    cout<< "\n     A. Bone \n";
    cout<< "\n     B. Nails \n";
    cout<< "\n     C. Tooth enamel\n";
    cout<< "\n     D. Tooth\n";
    cout<< "\n Answer: ";
    cin>>b1;
    
    
    if (b1=='C' || b1=='c'){
    scoreB1++;
    
    }
     
    cout<< "\n2. Which is the rarest blood type in Human? \n";
    cout<< "\n     A. O \n";
    cout<< "\n     B. A \n";
    cout<< "\n     C. AB negative \n";
    cout<< "\n     D. B \n";
    cout<< "\n Answer: ";
    cin>>b2;
    
    
    if (b2=='C' || b2=='c'){
    scoreB1++;
    
    }
    
    cout<< "\n3.  How many teeth are does an average human adult has? \n";
    cout<< "\n     A. 16 \n";
    cout<< "\n     B. 32  \n";
    cout<< "\n     C. 26  \n";
    cout<< "\n     D. 30 \n";
    cout<< "\n Answer: ";
    cin>>b3;
    
    if (b3=='B' || b3=='b'){
    scoreB1++;
    }
    
    cout<< "\n#include<iostream>
using namespace std;

int main(){

    char category,catA, catB, catC,catD; //category
    char difficulty;
    char a1,a2,a3,a4,a5; //category A, EASY
    char am1, am2, am3, am4, am5; //category A MEDIUM
    char ah1, ah2, ah3, ah4, ah5;//category A HARD
    char b1,b2,b3,b4,b5,bm1,bm2,bm3,bm4,bm5,bh1,bh2,bh3,bh4,bh5; // questions category B EASY,MEDIUM,HARD
    char c1, c2, c3, c4, c5,cm1,cm2,cm3,cm4,cm5,ch1,ch2,ch3,ch4,ch5; // questions C EASY,MEDIUM,HARD
    char d1, d2, d3, d4, d5; // questions D Easy
    char answer;
    int score=0,scoreA2=0,scoreA3=0,scoreB1=0,scoreB2=0,scoreB3=0,scoreC1=0,scoreC2=0,scoreC3=0,scoreD1=0;
    

    cout << "\n         ================================\n";
    cout << " \n        ¦          MIND GAMES\n         ¦\n";     
    cout << "\n         ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~";
    cout << " \n ";
    cout << " \n________________________________________________________________________________\n";
    cout << " \n Welcome to mind games,a game solely created to test out your basic knowledge.";
    cout << " This game contains 4 categories with 3 levels of Difficulty. Each one has 5 questions";
    cout << " for you to answer\n";
    cout << " \n";
    cout << " Mechanics: Just type the correct letter of your answer and get 1 point each. ";
    cout << " \n";
    cout << " \n";
    cout << " \n Here are the categories: \n";
    cout << " \n     A. Random Trivia Questions  \n";
    cout << " \n     B. Human Body\n";
    cout << " \n     C. Geography \n";
    cout << " \n     D. Psychology \n";
    cout << " \n";
    cout << " \n Levels of Difficulty: \n";
    cout << " \n     A. Easy  \n";
    cout << " \n     B. Medium \n";
    cout << " \n     C. Hard \n";
    cout << " \n";
    cout << " \n ";
    cout<<"\n Do you want to begin? Y/N: ";
    cin>>answer;
    
    
    if(answer=='Y' || answer=='y'){
    cout << "\n Enter the letter of your Category: ";
    cin>>category;
    cout << "\n Enter the letter of your Difficulty: ";
    cin>>difficulty;
    
     }
     
    else{
    cout << " \n Stop fooling around child\n";
    cout << " \n       <( `ε´ )>  \n";
    }
    system("cls");

    
   
   
   if((category=='A' && difficulty =='A') || (category=='a' && difficulty =='a')){
    cout<< "\n";
    cout<< "\n____________________________________________________";
    cout<< "\n           WELCOME TO CATEGORY A!\n ";
    cout<< "\n          R A N D O M  T R I V I A \n";
    cout<< "\n           - e a s y   l e v e l -\n";
    cout<< "\n              Now let's begin!\n";
    cout<< "\n ";
    cout<< "\n";
    
   
    
    cout<< "1. Meteorology is the study of what? \n ";
    cout<< "\n       A. Cosmo \n";
    cout<< "\n       B. Weather \n";
    cout<< "\n       C. Meteors \n";
    cout<< "\n       D. Stars \n";
    cout<< "\n Answer: ";
    cin>>a1;

    
    if (a1=='B' || a1=='b'){
    score++;
    
    }
    
    cout<< "\n 2. What plant has similar DNA to humans?\n ";
    cout<< "\n       A. Ginger \n";
    cout<< "\n       B. Banana \n";
    cout<< "\n       C. Flower \n";
    cout<< "\n       D. Grass \n";
    cout<< "\n Answer: ";
    cin>>a2;
    
    
    if (a2=='B' || a2=='b'){
    score++;
    
    }
    
    cout<< "\n 3. What is the body's largest external organ called? \n ";
    cout<< "\n       A. Liver \n";
    cout<< "\n       B. Lungs \n";
    cout<< "\n       C. Skin \n";
    cout<< "\n       D. Brain \n";
    cout<< "\n Answer: ";
    cin>>a3;
    
    
    if (a3=='C' || a3=='c'){
    score++;
    
    }
    
    cout<< "\n 4. Which is the only body part that is fully grown from birth? \n ";
    cout<< "\n       A. Lips \n";
    cout<< "\n       B. Gums \n";
    cout<< "\n       C. Eyeball \n";
    cout<< "\n       D. Belly Button \n";
    cout<< "\n Answer: ";
    cin>>a4;
    
    
    if (a4=='C' || a4=='c'){
    score++;
    
    }
    
    cout<< "\n 5. Where is the heart of a shrimp located in its body ? \n ";
    cout<< "\n       A. Tail \n";
    cout<< "\n       B. Center \n";
    cout<< "\n       C. Head \n";
    cout<< "\n       D. Abdomen \n";
    cout<< "\n Answer: ";
    cin>>a5;
    
    
    if (a5=='C' || a5=='c'){
    score++;
    
    }
    
    cout << " \n Ready for your score? \n";
    cout << " \n";
    cout << "\n | You got "<<score<<"/5 |\n";
    cout << " \n \n";
    
    if (score==5){
    cout<<"\nYou are definitely smarter than an 8th grader\n";
    cout<<"\nPerfect!\n";
    
    }
     
   
   }
   else if((category=='A' && difficulty =='B') || (category=='a' && difficulty =='b')){
    cout<< "\n          WELCOME TO CATEGORY A!\n ";
    cout<< "\n          R A N D O M  T R I V I A \n";
    cout<< "\n            m e d i u m   l e v e l\n";
    cout<< "\n             Now let's begin!\n";
    cout<< "\n";
    cout<< "\n";
    
   
    
    cout<< "1. what is a group of crows called? \n ";
    cout<< "\n       A. A mischief \n";
    cout<< "\n       B. An asylum \n";
    cout<< "\n       C. A murder\n";
    cout<< "\n       D. A spiral\n";
    cout<< "\n Answer: ";
    cin>>am1;

    
    if (am1=='C' || am1=='c'){
    scoreA2++;
    
    }
    
    cout<< "\n 2. What was the name of the greek god of war?\n";
    cout<< "\n       A. Zeus \n";
    cout<< "\n       B. Apollo \n";
    cout<< "\n       C. Ares \n";
    cout<< "\n       D. Poseidon \n";
    cout<< "\n Answer: ";
    cin>>am2;
    
    
    if (am2=='C' || am2=='c'){
    scoreA2++;
    
    }
    
    cout<< "\n 3. Which color represents envy? \n ";
    cout<< "\n       A. Red \n";
    cout<< "\n       B. Purple \n";
    cout<< "\n       C. Black \n";
    cout<< "\n       D. Green \n";
    cout<< "\n Answer: ";
    cin>>am3;
    
    
    if (am3=='D' || am3=='d'){
    scoreA2++;
    
    }
    
    cout<< "\n 4. What was the first fruit that was eaten on the moon? \n ";
    cout<< "\n       A. Apple \n";
    cout<< "\n       B. Tangerine \n";
    cout<< "\n       C. Peach \n";
    cout<< "\n       D. Corn \n";
    cout<< "\n Answer: ";
    cin>>am4;
    
    
    if (am4=='C' || am4=='c'){
    scoreA2++;
    
    }
    
    cout<< "\n 5. Which sport was called the 'american pasttime'?";
    cout<< "\n      A. Baseball \n";
    cout<< "\n      B. Hockey \n";
    cout<< "\n      C. Basketball \n";
    cout<< "\n      D. Soccer \n";
    cout<< "\n Answer: ";
    cin>>am5;
    
    
    if (am5=='A' || am5=='a'){
    scoreA2++;
    
    }
    
    cout << " \n Ready for your score? \n";
    cout << " \n You got "<<scoreA2<<"/5 \n";
   
   
   
   
   
   }
   else if((category=='A' && difficulty =='C') || (category=='a' && difficulty =='c')){
    cout<< "\n           WELCOME TO CATEGORY A!\n ";
    cout<< "\n          R A N D O M  T R I V I A \n";
    cout<< "\n             h a r d    l e v e l\n";
    cout<< "\n               Now let's begin!\n";
    cout<< "\n";
    cout<< "\n";
    
   
    
    cout<< "1. Where on the human body is the zygomatic bone found ? \n ";
    cout<< "\n       A. Facial Cheek\n";
    cout<< "\n       B. Pelvis \n";
    cout<< "\n       C. Backbone\n";
    cout<< "\n       D. Ribs\n";
    cout<< "\n Answer: ";
    cin>>ah1;

    
    if (ah1=='A' || ah1=='a'){
    scoreA3++;
    
    }
    
    cout<< "\n 2. When held to ultraviolet light, what animal’s urine glows in the dark?\n";
    cout<< "\n       A. Dog \n";
    cout<< "\n       B. Horse \n";
    cout<< "\n       C. Cat \n";
    cout<< "\n       D. Rabbit \n";
    cout<< "\n Answer: ";
    cin>>ah2;
    
    
    if (ah2=='C' || ah2=='c'){
    scoreA3++;
    
    }
    
    cout<< "\n 3. Mageirocophobia is the fear of what?? \n ";
    cout<< "\n       A. Eye contact \n";
    cout<< "\n       B. Man \n";
    cout<< "\n       C. Cooking \n";
    cout<< "\n       D. Transportation\n";
    cout<< "\n Answer: ";
    cin>>ah3;
    
    
    if (ah3=='C' || ah3=='c'){
    scoreA3++;
    
    }
    
    cout<< "\n 4. What was the original name of the search engine 'Google' ? \n ";
    cout<< "\n       A. Backrub \n";
    cout<< "\n       B. FindLauncher \n";
    cout<< "\n       C. GrowRadar \n";
    cout<< "\n       D. Glegool \n";
    cout<< "\n Answer: ";
    cin>>ah4;
    
    
    if (ah4=='A' || ah4=='a'){
    scoreA3++;
    
    }
    
    cout<< "\n 5. Which of the following languages does NOT use gender as a part of its grammar? \n";
    cout<< "\n       A. Dutch \n";
    cout<< "\n       B. Filipino \n";
    cout<< "\n       C. Japanese \n";
    cout<< "\n       D. Turkish \n";
    cout<< "\n Answer: ";
    cin>>ah5;
    
    
    if (ah5=='D' || ah5=='d'){
    scoreA3++;
    
    }
    
    cout << " \n Ready for your score? \n";
    cout << " \n You got "<<scoreA3<<"/5 \n";
   
   
   
   
   }
   else if ((category=='B' && difficulty=='a') || (category=='b' && difficulty=='a')){
   
    cout<<"\n ";
    cout<<"\n";
    cout<< "\n          Welcome to Category C!\n ";
    cout<<"\n         T H E  H U M A N  B O D Y \n";
    cout<<"\n              e a s y  l e v e l\n";
    cout<< "\n            Now let's begin!\n";
    cout<< "\n";
    cout<< "\n";
     
    cout<< "\n1. What is the hardest substance in the human body? \n";
    cout<< "\n     A. Bone \n";
    cout<< "\n     B. Nails \n";
    cout<< "\n     C. Tooth enamel\n";
    cout<< "\n     D. Tooth\n";
    cout<< "\n Answer: ";
    cin>>b1;
    
    
    if (b1=='C' || b1=='c'){
    scoreB1++;
    
    }
     
    cout<< "\n2. Which is the rarest blood type in Human? \n";
    cout<< "\n     A. O \n";
    cout<< "\n     B. A \n";
    cout<< "\n     C. AB negative \n";
    cout<< "\n     D. B \n";
    cout<< "\n Answer: ";
    cin>>b2;
    
    
    if (b2=='C' || b2=='c'){
    scoreB1++;
    
    }
    
    cout<< "\n3.  How many teeth are does an average human adult has? \n";
    cout<< "\n     A. 16 \n";
    cout<< "\n     B. 32  \n";
    cout<< "\n     C. 26  \n";
    cout<< "\n     D. 30 \n";
    cout<< "\n Answer: ";
    cin>>b3;
    
    if (b3=='B' || b3=='b'){
    scoreB1++;
    }
    
    cout<< "\n
