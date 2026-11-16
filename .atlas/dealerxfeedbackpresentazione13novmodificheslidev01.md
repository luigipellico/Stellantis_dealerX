---
unique-name: dealerxfeedbackpresentazione13novmodificheslidev01
display-name: DealerX Feedback Presentazione 13nov Modifiche Slide v0.1
category: GENERAL
description: - Giudizio sulla soluzione positivo. Matt Regan in chiusura [1:18:09]: "all the stuff you submitted and the PoV, that was good… we just need to cross a few I's and dot a few T's". Il problema non è
---

DealerX Sales Portal – Risposta RFQ Stellantis

Esito della presentazione del 13/11 e riallineamento della proposta

Analisi della trascrizione, richieste del cliente e modifiche da apportare al Defense Meeting deck e alla Technical Proposal

# 1. Sintesi per la decisione

- Giudizio sulla soluzione positivo. Matt Regan in chiusura [1:18:09]: "all the stuff you submitted and the PoV, that was good… we just need to cross a few I's and dot a few T's". Il problema non è tecnico ma di perimetro e coerenza commerciale.
- Il cliente ha detto esplicitamente cosa vuole [1:15:53]: "mini web app, sales performance and obviously the rollout, you find the way how to integrate. Run AMS, you do not integrate, but you do a proper quote to us… otherwise we do not fulfil the scope". Ha chiesto anche di includere il forum [1:11:49] e ha detto che la call con loro di lunedì non serve: "we already told you what to include".
- Incoerenze rilevate dal cliente: il forum è core nella TP 13 ("Mandatory in first release") e add-on nella DEF 10 [Matt 1:14:49]; la TP 46 presenta come "Added value" il Context service (dealer entity e brand), che per Matt deve essere di base [1:07:17]; Nicola ha confermato a voce che "le altre cinque" box della TP 46 sono incluse [1:05:04–1:05:18].
- Run/AMS: l'RFQ §6.2 chiede una "Application Maintenance Support Costs high level estimation" su 3.000–6.000 ticket/anno, Build e Run quotati separatamente e la quotazione del KT. Il Run va quindi tolto dagli add-on "S/M/L" e quotato in forma budgettaria: separato dal prezzo build (come dice Cerdelli), ma presente (come dice Nicola).
- Forum: la posizione interna indicata è "forum non incluso". È in contrasto diretto con Q-008 ("mandatory for the first release… must not be treated as an optional add-on") e con la richiesta verbale di Mikita e Matt. Va deciso lunedì in modo esplicito (D1), perché è il punto più visibile dell'incoerenza.
- Prezzo: la quotazione emessa (STLA_DealerX_Economics_V01) vale 499 k€ di build con margine 23%, più 124 k€/anno di AMS. Le richieste del cliente nella forma "essential" valgono indicativamente circa +100 k€; nella forma piena circa +250 k€. Restare allo stesso prezzo è possibile solo con compensazioni sul perimetro attuale (§5). Il file economico va anche ripulito e corretto prima di ogni reinvio (§6).
- Altre richieste: una nuova slide dedicata ad AEM, promessa da Nicola a Diletta [52:28]. Un piano Spagna con un contenuto funzionale chiaro per ogni release, non un "almost empty portal" [Mikita 57:31]. Va ripensato il valore del rilascio del 22/12 [Matt 51–56].
- Da declassare o rimuovere dagli add-on: Ticketing extensions ("I don't need an extension… if I have a good front end I'm good" [1:09:39]) e NSC & incentive claims ("not necessarily part of this tender" [1:12:59]). La legacy migration resta opzionale e ridotta ("we don't need a lot of content to migrate").
- Il cliente consente il reinvio: "if needed we are even able to open the portal so that you really resubmit" [1:16:54].

# 2. Richieste del cliente: cosa vuole e cosa no

Lettura puntuale della trascrizione. Priorità:

- MUST: richiesto come condizione per "fulfil the scope".
- ALTA: incoerenza segnalata dal cliente.
- MEDIA: chiarimento.
- BASSA/OUT: il cliente non è interessato.

| # | Tema | Chi e cosa ha detto | Lettura / vincoli | Azione proposta | Priorità |
|---|---|---|---|---|---|
| R1 | Run / AMS | Mikita [1:11:27]: "running AMS is something you need to quote fully, but is an optional on top of the current quote, but it should be there… I want to consider AMS with you… 2027, 2028 full speed". [1:15:53]: "proper quote". | Coerente con RFQ §6.2: AMS high-level su 3.000–6.000 ticket/anno, Build e Run separati e opzionali per Stellantis, KT quotato. Nicola: non si può escludere. Cerdelli: forma budgettaria. | Togliere "Run & AMS" dalla DEF 10. Quotazione budgettaria annua per 2027, 2028 e anno a regime, per fascia 3.000 / 6.000 ticket: L2/L3, SLA IMS, pool evolutivo; KT quotato a parte. Aggiornare DEF 29 / TP 70 e l'offerta economica. | MUST |
| R2 | Forum & community | Mikita [1:11:49]: "something small, I don't see why that could be an add-on". Matt [1:14:49]: core nella slide 14, Wave 0 e 2, ma add-on qui: "either it's in or it's out". Nicola [1:15:28]: "misalignment… we will review". | Q-008: forum obbligatorio nella prima release, nel prezzo, non add-on. Posizione interna comunicata: forum NON incluso. La card add-on DEF 10 riporta anche "Mandatory in the first release" (refuso). | Decisione D1. In ogni caso il forum deve comparire in UN solo posto, con la stessa definizione in DEF e TP. | ALTA |
| R3 | Rollout EE + training ai paesi | Mikita [1:12:20–1:12:38]: "of course we want to roll out everywhere… the training with the other countries to know how to do content on this portal should of course be part of". [1:14:02]: "e-market rollout, which is by design the must". | RFQ: "live in 1 year in EE". Q-036: training per utenti, autori, admin, supporto, sviluppatori. RFQ: 2 mesi di post go-live per ogni go-live. Il "close support" (hypercare intensivo) è negoziabile. | Portare nel prezzo un "rollout essential":<br>• setup per mercato;<br>• publisher NSC delegati;<br>• train-the-trainer per i content author di ogni paese;<br>• 2 mesi di post go-live per wave.<br>Lasciare opzionali floor-walking e hypercare esteso. | MUST |
| R4 | Mini web apps & forms | Mikita [1:13:20]: "two things that are key on top for me, mini apps and forms… Logotel having some mini apps, and not only Logotel… that will enter in the scope of migration". [1:14:30]: "a must". | La TP 13 le elenca già tra le "core functionalities" (SDK micro-frontends): il cliente le ha lette come incluse. In stima sono add-on (FE06 + quota BE Opz. D). | Includere il container mini-app/form (micro-frontend, BFF, API Connect) e un numero definito di mini-app/form di riferimento (es. 2–3 da Logotel). Le ulteriori vanno a pacchetti S/M/L o nella migrazione per sorgente. | MUST |
| R5 | Sales performance | Mikita [1:14:02]: lead da Customer First (C1st), "not rocket science, but integration is important"; Power BI "we have a solution already… just to integrate". "Sales performance and mini web apps are… a must". | Q-009 li definiva "indicative future-value examples": ora il cliente li chiede. La TP 14 indica già come core "Embedded KPIs, Power BI embedding". Il Customer First CRM widget è stato dichiarato opzionale da Nicola [1:03:57]. | Includere:<br>• embedding dei report Power BI esistenti;<br>• widget lead C1st (lettura e deep-link);<br>• KPI via inbound connectors su sorgenti esistenti.<br>Restano opzionali: dashboard custom nuove, KPI coach AI, forecasting, OMNI order validation. | MUST |
| R6 | Ticketing | Mikita [1:09:39]: "I don't need an extension… I need a front end that allows me to be a front officer… keep the integration in real time… if I'm having a good front end I'm good". | Q-020: ConnectD create, update, view, status; DigitalMe open, view, status. La DEF 9 non cita "update". | Rimuovere la card "Ticketing extensions" dalla DEF 10. Rafforzare la card core: front office real-time su DigitalMe e ConnectD (create, update, view, status, notifiche). Console admin e adapter ServiceNow solo nella TP, come evoluzione. | MEDIA |
| R7 | Legacy migration | Mikita [1:12:59]: "less probably needed… usually we don't need a lot of content to migrate. We need, but not that much… that is fine". | Q-004: content, documents, FAQs e users in migration scope; redirect degli URL legacy. | Resta add-on, prezzata per sorgente. Inserire la dicitura "light migration" e il legame con le mini-app (R4). | BASSA |
| R8 | NSC & incentive claims | Mikita [1:12:59]: "not super interested in the integration… not necessarily part of this tender yet". | — | Togliere dalla DEF 10 (o spostare in una riga "future evolutions"). | OUT |
| R9 | Customer First CRM widget, gamification | Nicola [1:03:57]: CRM widget con KPI C1st "optional… out of scope of the price". Mikita: "what was in purple is optional". | Si sovrappone a R5 (i lead C1st ora sono un must). | Separare il "lead widget C1st" (incluso, R5) dalla "CRM dashboard avanzata" (opzione). La gamification resta un'opzione (E9). | MEDIA |
| R10 | Context service e TP 46 | Matt [1:07:17]: dealer entity e brand "kept in context no matter what, not as an added value. I get the VINs and the ticket stuff". Mikita [1:05:04]: "all these other five are included, correct?" Nicola: "Yes". | Le 5 box della TP 46 confermate a voce: OMNI order validation, Context service, Ticketing abstraction, AI observability & FinOps, Widget onboarding packages. Nella DEF 10 alcune sono add-on (OMNI dentro Sales performance, widget packages). | Riscrivere la TP 46 con due blocchi etichettati "Included" / "Optional".<br>• Dealer entity e brand: nel core (Wave 0).<br>• VIN e ticket context: da decidere (FE09 è add-on in stima).<br>• OMNI order validation: dichiararlo opzionale per iscritto, correggendo il "Yes". | ALTA |
| R11 | Release 22/12 e contenuto per la Spagna | Matt [51–56]: un rilascio "SSO-lite" a dicembre seguito dal pilota a febbraio è "of limited benefit"; con rilasci piccoli i mercati "lose interest". Mikita [57:31]: "something consistent… not an almost empty portal… what you are shipping in terms of features". Roadmap Omni poco affidabile. | Matt accetta l'allineamento con Omni "as aspirational". | Nuova slide "Spain pilot: what dealers get, release by release" con l'elenco funzionale. Valutare il 22/12 come soft-launch tecnico per un pilot group e il lancio ai dealer quando ci sono landing, news, documenti, bookmark e ticketing. Svincolare il piano dalla data Omni. | ALTA |
| R12 | AEM esistente | Diletta [51:25]: oggi usano experience fragment; permessi admin/read-only gestiti in AEM; tassonomia per mercato e lingua; "is there something you expect from us… to avoid a blocking point". Nicola [52:28]: nuova slide dedicata. | La TP 28 parla di "content fragments" e non cita gli experience fragment: va allineata. | Nuova slide AEM (§4.3) e proposta di deep-dive con Cerdelli e il team Adobe. | ALTA |

Nota: in chiusura Mikita parla di "the elephant in the room" [1:16:54] senza dire quale sia. Il contesto (ultimo tema trattato) fa pensare al riallineamento commerciale e di perimetro. Da verificare con Nicola.

# 3. Nuovo perimetro funzionale proposto (slide 9 e 10)

Ragionamento per funzionalità, come nelle slide attuali. In giallo le voci che cambiano.

| Funzionalità | Deck 13/11 | Proposta | Contenuto della card / note |
|---|---|---|---|
| Access & SSO | Incluso | Incluso | Aggiungere: dealer entity e brand mantenuti nel contesto su tutte le pagine e nei deep-link (risposta a Matt) |
| Personalised landing | Incluso | Incluso | Invariata |
| News & knowledge | Incluso | Incluso | Citare l'uso degli experience fragment e della tassonomia AEM esistenti |
| Document repository | Incluso | Incluso | Invariata |
| Search & notifications | Incluso | Incluso | Invariata |
| Tickets · DigitalMe | Incluso | Incluso | Testo "front office real-time": open, view, follow status, notifiche |
| Claims · ConnectD | Incluso | Incluso | Aggiungere "update" (Q-020): create, update, view, status widget e dashboard |
| Applications & SalesWeb | Incluso | Incluso | Invariata |
| AI search & assistant | Incluso | Incluso | Invariata |
| Carflow V2 agent | Incluso | Incluso | Invariata |
| Multilingual & accessible | Incluso | Incluso | Invariata (eventualmente come riga di piede, per liberare spazio) |
| Mini web apps & forms | Add-on | INCLUSO (essential) | Container micro-frontend, form dinamici, N mini-app di riferimento (da Logotel); le ulteriori a pacchetti S/M/L |
| Sales performance | Add-on | INCLUSO (essential) | Power BI esistente embedded, widget lead Customer First, KPI da sorgenti esistenti. Opzionali: dashboard nuove, KPI coach, forecasting, OMNI order validation |
| EE market rollout & training | Add-on | INCLUSO (essential) | Setup mercati, publisher NSC delegati, train-the-trainer per i content author, 2 mesi di post go-live per wave. Opzionali: floor-walking, hypercare esteso |
| Forum & community | In entrambe (refuso) | DECISIONE D1 | Se fuori: card add-on SENZA "Mandatory in the first release" e gestione esplicita di Q-008. Se dentro: card core "essential" (canali, post, commenti, reazioni, moderazione per mercato) |
| Run & AMS | Add-on S/M/L | QUOTATO A PARTE | Fuori dalla griglia add-on: riquadro "Run & AMS quoted separately (budgetary, 2027–2028)" con rimando alla DEF 29 |
| Ticketing extensions | Add-on | RIMOSSO | Il cliente non le vuole; resta nella TP come evoluzione verso ServiceNow |
| NSC & incentive claims | Add-on | RIMOSSO | Non di interesse per questa gara |
| Legacy migration | Add-on | Add-on | Per sorgente, "light"; collegata alle mini-app |
| Connected vehicle & service | Add-on | Add-on | Invariata (nessun commento del cliente) |
| Campaigns & engagement | Add-on | Add-on | Gamification, raccomandazioni, PWA push |
| Personal widgets | Add-on | Add-on (da allineare) | La TP 14 dichiara core "build-your-own widgets": allineare (wizard opzionale, oppure togliere dalla TP 14) |
| More AI agents | Add-on | Add-on | Invariata |
| AI Knowledge Base extensions | Add-on | Add-on | Invariata (incluso Kendra→Bedrock) |

Effetto sul layout: la DEF 9 passa da 12 a 14–15 card (griglia 5×3 o 4×4, testi più corti); la DEF 10 scende a 7–8 card più il riquadro Run & AMS. In alternativa si mantiene la griglia 4×3 spostando "Multilingual & accessible" nel sottotitolo e unendo "Search & notifications" con "AI search".

# 4. Modifiche slide per slide

## 4.1 Defense Meeting deck (ENG_DealerX_DefenseMeeting_v1.0.pptx)

| Slide | Oggi | Modifica | Rif. |
|---|---|---|---|
| DEF 7 – Five commitments | Hot release fino a fine febbraio con "forum" | Allineare il forum a D1; riformulare la release del 22/12 secondo D4 | R2, R11 |
| DEF 8 – Four ways to work | Cita "Forum / community" e "Mini web apps & forms" | Mini web apps confermate; forum secondo D1 | R2, R4 |
| DEF 9 – What is included | 12 card | • Aggiungere Mini web apps, Sales performance, EE rollout & training (essential).<br>• Aggiungere "update" su ConnectD e il contesto dealer/brand in Access & SSO.<br>• Forum secondo D1.<br>• Aggiornare il sottotitolo ("Spain pilot, Wave 1 and EE rollout…") e le note relatore. | R3–R6, R10 |
| DEF 10 – Add-ons | 13 card: tra queste Forum ("Mandatory in the first release"), Run & AMS, Ticketing extensions, Incentive claims | • Rimuovere: Run & AMS, Ticketing extensions, NSC & incentive claims, Mini web apps, Sales performance, EE rollout.<br>• Forum: rimuovere, oppure lasciarlo senza "Mandatory" se D1 = fuori.<br>• Aggiungere il riquadro "Run & AMS: quoted separately".<br>• Aggiungere le versioni "plus" dei must (dashboard nuove, KPI coach, hypercare esteso). | R1–R8 |
| DEF 11 – PoV to production | "Community participation – Wave 0 · to confirm"; Sales Manager KPIs "Option" | Forum secondo D1; KPI e lead C1st → "Wave 1–2, included (essential)"; OMNI order validation → "Option" | R2, R5 |
| DEF 12 – Architecture | "Forum and community on Aurora" | Secondo D1 (se fuori: "optional module") | R2 |
| NUOVA dopo DEF 12/13 – AEM | — | Slide "How we use your AEM" (contenuti al §4.3) | R12 |
| DEF 24 – Delivery plan | "SSO release 22 Dec, Spain pilot end Feb"; mini web apps in Wave 2 | Titolo e barra R1 secondo D4; mini web apps e sales performance come incluse nella loro wave; rollout EE con training per mercato | R3, R4, R11 |
| DEF 25 – Wave 0 | Elenco delle hot release (forum a inizio febbraio) | Trasformare in "what Spanish dealers get, release by release" con l'elenco funzionale; forum secondo D1 | R11 |
| NUOVA dopo DEF 25 – Spain pilot content (facoltativa) | — | Tabella release → funzionalità → utenti (risponde a Mikita [57:31]) | R11 |
| DEF 28 – Team | Change & Training Lead | Confermare la capacità di training e rollout per mercato | R3 |
| DEF 29 – Run & AMS | "Run is a separate, optional package"; stima senza numeri | Mantenere "separate", ma aggiungere:<br>• valori budgettari annui (2027, 2028, a regime) per fascia 3.000/6.000 ticket;<br>• KT quotato;<br>• pool evolutivo;<br>• rapporto tra garanzia e AMS (Q-040). | R1 |
| DEF 32 – Reuse, extend, build | Riga "Forum and community – Built from scratch on Aurora – New" | Secondo D1 | R2 |
| DEF 33 – Deliverables | D12 "per wave", D15 KT "On request", D19 AMS | D12: training per mercato EE. D15: "quoted separately". D19: legato alla quotazione Run | R1, R3 |
| DEF 34/35 – Assumptions | — | Aggiungere:<br>• numero di mini-app/form incluse;<br>• Power BI e API C1st esistenti e disponibili;<br>• training in modalità train-the-trainer (lingua EN);<br>• volumi AMS di 3.000–6.000 ticket;<br>• istanza AEM esistente riusata. | R3–R5, R12 |
| DEF 36 – Exclusions | E9 "Gamification and the other optional services" | Allineare E9 al nuovo elenco di opzioni; escludere esplicitamente le dashboard nuove e il forecasting | R5, R9 |
| DEF 37–39 – Traceability | Riga "Forum mandatory in the first release" | Aggiornare: forum (D1), mini web apps, KPI, rollout, AMS e KT | tutte |

## 4.2 Technical Proposal (ENG_DealerX_Technical_Proposal_v1.0.pptx)

Il cliente legge la TP come documento contrattuale. Oggi è più ampia della DEF 9 e alimenta quindi l'aspettativa che siano inclusi mini web apps, Power BI, widget personali e contesto pagina.

| Slide | Oggi | Modifica | Rif. |
|---|---|---|---|
| TP 5, 7 – Executive summary / delivery path | Forum nelle hot release; mini web apps in Wave 2 | Allineare a D1 e D4; mini web apps incluse | R2, R4, R11 |
| TP 12–14 – Core functionalities | Forum "Mandatory in first release"; Mini web apps; Analytics con Power BI; User personalisation con build-your-own widgets; Ticket forms con contesto (page, dealer, VIN) | • Aggiungere una colonna "Included / Option" per ogni modulo, coerente con la DEF 9/10.<br>• Forum secondo D1.<br>• Widget wizard e contesto VIN → Option, se così restano in stima. | R2, R4, R5, R10 |
| TP 15 – Coverage matrix | Dashboard Wave 1–2; forum Wave 0/2; context service Wave 0 | Allineare alla DEF 9 aggiornata (sales performance essential inclusa) | R5 |
| TP 17 – Ticketing | KPI ticket via Power BI | Enfasi sul front office real-time; KPI ticket come option | R6 |
| TP 21 – PoV to production | Come DEF 11 | Come DEF 11 | R2, R5 |
| TP 24–26 – Widget e applicazioni | C1st e OMNI "Future value" | Lead C1st → incluso (essential); OMNI → option | R5 |
| TP 27 – Legacy migration | Cinque step per tool | Aggiungere le mini-app Logotel come caso di re-platform a widget/mini-app | R4, R7 |
| TP 28 – Content governance AEM | "content fragments" | Allineare all'uso attuale di experience fragment, permessi e tassonomia (oppure rimandare alla nuova slide AEM) | R12 |
| TP 36 – Reuse matrix | Forum "New" | Secondo D1 | R2 |
| TP 44 – Critical analysis | "Forum mandatory in the first release" | Secondo D1 (se fuori, va motivato rispetto a Q-008) | R2 |
| TP 46 – Added value | 6 box senza un'indicazione chiara di incluso/opzionale; Context service come "added value" | Due blocchi espliciti:<br>• INCLUDED: Context service dealer/brand, Ticketing abstraction, AI observability, Widget onboarding packages (contratto standard).<br>• OPTIONAL: Customer First CRM dashboard, OMNI order validation, gamification, PWA, image/video search, connected vehicle.<br>Scrivere l'etichetta nel testo, non solo con il colore (Matt: nel PDF il colore si perde). | R9, R10 |
| TP 50–51 – Wave 0 / Delivery plan | R1 22/12 SSO + hot release | Come DEF 24/25 | R11 |
| TP 54–56 – Team, capacity, change | Training "for users, authors, admins…" | Esplicitare che il rollout EE è incluso (train-the-trainer per paese) e la relativa capacità | R3 |
| TP 57 – Deliverables | Come DEF 33 | Come DEF 33 | R1, R3 |
| TP 70 – Run | Senza valori | Come DEF 29, con rimando all'offerta economica | R1 |
| TP 74 – Commercial offer (note) | Checklist RFQ §6.2 | Verificare che l'offerta economica contenga la tabella costi 2026/2027 con AMS high-level, il KT quotato e Build/Run separati | R1 |
| TP 77 – Exclusions | E8 L1 service desk; E9 opzioni | Allineare E9; aggiungere le esclusioni del perimetro "essential" | R5, R9 |
| TP 78–80 – Traceability | Forum, KPI, AMS | Come DEF 37–39 | tutte |
| NUOVA – AEM | — | Stessa slide della DEF | R12 |

## 4.3 Contenuto proposto per la nuova slide AEM

- Titolo: "Your AEM, reused | How DealerX content runs on the existing instance".
- Cosa riusiamo: l'istanza AEM as a Cloud Service esistente, gli experience fragment e i template attuali, i componenti già in libreria; Universal Editor per l'authoring sulle pagine template (come spiegato da Cerdelli [50:40]).
- Permessi: il modello di gruppi e permessi AEM esistente (admin, author, read-only), esteso per brand, mercato e publisher NSC delegati. Nessun nuovo sistema di permessi.
- Tassonomia: la tassonomia esistente per mercato e lingua come base; le estensioni (topic, audience, ruolo) concordate con la Design Authority. La stessa tassonomia guida targeting, ricerca e AI.
- Delivery headless: come i contenuti (experience e content fragment) arrivano all'Angular SPA tramite il mapping AEM-Angular; cosa resta in AEM e cosa va nel repository documentale S3/CDN.
- Cosa ci serve da Stellantis prima dello start (per evitare blocchi):
  - accesso agli ambienti AEM (dev/stage);
  - export della struttura e della tassonomia;
  - matrice di gruppi e permessi;
  - elenco degli experience fragment e dei template in uso;
  - un referente AEM della piattaforma.
- Next step: deep-dive tecnico dedicato con Diletta, Cerdelli e il team Adobe di Engineering (proposto da Nicola [51:06]).

# 5. Impatto economico sulla quotazione emessa (STLA_DealerX_Economics_V01)

## 5.1 La quotazione emessa

Fogli "Price 1° Uscita" e "MAIN-COSTI 1° Uscita". Prezzo = costo / (1 − 23%).

| Componente | Costo | Prezzo | Note |
|---|---|---|---|
| Build – Back-end | 83,0 k€ | 107,8 k€ | ≈ 237 gg/u a 350 €/gg: meno della metà dell'"MVP ridotto" del file BE v04 (488 gg/u) |
| Build – Front-end | 82,5 k€ | 107,1 k€ |  |
| Build – Design UX/UI | 54,7 k€ | 71,0 k€ |  |
| Build – AI | 143,1 k€ | 185,8 k€ | AI Cost Summary: 423 gg/u (Wave 0 180, Wave 1 130, Wave 2 45, Wave 3 15 + coordinamento e contingency). Primo stream per peso (37%) |
| Build – PM/PMO | 21,0 k€ | 27,3 k€ |  |
| Totale build | 384,2 k€ | 499,0 k€ | Per wave: W0 97,4 · W1 175,3 · W2 127,3 · W3 99,0 k€. Dettagli dichiarati: SSO, contenuti personalizzati, widget & analytics, AI search & assistant, ticketing & claims (il forum non è citato) |
| AMS annuo – BE / FE / AI / PM | 18,4 / 36,6 / 29,8 / 10,0 k€ | 23,9 / 47,5 / 40,0 / 13,0 k€ |  |
| Totale AMS annuo | 94,8 k€ | 124,4 k€ | ≈ 255 gg/u/anno, circa 1,2 FTE |
| Running nel foglio Price (righe 20–25) | — | 2027 Q3 66 k€ · 2027 Q4 73 k€ · 2028 144 k€ | Include "Cloud/infrastructure running – managed operations" (11–26 k€) con margine Run del 20%; non coincide con il totale AMS di MAIN-COSTI (vedi §6) |

## 5.2 Valore delle richieste del cliente, riprezzate con i parametri del V01

Giorni/uomo presi dai file di stima per stream (BE v04, EngX v01, AI v03, PM v02); costo ai tassi standard (BE 350 €/gg + 10% PM, FE 433 €/gg, AI 338 €/gg); prezzo con margine 23%. Valori indicativi, da validare con i responsabili di stream. Le voci "da stimare" non hanno righe dedicate nei file.

| Richiesta | Base di stima | Versione "essential" | Versione piena | Note |
|---|---|---|---|---|
| EE rollout + training | BE "Market rollout and localisation" (MVP 57 gg) + garanzia Wave 1 (32 gg) + PM; AI19 EE rollout. Piena: Opz. E (264 gg) + AI12/AI19 + PM W2–W3 + garanzia W1 | ≈ 53 k€ | ≈ 185 k€ | Essential: setup mercati, publisher NSC, train-the-trainer per content author, 2 mesi di post go-live per wave |
| Sales performance | Connettori inbound C1st / OMNI / Power BI (T093–T095, 18 gg) + FE07 Power BI embedding (7,6 gg) + FE02 dashboard e widget (13,6 gg) | ≈ 21 k€ | ≈ 21 k€ + dashboard nuove | KPI coach AI (AI26) e forecasting restano opzionali |
| Mini web apps & forms | FE06 container mini-app / micro-frontend (15,5 gg); BE per BFF e API Connect: nessuna riga dedicata | ≈ 9 k€ FE + BE da stimare | + pacchetti S/M/L per ogni mini-app | Fissare il numero di mini-app/form incluse (es. 2–3 da Logotel) |
| Forum & community | BE "Social interactions (forum)": MVP ridotto 36,8 gg / MVP 75,2 gg; FE forum UI: nessuna riga dedicata | ≈ 18 k€ BE + FE da stimare | ≈ 38 k€ BE + FE da stimare | Il V01 non lo cita nel dettaglio del build: coerente con la posizione interna "fuori", ma va verificato |
| Ticketing extensions, incentive claims | Erano add-on | 0 | 0 | Escono dal deck senza effetti sul prezzo |
| Totale indicativo |  | ≈ +100 k€ + voci da stimare → ≈ 600 k€ | ≈ +250 k€ → ≈ 750 k€ | Rispetto ai 499 k€ emessi |

## 5.3 Run/AMS: cosa presentare

- Il V01 contiene già un AMS annuo di 124,4 k€ (costo 94,8 k€): la richiesta di Mikita ("quote fully… it should be there") e il vincolo di Nicola (quotazione emessa) sono rispettati a patto di presentarlo in modo esplicito nelle slide, non come add-on S/M/L.
- Forma budgettaria richiesta dall'RFQ §6.2 e da Cerdelli: canone annuo 2027 (ramp-up) e 2028 (a regime), riferito alla fascia 3.000–6.000 ticket/anno, con perimetro L2/L3, SLA IMS e pool evolutivo.
- Rischio di sottodimensionamento: circa 1,2 FTE per 3.000–6.000 ticket. La quota BE (18,4 k€ di costo, circa 53 gg/anno) è sotto lo scenario minimo del file BE v04, che vale 140 gg e 69,9 k€ di prezzo. Esplicitare l'ipotesi sulla quota di ticket che arriva al L2/L3 oppure presentare una fascia (es. 124 k€ a 3.000 ticket e un valore più alto a 6.000).
- Mancano: la quotazione del KT verso un altro integratore (richiesta dall'RFQ) e la copertura tra la fine dei 2 mesi di post go-live del pilota (circa aprile 2027) e l'avvio del running nel foglio Price (Q3 2027).

## 5.4 Risposta alla domanda di Cerdelli: "rimanendo dentro lo stesso prezzo?"

Per restare a 499 k€ con le richieste in forma "essential" vanno recuperati circa 100 k€, cioè il 20% del build. Tre scenari èpssibili:

| Scenario | Prezzo build | Descrizione | Pro | Contro |
|---|---|---|---|---|
| S1 – Prezzo invariato | 499 k€ | Richieste in forma "essential"; forum fuori; compensazione di circa 100 k€ sul perimetro attuale | Nessuna riapertura del prezzo; risponde al "find the way to integrate" | Tagli rilevanti (vedi leve); il rischio su Q-008 resta |
| S2 – Nuovo prezzo | ≈ 600 k€ (essential) – 620 k€ con forum | Build + richieste "essential" (+ forum essential); il cliente ha aperto al reinvio | Perimetro coerente con RFQ, Q-008 e richieste verbali | Sopra il target del Client Manager |
| S3 – Prezzo invariato + must prezzati | 499 k€ + opzioni ≈ 100 k€ | Le richieste restano opzioni prezzate "raccomandate" | Trasparenza, nessun taglio | Il cliente le ha definite must: rischio commerciale più alto |

Leve di compensazione per S1 (da validare con i responsabili di stream):

- AI (185,8 k€): spostare in opzione lo sviluppo AI di Wave 2–3 (60 gg/u, ≈ 26 k€) e rivedere il coordinamento tecnico (35 gg/u, ≈ 19 k€): è lo stream con più peso.
- Design UX/UI (71,0 k€): fare leva sul PoV già realizzato e sul design system esistente.
- Rollout "essential" in modalità train-the-trainer remota, con materiali in inglese e localizzazione a cura di Stellantis (Q-036 lascia aperti lingue e ownership).
- Mini web apps: container più un numero chiuso di mini-app/form; il resto a pacchetti S/M/L (le taglie AI S/M/L/XL a 14/24/42/56 k€ sono un riferimento di formato).
- Sales performance: solo embedding del Power BI esistente e lead C1st in lettura.
- Contesto VIN/ticket e widget wizard lasciati in opzione, dichiarandolo nella TP.

# 6. Modifiche da fare al file STLA_DealerX_Economics_V01.xlsx

Il file contiene ancora parti di un'altra offerta (New Incentive Tool). Se viene allegato o se ne ricavano tabelle per il cliente, va pulito. Le modifiche di perimetro dipendono dalle decisioni D1–D3.

| # | Foglio / cella | Problema | Modifica proposta | Priorità |
|---|---|---|---|---|
| E1 | Invoicing plan 1° Uscita (2) | Intero foglio della gara "New Incentive Tool": totale 1,45 M€ e 2,718 M€, milestone Wave 1–5, Middle East, Argentina & Brasile | Eliminare o ricostruire con le milestone DealerX (kick-off, R1, pilota Spagna, Wave 1, 2, 3) sui 499 k€ | ALTA |
| E2 | MAIN-RICAVI, NewInc_ScopePerimeter | Moduli e perimetro del New Incentive Tool (2,15 M€) | Eliminare dal file DealerX | ALTA |
| E3 | Confronto ENG vs Purchasing (3) | Tutte le formule in #REF!; target di acquisto con valori di un'altra gara (2.312 k€ OTC, 1.200 k€ Run) | Eliminare o ricollegare ai valori DealerX | ALTA |
| E4 | Price 1° Uscita, righe 9–18 e 34–65 | Running 440/510 k€, "Quick Win AI Use Case", "Middle East extension", "Argentina & Brasil extension"; note B28 "experience in incentive processes", "In-app AI assistant not included" (in DealerX l'assistente è incluso) | Eliminare le righe non DealerX e le note non pertinenti | ALTA |
| E5 | Price 1° Uscita, righe 21–25 (Running) | Etichette di un'altra gara ("Pilot PT + IT + SP", "Ramp-up 3 months from beginning of Wave 1 Oct 2027"); F25 somma anche la cella margine (I24) → 139.000,18; margine Run 20% contro il 23% di MAIN-COSTI; 2028 = 144 k€ contro 124,4 k€ di MAIN-COSTI | Riallineare a un'unica fonte (MAIN-COSTI); etichette per anno DealerX (2027 ramp-up dal pilota, 2028 a regime); correggere F25 | ALTA |
| E6 | Price 1° Uscita, riga 23 "Cloud/infrastructure running – managed operations" | Non presente in MAIN-COSTI; da chiarire rispetto all'esclusione E3 (licenze e consumi cloud a carico Stellantis) | Togliere, oppure descrivere come servizio di gestione operativa e non come consumo | MEDIA |
| E7 | Price 1° Uscita, riga 3 (ripartizione 5/50/30/10%) | Non corrisponde ai valori per wave (19,5/35,1/25,5/19,8%) | Allineare o rimuovere | BASSA |
| E8 | Price 1° Uscita, riga 8 (RFQ Scope) | Il dettaglio non cita forum, mini web apps, sales performance, rollout EE | Aggiornare il dettaglio secondo D1/D2; aggiungere le righe delle richieste incluse ("essential") con la loro wave | ALTA |
| E9 | MAIN-COSTI 1° Uscita, righe 2–7 | Ripartizione per stream senza le nuove voci; colonne K–L con uno scenario alternativo (548 k€ ricondotti a 500 k€) senza etichetta | Aggiungere le voci di §5.2 per stream (BE, FE, AI, PM); etichettare o eliminare K–L | ALTA |
| E10 | MAIN-COSTI 1° Uscita, righe 10–16 (AMS) | Un solo valore annuo; BE sotto lo scenario minimo del file BE v04 | Presentare due fasce (3.000 / 6.000 ticket) o esplicitare l'ipotesi di ticket L2/L3; aggiungere il ramp-up 2027 | ALTA |
| E11 | Nuova riga / nuovo foglio | Mancano la quotazione del KT verso un altro integratore e la garanzia/post go-live di 2 mesi per go-live in forma esplicita | Aggiungere la riga KT (one-off) e indicare dove è coperto il post go-live (dentro il build per ogni wave inclusa) | ALTA |
| E12 | Nuovo foglio "Opzioni" | Gli add-on della DEF 10 non hanno un prezzo nel V01 | Listino opzioni con prezzo o fascia S/M/L: connected vehicle, campaigns & engagement, personal widgets, more AI agents (AI S/M/L/XL 14/24/42/56 k€), AI KB extensions, legacy migration per sorgente, forum (se D1 = fuori) | MEDIA |
| E13 | Tabella RFQ §6.2 | L'RFQ chiede costi 2026/2027 (setup con 2 mesi di post go-live, AMS high-level) e tabella licenze | Verificare che l'allegato economico per il cliente segua questo formato: 2026 = 97,4 k€; 2027 = 401,6 k€ + AMS | MEDIA |

# 7. Decisioni da prendere

| ID | Decisione | Opzioni | Raccomandazione / note | Owner |
|---|---|---|---|---|
| D1 | Forum dentro o fuori dal prezzo | a) fuori, come opzione prezzata; b) dentro in forma "essential" | Indicazione interna: fuori. Rischio: Q-008 scritto + richiesta di Mikita e Matt. Se resta fuori, serve una motivazione esplicita nella TP 44 e nella risposta al cliente. Il V01 non lo cita nel build. La versione "essential" vale ≈ 18 k€ di BE più la quota FE da stimare (§5.2) | Nicola |
| D2 | Prezzo: invariato o nuovo | S1 / S2 / S3 (§5.4) | Il cliente ha aperto al reinvio: definire il prezzo prima di rifare le slide | Nicola, Cerdelli |
| D3 | Forma della quotazione Run/AMS | Budgettaria annua per fascia di ticket e anno; KT a parte | Il V01 ha già 124,4 k€/anno: renderlo esplicito nelle slide, verificarne il dimensionamento e aggiungere il KT (§5.3) | Cerdelli |
| D4 | Release del 22/12 | a) mantenerla come soft-launch per un pilot group; b) primo rilascio ai dealer con contenuto (metà gennaio) | Rispondere a Matt con una scelta motivata e la tabella delle funzionalità per release | Nicola |
| D5 | Perimetro "essential" dei tre must | Numero di mini-app/form, KPI e report, livello di training | Fissarlo come assunzioni (DEF 34/35, TP 75/76) | Stream lead |
| D6 | OMNI order validation e risposta "Yes" sulla TP 46 | Includere, oppure correggere per iscritto | Raccomandato: opzione, chiarita nella nuova TP 46 | Nicola |
| D7 | Deep-dive AEM con Stellantis | Data e partecipanti | Cerdelli, team Adobe, Diletta | Nicola |
| D8 | Tempi del reinvio | Data di riapertura del portale | Da concordare con Mikita | Nicola |

# 8. Prossimi passi

- Lunedì: decisioni D1–D8.
- Aggiornare STLA_DealerX_Economics_V01 secondo il §6 (pulizia dei fogli di altre gare, nuove voci, AMS e KT) e salvarlo come V02.
- Aggiornare la DEF (slide 7–12, 24–25, 29, 32–39, più le nuove slide AEM e Spain pilot) e la TP (slide 5–7, 12–28, 36, 44, 46, 50–57, 70, 74–80).
- Rileggere tutta la TP cercando "forum", "mandatory", "option", "add-on", "Wave" per eliminare le incoerenze residue: Matt ci ha messo due giorni a trovarle, il cliente rilegge con attenzione.
- Reinvio sul portale e mail di accompagnamento a Mikita con l'elenco delle modifiche.