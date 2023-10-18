# Case: Fullstack Cinema

I detta caset ska ni fortsätta på er Bookningsapp för en biosalong. Den här gången ska ni har er egen backend bygg med node.js med hjälp av express webserver biblioteket samt React.js för en frontend.

## Krav

### Code minimum
* En README.md med **tydliga instruktioner** för hur man startar applikationen
* Minst 10 git commits som visar att ni har arbetat med caset över tid
* Det ska vara möjligt att bläddra bland filmer som är tillgänglig på biografen [Resurs: Movie]
* Vid val film ska man kunna se kommande föreställningar
* Föreställningar [Resurs: Show] ska kunna bokas och meddela användaren
* en bokning [Resurs: Booking] ska kunna minst innehålla *namn* och *email*
* en ny bokning [Resurs: Booking] ska registreras i databasen
* All information ska vara sparas till en databas (i en json-fil)
* En användare [Resurs: User] ska kunna logga in och ut
    * inloggad användare ska kunna se sin egna samling av Bokningar
    * ej inloggad användare ska inte kunna se någon annans Boknigar


### Code Extra
* Publicerad via Linode eller motsvarade
* När en inloggad användare bokar så behöver personen inte skriva in namn och email
* Inloggade användare kan ge Rating (1 till 5) till en film
* Inloggade användare kan ge Reviews till en film
* Reviews & Rating kan tas bort av författande användare (inte någon annan)
* Reviews & Rating kan editeras av författande användare (inte någon annan)


## Förslag till upplägg
Min rekommendation är att ni har hela projektet i en map som ser ut som följande:

```

fullstack-project/
	| .gitignore
        | package.json
	|----> frontend/     (ert react project)
	|
	|----> backend/      (ert nodejs project)

```



## Feedback
Veckan efter presentation kommer feedback ges under följande rubriker:

- Backend
- Frontend
- Allmän kodstil

*Designfeedback tillkommer från Mattias*

## Presentation- och Inlämningsdatum
Presenteras och in lämning för feedback måndagen den **13de November** kl 10.25. Tiden 14de till 19de November är feedbackperiod då ni får feedback, ni kan under tiden jobba med er portfolio och göra klart gamla case.
Vi kommer även under denna perioden boka in enskilda möten med samtliga deltagare för att ställa relevanta kunskapsfrågor. Ni behöver vara godkända på dessa frågor för att vara godkända på modulen.
