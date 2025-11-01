# WebApp Comuni

## Overview
Questo progetto implementa una web application per la gestione dei Comuni italiani, sviluppata all'interno del corso di Ingegneria del Software.  
La WebApp permette visualizzazione e gestione CRUD di dati relativi ai Comuni, con persistenza su database H2 integrato.

---

## Ingegneria dei Requisiti
### Requisiti Funzionali
- FR1: L’utente può visualizzare la lista dei Comuni
- FR2: L’utente può aggiungere un nuovo Comune
- FR3: L’utente può modificare i dati di un Comune esistente
- FR4: L’utente può eliminare un Comune
- ...

### Requisiti non Funzionali
- Semplicità di utilizzo
- Rapid setup / rapid deploy locale
- Persistenza dati senza necessità di installare DB esterni

### Elicitazione dei requisiti
- Analisi del dominio
- Modellazione concettuale tramite UML (prodotta in Visual Paradigm)
- ...

---

## Analysis Model
L’analisi è stata svolta tramite UML ed è presente nel file Visual Paradigm incluso nel progetto.

UML prodotti:
- Use Case Diagram
- Class Diagram
- Sequence Diagrams
- Project Class Diagram

---

## Software Design
### Architectural Style
Architettura **MVC** tipica Spring Boot strutturata in:
- Controller
- Service
- Repository
- Model

### Design Patterns
- **Dependency Injection** (nativo Spring)
- **Repository Pattern** per l’accesso ai dati tramite Hibernate/JPA
- **Factory** per la creazione degli oggetti

---

## Implementazione
- **Language**: Java
- **Framework**: Spring Boot
- **Persistence**: Hibernate + JPA
- **Database**: H2 embedded in memory (per semplicità ed esecuzione immediata)

---

## Strategia di Testing
- Unit testing (JUnit)
- Test di integrazione su repository H2 in embedded mode

---

## Project Management
- GitHub per Version Control e Issue Tracking
- Branching semplice main/feature branch

---

## Conclusione
Il progetto dimostra la costruzione di una WebApp completa backend-centric seguendo tecniche standard di Ingegneria del Software.  

---

## Autori
- **Michael Cimarelli** 
- **Leonardo Pierucci**
