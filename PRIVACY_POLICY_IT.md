# Informativa sulla Privacy — Stride

**Versione:** 2.1  
**Data di aggiornamento:** 16 agosto 2026  
**Lingua:** Italiano  

> Documento informativo ai sensi degli artt. 13–14 del Regolamento (UE) 2016/679 (GDPR) e del D.Lgs. 196/2003 (Codice Privacy), come modificato dal D.Lgs. 101/2018.  
> **Avvertenza:** il presente testo è un modello operativo aggiornato alle prassi GDPR; per la pubblicazione in produzione si raccomanda la revisione da parte di un legale/DPO.

---

## 1. Titolare del trattamento

**Titolare:** Mauro Ferrari (sviluppatore dell’applicazione Stride)  
**Contatto privacy:** `maufer1@gmail.com`  
**Sede / residenza ai fini del contatto:** Italia

Per esercitare i diritti GDPR scrivere all’indirizzo privacy sopra indicato, indicando nell’oggetto “Richiesta privacy Stride”.

---

## 2. Ambito e natura del servizio

L’applicazione è pubblicata come **Stride** (precedentemente MOVE Fitness / M.O.V.E.).

Stride è un’applicazione di **fitness** (corsa, palestra e allenamento Apple Watch) e di **organizzazione dell’allenamento**.  
**Non è un dispositivo medico** (MDR / D.Lgs. 46/1997 e s.m.i.), non fornisce diagnosi, terapie o consulenza sanitaria.

Le “aree di attenzione” / limitazioni fisiche inserite dall’utente sono **preferenze di allenamento autodichiarate**, non cartelle cliniche. Qualora tali dati possano essere qualificati come dati relativi alla salute (art. 9 GDPR), il trattamento avviene solo con **consenso esplicito** dell’interessato (art. 9, par. 2, lett. a).

---

## 3. Categorie di dati trattati

| Categoria | Esempi | Base giuridica tipica |
|---|---|---|
| Dati di account / identificativi | nome profilo, email/telefono opzionali | Art. 6(1)(b) contratto / (a) consenso |
| Dati di allenamento | schede, serie, cronologia sessioni, note | Art. 6(1)(b) |
| Dati biometrici fitness autodichiarati | peso, altezza, composizione corporea opzionale | Art. 6(1)(a)/(b); se riconducibili a salute → Art. 9(2)(a) |
| Aree di attenzione / limitazioni | tag di focus fisico scelti dall’utente | Art. 9(2)(a) consenso esplicito |
| Dati di utilizzo tecnici | log diagnostici locali, preferenze app | Art. 6(1)(f) legittimo interesse / (b) |
| Acquisti in-app | stato abbonamento (via App Store / RevenueCat) | Art. 6(1)(b) |
| Dati HealthKit / Watch (se autorizzati) | frequenza cardiaca, energia attiva, workout | Art. 6(1)(a) + autorizzazione Apple |
| Immagini (import scheda da foto) | foto della scheda cartacea elaborata localmente/via AI | Art. 6(1)(a)/(b) |
| Prompt AI (se funzioni AI attive) | testo/contenuto inviato al modello generativo | Art. 6(1)(a)/(b) |

L’app **non richiede** documenti di identità né dati di pagamento gestiti direttamente dal Titolare (i pagamenti passano da Apple / store).

---

## 4. Finalità del trattamento

1. Erogare le funzionalità fitness (schede, timer, storico, export).  
2. Gestire profili atleta/cliente e preferenze di allenamento.  
3. Sincronizzare allenamenti con Apple Watch (se abilitato).  
4. Gestire abbonamenti e crediti AI.  
5. Migliorare stabilità e sicurezza del prodotto (diagnostica tecnica).  
6. Adempiere obblighi di legge.

**Non** utilizziamo i dati per profilazione pubblicitaria di terzi né per vendita a data broker.

---

## 5. Modalità e luogo di conservazione

- Architettura **offline-first**: la maggior parte dei dati resta sul dispositivo dell’utente (storage locale / Hive).  
- Backup, export o sync avvengono solo se avviati dall’utente o richiesti dalla funzione (es. WatchConnectivity).  
- Periodo di conservazione: fino a cancellazione dell’account/dati dall’app, disinstallazione, o richiesta di cancellazione; i dati di fatturazione restano presso Apple secondo le relative policy.

---

## 6. Destinatari e responsabili del trattamento

Possono trattare dati, nei limiti del servizio:

| Soggetto | Ruolo | Dati tipici |
|---|---|---|
| Apple Inc. / App Store | Pagamenti, hosting app, HealthKit | Acquisti, autorizzazioni sistema |
| RevenueCat | Gestione entitlement abbonamenti | Identificativi abbonamento |
| Google (Gemini / Generative Language API) | Funzioni AI opzionali | Contenuti inviati dall’utente alle API AI |
| Dispositivo / iCloud (se l’utente attiva backup Apple) | Backup di sistema | Dati app secondo impostazioni utente |

I trasferimenti extra-SEE (es. USA) avvengono, ove applicabile, con garanzie di cui al Capo V GDPR (SCC / decisioni di adeguatezza / misure aggiuntive dei fornitori).

---

## 7. Diritti dell’interessato (Capo III GDPR)

Puoi esercitare in qualsiasi momento:

- accesso (art. 15)  
- rettifica (art. 16)  
- cancellazione (art. 17)  
- limitazione (art. 18)  
- portabilità (art. 20)  
- opposizione (art. 21)  
- revoca del consenso (art. 7), senza pregiudicare la liceità del trattamento precedente  
- reclamo al **Garante per la protezione dei dati personali** (www.garanteprivacy.it)

Per cancellare i dati dall’app: usa le funzioni di eliminazione profilo/dati in Impostazioni oppure contatta il Titolare. La disinstallazione rimuove i dati locali residui sul dispositivo, fatte salve copie di backup di sistema create dall’utente.

---

## 8. Minori

Il servizio è destinato a utenti con età conforme ai requisiti dello store e, in Italia, di regola **almeno 14 anni** per il consenso digitale autonomo (art. 2-quinquies Codice Privacy), salvo diversa capacità. Se hai meno di 14 anni serve il consenso del titolare della responsabilità genitoriale.

---

## 9. Sicurezza

Adottiamo misure tecniche e organizzative adeguate al rischio (accesso dispositivo, sandbox iOS, minimizzazione). Nessun sistema è sicuro al 100%: l’utente deve proteggere il dispositivo con codice/biometria e non condividere backup non cifrati.

---

## 10. Cookie / tracking web

L’app nativa non usa cookie di profilazione. Eventuali siti collegati (landing / documenti legali) possono usare cookie tecnici; dettagli nelle relative informative web.

---

## 11. Modifiche

Aggiorneremo questa informativa in caso di variazioni rilevanti. La data in testa indica la versione vigente. L’uso continuato dopo la pubblicazione può costituire accettazione delle modifiche non sostanziali; per modifiche che richiedono un nuovo consenso, verrà richiesto in-app.

---

## 12. Contatti

Email privacy: `maufer1@gmail.com`  
Per questioni legali generiche relative al prodotto: stesso canale o indirizzo indicato su App Store Connect.
