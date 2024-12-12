Examen - RA6: Creació i Gestió d'un Projecte Web amb Git i Desplegament en Vercel
Durada máxima: 1 hora i 30 minuts
Objectiu
Crear un projecte web amb documents HTML, CSS i JavaScript. Gestionar amb Git, utilitzar branques i publicar un projecte.

Documentació
Has de crear un document en format Markdown amb les imatges i l'explicació necessària que es demana a l'examen.

En acabar l'últim pas de l'examen, hauràs de penjar aquest document a la branca de documentació, incloent-hi les fotografies corresponents.

Instruccions
1. Configuració inicial
Comprova la versió instal·lada de Git, fes captura del terminal.

![git_version 1](https://github.com/user-attachments/assets/4a09cc28-4635-4278-8fbc-4fa2febbc492)]

Configura Git al teu sistema (opcional)

![git_config 2 1](https://github.com/user-attachments/assets/8aa43172-b531-4a5a-8dc2-c66a85604aef)

Mostra la configuració actual per verificar-ho, fes captura del terminal. Explica com veig que he configurat correctament el email i el nom.

![git_config 2](https://github.com/user-attachments/assets/fdf1b219-4cb3-47aa-b702-33f49d8d0f79)

**Es pot veure que s'ha configurat bé el nom ja que com es veu en la imatge no dona cap error i en l'apartat de user.name i user.email es veu com esta escrit correctament.**

Inicia un nou repositori Git al directori de treball on consideris. El nom del directorio ha de ser Cognom1Cognom2Examen2425.

![git init 3](https://github.com/user-attachments/assets/a5c02b8d-d485-4f32-b53b-f070f8c1e52a)

Crea un document README.md, afegeix el document i fes un primer commit que amb el missatge 1 - Git init

![git README 5](https://github.com/user-attachments/assets/e2fe3c7b-9ed2-40ae-b463-9e383fc46601)

2. Creació del projecte web
Crea els fitxers següents al directori del projecte:

index.html
testunitari.html
style.css
main.js
Afegeix contingut bàsic a cada fitxer.

![ex 2 (echo i nano)](https://github.com/user-attachments/assets/1ee1fbac-1759-427e-8f6b-47c1455310d0)

3. Gestió amb Git
Afegir fitxers:

Utilitza un patró d'expressió regular per afegir tots els fitxers .html i .css. Fes captura del terminal
Verifica l'estat del repositori, fes captura del terminal

![add els html i css 3](https://github.com/user-attachments/assets/2bfae426-6591-428d-997f-6d1780ad19b3)

*Aquesta captura agrupa els dos exercicis primers del punt 3*

Elimina testunitari.html del staging

Fes un commit que amb el missatge '2- Estructura bàsica'

Consulta l'historial de commits, fes captura del terminal.

![git commit 3 4 i 3 5](https://github.com/user-attachments/assets/79412572-8c67-4c6d-b7ee-7ad8cb798631)

4. Creació de branques i documentació
Crea una nova branca per a la documentació

![branca 4](https://github.com/user-attachments/assets/cbb76083-50f7-4ccf-a640-175b3656fb9c)

Crea un fitxer README.md si es necessari:

Explica dins del fitxer el propòsit del projecte.
Afegeix i fes commit dels canvis a la branca documentacio. El missatge del commit ha de ser "3 - README.md amb documentació inicial"

Torna a la branca principal (main) i fes un merge

![merge de branch 4 4](https://github.com/user-attachments/assets/e4bb0013-c9d8-4623-8ba3-73a816ba4e70)

5. Remot i publicació
Configura un remot per al repositori que has de crear en GitHub, el nom del repositorio de GitHub ha de ser Cognom1Cognom2Examen2425. Fes captura al terminal de com has configurat el repositori remot.

![git remote 5 1](https://github.com/user-attachments/assets/ba25d6eb-ff24-4000-ba06-43836c136e1a)

Puja els canvis al remot desde terminal.Fes captura al terminal.

![push 5 2](https://github.com/user-attachments/assets/5f44ecdd-88bc-4eb3-9cf9-6421a375a397)

Publica el projecte a Vercel i indica l'enllaç en el document Markdown del examen.

https://sbert-dasilva-adria-examen2425-eenc5l65b-adrisbert06s-projects.vercel.app
