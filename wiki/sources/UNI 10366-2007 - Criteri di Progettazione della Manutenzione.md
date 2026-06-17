---
type: source
title: "UNI 10366:2007 - Manutenzione - Criteri di progettazione della manutenzione"
created: 2026-06-13
updated: 2026-06-13
tags:
  - laboratorio-medico
  - source
  - manutenzione
  - norma-uni
  - progettazione
status: stable
related:
  - "[[Terminologia e Tipologie di Manutenzione (UNI 13306)]]"
  - "[[UNI EN 13306-2018 - Manutenzione Terminologia]]"
  - "[[UNI 10147-2013 - Manutenzione Termini Aggiuntivi]]"
  - "[[UNI 11063-2017 - Manutenzione Ordinaria e Straordinaria]]"
  - "[[Gestione degli Asset e Apparecchiature di Laboratorio (ISO 55001)]]"
sources:
  - ".raw/unlocked_UNI 10366_2007 - Manutenzione - Criteri di progettazione della manutenzione.pdf"
address: c-000173
---

## Sintesi

**UNI 10366:2007** ("Manutenzione - Criteri di progettazione della manutenzione", revisione della UNI 10366:1994) specifica i **criteri e metodi generali per progettare la manutenzione** di un'azienda, indirizzando la scelta delle **politiche di manutenzione** in funzione delle caratteristiche e del comportamento dei beni, in coerenza con gli obiettivi aziendali, e la **quantificazione delle risorse e degli strumenti operativi** necessari per attuarle. Si applica alla funzione manutenzione di aziende industriali (estensibile per analogia a strutture sanitarie/laboratori che gestiscono parchi di apparecchiature).

Richiama e si fonda su **UNI 9910** (fidatezza), **UNI 10147:2003**, **UNI 11063**, **UNI EN 13306**, **UNI 10584** (sistema informativo di manutenzione), **UNI 10992** (budget di manutenzione).

## Struttura della norma

1. **Introduzione / Scopo e campo di applicazione**
2. **Riferimenti normativi e Termini e definizioni** - introduce: *bene critico/entità critica*, *costo d'indisponibilità*, *costo di sostituzione*, *segnale debole*.
3. **Raccolta delle informazioni** (cap. 4): censimento dei beni (inventario patrimoniale), costi di sostituzione, costo d'indisponibilità/disservizio, manutenibilità dei beni, specifiche tecniche, manuali d'uso/manutenzione, diario macchina, stima di comportamento, tracciato impiantistico; piani di produzione/servizio; risorse aziendali ed esterne; funzioni di supporto.
4. **Definizione della politica aziendale di manutenzione** (cap. 5):
   - **5.2 Criteri per la selezione dei beni**: criteri di sicurezza (vincolanti, di legge) + criteri tecnico-economici, sintetizzati nel **diagramma a quadranti costo di sostituzione (X) / manutenibilità (Y)**:
     - **Quadrante A** (bassa manutenibilità, basso costo): non conviene manutenere - sostituire a guasto.
     - **Quadrante B** (alta manutenibilità, basso costo): scelta manutenere/sostituire in base alla convenienza economica.
     - **Quadrante C** (alta manutenibilità, alto costo): conviene manutenere.
     - **Quadrante D** (bassa manutenibilità, alto costo): occorre **migliorare la manutenibilità** (interventi migliorativi, attrezzature dedicate).
     - Output: lista dei beni "da non manutenere" (sostituire a guasto) e lista "da manutenere".
   - **5.3 Scelta delle politiche di manutenzione** - processo a tre fasi:
     - **Fase 1 - Individuazione dei beni critici**: elementi discriminanti in ordine di priorità - sicurezza delle persone, effetti ambientali, disposizioni legislative (controlli/collaudi periodici), disponibilità richiesta dai piani di produzione, ridondanza, flessibilità impiantistica, effetti su qualità del prodotto, effetti sul danneggiamento/indisponibilità. I beni **non critici** vengono assegnati direttamente a una tipologia d'intervento (a guasto, preventiva ciclica, secondo condizione/predittiva, migliorativa); i beni **critici** richiedono ulteriore analisi.
     - **Fase 2 - Beni critici: analisi guasti/effetti/criticità**: gruppo multidisciplinare; analisi FMECA-like (scomposizione in parti funzionali/componenti, modi di guasto, frequenza/durata, effetti su quantità/qualità); **indice di criticità del guasto** basato su frequenza, durata del disservizio, gravità delle conseguenze (produzione, scarti, derive qualitative, sicurezza/ambiente) - per definire **priorità** (non valori assoluti). Per i beni critici si privilegiano politiche preventive (secondo condizione/predittive) rispetto alla manutenzione a guasto, e interventi migliorativi per aumentare affidabilità/disponibilità/manutenibilità.
     - **Fase 3 - Valutazione economica - costo globale di manutenzione**: tecniche ACE (Analisi Costi-Efficacia) / ACB (Analisi Costi-Benefici). Il **costo globale** = costo proprio di manutenzione (manodopera, materiali/ricambi, attrezzature, costi generali, + costi di programmazione per la preventiva ciclica, + costi di controlli/ispezioni/strumenti di monitoraggio per la preventiva su condizione) + costi indotti (immobilizzo scorte, costo d'indisponibilità, immobilizzo scorte prodotto finito, scarti, mancata erogazione del servizio). Obiettivo: **manutenzione produttiva** - sinergia manutenzione/produzione per il miglioramento continuo del risultato operativo.
5. **Stesura del piano di manutenzione** (cap. 6): piano annuale (budget), in collaborazione con produzione/acquisti/personale; eventuali piani specifici o poliennali.
6. **Definizione e quantificazione delle risorse necessarie** (cap. 7): manodopera per mestiere/professionalità (incluso il ruolo dei conduttori in "manutenzione produttiva" - automanutenzione, segnali deboli); materiali (approvvigionamento "a fabbisogno"/"a scorta"/"a punto d'ordine", gestione scorte coordinata tra manutenzione/approvvigionamenti/magazzino, analisi critica periodica delle scorte); mezzi e attrezzature di supporto; attrezzature d'ispezione.
7. **Controllo economico della manutenzione** (cap. 8, rinvio a UNI 10992) e **Sistemi informativi per la progettazione della manutenzione** (cap. 9, rinvio a UNI 10584).
8. **Informazioni di ritorno** (cap. 10): verifica del "progetto manutenzione" tramite flussi informativi tecnici (**MTBF, MTTR, tasso di guasto**, diario macchina) ed economici (consuntivo); **riprogettazione continua della manutenzione** verso l'"ottimo economico" dinamico, con obiettivo "zero guasti, zero difetti".

## Rilevanza per il laboratorio

UNI 10366 fornisce il **metodo sistematico** per decidere, per ogni apparecchiatura del parco analitico, **quale politica manutentiva applicare** (a guasto / preventiva ciclica / secondo condizione-predittiva / migliorativa / straordinaria) sulla base di:
- la **criticità clinica e operativa** dello strumento (impatto su sicurezza, continuità diagnostica, qualità analitica - elementi a)-h) del cap. 5.3.2.1, direttamente traducibili in criteri di criticità degli analizzatori di laboratorio);
- il rapporto **costo di sostituzione / manutenibilità** (quadranti A-D), utile per decisioni "manutenere vs. sostituire" su strumentazione obsoleta;
- il **costo globale di manutenzione**, che nel laboratorio include esplicitamente il costo d'indisponibilità di un analizzatore (mancata erogazione di referti, ripetizione di test, impatto su TAT).

Questo metodo di **selezione delle politiche** si integra con il vocabolario terminologico già trattato in **[[Terminologia e Tipologie di Manutenzione (UNI 13306)]]** e con il **SAMP** descritto in **[[Gestione degli Asset e Apparecchiature di Laboratorio (ISO 55001)]]**, fornendo i criteri operativi con cui un laboratorio può differenziare il trattamento manutentivo del proprio parco strumenti (es. analizzatore core 24/7 = bene critico con manutenzione preventiva/predittiva spinta; centrifuga di riserva = bene non critico, gestibile a guasto).
