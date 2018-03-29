# Taller-Logit-y-Probit
Llamamos la base de datos a trabajar

load("logitprobit.Rdata")

Seleccionamos las variables de interes. Esta base de datos corresponde a la gran encuesta integrada de hogares (GEIH) del año 2015. Para una mejor comprension definimos las variables 

data=datos[,c("P7170s1","Inglabo","P6040","P6870","P4030s1a1")]
colnames(data)=c("satisfecho","ingreso","edad","nro.personas","estrato")

dim(data)

head(data)
