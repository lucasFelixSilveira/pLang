# 📌 Instalação
> Infelizmente o projeto ainda está em desenvolvimento.

# 📄 Dumentação
- Ainda contem poucos itens, mas vamos sempre melhorando.


<h2>
  <strong>
    🧶 Variáveis e constantes:
  </strong>
</h2>

- Para declarar uma `var` use:
```plang
var:string text = "Hello world"
```

- Para declarar uma `const` use:
```plang
const:string text = "Hello world"
```
- Uma variável é compatível com mudanças, você pode muda-la usando o método [Set](https://github.com/lucasFelixSilveira/pLang/edit/main/README.md#-------set--).

<h2>
  <strong>
    ♻ Set:
  </strong>
</h2>

- O método set pode ser usado para diversas coisas:
- - Transformar uma [Var](https://github.com/lucasFelixSilveira/pLang/edit/main/README.md#-------vari%C3%A1veis-e-constantes--) em [Const](https://github.com/lucasFelixSilveira/pLang/edit/main/README.md#-------vari%C3%A1veis-e-constantes--) (Irreversível)
```
const:string ExempleName = "Lucas"; § Declara o nome do usuário
var:string exemple = f@"Bem vindo, Sr. ${ExempleName}!"; § Declara uma string que contém o conteúdo da constante ExempleName.

set static exemple; § Transforma a variável exemple em uma constante. 
```
- - Transformar uma [Var](https://github.com/lucasFelixSilveira/pLang/edit/main/README.md#-------vari%C3%A1veis-e-constantes--) em [Const](https://github.com/lucasFelixSilveira/pLang/edit/main/README.md#-------vari%C3%A1veis-e-constantes--) (Irreversível) Além de atribuir um novo valor a essa constate.
```
const:string ExempleName = "Lucas"; § Declara o nome do usuário
var:string exemple = "Carregando..."; § Declara uma string que contém o conteúdo da constante ExempleName.

set static exemple to f@"Bem vindo, Sr. ${ExempleName}!"; § Transforma a variável exemple em uma constante, além de antes definir outro valor a ela.
```
