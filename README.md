Descripción:  The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact with the same client was required in order to confirm if the product (bank term deposit) would be (or not) subscribed. 

Fuente original de los datos:  Datos procedentes de los siguientes estudios (aunque con modificaciones posteriores):
-	S. Moro, R. Laureano and P. Cortez. Using Data Mining for Bank Direct Marketing: An Application of the CRISP-DM Methodology. 
-	P. Novais et al. Proceedings of the European Simulation and Modelling Conference - ESM'2011, pp. 117-121, Guimarães, Portugal, October, 2011. EUROSIS.

Descripción de las variables:

# bank client data:
   1 - age 
   2 - job : type of job 
   3 - marital : marital status ("divorced" means divorced or widowed)
   4 - education 
   5 - default: has credit in default? 
   6 - housing: has housing loan? 
   7 - loan: has personal loan? 

   # related with the last contact of the current campaign:
   8 - contact: contact communication type 
   9 - month: last contact month of year 
  10 - day_of_week: last contact day of the week 
  11 - duration: last contact duration, in seconds. 

   # other attributes:
  12 - campaign: number of contacts performed during this campaign and for this client
  13 - pdays: number of days that passed by after the client was last contacted from a previous campaign (999 means client was not previously contacted)
  14 - previous: number of contacts performed before this campaign and for this client 
  15 - poutcome: outcome of the previous marketing campaign 

   # social and economic context attributes
  16 - emp.var.rate: employment variation rate - quarterly indicator (numeric)
  17 - cons.price.idx: consumer price index - monthly indicator (numeric)     
  18 - cons.conf.idx: consumer confidence index - monthly indicator (numeric)     
  19 - euribor3m: euribor 3 month rate - daily indicator (numeric)
  20 - nr.employed: number of employees - quarterly indicator (numeric)
  21 - y - has the client subscribed a term deposit? (binary: "yes","no")


Guión para la realización del trabajo

1.	Exploración y limpieza de la BBDD
•	Análisis descriptivo de la BBDD.
•	Descartar variables que no se vayan a analizar estadísticamente, razonando por qué.
•	Tabla auxiliar con las variables a utilizar en los análisis estadísticos, indicando el tipo: categórica ordinal, categórica nominal, numérica discreta, numérica continua, fechas, otros.
•	Exploración de la BBDD para identificar variables constantes (o casi), valores anómalos, valores inconsistentes, valores faltantes.
•	Corrección de variables: Formato? Recodificación? Nombres?
•	Creación de nuevas variables?
•	Tratamiento de valores faltantes.
•	…
