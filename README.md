# TP 4 — Classes, Objets et Associations en Java

Ce TP a pour objectif de mettre en pratique les concepts de la programmation orientée objet (POO) en Java, notamment la création de classes, les constructeurs, l'encapsulation, les associations entre objets et la gestion des collections.

## 📌 Exercice 1 — Gestion d'un étudiant avec tableau de notes
<img width="1366" height="768" alt="1" src="https://github.com/user-attachments/assets/1c357807-a1ad-40df-a06d-e1f527c96711" />

<img width="1366" height="768" alt="p1" src="https://github.com/user-attachments/assets/4cda3ca6-60b4-42e2-8dd7-680b4ea9a96d" />

Dans cet exercice, nous avons créé une classe `Etudiant` permettant de gérer les informations d'un étudiant et ses notes.

### Concepts utilisés :

* Création d'une classe Java
* Attributs `private`
* Constructeurs
* Identifiant automatique avec `static`
* Identifiant non modifiable avec `final`
* Tableau dynamique de notes
* Calcul de la moyenne
* Redimensionnement du tableau avec `System.arraycopy()`
* Redéfinition de la méthode `toString()`

L'objectif est de permettre à un étudiant d'ajouter plusieurs notes et d'afficher ses informations ainsi que sa moyenne.

---

## 📌 Exercice 2 — Association entre Étudiant et Filière

<img width="1366" height="768" alt="2" src="https://github.com/user-attachments/assets/e05e377e-d9d4-4ec9-abdf-f76cf9895751" />

Cet exercice introduit l'association entre deux classes : `Etudiant` et `Filiere`.

Un étudiant appartient à une filière et une filière peut contenir plusieurs étudiants.

### Concepts utilisés :

* Association entre deux classes
* Relation `Etudiant → Filiere`
* Gestion de plusieurs étudiants
* Tableaux d'objets
* Agrandissement automatique du tableau
* Getters et setters
* Association bidirectionnelle

Lorsqu'un étudiant est ajouté à une filière, la relation est également enregistrée au niveau de l'étudiant.

---

## 📌 Exercice 3 — Gestion des articles et des catégories

<img width="1366" height="768" alt="3" src="https://github.com/user-attachments/assets/f21eb063-dc2a-4329-9122-58c21d4e4dd8" />

Dans cet exercice, nous avons créé un système simple permettant de gérer des `Article` et des `Categorie`.

Chaque article appartient à une catégorie.

### Concepts utilisés :

* Création de plusieurs classes
* Association `Article → Categorie`
* Identifiants automatiques
* Encapsulation
* Getters et setters
* Parcours de tableaux avec des boucles
* Recherche des articles appartenant à une catégorie
* Utilisation de plusieurs packages

Les articles sont ensuite affichés en fonction de leur catégorie.

---

## 📌 Exercice 4 — Gestion des auteurs, livres et bibliothèques

<img width="1366" height="768" alt="4" src="https://github.com/user-attachments/assets/552027bd-6c51-4d2c-accd-d5d7be4b06c6" />

Le dernier exercice permet de travailler avec plusieurs associations entre objets.

Nous avons créé trois classes :

* `Auteur`
* `Livre`
* `Bibliotheque`

Un auteur peut écrire plusieurs livres et une bibliothèque peut contenir plusieurs livres.

### Concepts utilisés :

* Association `Auteur → Livre`
* Gestion d'une liste avec `List<Livre>`
* Utilisation de `ArrayList`
* Utilisation de `HashSet`
* Association entre plusieurs objets
* Identifiants automatiques
* Collections Java
* Parcours avec `forEach`
* Redéfinition de `toString()`

Cet exercice permet notamment de comprendre la différence entre un tableau classique et une collection comme `ArrayList`.

---

## 🎯 Objectif général du TP

À travers ces quatre exercices, ce TP permet de pratiquer progressivement :

* Les classes et les objets
* Les attributs et méthodes
* Les constructeurs
* L'encapsulation
* Les attributs `static` et `final`
* Les associations entre classes
* Les tableaux d'objets
* `List` et `ArrayList`
* `Set` et `HashSet`
* Les associations un-à-plusieurs
* La gestion de plusieurs objets
* Le parcours des collections

## 🛠️ Technologies

* **Java**
* **JDK 8+**
* **Programmation Orientée Objet (POO)**



Ce TP m'a permis de mieux comprendre la manipulation des objets et surtout les associations entre plusieurs classes en Java.
