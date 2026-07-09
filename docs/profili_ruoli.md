---
title: Profili e Ruoli
tipologia: software
nome: HyperBeauty
produttore: Custom S.p.A.
argomento: Profili utente e ruoli di accesso al gestionale
autore: Robuschi Ivan
documento_destinato_a: partner
data_creazione: 2026-07-05
revisione: "1.1"
lingua: it
livello_corso: level_2
tipo_contenuto: guida-operativa
sezione_ordine: 9
prodotto_versione: "2026"
keywords:
  - profili
  - ruoli
  - permessi
  - accessi
  - sicurezza
---

# Profili e Ruoli

I profili e i ruoli definiscono **chi può fare cosa** all'interno di HyperBeauty: assegnando a ciascun operatore un ruolo, si controlla l'accesso alle diverse aree del gestionale (agenda, cassa, documenti, report, impostazioni).

Il funzionamento è in due tempi: prima si crea un **Ruolo** (un insieme di permessi), poi si crea un **Profilo** che collega l'operatore ai ruoli sui vari livelli dell'organizzazione. Tutto si gestisce da **Configurazione → Autorizzazioni**.

---

## A cosa servono

Un **Ruolo** è il set di permessi che abilita o limita le funzioni visibili (es. Titolare, Reception, Operatore). Un **Profilo** è l'associazione tra l'operatore e i ruoli, definita per ogni Azienda, Sede e Area.

!!! tip "Perché è importante"
    Assegnare ruoli corretti semplifica l'uso quotidiano — ogni operatore vede solo ciò che gli serve — e mantiene ordinati dati e documenti, mostrando a ciascuno l'ambito di sua competenza.

---

## Passo 1 — Crea un nuovo Ruolo

Vai su **Configurazione → Autorizzazioni → Ruoli** e clicca **Nuovo Ruolo**. L'elenco mostra i ruoli esistenti con **Id, Livello, Nome e Permessi**.

![Elenco dei ruoli con il pulsante Nuovo Ruolo](assets/images/profili_ruoli/step_01.png)

!!! info "Il livello del ruolo"
    Ogni ruolo è definito su un **livello** dell'organizzazione — **Gruppo, Azienda, Sede o Area** — così i permessi si applicano esattamente all'ambito desiderato.

## Passo 2 — Scegli i permessi per categoria

Nella finestra **Permessi Ruolo** attivi o disattivi i permessi raggruppati per **categoria**: dati anagrafici, gestione profili e ruoli, trattamenti, prodotti, servizi, offerte, statistiche, report personalizzati, centri di costo e altro. Ti basta spuntare le voci che il ruolo deve poter usare.

![Selezione dei permessi per categoria](assets/images/profili_ruoli/step_02.png)

## Passo 3 — Regola i permessi di dettaglio

Ogni categoria si espande in **permessi granulari**. Per l'**Uso Documenti**, ad esempio, puoi decidere per i documenti di vendita e di acquisto se il ruolo può **Creare, Leggere, Modificare o Eliminare**, oltre alla **visibilità dei preventivi** e delle stampe/report. È così che stabilisci con precisione cosa ciascun ruolo vede e può fare.

![Permessi di dettaglio sull'uso dei documenti](assets/images/profili_ruoli/step_03.png)

!!! tip "Suggerimento"
    Usa il campo **Cerca** in alto nella finestra per trovare velocemente un permesso senza scorrere tutto l'albero.

## Passo 4 — Crea il Profilo e assegna i ruoli

Passa a **Configurazione → Autorizzazioni → Profili**. Nella **Configurazione Operatore** scegli, per ogni **Azienda, Sede e Area**, il **Ruolo** da applicare tramite gli appositi menu a tendina, poi premi **Salva**. In questo modo l'operatore erediterà i permessi giusti su ciascun livello.

![Assegnazione dei ruoli nel profilo operatore](assets/images/profili_ruoli/step_04.png)

!!! info "Ruoli diversi su livelli diversi"
    Uno stesso operatore può avere un ruolo su una sede e un ruolo differente su un'altra: basta impostare il menu **Ruolo** riga per riga.

---

*Documento a cura di Custom S.p.a. — HyperBeauty Training Program — Versione 1.0 — Luglio 2026*
