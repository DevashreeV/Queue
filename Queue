//Queue using Array

#include <stdio.h>
#include <stdlib.h>
void enqueue();
void dequeue();
void display();
int front=-1;
int rear=-1;
#define MAX 3
int array[MAX];

int main()
{
	int choice=1;
	while (choice==1 || choice==2 || choice==3)
		{
			printf(" \n Enter the no. of function to be performed \n 1.Enqueue 2.Dequeue 3.Display 4.Exit \n");
			scanf("%d",&choice);
			if (choice==1)
			{
				enqueue();
			}
			else if (choice==2)
			{
				dequeue();
			}
			else if (choice==3)
			{
				display();
			}
			else
			{
				break;
			}
		}
}
 void enqueue()
 {
 	if(rear==MAX-1)
 	{
 		printf("Overflow");
	}
	else
	{
		int data;
		printf("Enter data to be inserted \n");
		scanf("%d",&data);
		rear=rear+1;
		array[rear]=data;
		if(front==-1)
		{
			front=0;
		}
		
	}
 }
 void dequeue()
 {
 	if(front==-1 || front==rear+1)
 	{
 	printf("Underflow");
	}
	else if(front==rear)
	{
		front=-1;
		rear=-1;
	}
	else
	{
		front=front+1; 
	}
 }
void display()
{
	int i;
	
	if (front==-1)
	{
		printf("The queue is Empty \n");
	}
	else
	{
		printf("The queue is \n");
	for (i=front;i<=rear;i++)
	{
		printf("%d	",array[i]);
	}
}
	//printf("%d %d",front,rear);
}