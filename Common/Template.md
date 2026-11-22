

# UC-01 – Nome del Caso d'Uso

## Informazioni Generali

| Campo | Valore |
|--------|---------|
| **ID** | UC-01 |
| **Nome** | Login |
| **Attore Primario** | Utente |
| **Attori Secondari** | Database |
| **Priorità** | Alta |
| **Livello** | User Goal |
| **Trigger** | L'utente apre la schermata di login |

---
<br></br>




## Descrizione

Breve descrizione dell'obiettivo del caso d'uso.

---
<br></br>



## Precondizioni

- L'applicazione è in esecuzione.
- L'utente possiede un account.


---
<br></br>



## Postcondizioni

### Successo

- L'utente è autenticato.
- Viene mostrata la Home.

### Fallimento

- L'utente rimane nella schermata di login.
- Viene visualizzato un messaggio di errore.

---
<br></br>




## Flusso Principale

| Passo | Azione |
|--------|---------|
| 1 | L'utente apre la schermata di login. |
| 2 | Inserisce username e password. |
| 3 | Preme **Accedi**. |
| 4 | Il sistema valida le credenziali. |
| 5 | Il sistema autentica l'utente. |
| 6 | Il sistema mostra la Home. |

---
<br></br>



## Flussi Alternativi

### A1 - Credenziali errate

| Passo | Azione |
|--------|---------|
| 4a | Username o password non validi. |
| 5a | Il sistema mostra un messaggio di errore. |
| 6a | L'utente può riprovare. |

---

### A2 - Campi vuoti

| Passo | Azione |
|--------|---------|
| 2a | Uno o più campi sono vuoti. |
| 3a | Il sistema evidenzia i campi mancanti. |

---
<br></br>



## Eccezioni

- Database non raggiungibile.
- Server non disponibile.
- Timeout della richiesta.

---
<br></br>




## Requisiti soddisfatti

- RF-01
- RF-02
- RF-05

---
<br></br>



## Note

Eventuali osservazioni aggiuntive.

<br></br>
<br></br>
---
---
<br></br>
<br></br>