# Testing 

### Testing pyramid

Der findes mange forskellige test pyramider. 

Underviserens yndlings pyramide indeholder acceptence test, system test, integrations test, component test og til sidst unit test. 

En unit i en unit test er en "udelelig" del af kildekoden. Dog skal det siges at der er stor uenighed om hvad en "udelelig" del er. 

Ved komponenter handler det om komposition. (Category theory??)

Accept test er test hos brugeren. Hvor kunden og PO osv tester inden vi smider det i produktion. 

## Test quadrants 

I den agile verden. 
Q = quadrant

Q1 er unit tests og component test.
Q2 Functional tests - fx story tests, prototypes osv.
Q3 Exploratory testing - mauelle test - meget omkostningstunge - usability testing, user acceptence testing, alpha beta.
Q4 Performance + Load testing og security testing. (skal der ske mange kald, skal der køres red team/blue team test)

Denne kan man også finde mange billder af med google.

## Testing strategy

Idag test - who will review the test strategy og who will approve the test strategy.

Man nedskriver hvad der skal testes og hvornår, samt hvem der står for det. 

Automatiske værktøjer til unit test osv samt anvendelse af disse i versionsstyring osv osv osv . 

Regression Testing er al test vi har lavet gennem tidne. Det indebærer at man tester alle gamle test hver gang man tilføjer en ny feature. 

### Testing environment 

Så tæt på den virkelige verden som muligt. 

risikoanalyse

backup af test data, samt restore strategy (versionsstyring og redundans ift database)

### Testing tools 

automatisering og er det open source ller kommercielle værktøjer.

### Release Control

versionering osv 
devops osv 
Det er en del af test strategi.
skal det deployes til skyen eller afleveres på floppy disc.

### Risk analysis

Esimering af risiko - det kunne være med en numerisk værdi (arbitrær).

Risikomitigering - hvordan mitigerer vi de risiko der er forbundet med produktet. 
```bash
risiko for forretningen og IT-sikkerhed og data sikkerhed 
```

nødplaner hvis noget går galt

Test strategi er guidelines som man følger osv.
Test Plan er scope af testing defineret og tidsplaner for test er nedskrevet. 

oooo..
