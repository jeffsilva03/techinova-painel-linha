# Respostas do LAB 01

Nome: Jefferson José da Silva
Dupla (M2 em diante): João Pedro de França Maciel

---

## M2 - Quem quebrou o painel

**Hash curto do commit que introduziu o erro: 7ad6826**

**Autor: Tarcisio Melo**

**Data:15/06/2026 22:38:00**

**Linha alterada (antes e depois):**

```
antes:

return (leitura - 32) * 5 / 9;


depois:

return leitura * 9 / 5 + 32;

```

---

## M3 - O segredo vazado

**O que voce esperava ver no `git status` e o que apareceu:**

**Depois do push, alguem que clonar o repositorio ainda consegue ler a chave?
Responda em duas linhas, explicando o motivo:**

Sim. A chave ainda pode ser encontrada nos commits antigos do histórico.
Por isso, em uma situação real, a chave deveria ser trocada.


---

## M4 - Colisao

**O que significavam os marcadores que apareceram dentro do arquivo:**

- <<<<<<< : mostra o início da versão que estava na main.
- ======= : separa as duas versões que entraram em conflito.
- >>>>>>> : mostra o fim da versão da branch painel-b.

**Qual pedaco veio de quem, e qual titulo voces decidiram manter:**

---

## Casa - Incidente na linha 3

**Hash do commit que quebrou o painel:**

**Hash do commit de revert:**

**Por que `git revert` e nao `git reset` neste caso:**
