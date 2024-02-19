# PROJECTE FINAL: Anàlisi i predicció del rendiment en l'IRONMAN 70.3 mitjançant Machine Learning

**1. Presentació del conjunt de dades escollit:**

El dataset és una versió preprocessada de les dades del lloc web oficial d'Ironman.

El triatló IRONMAN és una competició esportiva que consta de 3,86 km de natació, 180,25 km de bicicleta i 42,2 km de carrera a peu.

L'IRONMAN es va establir a Hawaii l'any 1978 i, des de llavors, ha atret molts atletes a participar en una de les curses d'un dia més dures. Els tres esports (natació, ciclisme i córrer) es completen en una sessió; per tant, no hi ha descans per als atletes a causa de la competició. Fins i tot les zones de transició, on un esportista es prepara per al
següent esport, es fan tan ràpid com sigui possible. Els atletes participen en dues categories: una categoria PRO i grups d'edat (AG). La categoria PRO és només una i està destinada a competidors per als quals el triatló és la seva professió, mentre
que alguns dels AG són aplicables a altres competidors. 

IRONMAN 70.3 és l'anomenat half-IRONMAN, que consta d'1,9 km de natació, 90 km de bicicleta i 21 km de carrera.

**2. Característiques generals i definició de les variables:**

Les dades s'han extret del lloc web (30/01/24):
https://www.kaggle.com/datasets/aiaiaidavid/ironman-703-race-data-between-2004-
and-2020/data

El dataset inclou 840.075 registres d'Ironman 70.3 PRO i de triatletes recreatius
(grups d'edat) entre 2004 i 2020, amb el seu gènere, país d'origen, grup d'edat (no
per PRO) i ubicació i any de la competició.

Cada fila del conjunt de dades representa les dades d'un participant en un
esdeveniment específic. El conjunt de dades recull diversos aspectes, com ara
informació demogràfica (sexe, edat), país d'origen, detalls de l'esdeveniment i
horaris per a diferents segments del triatló.

Les variables son les següents:

• Gènere: El gènere del participant amb els valors 'M' (Masculí) i 'F' (Dona).
(Variable Categòrica)

• AgeGroup: Grup d'edat dels participants. (Variable Categòrica)

• AgeBand: Representació numèrica del grup d'edat. Per exemple, "40"
correspon al grup d'edat "40-44". (Variable numèrica)

• País: el país d'origen del participant. (Variable Categòrica)

• CountryISO2: codi estandarditzat de dues lletres per a cada país. (Variable
Categòrica)

• EventYear: l'any en què va tenir lloc l'esdeveniment. (Variable numèrica)

• EventLocation: La ubicació o el nom de l'esdeveniment. (Variable
Categòrica)

• SwimTime: El temps que triga el participant a la part de natació de
l'esdeveniment, mesurat en segons. (Variable numèrica)

• Transition1Time: el temps trigat durant la primera transició entre la natació i
el ciclisme, mesurat en segons. (Variable numèrica)

• BikeTime: El temps que triga el participant a la part de ciclisme de
l'esdeveniment, mesurat en segons. (Variable numèrica)

• Transition2Time: el temps trigat durant la segona transició entre anar en
bicicleta i córrer, mesurat en segons. (Variable numèrica)

• Temps d'execució: El temps que triga el participant a la part de carrera de
l'esdeveniment, mesurat en alguna unitat de temps. (Variable numèrica)

• FinishTime: El temps total que triga el participant a acabar tot
l'esdeveniment, des de l'inici de la natació fins al final de la carrera, mesurat
en segons. (Variable numèrica)

**3. Presentació dels objectius: detallar els objectius inicials marcats de cara a
extreure informació rellevant del conjunt de dades.**

**Objectiu General**

Analitzar i predir mitjançant Machine Learning el temps final d’un atleta en una proba
IRONMAN 7.3 a partir de les seves dades personals.

**Objectius Específics**

1. Conduir un Anàlisi Exploratori de Dades (EDA) per aprofundir en el
comportament del conjunt de dades.

2. Emprar algoritmes de Machine Learning per establir models que descriguin la
interacció entre les variables i anticipar el rendiment dels esportistes, avaluant
la precisió i utilitat d'aquests models.

3. Explorar com les variables “Edat”, “Gènere” i “Temps de Transició” poden
contribuir en les prediccions del model.
