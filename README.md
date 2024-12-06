# Domain Name System (DNS) e Active Directory Domain Services (AD DS)

**DNS** è una suite di protocolli standard che comprende il protocollo **TCP/IP**. Insieme, il client e il server DNS offrono ai computer e agli utenti servizi di risoluzione del nome tramite il mapping tra **nome computer** e **indirizzo IP**.

Se si installa una nuova foresta e un nuovo dominio di **Active Directory**, DNS viene installato automaticamente con Active Directory come server di catalogo globale per la foresta e il dominio.

**Active Directory Domain Services** (AD DS) usa DNS come meccanismo di posizione del controller di dominio. Quando viene eseguita una delle operazioni principali di Active Directory (l'autenticazione, l'aggiornamento, la ricerca ...) i computer usano DNS per individuare i controller di dominio Active Directory, i quali usano DNS per individuarsi tra loro.

> [!NOTE]
> Il client DNS è incluso in tutte le versioni client e server del sistema operativo Windows ed è in esecuzione per impostazione predefinita sin dall'installazione del sistema operativo.

Quando si configura una connessione di rete TCP/IP con l'indirizzo IP di un server DNS, il client DNS esegue una query sul server DNS per individuare i controller di dominio per il dominio di Active Directory e risolvere i nomi dei computer in indirizzi IP. Quando il server DNS risponde alla query e fornisce l'indirizzo IP del controller di dominio al client, il client contatta il controller di dominio e il processo di autenticazione può iniziare.

RIf.: [Microsoft Learn Challenge](https://learn.microsoft.com/it-it/windows-server/networking/dns/dns-top)
