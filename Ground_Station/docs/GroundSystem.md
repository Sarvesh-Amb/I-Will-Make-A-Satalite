# Ground System

## SubSystems

* The Antenna Subsystems(The Ears)
* The RF/Radio Hardware chain
* Processing and control software

## Singnificiance
Even tho ISRO (or any other space agency you colaborate with for your statlite program) will send your satalite to space but tracking it and monitorning it's data is complelty your responsibilty, so a ground system is **Extremely** Nessery.

## AWS ground station
Amazon Webservices (AWS) provide you with a groundsystem that you can use, they have locations all over the globe and have a pay as you go scheme with no minimul requirements and charge by the minute.

### Amazon AWS vs self made ground station 

| |Amazon AWS | Self Made Ground Station|
|:-- |:-- |:-- |
|cost | increases as you go| one time initial cost|
|complexity| comaratively simples | have to figure out a lot of hardware|
|taking data | raw data + ML data | have to figure out yourself again |
|reading data | more difficult to menuver satalite over aws locations |simples to get satalite over your location |
|cooler ? | kinda lame | very  cool |

making you satalite passs over the aws locations is much more diffucult than making it go over you location every day ( it will pass for 15 - 20 mins)
I have to do more research on which is easier and why but this is what ai got me, and I also relly just wanna make a ground station

## Satalite Design and Ground sation corelation

### frequency selection
what type of data your satalite transfers makes an impact on your frequency selection, inturn affecting your harware
for examble if you want to transfer high resolution images, you would need a dish anntena, a simple Yagi won't work ( IDK what a Yagi it but it won't work :/)

### Transmitter power
if your onboard satalite battery only allows for a weak 1 watt transmitter your ground sation anntenna would need to compensate with a higher gain more powerful mast mound amp (idk what that is either)

### Polarization 
when your satalite shifts slightly in apce the radio wave it transmits shift as well,
if your satalite uses linear polarization your antennas need to match 
if your satalite uses circular polarization your Yagi anntenas must be "corssed Yagis" with a phasing harness so they don't lose singal as the satalite rolls


