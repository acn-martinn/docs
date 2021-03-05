---
title: Migrere tjenester
description: Reisen til Altinn Tjenester 3.0
weight: 70
aliases:
- /guides/migrate-services/
---

Følgende viser de overordnede steg for å migrere en eksisterende tjeneste til Tjenester 3.0
1. Opprett [bruker](https://altinn.github.io/docs/altinn-studio/first-time-setup/) og [app](https://altinn.github.io/docs/altinn-studio/app-creation/create-app/) i [Altinn Studio](https://altinn.studio/)
2. Utvikle app/tjeneste
2. [Importer](https://altinn.github.io/docs/altinn-studio/app-creation/data-model/) .XSD
2. Kombiner [designer](https://altinn.github.io/docs/altinn-studio/app-creation/ui-editor/) og [kodeverktøy](https://altinn.github.io/docs/altinn-studio/app-creation/navigation/#code)
3. Vurder bruk av [tjenestemigreringsverktøy](https://github.com/Altinn/altinn2-convert)
4. Test [lokalt](https://altinn.github.io/docs/altinn-studio/testing/local/)
5. Bestill din infrastruktur
6. Sette app i produksjon – i [testmiljø](https://altinn.github.io/docs/altinn-studio/testing/deploy/) og [produksjonsmiljø](https://altinn.github.io/docs/altinn-studio/deploy-maintain/)

  
For å migrere en utvalgt tjeneste kan det være nyttig å lage seg en skisse av tjenesten slik at man gjør seg kjent med designelementer i Altinn 3, og slik at man har en referanse å se til når man utvikler løsningen. Slik gjør du dette.


- Gå inn på nettsiden [https://www.figma.com/](https://www.figma.com/) og lag deg en bruker.
- Figma kan installeres lokalt eller brukes i din nettleser.
- Altinn har et åpent design kit for eksterne og det finner du [her](https://www.figma.com/proto/wnBveAG2ikUspFsQwM3GNE/ADS---Prototyping-for-eksterne?node-id=47%3A4068&amp;viewport=326%2C2144%2C0.653957724571228&amp;scaling=min-zoom).
- Gå inn på [denne](https://docs.altinn.studio/design/figma/) siden for å få mer informasjon om hvordan du kan komme i gang med Figma.

For å migrere tjenester til Altinn 3 må du ha tilgang til verktøyet Altinn studio. Altinn studio er verktøyet som brukes til å lage fullstendige Altinn 3 tjenester. Det er dette verktøyet som erstatter den gamle løsningen TUL. Tjenester i Altinn studio kalles app.

- For å få tilgang til å utvikle en app i Altinn studio så må du lage en bruker. Her kan du se hvordan du oppretter en ny bruker. [https://altinn.github.io/docs/altinn-studio/first-time-setup/](https://altinn.github.io/docs/altinn-studio/first-time-setup/)
- Etter du har laget en bruker I Altinn studio kan du lage en app. Du kan stå du som eier av appen, dette kan være nyttig om du ønsker og teste hvordan Altinn studio fungerer.
- Når du skal lage app for din organisasjon må du få tilgang til din organisasjon i Altinn studio. Tilgangen får du av administrator for din organisasjon. Tilgangsstyring i Altinn studio. [https://altinn.github.io/docs/altinn-studio/access-management/](https://altinn.github.io/docs/altinn-studio/access-management/)
- Slik lager og redigerer du apper i Altinn studio. [https://altinn.github.io/docs/altinn-studio/app-creation/create-app/](https://altinn.github.io/docs/altinn-studio/app-creation/create-app/)
- Her finner du informasjon om hvordan du navigerer mellom de ulike delene I Altinn studio. [https://altinn.github.io/docs/altinn-studio/app-creation/navigation/](https://altinn.github.io/docs/altinn-studio/app-creation/navigation/)
- Vi anbefaler å bruke koderedigeringsverktøy eksempel Visual Studio Code. Det anbefales også å sette opp et lokat testmiljø for å enkelt og effektivt kunne teste apper. Sette opp lokalt testmiljø: [https://github.com/Altinn/altinn-studio/blob/master/LOCALAPP.md](https://github.com/Altinn/altinn-studio/blob/master/LOCALAPP.md)
- For å definere hvilke data som skal være med i appen så må du laste opp en datamodell. Slik laster du opp datamodell i Altinn studio: [https://altinn.github.io/docs/altinn-studio/app-creation/data-model/](https://altinn.github.io/docs/altinn-studio/app-creation/data-model/)

- Tilrettelegge system for mottak av data.