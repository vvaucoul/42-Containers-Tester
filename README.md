# ft_containers

Un simple testeur du projet "FT-Ccontainers" de l'école 42.

* [Informations](#infos)
* [Setup](#setup)
* [Usage](#usage)

## Informations
L'objectif de ce testeur est de vous aider à valider le projet ft_containers.
Si vous échouez sur certains tests, celà ne veut pas dire que votre fonction est fausse.
Dans ce cas, faites des tests de votre côté.

Liste des containers:
* Vector
* List
* Map
* Queue
* Stack

Bonus:

* Deque
* Multimap
* Multiset
* Set

Même si le sujet du projet change, le testeur restera valide.

## Setup
```
$ git clone git@github.com:vvaucoul/42-Containers-Tester.git
$ cd 42-Containers-Tester
```

Modifiez ensuite 2 fichiers:

* Makefile : Remplacez chaque header de la règle "CXXFLAGS" par l'emplacement de vos headers.
* tests/Tests.hpp : Remplacez les includes *.hpp par l'emplacement de vos headers

## Usage

```
$ Make
$ ./container_tests [Container (vector, list, map, queue, etc...)]
$ ./container_tests_bonus [Container (deque, multimap, multiset, etc...)]
$ ./container_tests all
$ ./container_tests_bonus bonus
```
La méthode max_size() de chaque container diffère entre Linux et Mac !
Il se peut que cette partie ne soit pas valide.
