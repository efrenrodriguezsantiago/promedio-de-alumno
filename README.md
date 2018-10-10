#include<iostream>
using namespace std;
int main()
{
	int c_exam,c_pra,c_tar,c_part,c_dic,c_tra;
	int resultado,calificacion;
	
	cout<<"solicitar calificacion de examen: /n";cin>>c_exam;
	
	cout<<"solicitar calificacion de practicas: /n";cin>>c_pra;
	
	cout<<"solicitar calificacion de tareas: /n";cin>>c_tar;
	
	cout<<"silicitar calificacion de participantes :/n";cin>>c_part;
	
	cout<<"solicitar calificacion de disciplina: /n";cin>>c_dic;
	
	cout<<"solicita calificacion de trabajo en equipo: /n";cin>>c_tra;
	
	resultado = c_exam + c_pra+c_tar+c_part+c_dic+c_tra;
	
	calificacion = resultado / 6;
	
	cout<<"\nla calificacion final es:"<<calificacion<<endl;
	
	
	
	
	return 0;
}
//calcular el promedio de un alumno de la asignatura metodologia de la programacion
