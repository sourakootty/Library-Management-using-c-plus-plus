//***************************************************************
//                   HEADER FILE USED IN PROJECT
//****************************************************************

#include<fstream.h>
#include<conio.h>
#include<stdio.h>
#include<process.h>
#include<string.h>
#include<iomanip.h>
#include<dos.h>
#include<stdlib.h>

//***************************************************************
//                   CLASS USED IN PROJECT
//****************************************************************


void main();
class book
{
	char bno[6];
	char bname[50];
	char aname[20];
  public:
	void create_book()
	{
		cout<<"\n\n\n\n\n\n\n\n\n";
		cout<<"\n\t\t ษออออออออออออออออออออออออออออออออออออออออออป";
		cout<<"\n\t\t บ              NEW BOOK ENTRY              บ";
		cout<<"\n\t\t บ                                          บ";
		cout<<"\n\t\t บ BOOK NO :                                บ";
		cout<<"\n\t\t ศออออออออออออออออออออออออออออออออออออออออออผ";
		gotoxy(30,14);
		cin>>bno;
		clrscr();
		cout<<"\n\n\n\n\n\n\n\n\n";
		cout<<"\n\t\t ษออออออออออออออออออออออออออออออออออออออออออป";
		cout<<"\n\t\t บ              NEW BOOK ENTRY              บ";
		cout<<"\n\t\t บ                                          บ";
		cout<<"\n\t\t บ BOOK NO :                                บ";
		cout<<"\n\t\t บ BOOK NAME:                               บ";
		cout<<"\n\t\t ศออออออออออออออออออออออออออออออออออออออออออผ";
		gotoxy(30,14);
		cout<<bno;
		gotoxy(31,15);
		gets(bname);
		clrscr();
		cout<<"\n\n\n\n\n\n\n\n\n";
		cout<<"\n\t\t ษออออออออออออออออออออออออออออออออออออออออออป";
		cout<<"\n\t\t บ              NEW BOOK ENTRY              บ";
		cout<<"\n\t\t บ                                          บ";
		cout<<"\n\t\t บ BOOK NO :                                บ";
		cout<<"\n\t\t บ BOOK NAME:                               บ";
		cout<<"\n\t\t บ AUTHOR'S NAME:                           บ";
		cout<<"\n\t\t ศออออออออออออออออออออออออออออออออออออออออออผ";
		gotoxy(30,14);
		cout<<bno;
		gotoxy(31,15);
		cout<<bname;
		gotoxy(35,16);
		gets(aname);
		cout<<"\n\n\t\t*****BOOK CREATED*****";
	}

	void show_book()
	{
		clrscr();
		cout<<"\n\n\n\n\n\n\n";
		cout<<"\n\t\t ษออออออออออออออออออออออออออออออออออออออออออป";
		cout<<"\n\t\t บ               BOOK DETAILS               บ";
		cout<<"\n\t\t บ                                          บ";
		cout<<"\n\t\t บ BOOK NO :                                บ";
		cout<<"\n\t\t บ BOOK NAME:                               บ";
		cout<<"\n\t\t บ AUTHOR'S NAME:                           บ";
		cout<<"\n\t\t ศออออออออออออออออออออออออออออออออออออออออออผ";
		gotoxy(30,12);
		cout<<bno;
		gotoxy(31,13);
		puts(bname);
		gotoxy(35,14);
		puts(aname);
	}

	void modify_book()
	{

		cout<<"\n\t MODIFY BOOK NAME : ";
		gets(bname);
		cout<<"\n\t MODIFY AUTHOR'S NAME OF BOOK : ";
		gets(aname);
	}

	char* retbno()
	{
		return bno;
	}

	void report()
	{cout<<bno<<setw(30)<<bname<<setw(30)<<aname<<endl;}


};         //class ends here




class student
{
	char admno[6];
	char name[20];
	char stbno[6];
	int token;
public:
	void create_student()
	{
		clrscr();
		cout<<"\n\n\n\n\n\n\n\n\n";
		cout<<"\n\t\t ษออออออออออออออออออออออออออออออออออออออออออป";
		cout<<"\n\t\t บ               NEW STUDENT ENTRY          บ";
		cout<<"\n\t\t บ                                          บ";
		cout<<"\n\t\t บ STUDENT ADMISSION NO :                   บ";
		cout<<"\n\t\t ศออออออออออออออออออออออออออออออออออออออออออผ";
		gotoxy(43,14);
		cin>>admno;
		clrscr();
		cout<<"\n\n\n\n\n\n\n\n\n";
		cout<<"\n\t\t ษออออออออออออออออออออออออออออออออออออออออออป";
		cout<<"\n\t\t บ               NEW STUDENT ENTRY          บ";
		cout<<"\n\t\t บ                                          บ";
		cout<<"\n\t\t บ STUDENT ADMISSION NO :                   บ";
		cout<<"\n\t\t บ STUDENT NAME :                           บ";
		cout<<"\n\t\t ศออออออออออออออออออออออออออออออออออออออออออผ";
		gotoxy(43,14);
		cout<<admno;
		gotoxy(35,15);
		gets(name);
		token=0;
		stbno[0]='/0';
		cout<<"\n\n\t\t *****STUDENT RECORD CREATED*****";
	}

	void show_student()
	{
		clrscr();
		cout<<"\n\n\n\n\n\n\n";
		cout<<"\n\t\t ษออออออออออออออออออออออออออออออออออออออออออป";
		cout<<"\n\t\t บ              STUDENT DETAILS             บ";
		cout<<"\n\t\t บ                                          บ";
		cout<<"\n\t\t บ STUDENT ADMISSION NO :                   บ";
		cout<<"\n\t\t บ STUDENT NAME:                            บ";
		cout<<"\n\t\t บ BOOKS ISSUED:                            บ";
		cout<<"\n\t\t ศออออออออออออออออออออออออออออออออออออออออออผ";
		gotoxy(43,12);
		cout<<admno;
		gotoxy(34,13);
		puts(name);
		gotoxy(34,14);
		cout<<token;
		if(token==1)
		{
			clrscr();
			cout<<"\n\n\n\n\n\n\n";
			cout<<"\n\t\t ษออออออออออออออออออออออออออออออออออออออออออป";
			cout<<"\n\t\t บ              STUDENT DETAILS             บ";
			cout<<"\n\t\t บ                                          บ";
			cout<<"\n\t\t บ STUDENT ADMISSION NO :                   บ";
			cout<<"\n\t\t บ STUDENT NAME:                            บ";
			cout<<"\n\t\t บ BOOKS ISSUED:                            บ";
			cout<<"\n\t\t บ BOOK NO:                                 บ";
			cout<<"\n\t\t ศออออออออออออออออออออออออออออออออออออออออออผ";
			gotoxy(43,12);
			cout<<admno;
			gotoxy(34,13);
			puts(name);
			gotoxy(34,14);
			cout<<token;
			gotoxy(29,15);
			cout<<stbno;

		}

	}

	void modify_student()
	{

		cout<<"\n\t MODIFY STUDENT NAME : ";
		gets(name);
	}

	char* retadmno()
	{
		return admno;
	}

	char* retstbno()
	{
		return stbno;
	}

	int rettoken()
	{
		return token;
	}

	void addtoken()
	{token=1;}

	void resettoken()
	{token=0;}

	void getstbno(char t[])
	{
		strcpy(stbno,t);
	}

	void report()
	{cout<<"\t"<<admno<<setw(25)<<name<<setw(10)<<token<<endl;}

};         //class ends here




//***************************************************************
//    	global declaration for stream object, object
//****************************************************************

fstream fp,fp1;
book bk;
student st;
int start=1;


//***************************************************************
//    	function to write in file
//****************************************************************

void write_book()
{
	char ch;
	fp.open("book.dat",ios::out|ios::app);
	do
	{
		clrscr();
		bk.create_book();
		fp.write((char*)&bk,sizeof(book));
		cout<<"\n\n\t\tDO YOU WANT TO ADD MORE RECORD..(y/n?): ";
		ch=getche();
		delay(500);
	}while(ch=='y'||ch=='Y');
	fp.close();
}

void write_student()
{
	char ch;
	fp.open("student.dat",ios::out|ios::app);
	do
	{
		st.create_student();
		fp.write((char*)&st,sizeof(student));
		cout<<"\n\n\t\tDO YOU WANT TO ADD MORE RECORD..(y/n?): ";
		ch=getche();
		delay(500);
	}while(ch=='y'||ch=='Y');
	fp.close();
}


//***************************************************************
//    	function to read specific record from file
//****************************************************************


void display_spb(char n[])
{

	int flag=0;
	fp.open("book.dat",ios::in);
	while(fp.read((char*)&bk,sizeof(book)))
	{
		if(strcmpi(bk.retbno(),n)==0)
		{
			bk.show_book();
			flag=1;
		}
	}

	fp.close();
	if(flag==0)
		cout<<"\n\n\t\t*****BOOK DOES NOT EXIST*****";
	getch();
}

void display_sps(char n[])
{

	int flag=0;
	fp.open("student.dat",ios::in);
	while(fp.read((char*)&st,sizeof(student)))
	{
		if((strcmpi(st.retadmno(),n)==0))
		{
			st.show_student();
			flag=1;
		}
	}

	fp.close();
	if(flag==0)
		cout<<"\n\n\t\t *****STUDENT DOES NOT EXIST*****";
	getch();
}


//***************************************************************
//    	function to modify record of file
//****************************************************************


void modify_book()
{
	char n[6];
	int found=0;
	clrscr();
	cout<<"\n\n\n\n\n\n\n\n\n";
	cout<<"\n\t\t ษออออออออออออออออออออออออออออออออออออออออออป";
	cout<<"\n\t\t บ           MODIFY BOOK RECORD             บ";
	cout<<"\n\t\t บ                                          บ";
	cout<<"\n\t\t บ BOOK NO :                                บ";
	cout<<"\n\t\t ศออออออออออออออออออออออออออออออออออออออออออผ";
	gotoxy(30,14);
	cin>>n;
	fp.open("book.dat",ios::in|ios::out);
	while(fp.read((char*)&bk,sizeof(book)) && found==0)
	{
		if(strcmpi(bk.retbno(),n)==0)
		{
			bk.show_book();
			cout<<"\n\n\t\t  ENTER THE NEW DETAILS OF BOOK"<<endl;
			bk.modify_book();
			int pos=-1*sizeof(bk);
			fp.seekp(pos,ios::cur);
			fp.write((char*)&bk,sizeof(book));
			cout<<"\n\n\t\t *****RECORD UPDATED*****";
			found=1;
		}
	}

	fp.close();
	if(found==0)
		cout<<"\n\n\t\t *****RECORD NOT FOUND***** ";
	getch();
}


void modify_student()
{
	char n[6];
	int found=0;
	clrscr();
	cout<<"\n\n\n\n\n\n\n\n\n";
	cout<<"\n\t\t ษออออออออออออออออออออออออออออออออออออออออออป";
	cout<<"\n\t\t บ           MODIFY STUDENT RECORD          บ";
	cout<<"\n\t\t บ                                          บ";
	cout<<"\n\t\t บ STUDENT ADMISSION NO :                   บ";
	cout<<"\n\t\t ศออออออออออออออออออออออออออออออออออออออออออผ";
	gotoxy(43,14);
	cin>>n;
	fp.open("student.dat",ios::in|ios::out);
	while(fp.read((char*)&st,sizeof(student)) && found==0)
	{
		if(strcmpi(st.retadmno(),n)==0)
		{
			st.show_student();
			cout<<"\n\n\t\t  ENTER THE NEW DETAILS OF STUDENT"<<endl;
			st.modify_student();
			int pos=-1*sizeof(st);
			fp.seekp(pos,ios::cur);
			fp.write((char*)&st,sizeof(student));
			cout<<"\n\n\t\t*****RECORD UPDATED*****";
			found=1;
		}
	}

	fp.close();
	if(found==0)
		cout<<"\n\n\t\t *****RECORD NOT FOUND***** ";
	getch();
}

//***************************************************************
//    	function to delete record of file
//****************************************************************


void delete_student()
{
	char n[6];
	int flag=0;
	clrscr();
	cout<<"\n\n\n\n\n\n\n\n\n";
	cout<<"\n\t\t ษออออออออออออออออออออออออออออออออออออออออออป";
	cout<<"\n\t\t บ              DELETE STUDENT              บ";
	cout<<"\n\t\t บ                                          บ";
	cout<<"\n\t\t บ STUDENT ADMISSION NO :                   บ";
	cout<<"\n\t\t ศออออออออออออออออออออออออออออออออออออออออออผ";
	gotoxy(43,14);
	cin>>n;
	fp.open("student.dat",ios::in|ios::out);
	fstream fp2;
	fp2.open("Temp.dat",ios::out);
	fp.seekg(0,ios::beg);
	while(fp.read((char*)&st,sizeof(student)))
	{
		if(strcmpi(st.retadmno(),n)!=0)
			fp2.write((char*)&st,sizeof(student));
		else
			flag=1;
	}

	fp2.close();
	fp.close();
	remove("student.dat");
	rename("Temp.dat","student.dat");
	if(flag==1)
		cout<<"\n\n\t\t *****RECORD DELETED*****";
	else
		cout<<"\n\n\t\t *****RECORD NOT FOUND*****";
	getch();
}


void delete_book()
{
	char n[6];
	int flag=0;
	clrscr();
	cout<<"\n\n\n\n\n\n\n\n\n";
	cout<<"\n\t\t ษออออออออออออออออออออออออออออออออออออออออออป";
	cout<<"\n\t\t บ               DELETE BOOK                บ";
	cout<<"\n\t\t บ                                          บ";
	cout<<"\n\t\t บ BOOK NO :                                บ";
	cout<<"\n\t\t ศออออออออออออออออออออออออออออออออออออออออออผ";
	gotoxy(30,14);
	cin>>n;
	fp.open("book.dat",ios::in|ios::out);
	fstream fp2;
	fp2.open("Temp.dat",ios::out);
	fp.seekg(0,ios::beg);
	while(fp.read((char*)&bk,sizeof(book)))
	{
		if(strcmpi(bk.retbno(),n)!=0)
		{
			fp2.write((char*)&bk,sizeof(book));
		}
		else
			flag=1;
	}

	fp2.close();
	fp.close();
	remove("book.dat");
	rename("Temp.dat","book.dat");
	if(flag==1)
		cout<<"\n\n\t\t *****RECORD DELETED*****";
	else
		cout<<"\n\n\t\t *****RECORD NOT FOUND*****";
	getch();
}



//***************************************************************
//    	function to display all students list
//****************************************************************

void display_alls()
{
	clrscr();
	fp.open("student.dat",ios::in);
	if(!fp)
	{
		cout<<"\n\n\t\tERROR!!! FILE COULD NOT BE OPEN ";
		getch();
		return;
	}

	cout<<"\n\n\t\t\tSTUDENT LIST\n\n";
	cout<<"==================================================================\n";
	cout<<"\tADMISSION NO."<<setw(10)<<"NAME"<<setw(20)<<"BOOK ISSUED\n";
	cout<<"==================================================================\n";

	while(fp.read((char*)&st,sizeof(student)))
	{
		st.report();
	}

	fp.close();
	getch();
}


//***************************************************************
//    	function to display Books list
//****************************************************************

void display_allb()
{
	clrscr();
	fp.open("book.dat",ios::in);
	if(!fp)
	{
		cout<<"ERROR!!! FILE COULD NOT BE OPEN ";
		getch();
		return;
	}

	cout<<"\n\n\t\tBOOK LIST\n\n";
	cout<<"=========================================================================\n";
	cout<<"BOOK NUMBER"<<setw(20)<<"BOOK NAME"<<setw(25)<<"AUTHOR\n";
	cout<<"=========================================================================\n";

	while(fp.read((char*)&bk,sizeof(book)))
	{
		bk.report();
	}
	fp.close();
	getch();
}



//***************************************************************
//    	function to issue book
//****************************************************************

void book_issue()
{
	char sn[6],bn[6];
	int found=0,flag=0;
	clrscr();
	cout<<"\n\n\n\n\n\n\n\n\n";
	cout<<"\n\t\t ษอออออออออออออออออออออออออออออออออออออออป";
	cout<<"\n\t\t บ               BOOK ISSUE              บ";
	cout<<"\n\t\t บ                                       บ";
	cout<<"\n\t\t บ ENTER THE STUDENT'S ADMISSION NO :    บ";
	cout<<"\n\t\t ศอออออออออออออออออออออออออออออออออออออออผ";
	gotoxy(55,14);
	cin>>sn;
	fp.open("student.dat",ios::in|ios::out);
	fp1.open("book.dat",ios::in|ios::out);
	while(fp.read((char*)&st,sizeof(student)) && found==0)
	{
		if(strcmpi(st.retadmno(),sn)==0)
		{
			found=1;
			if(st.rettoken()==0)
			{
				clrscr();
				cout<<"\n\n\n\n\n\n\n\n\n";
				cout<<"\n\t\t ษอออออออออออออออออออออออออออออออออออออออป";
				cout<<"\n\t\t บ               BOOK ISSUE              บ";
				cout<<"\n\t\t บ                                       บ";
				cout<<"\n\t\t บ ENTER THE STUDENT'S ADMISSION NO :    บ";
				cout<<"\n\t\t บ ENTER BOOK NO :                       บ";
				cout<<"\n\t\t ศอออออออออออออออออออออออออออออออออออออออผ";
				gotoxy(55,14);
				cout<<sn;
				gotoxy(36,15);
				cin>>bn;
				while(fp1.read((char*)&bk,sizeof(book))&& flag==0)
				{
					if(strcmpi(bk.retbno(),bn)==0)
					{
						bk.show_book();
						flag=1;
						st.addtoken();
						st.getstbno(bk.retbno());
						int pos=-1*sizeof(st);
						fp.seekp(pos,ios::cur);
						fp.write((char*)&st,sizeof(student));
						cout<<"\n\n\t\t *****BOOK ISSUED SUCCESSFULLY*****";
						cout<<"\n\nPLEASE NOTE: submit within 15 days fine Rs. 1 for each day after 15 days period";
					}
				}
				if(flag==0)
					cout<<"\n\n\t\t *****BOOK NO DOES NOT EXIST*****";
			}
			else
				cout<<"\n\n\t\t *****YOU HAVE NOT RETURNED LAST BOOK***** ";

		}
	}
	if(found==0)
		cout<<"\n\n\t\t *****STUDENT RECORD NOT EXIST*****";
	getch();
	fp.close();
	fp1.close();
}

//***************************************************************
//    	function to deposit book
//****************************************************************

void book_deposit()
{
    char sn[6],bn[6];
    int found=0,flag=0,day,fine;
    clrscr();
    cout<<"\n\n\n\n\n\n\n\n\n";
    cout<<"\n\t\t ษอออออออออออออออออออออออออออออออออออออออป";
    cout<<"\n\t\t บ             BOOK DEPOSITE             บ";
    cout<<"\n\t\t บ                                       บ";
    cout<<"\n\t\t บ ENTER THE STUDENT'S ADMISSION NO :    บ";
    cout<<"\n\t\t ศอออออออออออออออออออออออออออออออออออออออผ";
    gotoxy(55,14);
    cin>>sn;
    fp.open("student.dat",ios::in|ios::out);
    fp1.open("book.dat",ios::in|ios::out);
    while(fp.read((char*)&st,sizeof(student)) && found==0)
       {
	    if(strcmpi(st.retadmno(),sn)==0)
	    {
		    found=1;
		    if(st.rettoken()==1)
		    {
			while(fp1.read((char*)&bk,sizeof(book))&& flag==0)
			{
			   if(strcmpi(bk.retbno(),st.retstbno())==0)
			{
				bk.show_book();
				flag=1;
				cout<<"\n\n\t\t BOOK DEPOSITED IN NO. OF DAYS: ";
				cin>>day;
				if(day>15)
				{
				   fine=(day-15)*1;
				   cout<<"\n\t\t *****Fine has to deposited Rs: "<<fine<<" *****";
				}
					st.resettoken();
					int pos=-1*sizeof(st);
					fp.seekp(pos,ios::cur);
					fp.write((char*)&st,sizeof(student));
					cout<<"\n\t\t *****BOOK DEPOSITED SUCCESSFULLY*****";
			}
		    }
		  if(flag==0)
		    cout<<"\n\n\t\t *****BOOK NO DOES NOT EXIST*****";
		      }
		 else
			cout<<"\n\n\t\t *****NO BOOK IS ISSUED..PLEASE CHECK!!";
		}
	   }
      if(found==0)
	cout<<"\n\n\t\t *****STUDENT RECORD NOT EXIST*****";
	getch();
  fp.close();
  fp1.close();
  }




//***************************************************************
//    	INTRODUCTION FUNCTION
//****************************************************************

void intro()
{
	textcolor(14);
	clrscr();
	cout<<"\n\n\n\n\n\n\n\n\n\n";
	cout<<"\n\t\t   ษออออออออออออออออออออออออออออออออออออออป";
	cout<<"\n\t\t   บ              WELCOME TO              บ ";
	cout<<"\n\t\t   บ       LIBRARY MANAGEMENT SYSTEM      บ ";
	cout<<"\n\t\t   ศออออออออออออออออออออออออออออออออออออออผ                      ";
	delay(2000);
}



//***************************************************************
//    	ADMINISTRATOR MENU FUNCTION
//****************************************************************

void admin_menu()
{
	textcolor(10);
	clrscr();
	char ch2;
	cout<<"\n\n\n\n\n";
	cout<<"\n\t\t ษอออออออออออออออออออออออออออออออออออออออออป ";
	cout<<"\n\t\t บ            ADMINISTRATOR MENU           บ ";
	cout<<"\n\t\t บ                                         บ ";
	cout<<"\n\t\t บ 1.CREATE STUDENT RECORD                 บ ";
	cout<<"\n\t\t บ 2.DISPLAY ALL STUDENTS RECORD           บ ";
	cout<<"\n\t\t บ 3.DISPLAY SPECIFIC STUDENT RECORD       บ ";
	cout<<"\n\t\t บ 4.MODIFY STUDENT RECORD                 บ ";
	cout<<"\n\t\t บ 5.DELETE STUDENT RECORD                 บ ";
	cout<<"\n\t\t บ 6.CREATE BOOK                           บ ";
	cout<<"\n\t\t บ 7.DISPLAY ALL BOOKS                     บ ";
	cout<<"\n\t\t บ 8.DISPLAY SPECIFIC BOOK                 บ ";
	cout<<"\n\t\t บ 9.MODIFY BOOK                           บ ";
	cout<<"\n\t\t บ D.DELETE BOOK                           บ ";
	cout<<"\n\t\t บ M.BACK TO MAIN MENU                     บ ";
	cout<<"\n\t\t ศอออออออออออออออออออออออออออออออออออออออออผ\n ";
	cout<<"\n\t\t     PLEASE ENTER YOUR CHOICE (1-9 & D/M): ";
	ch2=getche();
	delay(500);
	switch(ch2)
	{
		case '1': clrscr();
			write_student();break;
		case '2': display_alls();break;
		case '3':
			char num[6];
			clrscr();
			cout<<"\n\n\t\tPLEASE ENTER THE ADMISSION NO : ";
			cin>>num;
			display_sps(num);
			break;
		case '4': modify_student();break;
		case '5': delete_student();break;
		case '6': clrscr();
			write_book();break;
		case '7': display_allb();break;
		case '8': {
			char num[6];
			clrscr();
			cout<<"\n\n\t\tPLEASE ENTER THE BOOK NO :  ";
			cin>>num;
			display_spb(num);
			break;
			}
		case '9': modify_book();break;
		case 'D': delete_book();break;
		case 'M': main();
		default:cout<<"\a";
	}
	admin_menu();
}

//***************************************************************
//      THE LOADING FUNCTION OF PROGRAM
//***************************************************************
void load()
{
	clrscr();
	int i,j,k;
	for (i=0;i<51;i++)
	{

		clrscr();
		textcolor(i);
		cout<<"\n\n\n\n\n\n\n\n\n\n\t\t\t\tPROGRAM IS LOADING......\n\t\t";
		for (j=0;j<i;j++)
		{

			cout<<"Ü";
		}
		for (k=j;k<50;k++)
		{
			if(k==0)
			cout<<"ฺ";
			cout<<"ฤ";
			if (k==49)
			cout<<"ฟ";
		}
		cout<<"\n\t\t";
		for (j=0;j<i;j++)
		{
			cout<<"฿";
		}
		for (k=j;k<50;k++)
		{
			if(k==0)
			cout<<"ภ";
			cout<<"ฤ";
			if (k==49)
			cout<<"ู";
		}
		cout<<"\n\t\t\t";
		for (k=j;k<50;k++);
		{
			cout<<"\t\t"<<i*2<<"%";
		}
		if(i==0)
		delay(2000);
		else
		delay(100);


	}
	delay(2000);

}

//***************************************************************
//    	THE MAIN FUNCTION OF PROGRAM
//****************************************************************


void main()
{
	char ch;
	if (start==1)
	{
	intro();
	load();
	start=0;
	}
	do
	{
		textcolor(13);
		clrscr();
		cout<<"\n\n\n\n\n\n\n";
		cout<<"\n\t\t ษออออออออออออออออออออออออออออออออออออออป ";
		cout<<"\n\t\t บ                MAIN MENU             บ ";
		cout<<"\n\t\t บ                                      บ ";
		cout<<"\n\t\t บ 1. BOOK ISSUE                        บ ";
		cout<<"\n\t\t บ 2. BOOK DEPOSIT                      บ ";
		cout<<"\n\t\t บ 3. ADMINISTRATOR MENU                บ ";
		cout<<"\n\t\t บ 4. EXIT                              บ ";
		cout<<"\n\t\t ศออออออออออออออออออออออออออออออออออออออผ ";
		cout<<"\n\n\t\t    PLEASE SELECT YOUR OPTION (1-4): ";
		ch=getche();
		delay(500);
	  	switch(ch)
	  	{
			case '1':clrscr();
				 book_issue();
			   	 break;
		  	case '2':book_deposit();
			    	 break;
		  	case '3':admin_menu();
				 break;
		  	case '4':exit(0);
		  	default :cout<<"\a";
		}
    	}while(ch!='4');
}

//***************************************************************
//    			END OF PROJECT
//***************************************************************
