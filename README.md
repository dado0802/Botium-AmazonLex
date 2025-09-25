# Botium-AmazonLex
# 🎓 Amazon Lex V2 Chatbots – Testing & Evaluation with Botium

Questo repository raccoglie il lavoro svolto durante il progetto di tesi triennale in Informatica presso l’Università degli Studi di Milano-Bicocca.  
Il focus principale è stato **lo sviluppo di chatbot basati su Amazon Lex V2** e la loro **valutazione tramite la piattaforma Botium**.

---

## 🚀 Obiettivi del progetto
- Progettare e sviluppare **chatbot tematici** (retail, banking, assicurazioni, viaggi, telecomunicazioni, ecc.) utilizzando **Amazon Lex V2**.
- Analizzare le **potenzialità e i limiti** di Amazon Lex nella gestione di intenti, slot e integrazione con **AWS Lambda**.
- Applicare **Botium** per il testing automatico dei bot, con particolare attenzione alla **copertura dei test**, ai **fallback intent** e ai limiti della piattaforma.
- Raccogliere e documentare i **risultati sperimentali**, evidenziando punti di forza e debolezza dei diversi bot.

---

- **bots/** → esportazioni Amazon Lex V2 (formato `LexJson.zip`)  
- **TestRun/** → output dei test Botium in formato XLSX e analisi   
- **infoBot.xlsx/** → Informazioni utili sulla struttura dei chatbot  
- **thesis/** → materiali di supporto utilizzati per la stesura della tesi  

---

## 🛠️ Strumenti utilizzati
- **Amazon Lex V2** → creazione di chatbot con intenti, slot e dialoghi multi-turno  
- **AWS Lambda** → gestione logica lato server (validazione slot, esecuzione task, ecc.)  
- **Botium CLI** → testing automatizzato di chatbot con generazione di utterance e simulazione di conversazioni  
- **Node.js** → ambiente runtime per Botium e script di test  

---

## 📊 Metodologia di test
1. **Esportazione dei bot** da Amazon Lex in formato `LexJson.zip`.  
2. **Caricamento in Botium** per la generazione automatica dei test.  
3. **Esecuzione dei test** tramite Botium CLI, con analisi delle metriche di copertura.  
4. **Valutazione dei risultati** considerando:
   - Correttezza del riconoscimento degli intenti
   - Gestione degli slot e dei valori non validi
   - Robustezza nella gestione del fallback intent
   - Limiti della generazione automatica di Botium (approccio superficiale, bassa profondità di test)

---

## 📈 Risultati e analisi
- **Punti di forza di Amazon Lex**:
  - Interfaccia intuitiva e gestione multi-turno avanzata
  - Buona integrazione con AWS Lambda
  - Struttura chiara di intenti e slot

- **Limiti riscontrati**:
  - Difficoltà nella gestione di utterance molto complesse
  - Fallback intent poco testato automaticamente da Botium
  - Botium fornisce test veloci, ma **non profondi né esaustivi**

- **Conclusioni**:  
  I test hanno evidenziato come Amazon Lex V2 sia una piattaforma potente per prototipi e applicazioni reali, ma che il testing automatizzato con Botium richieda un’integrazione manuale per coprire casi più complessi.

---

## 👨‍💻 Autore
**Davide Olmi**  
Studente di Informatica – Università degli Studi di Milano-Bicocca 