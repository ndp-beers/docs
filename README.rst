Réalisation d'une pico brasserie
################################

Ce dépot contient de la documentation sur comment réaliser une pico brasserie.
Il s'agit d'un travail en cours, et donc par définition non terminé.

Notre objectif est de rendre notre processus de création le plus ouvert
possible, afin de faciliter sa reproduction.


Comment installer cette documentation localement ?
--------------------------------------------------

Pour installer la documentation localement, il vous faut à minima `virtualenv`
et `python` + `pip`. Avec tout ça d'installé, lancez les commandes suivantes::

  $ virtualenv .venv
  $ .venv/bin/pip install -r requirements.txt

Puis ensuite, lancez `make html` une fois dans le repertoire `docs`::

  $ cd docs
  $ make html
