# BLOCKCHAIN TEMPLATE BUILDER

Il progetto consiste in uno script bash che mira a **semplificare la creazione di precompile contracts** durante la creazione di una blockchain, attraverso lo strumento Avalanche in [precompile-EVM](https://github.com/ava-labs/precompile-evm).
Lo script si presenta come funzione "wrapper" dei passaggi 1-3 della [fase di creazione di precompile](https://build.avax.network/academy/avalanche-l1/customizing-evm/07-hash-function-precompile/00-intro).
Altamente consigliata è la conoscenza del funzionamento di precompile-evm. [Qui](https://build.avax.network/academy/avalanche-l1/customizing-evm) si può seguire il tutorial fornito da Avalanche Builder Hub.


## Funzionamento base in precompile-EVM

1. **Creare un'interfaccia Solidity per il precompile**
2. **Generare l'ABI**
3. **Scrivere il codice GO del precompile**
4. Configurare e registrare il precompile
5. Creare ed eseguire test


## Il problema

La creazione di interfacce Solidity assieme alla scrittura in Go della logica




## La soluzione

Fornire al programmatore la possibiltà di utilizzare template di contratti standard,
più o meno specifici.

E.g.
* Tipologia di blockchain: socialNetwork
    
* Possibili contratti usati: register, signIn, proofOfHumanity, massEngagementCounterved...
    
In questo caso il programmatore ottiene per ogni contratto richiesto:

* l'interfaccia Solidty 

* l'implementazione in Go della logica 

## Il progetto è community driven

L'idea è quella di integrare il nostro progetto con precompile-evm, affinché possa essere costantemente aggiornato in modo sicuro.
Più il numero di utenti che contribuiscono al progetto, fornendo template di blockchain
e funzioni, più gli stessi utenti avranno a disposizione strumenti affidabili per lo sviluppo della propria blockchain. Dunque, in un futuro non troppo lontano, qualsiasi programmatore, indipendentemente dalla sua esperienza, potrà virtualmente usufruire di moltissimi modelli per qualsiasi blockchain.
