# 📌 Instalação
> Infelizmente o projeto ainda está em desenvolvimento.

# 📄 Dumentação
- Ainda contem poucos itens, mas vamos sempre melhorando.


<h2>
  <strong>
    🧶 String:
  </strong>
</h2>

- As strings aqui, em declarações, devem ser definidas entre `>>`, assim como o exemplo seguinte: 

```plg
str:fix minhaPrimeiraString = >> string >>
``` 

- Strings em elementos segundários, tem que ser definidas dentro do método `Str()`, exemplo abaixo:
```plg
str:fix nome = >> Lucas >>
str:fix defaultWelcome = >> Bem vindo {user}! Aqui você poderá dar ideias para a linguágem evoluir! >>

cEclipsim( defaultWelcome().replace( Str({user}), nome().val ) )
```

<div align="center">
  <h3>
    mudaveis
  </h3>
</div>

- Você pode mudar usando `>>`
```plg
str:mud nome = >> Lucas >>
str:fix defaultWelcome = >> Bem vindo {user}! Aqui você poderá dar ideias para a linguágem evoluir! >>

set > nome >> Ana >>

cEclipsim( defaultWelcome().replace( Str({user}), nome().val ) )
```
- Ou mudar usando `Str()`
```plg
str:mud nome = >> Lucas >>
str:fix defaultWelcome = >> Bem vindo {user}! Aqui você poderá dar ideias para a linguágem evoluir! >>

set > nome Str(Ana)

cEclipsim( defaultWelcome().replace( Str({user}), nome().val ) )
```

<h2>
  <strong>
    ✅ Condições:
  </strong>
</h2>

- Para fazer uma if, voc|ê deve seguir as seguintes regras:
- - **Para todas as Strings:** Você deve usa-las pelo método `Str()`
- - **Operactionais:** `not`, `and`, `or` e outros do Java Script

