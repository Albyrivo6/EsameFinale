# 03/02

## Spiegazioni
### Unit Testing
HP, Happy Path, caso ideale giusto senza dare errori
Casi errati, e fare lanciare tutte le eccezioni
    
    - Eccezioni vanno lanciate il prima possibile, il catch il più tardi possibile
2 framework x testing, nUnit/xUnit, xUnit da usare è più nuovo

## Done
### Unit Testing
Inizio unit testing razzaService

- Inizializzazione progetto unit testing con xUnit project
- Inizio implementazione _razzaService per chiamare i metodi (avuto grossi problemi con il capire gli input necessari, e implementazione delle varie parti)
- Scrittura non completa dei primi insert

## To do

Scrivere file di unit testing x RazzaService

- Insert (HP, Validation Error)
- Update (HP, ID not found)
- Delete (HP, ID not found)
- Get (HP, ID not found)
- Find (HP, [](vuoto))
- Count (HP, ∅(null))

<br>
<br>
<br>
<br>

# 04/02
## Spiegazioni
SCRIVILO

## Done
### Unit testing
Continuo unit testing RazzaService
- Finitura implementazione _razzaService e tutte le implementazioni necessarie legate
- Implementazione metodi testing completa di: Insert, Update, Delete (con modifica da fare), Get
- Metodi mezzi implementati da controllare e finire: Find, Count

## To do 
- Fixare Find, Count
- Chiedere tipo diverso di testing
- Nuovi testing

<br>
<br>
<br>
<br>

# 05/02
## Spiegazioni
### Ricerche mie
- Altri tag di testing, trovato [Theory], esegue più volte il test con questo tag in base a quanti [InlineData()] sono inseriti nei tag del metodo
- [InlineData()] i dati forninti manualmente per le molteplici esecuzioni del metodo con tag [Theory]

## Done
### Unit testing
- Implementazione completata di metodi: Find, Count, Delete
- Finito unit testing RazzaService


<br>
<br>
<br>
<br>