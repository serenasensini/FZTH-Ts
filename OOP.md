# TypeScript: OOP

## Classi e oggetti
Per i concetti teorici, vedi [link](https://github.com/serenasensini/FZTH-Java/blob/master/Java-OOP.md)

Esempio:

```
//creazione del tipo Persona
export class Persona {
  //definizione degli attributi
  nome: string;
  cognome: string;
  eta: number;
  
  //uso del costruttore, da utilizzare per istanziare un oggetto
  constructor(n: string, c: string, e: number) {
    this.nome = n;
    this.cognome = c;
    this.eta = e;
  }
  //creazione di un metodo per il tipo
  saluta() {
    return 'Hello, I\'m ' + this.nome + ' ' + this.cognome ' and I\'m ' + this.eta + ' years old';
  }
}

```

```

Esempio:

```
//istanza dell'oggeto di tipo Persona
p1 = new Persona('Mario', 'Rossi', 34);
console.log(p1.saluta());
```
