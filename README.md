﻿# flightManagement
TABLE OF CONTENTS


S. No	CONTENTS	PAGE.NO
1.	Problem Statement	5
2.	Modules Description	6
3.	UML Diagrams	7
	3.1 Use case Diagram	8
	3.2 Class Diagram	9
	3.3 Sequence Diagram	10
	3.4 Collaboration Diagram	11
	3.5 State Chart Diagram	12
	3.6 Activity Diagram	13
	3.7 Package Diagram	14
	3.8 Component Diagram	15
	3.9 Deployment Diagram	16
4.	Coding	17
 


5.	Output	32
6.	Conclusion and Results	35
	References	36
 


1.	PROBLEM STATEMENT

•	Airline booking systems are an essential part of the aviation industry, allowing customers to book flights, select seats, and manage their travel itineraries.

•	However, several issues plague the airline booking system, leading to inefficiencies, security breaches, and customer dissatisfaction

•	This system is a user-friendly kind of system that can be easily modified.

•	The system provides you an efficient way for booking a flight ticket.

•	It will give you a convenient way to record all the passenger information.

•	By using this system, it will lessen the problem for booking a wrong flight detail to the passenger.



PROJECT NAME	AIRLINE BOOKING SYSTEM
ABSTRACT	Airline booking system UML Diagrams are used to represent the student system as well as its primary users, roles, activities, or
classes.
UML DIAGRAM	Sequence Diagram, Activity Diagram, Class Diagram, Use Case Diagram
USERS	Flight Owners, Travelers
TOOLS USED	Diagram tools that prove UML diagram symbols: star UML
 


2.	MODULES DESCRIPTION


Flight Inventory Management: This module manages flight schedules, availability, and pricing. It allows airlines to add or remove flights, update seat availability, and set pricingrules based on demand.
Reservation Management: This module manages the booking process, including seat selection, passenger information, payment processing, and itinerary creation. It enables airlines to manage bookings from multiple channels, such as online, mobile, or travel agents.
Check-in Management: This module manages the check-in process, including passenger identification, baggage handling, and boarding pass issuance. It enables airlines to streamline the check-in process and reduce waiting times for customers.
Loyalty Management: This module manages the airline's loyalty programs, such as frequent flyer programs, reward points, and tier-based benefits. It enables airlines to provide personalized services and incentives to loyal customers.
Revenue Management: This module manages the pricing strategy and revenue optimization for airlines. It uses advanced algorithms to predict demand, set pricing, and maximize revenue.
Ancillary Services Management: This module manages additional services, such as baggage fees, seat upgrades, in-flight meals, and entertainment. It enables airlines to generate additional revenue streams and provide customized services to customers.
Integration Management: This module manages the integration of various modules and systems used in the airline booking system, such as payment gateways, airline reservation systems, and third-party APIs.
 




3.	UML DIAGRAM

Unified Modelling Language (UML) diagrams are visual representations used for modelling object-oriented software systems. UML diagrams provide a standardized way to visualize and communicate software designs, making them easier to understand and implement.
There are two main types of UML diagrams: behavioral and structural. Structural UML diagrams describe the static structure of a system, including its components, classes, interfaces, and relationships between them. Behavioral UML diagrams describe the dynamic behavior of a system, including the interactions between objects and the changes in their states.

Structural UML Diagrams include:
1.	Class Diagrams
2.	Object Diagrams
3.	Component Diagrams
4.	Deployment Diagrams
5.	Package Diagrams


Behavioral UML Diagrams include:
1.	Use Case Diagrams
2.	Sequence Diagrams
3.	Collaboration Diagrams
4.	State Diagrams
5.	Activity Diagrams
 


3.1	USE CASE DIAGRAM
A use case diagram is a type of UML behavior diagram that represents the interactions between actors and a system to achieve specific goals or tasks. It visually depicts the different use cases and actors involved in a system, providing an overview of the system's functionalities and requirements.
The notations used are:



A use case diagram of an airline booking system illustrates the different types of actors (such as passengers, airline staff, and system administrators) and the various actions they can perform (such as searching for flights, booking tickets, and managing reservations) within the system.
 


3.2	CLASS DIAGRAM
A class diagram is a UML diagram that depicts the structure of a system by showing the classes, objects, interfaces, and their relationships. It provides a static view of the system and is used to visualize the objects and their interactions within the system. Classes are represented as boxes with their attributes and methods, and relationships between classes are shown using lines with various symbols.

A class diagram of an airline booking system shows the different classes, their attributes, and the relationships between them, such as passenger, flight, reservation, and payment classes.
 


3.3	SEQUENCE DIAGRAM
A sequence diagram is a type of UML diagram that illustrates the interactions between objects or components in a system over time. It depicts the order in which objects interact with each other to achieve a specific task or goal. It is a dynamic view of the system that shows the flow of messages exchanged between objects and the timing of their interactions.




A sequence diagram of an airline booking system illustrates the interactions between different objects and actors involved in booking a flight, such as searching for flights, selecting a seat, making a payment, and generating a ticket.
 


3.4	COLLABORATION DIAGRAM
A collaboration diagram is a type of UML diagram that shows the interactions between objects or components in a system to achieve a specific task or goal. It is a visual representation of the collaboration and communication among the objects in a system.


A collaboration diagram of an airline booking system depicts the objects and their associations, messages exchanged between them, and the sequence of events that occur during the booking process, such as booking a flight, selecting a seat, and making a payment.
 


3.5	STATE CHART DIAGRAM
A state chart diagram is a type of UML diagram that shows the different states and transitions of an object or system over time. It is a visual representation of the behavior of an object or system, and how it responds to external stimuli or events.
The notations used are:


 

The state chart diagram illustrates the various states that an object or entity can be in during the booking process, such as available, reserved, confirmed, and cancelled, and the events or triggers that cause the object to transition between these states.
 


3.6	ACTIVITY DIAGRAM
An activity diagram is a type of UML diagram that shows the workflow or activities of a system or process. It depicts the sequence of activities, decision points, and the flow of control or data between them.


An activity diagram of an airline booking system illustrates the flow of activities involved in booking a flight, such as searching for flights, selecting a seat, making a payment, and generating a ticket, and the decision points or conditions that determine the path taken through the process.
 


3.7	PACKAGE DIAGRAM
A package diagram is a type of UML diagram that shows the dependencies and organization of the packages or modules in a system. It depicts the relationships between packages and the elements they contain, such as classes, interfaces, and other packages.
The notations used are:







A package diagram of an airline booking system organizes the various components and modules of the system into logical groups or packages, showing the dependencies and relationships between them, such as booking, payment, reservation, and flight packages.
 


3.8	COMPONENT DIAGRAM
A component diagram is a type of UML diagram that shows the components, interfaces, and dependencies of a system or software application. It depicts the physical or logical components and their relationships, as well as the interfaces between them.



A component diagram of an airline booking system illustrates the physical components and modules of the system, such as databases, servers, APIs, and interfaces, and the dependencies and relationships between them, showing how they work together to provide the system's functionality.
 


3.9	DEPLOYMENT DIAGRAM
A deployment diagram is a type of UML diagram that shows the physical or logical deployment of a system or software application. It depicts the hardware or software nodes, the artifacts or components deployed on them, and the communication and dependencies between them.

A deployment diagram of an airline booking system illustrates the physical deployment of the system's components and modules onto hardware or software nodes, such as servers, databases, and devices, and the connections and communication paths between them, showing how the system is deployed in a real-world environment.
 



4.	CODING

#include <iostream> #include<fstream> #include<string.h> using namespace std;

int glob=0; int global=10;

class d_booking
{
protected: int pnr;
char f_d[10],toja[7],tojd[7]; long int doj;
int choice,src,dest; public:
void d_pnr()
{
glob++; pnr=glob;
}
int j_detail()
{
cout << "\nEnter Date of Flight(DDMMYY)." << "Please enter a valid date." << endl; cin >> doj;
cout << "1.Delhi(1) \t2.Bangalore(2) \t3.Mumbai(3) \t4.Chennai(4)" << endl << endl; cout << "\tEnter Source" << endl;
cin >> src;
cout << "\tEnter destination" << endl; cin >> dest;
if((src==1 && dest==2) || (src==2 && dest==1))//condition
{
cout << "\t \t \tFlights Found" << endl << endl;
cout << "Airline:\tDeparture:\tArrival:\tPrice:\t\tCategory:\n"; cout << "1.Spicejet(1)\t08:00\t\t11:05\t\t$100\t\tRefundable\n"; cout << "2.Indigo(2)\t14:00\t\t17:05\t\t$100\t\tRefundable\n"; cout << "3.Air India(3)\t19:00\t\t22:05\t\t$100\t\tRefundable\n";
}
 


else if((src==1 && dest==3) || (src==3 && dest==1))//condition
{
cout << "\t \t \tFlights Found" << endl << endl;
cout << "Airline:\tDeparture:\tArrival:\tPrice:\t\tCategory:\n"; cout << "1.Spicejet(1)\t08:00\t\t11:05\t\t$100\t\tRefundable\n"; cout << "2.Indigo(2)\t14:00\t\t17:05\t\t$100\t\tRefundable\n"; cout << "3.Air India(3)\t19:00\t\t22:05\t\t$100\t\tRefundable\n";
}

else if((src==1 && dest==4) || (src==4 && dest==1))//condition
{
cout << "\t \t \tFlights Found" << endl << endl;
cout << "Airline:\tDeparture:\tArrival:\tPrice:\t\tCategory:\n"; cout << "1.Spicejet(1)\t08:00\t\t11:05\t\t$200\t\tRefundable\n"; cout << "2.Indigo(2)\t14:00\t\t17:05\t\t$250\t\tRefundable\n"; cout << "3.Air India(3)\t19:00\t\t22:05\t\t$300\t\tRefundable\n";
}

else if((src==2 && dest==3) || (src==3 && dest==2))//condition
{
cout << "\t \t \tFlights Found" << endl << endl;
cout << "Airline:\tDeparture:\tArrival:\tPrice:\t\tCategory:\n"; cout << "1.Spicejet(1)\t08:00\t\t11:05\t\t$140\t\tRefundable\n"; cout << "2.Indigo(2)\t14:00\t\t17:05\t\t$150\t\tRefundable\n"; cout << "3.Air India(3)\t19:00\t\t22:05\t\t$180\t\tRefundable\n";
}

else if((src==2 && dest==4) || (src==4 && dest==2))//condition
{
cout << "\t \t \tFlights Found" << endl << endl;
cout << "Airline:\tDeparture:\tArrival:\tPrice:\t\tCategory:\n"; cout << "1.Spicejet(1)\t08:00\t\t11:05\t\t$200\t\tRefundable\n"; cout << "2.Indigo(2)\t14:00\t\t17:05\t\t$150\t\tRefundable\n"; cout << "3.Air India(3)\t19:00\t\t22:05\t\t$200\t\tRefundable\n";
}
else if((src==3 && dest==4) || (src==4 && dest==3))//condition
{
cout << "\t \t \tFlights Found" << endl << endl;
cout << "Airline:\tDeparture:\tArrival:\tPrice:\t\tCategory:\n"; cout << "1.Spicejet(1)\t08:00\t\t11:05\t\t$180\t\tRefundable\n"; cout << "2.Indigo(2)\t14:00\t\t17:05\t\t$50\t\tRefundable\n"; cout << "3.Air India(3)\t19:00\t\t22:05\t\t$150\t\tRefundable\n";
 


}
else if(src==dest)//condition
{
cout << "\nDestination can't be same.\nTry again\n\n\n" << endl; return j_detail();
}
else
{
cout <<"\nWrong input entered\nTry again\n\n\n" << endl; return j_detail();
}

}

int select_flight()
{ cout << "\nEnter your choice" << endl; cin >> choice;
switch(choice)
{
case 1:
cout << "\nFlight selected:"<<endl; cout << "Spicejet"<<endl; strcpy(f_d,"Spicejet");
cout << "Departure Time : 08:00"<<endl; cout<<"Arrival Time: 11:05"<<endl; strcpy(tojd,"8:00");
strcpy(toja,"11:05"); break;
case 2:
cout << "\nFlight selected:"<<endl; cout << "Indigo"<<endl; strcpy(f_d,"Indigo");
cout << "Departure Time : 14:00"<<endl; cout<<"Arrival Time: 17:05"<<endl; strcpy(tojd,"14:00");
strcpy(toja,"17:05"); break;
case 3:
cout << "\nFlight selected:" << endl; cout << "Air India" << endl; strcpy(f_d,"Air India");
cout << "Departure Time : 19:00" << endl;
 


cout<<"Arrival Time: 22:05" << endl; strcpy(tojd,"19:00");
strcpy(toja,"22:05"); break;
default:
cout << "Wrong input entered.\nTry again" << endl; return select_flight();
}
}
};

class i_booking
{
protected: int pnri;
char f_i[10],tojai[7],tojdi[7]; long int doji;
int srci,desti,choicei; public:
void i_pnr()
{
global++; pnri=global;
}

int j_detaili()
{
cout << "Enter Date of Flight(DDMMYY)." << "Please enter a valid date." << endl;; cin >> doji;
cout << "1.London(1) \2.Dubai(2) \3.Quatar(3) \4.Singapore(4) \5.Thailand(5) " << endl
<< endl;
cout << "\tEnter Source" << endl; cin >> srci;
cout << "\nEnter destination" ; cin >> desti;
cout << "\t \t \tFlights Found" << endl << endl;

if((srci==1 && desti==3) || (srci==3 && desti==1))//condition
{
cout << "Airline:\tDeparture:\tArrival:\tPrice:\t\tCategory:\n"; cout << "1.Speed(1)\t10:00\t\t14:05\t\t$250\tRefundable\n"; cout << "2.Zoom(2)\t14:00\t\t18:05\t\t$215\tRefundable\n";
 


cout << "3.Fly Away(3)\t18:00\t\t22:05\t\t$240\tRefundable\n";
}

else if((srci==1 && desti==4) || (srci==4 && desti==1))//condition
{
cout << "Airline:\tDeparture:\tArrival:\tPrice:\t\tCategory:\n"; cout << "1.Speed(1)\t10:00\t\t14:05\t\t$255\tRefundable\n"; cout << "2.Zoom(2)\t14:00\t\t18:05\t\t$213\tRefundable\n";
cout << "3.Fly Away(3)\t18:00\t\t22:05\t\t$246\t\tRefundable\n";
}

else if((srci==1 && desti==5) || (srci==5 || desti==1))//condition
{
cout << "Airline:\tDeparture:\tArrival:\tPrice:\t\tCategory:\n"; cout << "1.Speed(1)\t10:00\t\t14:05\t\t$250\tRefundable\n"; cout << "2.Zoom(2)\t14:00\t\t18:05\t\t$290\tRefundable\n"; cout << "3.Fly Away(3)\t18:00\t\t22:05\t\t$420\tRefundable\n";
}

else if((srci==2 && desti==3) || (srci==3 && desti==2))//condition
{
cout << "Airline:\tDeparture:\tArrival:\tPrice:\t\tCategory:\n"; cout << "1.Speed(1)\t10:00\t\t14:05\t\t$170\tRefundable\n"; cout << "2.Zoom(2)\t14:00\t\t18:05\t\t$140\tRefundable\n"; cout << "3.Fly Away(3)\t18:00\t\t22:05\t\t$170\tRefundable\n";
}

else if((srci==2 && desti==4) || (srci==4 && desti==2))//condition
{
cout << "Airline:\tDeparture:\tArrival:\tPrice:\t\tCategory:\n"; cout << "1.Speed(1)\t10:00\t\t14:05\t\t$100\tRefundable\n"; cout << "2.Zoom(2)\t14:00\t\t18:05\t\t$120\tRefundable\n";
cout << "3.Fly Away(3)\t18:00\t\t22:05\t\t$250\tRefundable\n";	}

else if(srci==2 && desti==5 || (srci==5 && desti==2))//condition
{
cout << "Airline:\tDeparture:\tArrival:\tPrice:\t\tCategory:\n"; cout << "1.Speed(1)\t10:00\t\t14:05\t\t$140\tRefundable\n"; cout << "2.Zoom(2)\t14:00\t\t18:05\t\t$120\tRefundable\n"; cout << "3.Fly Away(3)\t18:00\t\t22:05\t\t$140\tRefundable\n";

}
 


else if(srci==desti)//condition
{
cout << "wrong input entered.\nTry again\n\n\n"<< endl; return j_detaili();
}
else//condition
{
cout << "Wrong input entered.\nTry again\n\n\n"; return j_detaili();
}

}

int select_flighti()
{
cout << "\nEnter your choice" << endl; cin >> choicei;
switch(choicei)
{
case 1:
cout << "\nFlight selected:" <<endl; cout << "Speed" << endl; strcpy(f_i,"Speed");
cout << "Departure Time: 10:00" << endl; cout << "Arrival Time: 14:05" << endl; strcpy(tojdi,"10:00");
strcpy(tojai,"14:05"); break;
case 2:
cout << "\nFlight selected:" << endl; cout << "Zoom" << endl; strcpy(f_i,"Zoom");
cout << "Departure Time: 14:00" << endl; cout << "Arrival Time: 18:05" << endl; strcpy(tojdi,"14:00");
strcpy(tojai,"18:05"); break;
case 3:
cout << "\nFlight selected:" << endl; cout << "Fly Away" << endl; strcpy(f_i,"Fly Away");
cout << "Departure Time : 18:00" << endl;
 


cout << "Arrival Time: 22:05" << endl; strcpy(tojdi,"18:00");
strcpy(tojai,"22:05"); break;
default:
cout << "Wrong input entered" << endl; return select_flighti();
}
}
};


class passenger: public d_booking,public i_booking
{
protected:
char f_name[20],l_name[20],email[50]; int age,gender;
long int c_no; public:
void p_detail(int x)
{ if(x==1)
{ j_detail(); select_flight();
}
else
{ j_detaili(); select_flighti();
}
cout << "\n\n\nEnter passenger details"; cout << "\nFirst Name:";
cin >> f_name;
cout << "Last Name:"; cin >> l_name;
}
int gender_check()
{
cout << "\nGender:\nMale-press:1::\nFemale-press:2::"; cin >> gender;
if(gender>2)
{
cout << "\n\nWrong input entered.\nTry again\n\n" << endl; return gender_check();
 


}
}
void more_details()
{
cout << "Age:"; cin >> age;
cout << "Email Id:"; cin >> email;
cout << "Contact no.(6 digits):"; cin >> c_no;
cout << "\n\nDetails Entered:\n";
cout << "Name:" << f_name << " " << l_name << endl; cout << "Gender:" << gender << endl;
cout << "Age:" << age << endl;
cout << "Email id:" << email << endl; cout << "Contact No.:" << c_no << endl;
}


int getpnr()
{
return pnr;
}

int getpnri()
{
return pnri;
}

void disp()
{
cout<<"PNR:" << pnr << endl; cout<<"Flight:" << f_d << endl;
cout<<"Name:" << f_name << " " << l_name << endl; cout<<"DOJ:" << doj << endl;
cout<<"Departure Time:" << tojd << endl; cout<<"Arrival Time:" << toja;
}

void dispi()
{
cout<<"PNR:" << pnri << endl;
 


cout<<"Flight:" << f_i << endl;
cout<<"Name:" << f_name << " " << l_name << endl; cout<<"DOJ:" << doji << endl;
cout<<"Departure Time:" << tojdi << endl; cout<<"Arrival Time:" << tojai;
}
};




class payment
{
protected: long
int choice1,bank,card,date,cvv,user_id; char password[10];
public:
void pay_detail()
{	cout << "\n\n\nHow would you like to pay?:\n";
cout << "\n1.Debit Card(1) \n2.Credit Card(2) \n3.Net Banking(3)"; cout << "\n\nEnter your choice";
cin >> choice1; switch(choice1)
{
case 1:
cout << "\nEnter card no.:"; cin >> card;
cout << "\nEnter expiry date:"; cin >> date;
cout << "\nEnter CVV no.:"; cin >> cvv;
cout << "\nTransaction Successful\n"; break;
case 2://condition
cout << "\nEnter card no.:"; cin >> card;
cout << "\nEnter expiry date:"; cin >> date;
cout << "\nEnter password:"; cin >> password;
cout << "\nTransaction Successful\n"; break;
 


case 3://condition
cout << "Banks Available: 1.West Blue Bank(1) 2.Naga Bank(2) 3.Standard Bank(3) 4.Personal Bank(4) 5.Others(5)";
cout << "\nSelect your bank:"; cin >> bank;
cout << "\nYou have selected:" << bank; cout << "\nEnter user id:";
cin >> user_id;
cout << "\nEnter password:"; cin >> password;
cout << "\nTransaction Successful\n"; break;
default://condition
cout << "\nWrong input entered.\nTry again\n\n"; return pay_detail();
}
}

};

void createfile(passenger p)
{ ofstream fin("domestic.txt",ios::binary|ios::app); fin.write((char*)&p,sizeof(p));
fin.close();
}

void cancelticket(int x)
{ passenger p; int f=0;
ifstream fout("domestic.txt",ios::binary|ios::app); ofstream fin("domestic1.txt",ios::binary|ios::app); fout.read((char *)&p,sizeof(p));
while(fout)
{
if(p.getpnr()!=x)
fin.write((char *)&p,sizeof(p)); else
{
p.disp();
cout<<"\nYour Above ticket is being canceled:\n" << "Amount refunded: $100\n"; f++;
}
 


fout.read((char *)&p,sizeof(p));
}
if(f==0)
cout<<"Ticket not found\n"; fout.close();
fin.close(); remove("domestic.txt");
rename("domestic1.txt","domestic.txt");

}

void checkticket(int x)
{ passenger p; int f=0;
ifstream fout("domestic.txt",ios::binary); fout.read((char *)&p,sizeof(p)); while(fout)
{
if(p.getpnr()==x)
{p.disp();
cout<<"\nYour ticket"<<endl; f++;
break;
}
fout.read((char *)&p,sizeof(p));

}
fout.close(); if(f==0)
cout<<"Ticket not found"<<endl;

}
void createfilei(passenger p)
{ ofstream fin("international.txt",ios::binary|ios::app); fin.write((char*)&p,sizeof(p));
fin.close();
}
void cancelticketi(int x)
{ passenger p; int f=0;
ifstream fout("international.txt",ios::binary|ios::app); ofstream fin("international1.txt",ios::binary|ios::app);
 


fout.read((char *)&p,sizeof(p)); while(fout)
{
if(p.getpnri()!=x) fin.write((char *)&p,sizeof(p)); else
{
p.dispi();
cout<<"Your Above ticket is being deleted:\n"<<"Amount refunded: $100\n"; f++;
}
fout.read((char *)&p,sizeof(p));
}
if(f==0)
cout<<"\nTicket not found\n"; fout.close();
fin.close(); remove("international.txt");
rename("international1.txt","international.txt");

}
void checkticketi(int x)
{ passenger p; int f=0;
ifstream fout("international.txt",ios::binary); fout.read((char *)&p,sizeof(p));
while(fout)
{
if(p.getpnri()==x)
{p.dispi();
cout<<"\nYour ticket"<<endl; f++;
break;
}
fout.read((char *)&p,sizeof(p));

}
fout.close(); if(f==0)
cout<<"Ticket not found"<<endl;

}
 







int main()
{

class d_booking d1; class i_booking i1; class passenger p1; class payment p2; int ch,ch1,n;
char input; do
{
system("CLS");
cout << "\n\n \t\tWelcome To Airline Flight Booking System" << endl << endl;

cout << "\n\n\t\t\t1.Book Flight(1) \n\t\t\t2.Cancel Flight(2) \n\t\t\t3.Check Ticket(3)
\n\t\t\t4.Exit(4)" << endl;
cout << "\n\t\t Please enter your choice:"; cin >> ch;
switch(ch)
{
case 1:
system("CLS");
cout << "\n\n1.Domestic Flights(1) \n2.International Flights(2)" << endl; cout << "\nPlease enter your option" << endl;
cin >> ch1; switch(ch1)
{
case 1:
p1.d_pnr(); p1.p_detail(1); p1.gender_check(); p1.more_details(); p2.pay_detail(); p1.disp(); createfile(p1); break;
case 2:
p1.p_detail(2);
 


p1.i_pnr(); p1.gender_check(); p1.more_details(); p2.pay_detail(); p1.dispi(); createfilei(p1); break;
default:
cout << "Wrong input entered\nTry again\n\n\n" << endl; return main();
}
break; case 2:

system("CLS");
cout << "1.Domestic flights(1) \n2.International Flights(2)" << endl; cout << "\nPlease enter your option" << endl;
cin >> ch1; if(ch1==1)
{
cout << "Please enter your PNR no.:" << endl; cin>>n;
cancelticket(n);
}
else if(ch1==2)
{ cout << "Please enter your PNR no.:" << endl; cin>>n;
cancelticketi(n);
}
else
{
cout << "Wrong input entered\nTry again\n\n\n"; return main();
}
break; case 3:
system("CLS");
cout << "1.Domestic Flights(1) \n2.International Flights(2)" << endl; cout << "\nPlease enter your option" << endl;
cin >> ch1; if(ch1==1)
{cout << "Please enter your PNR no.:" << endl;
 


cin>>n; checkticket(n);} else if(ch1==2)
{ cout << "Please enter your PNR no.:" << endl; cin>>n;
checkticketi(n);
}
else
{
cout << "Wrong input entered.\nTry again\n\n\n"; return main();
}
 
break; case 4:


default:
 


system("CLS"); return 0;
 
cout << "Wrong input entered\nTry again.\n\n\n\n" << endl; return main();
}
cout<<"\n\n\nDo you wish to continue:(y/N)" << endl; cin >> input;
}while(input=='N' || input=='y');
}
 


5.	OUTPUT
1.	MAIN MENU

2.	BOOK FLIGHT MENU

 


3.	PASSENGER FLIGHT DETAIL AND BOOKING

 


4.	CANCEL FLIGHT:


5.	CHECK FLIGHT:

 


6.	CONCLUSION AND RESULTS

In conclusion, an airline booking system in C++ can be a powerful tool for managing flight reservations, cancellations, and other transactions. When properly designed and implemented, such a system can provide an efficient and reliable way to process bookings and ensure data accuracy and consistency.

One of the key advantages of using C++ for an airline booking system is its ability to handle large volumes of data and transactions, making it suitable for use in high-traffic environments. Additionally, C++ offers strong memory management capabilities, which can help ensure the system's stability and performance over time.

However, the success of an airline booking system in C++ also depends on factors such as its design, implementation, and maintenance. The system must be user-friendly and offer a variety of features that meet the needs of both customers and airline staff. It should also be scalable and adaptable to changing business requirements and technologies.

Overall, an airline booking system in C++ can be an asset for airlines looking to manage their bookings and transactions more effectively. By leveraging the strengths of C++ and paying close attention to the needs of their users, airlines can create a powerful and reliable system that helps them stay competitive in an increasingly complex and dynamic industry.

In conclusion, the result of an airline booking system in C++ can be highly effective if implemented correctly and maintained properly. With the right design, implementation, and maintenance, such a system can provide efficient and reliable management of flight bookings, helping airlines stay competitive in an increasingly dynamic industry
