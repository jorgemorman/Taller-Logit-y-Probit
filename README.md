# Taller-Logit-y-Probit
Llamamos la base de datos a trabajar

load("logitprobit.Rdata")

Seleccionamos las variables de interes. Esta base de datos corresponde a la gran encuesta integrada de hogares (GEIH) del año 2015. Para una mejor comprension definimos las variables 

data=datos[,c("P7170s1","Inglabo","P6040","P6870","P4030s1a1")]
colnames(data)=c("satisfecho","ingreso","edad","nro.personas","estrato")

dim(data)

head(data)

descripcion de las variables 

P7170s1: ¿Está satisfecho con su trabajo actual?

Inglabo: Ingresos laborales

P6O40: ¿Cuantos años cumplidos tiene?

P6870: ¿cuantas personas en total tiene la empresa o el sitio donde trabaja?

P4030s1a1: Estrato para tarifa:

Satisfecho 	Ingreso	Edad	N° de personas	Estrato 
1	1500000	41	9	1
NA	NA	42	NA	1
NA	NA	9	NA	1
NA	NA	8	NA	1
1	460000	26	1	1
NA	NA	29	NA	1
