# WorganicTabV1 / v21 : Table/Button/Edit/Selected

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.1.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.


## Development server json

Run `json-server --watch db.json` for a dev server. Navigate to `http://localhost:3000/`.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Get clone 
> https://github.com/worganic/TutoTab-St21-tableEditSelect.git
> npm install
> cd .\worganic-tab-v19\
> ng serve

## Project :
v21 - Tableau -> Button -> Edit -> selected

    - Ajout du type editType :
        \src\app\component\users\users.component.ts
            >> editType: 'select'
    - Suppression de l'option 'all' dans la ligne :
        \src\app\shared\component\worg-table\worg-table.component.ts
            >> listData.push("All");// getSelectList(): Observable<any> {
    - Suppression de 'all' dans les option de colonne :
        \src\app\component\users\users.component.ts
            >> filterSelectData: ['Homme','Femme'], 
    - Ajout dans la vue de All pour les filtres :
        \src\app\shared\component\worg-table\worg-table.component.html
            >> <option value="All">All</option>
    - Mise à jour de la zone Edit / select :
        \src\app\shared\component\worg-table\worg-table.component.html
            >> <div *ngIf="column.editType == 'select'" >...

## Problème à résoudre :
    

## Infos plus :
   
## Update

## Historique :
Avant -> v20 - Tableau -> Button -> edit
Après -> v22 - Tableau -> Add

## Ressource :
    - selected :
    https://www.delftstack.com/howto/angular/angular-select-default-value/

## Abouts
created by Johann Loreau
create at 2023/08/17
Le project évolura suivant les remarques et conseils des visiteurs.