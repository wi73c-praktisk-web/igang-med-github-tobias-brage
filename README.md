## Hvordan man opretter et repository på Github

* Besøg organisationen [wi73a-praktisk-web](https://github.com/wi73a-praktisk-web).
* I højre side befinder sig en grøn knap med teksten `new`, klik på den.
* Under `Owner` vær sikker på at `wi73a-praktisk-web` er valgt og ikke ens eget brugernavn.
* Derefter giv dit repository et navn, opgaven samt dit navn i en sætning hvor mellemrum er adskilt med `-`, eksempelvis `igang-med-github-tobias-brage`.
* Tilføj eventuelt en beskrivelse under `Description`.
* Vælg om dit repository skal være offenligt eller privat.
* Vær sikker på at `Initialize this repository with a README` er markeret.
* Under listen `Add .gitignore: None` skrive `node` og vælg den fra listen.
* Klik på `Create repository` og du er færdig!.

## Hvordan man tilføjer overskrifter som kan vises på Github

* Man laver en overskrift med `#` derefter mellemrum og så selve overskriften.
* Overskriftens størelse er baseret på antal af `#`, jo flere destro mindre bliver overskriften.

## Hvordan man tilføjer en liste som kan vises på Github

* Man tilføjer en liste med `*` derefter mellemrum og så hvad punktet skal indenholde.
* For at lave endnu et punkt skal man blot rykke en linje ned og gentage med `*` og punktets indhold.

## Hvordan man tilføjer et link som kan vises på Github

* Først skrives der `[]` efter fulgt af `()` uden mellemrum.
* I `[]` skrives teksten til linket og i `()` indsættes url'en, f.eks. `[Google](www.google.dk)`.

## Skriv til konsollen i Visual Studio Code

* Hvis der skal skrives til konsollen i tilfælde af debugging eller lignende skal kommandoen `console.log();` bruges.
* I `()` skrives hvad der skal vises i konsollen, f.eks. `console.log("Hello World");`.
* Hvis konsollen ikke er fremme kan genvejen `Shift-Command-Y` bruges ellers kan den også findes under `View-Debug Console`.
* For at få vist et resultatet af `console.log` funktionen skal du i konsollen skrives `node` mellemrum og navnet på filen (du behøver ikke skrive filtypen), f.eks. `node test`.

## Hvordan man tilføjer kode som kan vises på Github

* Først markeres hvilken type kode du vil vise ved at skrive ` ``` ` og derefter navnet på kodesproget, f.eks. javascript uden mellem rum.
* Du kan nu skrive din kode nedenunder og det vil vises som kode på Github.

```javascript
val trigger = true;

if(trigger === true) {
    console.log("variable is true");
}