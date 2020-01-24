# **Área y volumen de un cilindro**

**Proceso Cilindro**

Proceso Cilindro

	//Volumen de un cilindro=  Base* altura o V= Pi*r^2h
	
	//Área de cilindro= 2*pi*r* (h+r)
	
	Definir P, r, h, V, A Como Real
	
	Escribir "Introduzca el radio de la base del cilindro en metros"
	
	Leer r
	
	Escribir "Introduzca la altura del cilindro en metros"
	
	Leer h
	
	P<-3.1415
	
	V<-P * r^2 *h
	
	A<-2 *P * r * (h+r)
	
	Escribir "El volumen del cilindro en metros cúbicos es:", V
	
	Escribir "El área del cilindro en metros cuadrados es:", A
	
FinProceso




**Promedio ponderado**

Proceso Promedioponderado

	Definir P1, P2, Participa, Final, N1, N2, N3, N4, PP Como Real
	
	P1<-0.25
	
	P2<-0.25
	
	Participa<-0.2
	
	Final<-0.3
	
	Escribir "Introduzca la nota obtenida en el primer parcial"
	
	Leer N1
	
	Escribir "Introduzca la nota obtenida en el segundo parcial"
	
	Leer N2
	
	Escribir "Introduzca la nota obtenida por participación"
	
	Leer N3
	
	Escribir "Introduzca la nota obtenida en el parcial final"
	
	Leer N4
	
	pp<-((P1*N1) + (P2*N2) + (Participa*N3) + (Final*N4))/ (P1+ P2+ Participa + Final)
	
	Escribir "Su promedio ponderado para este curso es:", pp
	
FinProceso

