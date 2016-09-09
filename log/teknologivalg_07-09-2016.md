#Valg av teknologi - 07/09-2016

Forventninger til tirsdag 13. september:
* Tanker om valg av teknologi - hva skal lages og hvordan?
* User stories 
* Skisser/prototyper


##Teknologi
###Alternativer for teknologi
* Native apps for mobil 
    * En app for Android og en for iOS
    * Vanskelig når få av oss har Mac
    * Har fra før lite kjennskap til Android-utvikling
    * Kan evt lage til kun Android
* Hybrid/krossplattform
    * Utvikles i f.eks. HTML, før den konverteres
* Web
    * Språket vi har best kjennskap til
    * Vil gjerne gi minst læringsutbytte

###Teknologivalg
Vi har i utgangspunktet valgt å lage en native Android-applikasjon. Delvis fordi vi ser for oss at brukere flest vil foretrekke å bruke denne applikasjonen på sin smarttelefon. Samtidig som vi tror vi vil lære mye av å utvikle en Android-applikasjon, da dette er noe ingen av oss har gjort før. Veldig får av oss har Mac, så iOS var ikke like aktuelt.


##User stories
###Features
* Velg/finn skole
* Vise planleggingsdager
* Ferier
* Kalender
* Varsel
* Lokasjon
* Legg i kalender
* Offlinestøtte
* Flere ruter på samme skjerm
* Kontaktpersoner
* Neste fridag

<table>
    <tr>
        <th>User stories</th><th>Acceptance Criterias</th>
    </tr>
    <tr>
        <td>Som "rolle"<br>
            Vil "handling"<br>
            Slik at "verdi/effekt"</td>
        <td>Gitt "tilstand"<br>
            Når "handling"<br>
            Skal "utfall"<br>
        </td>
    </tr>
    <tr>
        <td>Som "forelder"<br>
Vil "starte appen for første gang"<br>
Slik at "app lar deg legge til skoler"
        </td>
        <td>Gitt "appen aldri åpnet før"<br>
Når "app åpnes"<br>
Skal "liste lokale skoler + søkefelt"
        </td>
    </tr>
    <tr>
        <td>Som "forelder"<br>
Vil "lagre skole"<br>
Slik at "app husker skole og viser den i liste i fremtiden"
        </td>
        <td>Gitt "skoler er søkt opp"<br>
            Når "legg til trykkes"<br>
            Skal "legg til knapp-endres til fjern"
        </td>
    </tr>
    <tr>
        <td>Som "forelder"<br>
Vil "finne neste fridag for skoler"<br>
Slik at "liste med skoler vises samt deres neste fridag"
        </td>
        <td>Gitt "skoler er lagret"<br>
            Når "app åpnes, eller bruker går til startskjerm"<br>
            Skal "liste med skoler og fridager vises"
        </td>
    </tr>
    <tr>
        <td>Som "forelder"<br>
Vil "se kalendervisning over fridager"<br>
Slik at "liste med skoler vises samt deres neste fridag"
        </td>
        <td>Gitt "skoler er lagret"<br>
        Når "bruker trykker på en av sine skoler"<br>
Skal "kalendervisning av valgt skole vises"
        </td>
    </tr>
    <tr>
        <td>Som "forelder"<br>
Vil "se kalendervisning over fridager"<br>
Slik at "liste med skoler vises samt deres neste fridag"
        </td>
        <td>Gitt "skoler er lagret"<br>
        Når "bruker trykker på en av sine skoler"<br>
Skal "kalendervisning av valgt skole vises"
        </td>
    </tr>
</table>


