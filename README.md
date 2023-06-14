1. Cos'è ReactJS?
ReactJS è una libreria JavaScript che viene utilizzata per creare interfacce utente dinamiche e interattive per le applicazioni web. Con ReactJS, puoi costruire parti visibili di una pagina web chiamate "componenti" e gestire lo stato e il rendering dei dati.

2. ReactJS è un framework, non una libreria. (Falso)
ReactJS è una libreria JavaScript. Questo significa che ReactJS si concentra principalmente sulla gestione delle interfacce utente e offre strumenti e metodi per costruire componenti riutilizzabili all'interno di un'applicazione, ma non fornisce funzionalità complete per la gestione del routing, la gestione dello stato globale o altre funzionalità tipiche di un framework.

3. Il file package.json contiene molte informazioni utili, come ad esempio l'elenco di tutte le dipendenze richieste dall'applicazione.
Il file package.json è un file di configurazione che viene utilizzato per gestire il progetto React. Contiene informazioni come il nome dell'applicazione, la versione, le dipendenze esterne necessarie e altro ancora.

4. create-react-app è l'unico modo possibile per creare un'applicazione React. (Falso)
create-react-app è uno strumento molto utile per creare rapidamente un'applicazione React preconfigurata con tutte le dipendenze e la struttura di base. Tuttavia, non è l'unico modo per creare un'applicazione React.

5. Il comando da lanciare nel terminale per creare una nuova create-react-app con nome "test" è: npx create-react-app test.
Puoi aprire il terminale, navigare nella directory in cui desideri creare il tuo progetto React e quindi eseguire il comando "npx create-react-app test". Questo comando creerà una nuova applicazione React chiamata "test" nella directory corrente.

6. Cos'è un componente React?
Un componente React è una parte isolata di un'interfaccia utente che può essere riutilizzata in diverse parti di un'applicazione. Può rappresentare qualsiasi elemento visibile, come un pulsante, un modulo di input o un'intera sezione di una pagina. I componenti React sono scritti utilizzando JavaScript e JSX (JavaScript XML) e contengono la logica e la struttura necessarie per visualizzare e interagire con i dati.

7. Un componente React può venire creato in tre modi: come funzione, classe o interfaccia. (Falso)
In React, un componente può essere creato come funzione o come classe.

8. Qual è la differenza tra componenti creati come funzione e componenti creati come classe?
I componenti creati come funzioni sono più semplici da scrivere e comprendere. Tuttavia, i componenti creati come classi offrono funzionalità avanzate e questo li rende più adatti per gestire componenti complessi e interazioni avanzate.

9. Le props sono frammenti di informazione assegnati a un componente React per renderlo dinamico e riutilizzabile. (Vero)
Le props, abbreviazione di "properties", sono frammenti di dati che vengono passati a un componente React da un componente genitore. Le props possono contenere qualsiasi tipo di informazione, come stringhe, numeri, oggetti o funzioni. Consentono di rendere i componenti più flessibili e riutilizzabili.

10. Le props possono essere passate sia da un componente genitore a un componente figlio, sia viceversa. (Falso)
In React, le props vengono passate solo da un componente genitore a un componente figlio.

11. Da dove possono venire recuperate le props all'interno di un componente React creato come classe?
Le props possono essere recuperate all'interno di un componente React creato come classe utilizzando l'oggetto 'this.props'. Le props vengono accedute come proprietà dell'oggetto 'this.props' all'interno dei metodi del componente. Ad esempio, per accedere a una prop chiamata "nome" all'interno di un componente, puoi utilizzare 'this.props.nome'.
