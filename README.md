- Un'azione automatizzata verifica che la versione sia presente e conforme agli standard.

### 1 **Validazione Automatica**
- Una GitHub Action o un CI/CD pipeline verifica la presenza della versione.
- Se la versione è corretta, il workflow prosegue.
- Se manca o è errata, il workflow viene 

### 2 **Merge sul Branch Primario**
- Se la versione è validata, il branch viene unito a main.
- Il merge avviene solo se i test di integrazione sono superati.
