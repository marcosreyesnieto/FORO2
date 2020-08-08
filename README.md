
#include<stdio.h>
#include<conio.h>
#include<windows.h>
#include<string.h>

struct empleado
{
	int id;
	char nombre[40];
	char puesto [15];
	int depot;
	char horario;
	int sucursal;
	char tiposal;
	float salario;
	int diast;
	float sbruto, imss, ipagado, iretenido,sneto;
};

empleado nomina[60];

void menu();

char otro;
int (opc);


int main()
{
	do
	{
		menu();
		fflush(stidin);
		printf("que opcion quieres");
		scanf("%d ,"&opc);
		switch(opc)
		{
			case 1:
				do 
				{
					fflush(stin);
					printf("introduce el id del empleado");
					scanf("%d",&nomina[contar].id);
					fflush(stidin);
					printf("captura el nombre");
					gets(nomina[contar].nombre);
					fflush(stidin);
					printf("puesto del nombre");
					gets(nomina[contar].puesto);
					printf("departamento \n");
					printf("1 R.H. \n");
					printf("2 Finanzas \n");
					printf("3 Sistemas \n");
					printf("4 ventas \n");
					printf("5 mantenimiento \n");
					flussh(stdin);
					printf("horario m=matutino v=vespertino");
					scanf("%c",&nomina[contar].horario);
					flush(stdin);
					printf("tipo de salario n=nomina h=honorarios");
					scanf("%c",&nomina[contar].tiposal);
					fflush(stdin);
					printf("dias de trabajo");
					scanf("%d",&nomina[contar].diast);
					
					nomina[contar].sbruto=nomina[contar].salario*nomina[contar]
					if(nomina)[contar].tiposal=='n')
					{
						nomina[contar].isr=nomina[contar].sbruto*.34;
						nomina[contar].imss=nomina[contar].sbruto*.04;
						nomina[contar].ipagado=0;
						nomina[contar].iretenido=0;
					}
					else
					{
						nomina[contar].isr=nomina[contar].sbruto*.10;
					}
					printf("quieres agregar otro empreado");
					scanf("%c",&otro);
				}while(otro=='s');
				break;
		} //termina switch
	}whilw(opc<7);
	
}//termina main

void menu()
{
	
} //termina menu 




