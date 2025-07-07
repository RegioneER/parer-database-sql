# Guida alla prima installazione base dati Oracle DB

Fonte template redazione documento:  https://www.makeareadme.com/.

# Descrizione

Il seguente progetto contiene, per ogni applicazione dell'ecosistema ParER, gli script standard sql per la prima creazione e manutenzione del dababase E-R (entity-relationship) per il DBSM di riferimento, ossia [Oracle DB](https://www.oracle.com/it/database/).

Il progetto è strutturato come segue: 
- la directory di primo livello, si riferisce al singolo progetto/schema (e.g. SACER);
- la directory di secondo livello, la versione applicativa (vedere su relativo progetto -> releases);
- infine, all'interno i vari script sql suddivisi per : creazione dello schema (create_SCHEMA_VERSION_oracle.sql), modifiche / alterazioni di qualunque natura (alter_SCHEMA_VERSION_oracle.sql), e.g. create_SACER_100_oracle.sql, alter_SACER_100_oracle.sql

# Requisiti database

- installazione **Oracle DB** alla versione minima consigliata **19c**;

# Supporto

Mantainer del progetto è [Engineering Ingegneria Informatica S.p.A.](https://www.eng.it/).

# Contributi

Se interessati a crontribuire alla crescita del progetto potete scrivere all'indirizzo email <a href="mailto:areasviluppoparer@regione.emilia-romagna.it">areasviluppoparer@regione.emilia-romagna.it</a>.

# Credits

Progetto di proprietà di [Regione Emilia-Romagna](https://www.regione.emilia-romagna.it/) sviluppato a cura di [Engineering Ingegneria Informatica S.p.A.](https://www.eng.it/).

# Licenza

Questo progetto è rilasciato sotto licenza GNU Affero General Public License v3.0 or later ([LICENSE.txt](LICENSE.txt)).

# Appendice

## Documentazione aggiuntiva

Tool utilizzati: 

* Oracle DB : https://www.oracle.com/it/database/
