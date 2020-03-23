---
format: Markdown
title: Proposta regolamento deliberativo assemblea online
categories: assemblee-pirata
...

# Configurazione Liquid

Sarà definita su liquid una nuova area dove sarà possibile aggiungere i seguenti tipi di policy

Policy derivate da "Comunicazioni in assemblea":

- Congresso Nazionale - Mozione Generale - Presentazione (tN: 0, tD: 0, tVer: 0; tVoto: 12h - Quorum: 0)
- Congresso Nazionale - Emendamento (tN: 0, tD: 0, tVer: 0; tVoto: 1h - Quorum: 0)

Policy derivate da "Comunicazioni in assemblea"

- Congresso Nazionale - Emendamenti - Votazione (tN: 0, tD: 0, tVer: 0; tVoto: 5m - Quorum: 0)
- Congresso Nazionale - Mozione Generale - Votazione(tN: 0, tD: 0, tVer: 0; tVoto: 5m - Quorum: 0)


# Registrazione congressisti iscritti 

Il giorno del congresso si procederà a rendere inattivi tutti gli iscritti in piattaforma. Sarà necessario un collegamento nel giorno del congresso per riattivare l'utenza. Saranno quindi considerati presenti al congresso i pirati iscritti per l'anno 2020 e attivi in piattaforma liquid.

# Quorum
Il numero degli iscritti attivi è comunicato dalla Presidenza al momento stabilito nell'ordine dei lavori.

# Mozioni Generali

Le mozioni generali, sono presentate dasingoli congressisti (non sono ammessi autori multipli) con una Iniziativa "Congresso Nazionale - Mozione Generale - Presentazione".

Devono essere VOTATE su liquid da non meno del X=40% e da non più di X+N congressisti. Ciascun congressista può sottoscrivere una singola mozione generale.

Al momento previsto nell'ordine dei lavori la Segreteria verifica le condizioni di ammissione della mazione (numero minimo e massimo di sottoscrittori e sostegno univoco alle singole mozione ESCLUDENDO dal computo coloro che hanno sostenuto più di una mozione generale (si considera voto nullo su ambedue le mozioni votate) ).

Le mozioni ammesse sono annunciate all'assemblea e se molteplici viene dato del tempo ai promotori, se lo voglioni, di comporre assieme le mozioni e ritrovare adeguato supporto per la mozione unificata, se la mozione unificata non troverà adeguato supporto andranno al voto le mozioni contrapposte.

Ciascuna mozione ammessa al voto può essere illustrata dal primo firmatario (presentatore) o da persona da lui indicata, per un limite di 10 min.



# Emendamenti alle Mozioni

Gli emendamenti sono presentati da singoli congressisti (non sono ammessi autori multipli) con iniziative "Congresso Nazionale - Emendamenti", indicando nel titolo "Emendamento a Mozione Generale #<n> - «descrizione»". Ciascun congressista può presentare più di una proposta, anche complessiva, di emendamento a ciascuna mozione.

Devono essere sottoscritte su liquid da non meno del X=20% e da non più di X+N congressisti. Ciascun congressista può sottoscrivere più emendamenti per ogni mozione.



# Dibattito

La Presidenza, all’inizio della fase conclusiva dei lavori, procede alla lettura delle mozioni generali, quindi dà la parola per l’illustrazione delle mozioni generali. Gli interventi dei congressisti possono essere limitati nel numero e nella durata, in relazione alle esigenze poste dall’ordine dei lavori e dall’andamento generale dei lavori.

Terminato il dibattito sulle mozioni generali, si procede all’esame degli emendamenti relativi. Qualora gli emendamenti alle mozioni non siano accolti dai presentatori dei documenti cui sono rivolti (l’accettazione deve essere espressa dal presentatore), la Presidenza dà la parola per l’illustrazione al presentatore dell’emendamento per due minuti. Su ciascuno emendamento la Presidenza ammette una dichiarazione di voto favorevole ed una contraria, della durata di due minuti ciascuna.

# Esecuzione delle votazioni sugli Emendamenti

Alla fine del dibattito sugli emendamenti la segreteria mette in Liquid gli emendamenti non accettati dai presentatori delle mozioni con una iniziativa con policy "Congresso Nazionale - Emendamenti - Votazione". Al termine delle votazioni la Presidenza dichiara l'esito del voto sugli emendamenti.

# Esecuzione della votazione sulle Mozioni

Terminate le votazioni sugli emendamenti, la Presidenza procede alla discussione sulla votazione delle mozioni generali, dando la parola per le dichiarazioni di voto per una durata di cinque minuti ciascuna e ad un numero limitato di iscritti per le dichiarazioni a favore, contro e per l’astensione. Durata e numero delle dichiarazioni di voto sono stabiliti, per ciascuna votazione, dalla Presidenza.

Alla fine della fase di dibattito la segreteria mette in Liquid tutte le Mozioni con policy "Congresso Nazionale - Mozione Generale - Votazione" dando modo ai congressisti di votare per ciascuna in un tempo limitato.Al termine delle votazioni la Presidenza dichiara l'esito del voto.  