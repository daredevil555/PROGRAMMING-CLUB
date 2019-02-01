
#include<stdio.h>

#include<conio.h>

#include<stdlib.h>

#include<string.h>

#include<time.h>

#include<process.h>

char username[15],password[15];

void openfile(file);

void writefile(file);

void funda();

void displayscore();

void help();

void writescore();

void about();

void members_coordinators();

void materials();

void sourcecode();

void news_facts();

void movies_documentaries();

void events_challenges();

void practice_tests();

void project_ideas();

void registration();

void login();

struct regi

{

char name[20],college_code[10],roll_number[10],gmail_address[30],contact_number[15],user_name[20],pass_word[20];

};

int main()

{

int choice;

printf("\n\n\t\t\t**************************************************************\n\n");

printf("\t\t\t\t\t**PROGRAMMING CLUB**\n\n");

printf("\t\t\t**************************************************************\n\n");

while(1)

{

    printf("\n\n\tLOG IN IF YOU ARE ALREADY REGISTERED");

    printf("\n\n\n\tREGISTER[1]\n\n\tLOG IN[2]\n\n\tEXIT[3]");

    printf("\n\n\tENTER YOUR CHOICE:");

scanf("%d",&choice);

switch(choice)

{

    case 1:registration();

    break;

    case 2:login();

    break;

    case 3:printf("\n\n\tSEE YOU AGAIN");

    getch();

    exit(0);

}

system("cls");

}

}

void login()

{

while(1)

{

    system("cls");

    int choice;

    printf("\n\n\t**************************************************************\n\n");

    printf("\t\t\t\t**LOG IN**\n\n");

    printf("\t**************************************************************\n\n");

    printf("\tENTER USERNAME:");

    scanf("%s",&username);

    printf("\n\tENTER PASSWORD:");

    scanf("%s",&password);

    if(strcmp(username,"sahith")==0)

    {

    if(strcmp(password,"password")==0)

    {

        system("cls");

while(1)

{

    printf("\n\n\t**************************************************************\n\n");

    printf("\t\t\t**PROGRAMMING CLUB**\n\n");

    printf("\t**************************************************************\n\n");

    printf("\n\n\t**HOME**");

    printf("\n\n\n\tABOUT US[1]");

    printf("\n\n\tMEMBERS & COORDINATORS[2]");

    printf("\n\n\tMATERIALS[3]");

    printf("\n\n\tSOURCE CODE[4]");

    printf("\n\n\tNEWS & FACTS[5]");

    printf("\n\n\tEVENTS & WEEKLY CHALLENGES[6]");

    printf("\n\n\tPRACTICE TESTS[7]");

    printf("\n\n\tPROJECT IDEAS[8]");

    printf("\n\n\tMOVIES & DOCUMENTARIES[9]");

    printf("\n\n\tEXIT[10]");

    printf("\n\n\n\tENTER YOUR CHOICE:");

    scanf("%d",&choice);

switch(choice)

{

    case 1:about();

    break;

    case 2:members_coordinators();

    break;

    case 3:materials();

    break;

    case 4:sourcecode();

    break;

    case 5:news_facts();

    break;

    case 6:events_challenges();

    break;

    case 7:practice_tests();

    break;

    case 8:project_ideas();

    break;

    case 9:movies_documentaries();

    break;

    case 10:printf("\n\n\t\tTHANK YOU FOR USING THE SOFTWARE");

    getch();

    exit(0);

    default: printf("YOU ENTERED WRONG CHOICE....\nPRESS ANY KEY TO TRY AGAIN");

    getch();

    break;

}

system("cls");

}

    }

    else

    {

        printf("YOU HAVE ENTERED WRONG PASSWORD, RETRY\n\n");

    }

    }

    else

    {

        printf("YOU HAVE ENTERED WRONG USERNAME, RETRY\n\n");

    }

    }

return 0;

}

void about()

{

    FILE *file;

    file="aboutf.txt";

    openfile(file);

}

void events_challenges()

{

    system("cls");

    int choice;

    printf("\n\n\t\t******************************************\n");

    printf("\n\t\t\t**EVENTS AND WEEKLY CHALLENGES**\n");

    printf("\n\t\t******************************************\n\n");

    while(1)

    {

    printf("\n\n\tWEEKLY CHALLENGES[1]\n\n\tEVENTS[2]\n\n\tEXIT[3]");

    printf("\n\nENTER THE CHOICE:");

    scanf("%d",&choice);

    switch(choice)

    {

    FILE *file;

    case 1:file="weekly challenges.txt";

    openfile(file);

    break;

    case 2:file="events.txt";

    openfile(file);

    break;

    case 3:return;

    getch();

    default: printf("YOU ENTERED WRONG CHOICE....\nPRESS ANY KEY TO TRY AGAIN");

    getch();

    }

system("cls");

    }

}

void materials()

{

    system("cls");

    int choice;

    printf("\n\n\t\t******************************************\n");

    printf("\n\t\t\t\t**MATERIALS**\n");

    printf("\n\t\t******************************************\n\n");

    while(1)

    {

    printf("\n\n\tFUNDAMENTALS OF COMPUTER[1]\n\n\tC[2]\n\n\tC++[3]\n\n\tC#[4]\n\n\tJAVA[5]\n\n\tJAVASCRIPT[6]\n\n\tPYTHON[7]\n\n\t.NET[8]\n\n\tINTERNET OF THINGS[9]\n\n\tBIG DATA ANALYTICS[10]\n\n\tCLOUD COMPUTING[11]\n\n\tPHP[12]\n\n\tDATA MINING[13]\n\n\tEXIT[14]\n\n\t");

    printf("\n\n\tENTER YOUR CHOICE:");

    scanf("%d",&choice);

switch(choice)

{

    FILE *file;

    case 1:file="funda.txt";

    openfile(file);

    break;

    case 2:file="c.txt";

    openfile(file);

    break;

    case 3:file="cpp.txt";

    openfile(file);

    break;

    case 4:file="c#.txt";

    openfile(file);

    break;

    case 5:file="java.txt";

    openfile(file);

    break;

    case 6:file="javascript.txt";

    openfile(file);

    break;

    case 7:file="python.txt";

    openfile(file);

    break;

    case 8:file=".net.txt";

    openfile(file);

    break;

    case 9:file="iot.txt";

    openfile(file);

    break;

     case 10:file="bda.txt";

    openfile(file);

    break;

    case 11:file="cloud computing.txt";

    openfile(file);

    break;

    case 12:file="phpmsql.txt";

    openfile(file);

    break;

     case 13:file="datamining.txt";

    openfile(file);

    break;

    case 14:return;

    getch();

    default: printf("YOU ENTERED WRONG CHOICE....\nPRESS ANY KEY TO TRY AGAIN");

    getch();

    break;

    }

    system("cls");
}

return;

}

void registration()

{


    system("cls");

    FILE *registerf;

    char another='y',roll_number[10];

    struct regi e;void openfile(file)

{

    char ch;

    system("cls");

    file=fopen(file,"r");

    if(file==NULL)

    {

        printf("FILE DOESNOT EXIST...\n PRESS ANY KEY TO EXIT...\n");

        getch();

        return;

    }

    else

    {

        rewind(file);

        while((ch=fgetc(file))!=EOF)

            putchar(ch);

    }

    fclose(file);

    printf("\n\nPRESS ANY KEY TO EXIT...");

    getch();
}

void writefile(file)

{

   int i,n=1;

  char str[100];

  printf("\n\n:: TYPE IN ONE LINE ::\n");

	file = fopen (file,"a");

	for(i = 0; i < n+1;i++)

		{

		fgets(str, sizeof str, stdin);

		fputs(str, file);

		}

   fclose(file);

    printf("\n\nPRESS ANY KEY TO EXIT...");

    getch();

    return;

}

    int ch5;

    printf("\n\n\t\t******************************************\n");

    printf("\n\t\t\t**REGISTRATION**\n");

    printf("\n\t\t******************************************\n\n");

    fflush(stdin);

    registerf=fopen("registerf.txt","ab+");


    if ( registerf == NULL )

    {

        registerf=fopen("registerf.txt","wb+");

        if(registerf==NULL)
        {

        printf("\nSYSTEM ERROR...\nPRESS ANY KEY TO EXIT");

    getch();

    return;

    }

    }

while(another=='y'||another=='Y')

    {

        ch5=0;

        fflush(stdin);

        printf("\n\tENTER YOUR ROLL NUMBER OR ID:");

        scanf("%s",&roll_number);

        rewind(registerf);

        while(fread(&e,sizeof(e),1,registerf)==1)

        {

            if(strcmp(e.roll_number,roll_number)==0)

            {

                printf("OOPS!!...THE MEMBER ALREADY EXIST");

                ch5=1;

            }

        }

        if(ch5==0)

        {

            strcpy(e.roll_number,roll_number);

            printf("\t\nENTER NAME:");

            fflush(stdin);

            gets(e.name);

            fflush(stdin);

            printf("\t\nENTER COLLEGE CODE:");

            gets(e.college_code);

            fflush(stdin);

             printf("\t\nENTER YOUR CONTACT NUMBER:");

            gets(e.contact_number);

            fflush(stdin);

            printf("\t\nENTER GMAIL ADDRESS:");
void openfile(file)

{

    char ch;

    system("cls");

    file=fopen(file,"r");

    if(file==NULL)

    {

        printf("FILE DOESNOT EXIST...\n PRESS ANY KEY TO EXIT...\n");

        getch();

        return;

    }

    else

    {

        rewind(file);

        while((ch=fgetc(file))!=EOF)

            putchar(ch);

    }

    fclose(file);

    printf("\n\nPRESS ANY KEY TO EXIT...");

    getch();
}

void writefile(file)

{

   int i,n=1;

  char str[100];

  printf("\n\n:: TYPE IN ONE LINE ::\n");

	file = fopen (file,"a");

	for(i = 0; i < n+1;i++)

		{

		fgets(str, sizeof str, stdin);

		fputs(str, file);

		}

   fclose(file);

    printf("\n\nPRESS ANY KEY TO EXIT...");

    getch();

    return;

}
            gets(e.gmail_address);

            fflush(stdin);

            printf("\t\nCREATE USERNAME:");

            gets(e.user_name);

            fflush(stdin);

            printf("\t\nCREATE PASSWORD:");

            gets(e.pass_word);

            fflush(stdin);

            fwrite ( &e, sizeof ( e ), 1, registerf ) ;

            printf("\nYOUR RECORD IS ADDED...\n");

}

        printf("\n\tADD MEMBER...(Y/N)");

        fflush(stdin);

        another=getchar();

    }

    fclose(registerf);

    printf("\n\n\tPRESS ANY KEY EXIT...");

    getch();

    }

    void members_coordinators()

{

    system("cls");

int choice;

     printf("\n\n\t\t******************************************\n");

    printf("\n\t\t\t**MEMBERS & COORDINATORS**\n");

    printf("\n\t\t******************************************\n\n");

    while(1)

    {

    printf("\n\n\tMEMBERS[1]\n\n\tCOORDINATORS[2]\n\n\tEXIT[3]");

    printf("\n\n\tENTER THE CHOICE:");

    scanf("%d",&choice);

    switch(choice)

    {

    FILE *file;

    case 1:file="registerf.txt";

    openfile(file);

    break;

    case 2:file="coordinators.txt";

    openfile(file);

    break;

     case 3:return;

    getch();

     default: printf("YOU ENTERED WRONG CHOICE....\nPRESS ANY KEY TO TRY AGAIN");

    getch();

    }

system("cls");

    }

    system("cls");

}

void sourcecode()

{

    system("cls");

    int choice;

    printf("\n\n\t\t******************************************\n");

    printf("\n\t\t\t\t**SOURCE CODE**\n");

    printf("\n\t\t******************************************\n\n");

    while(1)

    {

        printf("\n\n\tAPPLICATIONS:\n\n\n\tBANK MANAGEMENT[1]\n\n\tCALENDER[2]\n\n\tCONTACT MANAGEMENT[3]\n\n\tCUSTOMER BILLING[4]\n\n\tONLINE SHOPPING SYSTEM[5]\n\n\tHOSPITAL MANAGEMENT[6]\n\n\tLIBRARY MANAGEMENT[7]\n\n\tMEDICAL STORE[8]\n\n\tPAINT BRUSH[9]\n\n\tPERIODIC TABLE[10]\n\n\tPERSONAL DIARY[11]\n\n\tQUIZ[12]\n\n\tRAIL RESERVATION[13]\n\n\tSUPER MARKETING[14]\n\n\tTELECOM BILLING[15]");

        printf(" \n\n\n\tGAMES:\n\n\n\tARKANOID[16]\n\n\tASTEROIDS[17]\n\n\tBEJEWELED[18]\n\n\tCHESS[19]\n\n\tDOODLE JUMP[20]\n\n\tFIFTEEN PUZZLE[21]\n\n\tMAHJONG SOLITAIRE[22]\n\n\tMINESWEEPER[23]\n\n\tNET WALK[24]\n\n\tOUTRUN[25]\n\n\tRACING[26]\n\n\tSNAKE[27]\n\n\tTETRIS[28]\n\n\tTIC TAC TOE[29]\n\n\tTRON[30]\n\n\tVOLLEY BALL[31]\n\n\tXONIX[32]");

        printf("\n\n\tSUDOKU[33]\n\n\t T REX CHROME GAME[34]\n\n\n\tREQUEST FOR REQUIRED SOURCE CODE[35]\n\n\t\n\tEXIT[36]\n\t");

         printf("\n\n\tENTER YOUR CHOICE:");

        scanf("%d",&choice);

switch(choice)

{

    FILE *file;

    case 1:file="bank management.txt";

    openfile(file);

    break;

    case 2:file="calender.txt";

    openfile(file);

    break;

    case 3:file="contact management.txt";

    openfile(file);

    break;

    case 4:file="customer billing project.txt";

    openfile(file);

    break;

    case 5:file="online shopping system.txt";

    openfile(file);

    break;

    case 6:file="hospital management system.txt";

    openfile(file);

    break;

    case 7:file="library management.txt";

    openfile(file);

    break;

    case 8:file="medical store.txt";

    openfile(file);

    break;

    case 9:file="paint brush.txt";

    openfile(file);

    break;

     case 10:file="periodic table.txt";

     openfile(file);

    break;

    case 11:file="personal diary.txt";

    openfile(file);

    break;

    case 12:file="quiz.txt";

    openfile(file);

    break;

    case 13:file="railway reservation.txt";

    openfile(file);

    break;

    case 14:file="super market billing.txt";

    openfile(file);

    break;

    case 15:file="telecom billing.txt";

    openfile(file);

    break;

    case 16:file="arkanoid.txt";

    openfile(file);

    break;

    case 17:file="asteroids.txt";

    openfile();

    break;

    case 18:file="bejeweled.txt";

    openfile(file);

    break;

    case 19:file="chess.txt";

    openfile(file);

    break;

    case 20:file="doodlejump.txt";

    openfile(file);

    break;

    case 21:file="fifteen-puzzle.txt";

    openfile(file);

    break;

    case 22:file="mahjong solitaire.txt";

    openfile(file);

    break;

     case 23:file="minesweeper.txt";

     openfile(file);

    break;

    case 24:file="net walk.txt";

    openfile(file);

    break;

    case 25:file="outrun.txt";

    openfile(file);

    break;

    case 26:file="racing.txt";

    openfile(file);

    break;

     case 27:file="snake.txt";

     openfile(file);

    break;

    case 28:file="tetris.txt";

    openfile(file);

    break;

    case 29:file="tic tac toe.txt";

    openfile(file);

    break;

    case 30:file="tron.txt";

    openfile(file);

    break;

    case 31:file="volley ball.txt";

    openfile(file);

    break;

    case 32:file="xonix.txt";

    openfile(file);

    break;

    case 33:file="sudoku.txt";

    openfile(file);

    break;

    case 34:file="t rex chrome game.txt";

    openfile(file);

    break;

    case 35:file="asksourcecode.txt";

    writefile(file);

    break;

    case 36:return;

    getch();

    default: printf("YOU ENTERED WRONG CHOICE....\nPRESS ANY KEY TO TRY AGAIN");

    getch();

    break;

    }

    system("cls");

}

}

void openfile(file)

{

    char ch;

    system("cls");

    file=fopen(file,"r");

    if(file==NULL)

    {

        printf("FILE DOESNOT EXIST...\n PRESS ANY KEY TO EXIT...\n");

        getch();

        return;

    }

    else

    {

        rewind(file);

 //       while((ch=fgetc(file))!=EOF)
//
 //           putchar(ch);
system("type($file)|more");
    }

    fclose(file);

    printf("\n\nPRESS ANY KEY TO EXIT...");

    getch();
}

void writefile(file)

{

   int i,n=1;

  char str[100];

  printf("\n\n:: TYPE IN ONE LINE ::\n");

	file = fopen (file,"a");

	for(i = 0; i < n+1;i++)

		{

		fgets(str, sizeof str, stdin);

		fputs(str, file);

		}

   fclose(file);

    printf("\n\nPRESS ANY KEY TO EXIT...");

    getch();

    return;

}

void project_ideas()

{
    system("cls");

    printf("\n\n\t\t******************************************\n");

    printf("\n\t\t\t**PROJECT IDEAS**\n");

    printf("\n\t\t******************************************\n\n");

    printf("\n\n\tWRITE YOUR PROJECT IDEA....");

    FILE *file;

    file="ideas.txt";

    writefile(file);

    getch();

    return;

}

void news_facts()

{

    system("cls");

    int choice;

    printf("\n\n\t\t******************************************\n");

    printf("\n\t\t\t**NEWS & FACTS**\n");

    printf("\n\t\t******************************************\n\n");

    while(1)

    {

    printf("\n\n\tWE BRING YOU THE LATEST NEWS AND INTRESTING FACTS IN COMPUTER SCIENCE");

    printf("\n\n\tNEWS[1]\n\n\tFACTS[2]\n\n\tEXIT[3]");

    printf("\n\n\t\tENTER THE CHOICE:");

    scanf("%d",&choice);

    switch(choice)

    {

    FILE *file;

    case 1:

    printf("\n\n\tNEWS\n\n");

    file="news.txt";

    openfile(file);

    break;

    case 2:

    printf("\n\n\tINTTRESTING FACTS");

    file="facts.txt";

    openfile(file);

    break;

    case 3:return;

    getch();

    default: printf("YOU ENTERED WRONG CHOICE....\nPRESS ANY KEY TO TRY AGAIN");

    getch();

    }

    system("cls");

    }

}

void movies_documentaries()

{

    system("cls");

    printf("\n\n\t\t******************************************\n");

    printf("\n\t\t\t**FACTS & MOVIES**\n");

    printf("\n\t\t******************************************\n\n");

     printf("\n\n\tHERE ARE THE INSPIRING MOVIES & DOCUMENTARIES ON COMPUTER SCIENCE");

     printf("\n\n\t**MOVIES**");

     printf("\n\n\n\tTHE INTERNSHIP\n\n\tTHE SOCIAL NETWORK\n\n\tTHE PERFECT SCORE\n\n\tJOBS\n\n\tTHE IMITATION GAME\n\n\tANTI TRUST\n\n\tWIKI LEAKS\n\n\tPRIMER\n\n\tWAR GAMES\n\n\tHACKERS");

     printf("\n\n\n\t**DOCUMENTARY**");

     printf("\n\n\n\tPIRATES OF SILLICON VALLEY\n\n\tTHE PIXAL STORY\n\n\tTPB AFK: THE PIRATE BAY\n\n\tTETRIS:FROM RUSSIA WITH LOVE\n\n\tREVOLUTION OS\n\n\tTRIUMPH OF NERDS: THE RISE OF ACCIDENTAL EMPIRES\n\n\tNERDS:2.0.1:A BRIEF HISTORY OF THE INTERNET");

getch();

}

void practice_tests()

{

    system("cls");

    int choice;

    printf("\n\n\t\t******************************************\n");

    printf("\n\t\t\t\t**TEST YOURSELF**\n");

    printf("\n\t\t******************************************\n\n");

    while(1)

    {

        printf("\n\n\tFUNDAMENTALS OF COMPUTER[1]\n\n\tC[2]\n\n\tC++[3]\n\n\tC#[4]\n\n\tJAVA[5]\n\n\tJAVASCRIPT[6]\n\n\tPYTHON[7]\n\n\t.NET[8]\n\n\tINTERNET OF THINGS[9]\n\n\tBIG DATA ANALYTICS[10]\n\n\tCLOUD COMPUTING[11]\n\n\tPHP[12]\n\n\tDATA MINING[13]\n\n\tEXIT[14]\n\n\t");

         printf("\n\n\tENTER YOUR CHOICE:");

    scanf("%d",&choice);

switch(choice)

{

    case 1:funda();

    break;

    case 2:printf("\n\n\tUNDER CONSTRUCTION");

    break;

    case 3:printf("\n\n\tUNDER CONSTRUCTION");

    break;

    case 4:printf("\n\n\tUNDER CONSTRUCTION");

    break;

    case 5:printf("\n\n\tUNDER CONSTRUCTION");

    break;

    case 6:printf("\n\n\tUNDER CONSTRUCTION");

    break;

    case 7:printf("\n\n\tUNDER CONSTRUCTION");

    break;

    case 8:printf("\n\n\tUNDER CONSTRUCTION");

    break;

    case 9:printf("\n\n\tUNDER CONSTRUCTION");

    break;

     case 10:printf("\n\n\tUNDER CONSTRUCTION");

    break;

    case 11:printf("\n\n\tUNDER CONSTRUCTION");

    break;

    case 12:printf("\n\n\tUNDER CONSTRUCTION");

    break;

    case 13:printf("\n\n\tUNDER CONSTRUCTION");

    break;

    case 14:return;

    getch();

    default: printf("YOU ENTERED WRONG CHOICE....\nPRESS ANY KEY TO TRY AGAIN");

    getch();

    break;

    }

    system("cls");
}

}

void funda()

{

   void displayscore()

 {

 char name[20];

 float s;

 FILE *file;

 system("cls");

 file=fopen("score.txt","r");

 fscanf(file,"%s%f",&name,&s);

 printf("\n\n\t\t ");

 printf("\n\n\t\t %s has secured the Highest Score %.2f",name,s);

 printf("\n\n\t\t ");

 fclose(file);

 getch();

 }

void help()

 {

 system("cls");

 printf("\n\n\n\tThis is a simple pratice test. You'll be asked some general");

 printf("\n\n\t questions in the topic and the right answer is to be chosen among");

 printf("\n\n\the four options provided. Your score will be calculated at the");

 printf("\n\n\tend. Remember that the more quicker you give answer the more");

 printf("\n\n\ttscore you will secure. Your score will be calculated and displayed");

 printf("\n\n\tat the end and displayed. If you secure highest score, your score");

 printf("\n\n\twill be recorded. So BEST OF LUCK.");

 }

void writescore(float score, char plnm[20])

{

 float sc;

 char nm[20];

 FILE *file;

 system("cls");

 file=fopen("score.txt","r");

 fscanf(file,"%s%f",&nm,&sc);

 if (score>=sc)

   {
        sc=score;

     fclose(file);

     file=fopen("score.txt","w");

     fprintf(file,"n%.2f",plnm,sc);

     fclose(file);

   }

 }

     int countq,countr;

     int r,i;

    int pa;int nq[6];int w;

     float score;

    char choice;

     char playername[20];

     time_t initialtime,finaltime;

     system("cls");

     //randomize();

     mainhome:

     system("cls");

     puts("\n\t\t WELCOME TO I.Q. TEST PROGRAM\n\n") ;

     puts("\n\t\t-------------------------------");

     puts("\n\t\t Enter 'S' to start       ");

     puts("\n\t\t Enter 'V' to view high score  ");

     puts("\n\t\t Enter 'H' for help            ");

     puts("\n\t\t Enter 'Q' to quit             ");

     printf("\n\t\t-------------------------------\n\n\t\t  ");

     choice=toupper(getch());

     if (choice=='V')
 {

 displayscore();

 goto mainhome;

 }

     else if (choice=='Q')

 getch();

     else if (choice=='H')

 {

 help();

 getch();

 goto mainhome;

 }

    else if(choice=='S'){

     system("cls");

     printf("\n\n\n\t\t\tEnter your name...");

     printf("\n\t\t\t(only one word)\n\n\t\t\t");

     gets(playername);

     home:

     system("cls");

     initialtime=time(NULL);

     countq=countr=0;

     i=1;

     start:

     srand ( time(NULL) );

     r=rand()%23+1;

    nq[i]=r;

     for (w=0;w<i;w++)

 if (nq[w]==r) goto start;

     switch(r)
  {

  case 1:

  printf("\n\ncodes consisting of light and dark marks which may be optically read is known as \n\nA.Mnemonics \n\nB.Bar code\n\nC.Decoder\n\nD.All the above");

  countq++;

  if (toupper(getch())=='B')

   {
       printf("\n\nCorrect!!!");countr++; break;

       }

  else

         {
             printf("\n\nWrong!!! The correct answer is B.Bar code");break;

             }

  case 2:

  printf("\n\n\2.A compiler means \n\nA.A person who compiles source programs\n\nB.The same thing as a programmer\n\nC.Keypunch operator\n\nD.A program which translates source program into object program");

  countq++;

  if (toupper(getch())=='D')

   {printf("\n\nCorrect!!!");countr++; break;}

  else

         printf("\n\nWrong!!! The correct answer is D.A program which translates source program into object program");

  break;

  case 3:

  printf("\n\n3.Which of the following is used to insure the high quality of computer output?\n\nA.computer output microfilm\n\nB.output controls\n\nC.voice output systems\n\nD.liquid crystal display");

  countq++;

  if (toupper(getch())=='D')

   {printf("\n\nCorrect!!!");countr++; break;}

  else

         {printf("\n\nWrong!!! The correct answer is D.liquid crystal display");break;}

  case 4:

  printf("\n\n\n4.A double sided magnetic disk pack has six disks. Can you tell how many surfaces of this pack are normally used?\n\nA.	10\n\nB.	12\n\nC.	6\n\nD.  9	");

  countq++;

  if (toupper(getch())=='A')

   {
       printf("\n\nCorrect!!!");countr++; break;}

  else

         {
             printf("\n\nWrong!!! The correct answer is A.10");break;}

  case 5:

  printf("\n\n\nWho coordinates the sequencing of events within the central processor of a computer?\n\nA.Logic unit\n\nB.Arithmetic unit\n\nC.Register\n\nD.Control unit");

  countq++;

    if (toupper(getch())=='D')

   {
       printf("\n\nCorrect!!!");countr++; break;}
  else

         {
             printf("\n\nWrong!!! The correct answer is D.Control Unit");break;}

  case 6:

  printf("\n\n\nThe equipment with which the computer talks to its users is called a\n\nA.word processor\n\nB.peripheral\n\nC.software\n\nD.diskette");

  countq++;

if (toupper(getch())=='B' )

   {

       printf("\n\nCorrect!!!");countr++; break;}

  else

         {
             printf("\n\nWrong!!! The correct answer is B.peripheral");break;}

  case 7:

  printf("\n\n\nA computer-controlled device for training exercises that duplicates the work environment is a:\n\nA.simulator\n\nB.duplicator\n\nC.trainer\n\nD.COM device");

  countq++;

  if (toupper(getch())=='A')

   {
       printf("\n\nCorrect!!!");countr++; break;}

  else

         {
             printf("\n\nWrong!!! The correct answer is A.simulator");break;}

  case 8:

  printf("\n\n\n8.A computer program that converts an entire program into machine language at one time is called a/an\n\nA.interpreter\n\nB.simulator\n\nC.compiler\n\nD.commander");

  countq++;

  if (toupper(getch())=='C')

   {
       printf("\n\nCorrect!!!");countr++; break;}
  else

         {
             printf("\n\nWrong!!! The correct answer is C.compiler");break;}

  case 9:

  printf("\n\n\nThe computer translates the condition of each switch to a number. What number is represented by the OFF state?\n\nA.	-7\n\nB.	-3.7\n\n5C.	1\n\nD.	0");

  countq++;

  if (toupper(getch())=='D')

   {printf("\n\nCorrect!!!");countr++; break;}

  else
         {printf("\n\nWrong!!! The correct answer is D.0");break;}

  case 10:

  printf("\n\n\nFile specification books are created primarily for the use of\n\nA.systems analysts\n\nB.programmers\n\nC.operators\n\nD.managers");

   countq++;

  if (toupper(getch())=='B')

   {printf("\n\nCorrect!!!");countr++; break;}

  else

         {printf("\n\nWrong!!! The correct answer is B.programmers");break;}

  case 11:

  printf("\n\n\nWhich of the following languages is often translated to pseudo code?\n\nA.Assembly\n\nB.FORTRAN\n\nC.PASCAL\n\nD.BASIC");

  countq++;

  if (toupper(getch())=='C')

   {printf("\n\nCorrect!!!");countr++; break;}

  else

         {printf("\n\nWrong!!! The correct answer is C.PASCAL");break;}

  case 12:

  printf("\n\n\nA storage area used to store data to compensate for the difference in speed at which the different units can handle data is\n\nA.Memory\n\nB.Buffer\n\nC.Accumulator\n\nD.Address");

  countq++;

  if (toupper(getch())=='B')

   {printf("\n\nCorrect!!!");countr++; break;}

  else

         {printf("\n\nWrong!!! The correct answer is B.Buffer");break;}

  case 13:

  printf("\n\n\nTiny rings made of magnetic material that can be polarised to represent binary 1 or 0 is called\n\nA.Magnetic core\n\nB.Magnetic disk\n\nC.Card punch\n\nD.Floppy disk");

  countq++;

  if (toupper(getch())=='A')

   {printf("\n\nCorrect!!!");countr++; break;}

  else

         {printf("\n\nWrong!!! The correct answer is A.Magnetic core");break;}

  case 14:

  printf("\n\n\nThe process used to set up a programs once the system is operational is\n\nA.Operating system\n\nB.Black bon\n\nC.Boot strap\n\nD.Utility");

  if (toupper(getch())=='C')

   {printf("\n\nCorrect!!!");countr++; break;}

  else
         {printf("\n\nWrong!!! The correct answer is C.Boot strap");break;}

  case 15:

  printf("\n\n\nWhich memory stores the values of variables.\n\nA.SAM\n\nB.ROM\n\nC.RAM\n\nD.PROM");

  countq++;

  if (toupper(getch())=='C')

   {printf("\n\nCorrect!!!");countr++; break;}

  else

         {printf("\n\nWrong!!! The correct answer is C.RAM");break;}

  }

 i++;

 if (i<=5) goto start;

 finaltime=time(NULL);

 score=(float)countr/countq*100-difftime(finaltime,initialtime)/3;

 if (score<0) score=0;

 printf("\n\n\nYour Score: %.2f",score);

 if (score==100) printf("\n\nEXCELLENT!!! KEEP IT UP");

 else if (score>=80 && score<100) printf("\n\nVERY GOOD!!");

 else if (score>=60 &&score<80) printf("\n\nGOOD! BUT YOU NEED TO KNOW MORE.");

 else if (score>=40 && score<60) printf("\n\nSATISFACTORY RESULT, BUT THIS MUCH IS MUCH SUFFICIENT.");

 else printf("\n\nYOU ARE VERY POOR IN G.K.,WORK HARD");

 puts("\n\nNEXT PLAY?(Y/N)");

 if (toupper(getch())=='Y')

  goto home;

 else

  {

  writescore(score,playername);

  goto mainhome;

  }

 }

     else

 {

 printf("\n\n\t\t  Enter the right key\n\n\t\t  ");

 goto mainhome;

 }

 return 0;

}



