# Bootstrap
Denna repository är en kort inblick till hur man skapar en enkel bashemsida med hjälp av Bootstrap, jumbotrons, navbar, card och card deck. Områdena som tas upp utgår från Bootstraps version 4.6.x och används i Visual Studio Code.

## Vad är Bootstrap?

Bootstrap är ett stilklassbibliotek, ur Bootstrap kan du enkelt hitta färdiga CSS- och HTML-mallar och kopiera dem. Till mallarna följer en enklare beskrivning och exempel på hur de ser ut.
      
## Versioner av Bootstrap
        
Bootstrap har flera olika versioner, det rekomdenderas att hålla sig till mallar från en och samma version per projekt. Eftersom mallarna skiljer sig mellan versionerna och inte alltid fungerar bra ihop. I Bootstrap går det att välja vilken version som man vill se sidan i, det vill säga tidigare versioner går att se, ta och använda mallar från.

<img width="310" height="498" alt="image" src="https://github.com/user-attachments/assets/5b49b358-f889-4613-b83d-b32cf81dbddc" />

## Bootstrap som extension direkt i Visual Studio Code
  
  Bootstrap går att installera som en extension i visual studio code, välj extensions (Ctrl+Shift+X) i VSC, sök Bootstrap och installera. Det finns flera versioner att välja mellan men, eftersom denna repository utgår från version 4.6.x har jag valt att installera den. Genom att skriva b4 och sen enter dyker en startmall upp. Du kan enkelt välja färdiga mallar för componenter genom att lägga till ordet för componenten efter b4. 
  <img width="704" height="351" alt="image" src="https://github.com/user-attachments/assets/4a01017f-83b8-4b14-8644-4a8980ce6c6c" /> <img width="661" height="354" alt="image" src="https://github.com/user-attachments/assets/00150ab1-bff9-4cef-a297-deeb7a30941c" />


  ## En enkel grund till en hemsida med Bootstrap i VSC
  1. Börja med att öppna en html fil i VSC, klistra in en startmall från bootstrap eller skriv in direkt b4 och sedan enter.
     <img width="1222" height="508" alt="image" src="https://github.com/user-attachments/assets/4c287521-e155-4f06-9e36-6bb625105fd1" />
  2. Testa att lägga in en navbar i body delen genom att klistra in en mall från bootstrap alternativt b4navbar-deafult
     <img width="1140" height="714" alt="image" src="https://github.com/user-attachments/assets/6535ab3a-cae7-4b95-9aad-590c8b083d37" />
  3. Testa att lägga in en jumbotron under navbaren genom att klistra in en mall från bootstrap alternativt b4jumbotron
   <img width="1002" height="261" alt="image" src="https://github.com/user-attachments/assets/8516a118-b3b8-4c37-b1fb-e2abd978c97e" />
  4. Lägg till en card deck under jumbotron genom en mall från bootstrap eller b4cardecks
     <img width="1187" height="593" alt="image" src="https://github.com/user-attachments/assets/41408ce1-de15-48dc-b7e6-d4d487aa8192" />
  5. Resultat:
     <img width="1919" height="983" alt="image" src="https://github.com/user-attachments/assets/484a971e-e7f6-4d9e-ade3-887ea4711276" />
## Arbeta med Bootstrap 
Bootstrap är färdiga mallar, men det är inte alltid önskvärt att de ska se ut på det sättet. I bootstrap är det enkelt att byta ut texter i mallarna, men hur fungerar det med CSS. I starmallen finns en CSS fil länkad i head-delen, den ersätter style. På Bootstrap finns det CSS koder, exempelvis för färg, koderna går att kistra in och fungerar utan style. Alternativt kan man fortfarande anpassa själv med sin egen style, antingen genom att länka en egen CSS fil eller skriva egen style.
    
