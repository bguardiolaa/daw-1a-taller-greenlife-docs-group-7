# RESPOSTES.md

## Exercici 1

### 1. Quantes branques hi ha?

3: `main`, `feature/faq` i `feature/api-reference`.

### 2. Com veus les branques remotes?

Amb `git branch -a`.

### 3. Com veus els canvis de l'Anna sense canviar de branca?

Amb `git diff` o `git show`.

## Exercici 2

### 1. Què passa amb les branques després del merge?

Continuen existint fins que les eliminem.

### 2. Com elimines una branca remota?

Amb `git push origin --delete nom-branca`.

### 3. Per què eliminem les branques?

Per tenir el repositori més net i ordenat.

## Exercici 3

### 1. Per què s'ha produït el conflicte?

Perquè els dos desenvolupadors han modificat el mateix fitxer.

### 2. Com es podria haver evitat?

Fent `pull` sovint i parlant amb el company.

### 3. Què passa si modifiquen la mateixa línia?

Git mostra un conflicte i l'hem de resoldre manualment.

### Què fa `git blame`?

Mostra qui ha modificat cada línia d'un fitxer.

## Exercici 4

### 1. Diferència entre `git revert` i `git reset`?

`git revert` desfà canvis amb un commit nou. `git reset` torna a un
commit anterior.

### 2. Quan és segur fer `git push --force`?

En branques pròpies, no en branques compartides com `main`.

### 3. Com recuperes un canvi revertit?

Fent un `git revert` del commit que havia desfet el canvi.

## Exercici 5

### 1. Per què serveixen les branques de release?

Per preparar una versió sense afectar el desenvolupament.

### 2. Què és un tag?

És una etiqueta per identificar una versió, com `v1.0`.

### 3. Com veus tots els tags?

Amb `git tag`.

### Què fa `git show <tag>`?

Mostra informació del tag i del commit associat.

## Exercici 6

### 1. Per què vinculem commits amb issues?

Per saber quin problema resol cada canvi.

### 2. Com veus els issues tancats?

A GitHub apareixen com a tancats i es veu a la seva activitat.

### 3. Què passa si dos desenvolupadors treballen en el mateix issue?

Es poden trepitjar la feina i provocar conflictes.
