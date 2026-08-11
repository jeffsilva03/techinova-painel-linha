# Respostas do LAB 01

Nome: Jefferson José da Silva
Dupla (M2 em diante): João Pedro de França Maciel

---

## M2 - Quem quebrou o painel

**Hash curto do commit que introduziu o erro: 7ad6826**

**Autor: Diego Ferraz**

**Data:22/05/2026 11:30:00**

**Linha alterada (antes e depois):**

```
antes:

return (leitura - 32) * 5 / 9;
const celsius = converterTemperatura(sensor.valor).toFixed(1);


depois:

function converterTemperatura(leitura) {
}

```

---

## M3 - O segredo vazado

**O que voce esperava ver no `git status` e o que apareceu:**

**Depois do push, alguem que clonar o repositorio ainda consegue ler a chave?
Responda em duas linhas, explicando o motivo:**

---

## M4 - Colisao

**O que significavam os marcadores que apareceram dentro do arquivo:**

- `<<<<<<<` :
- `=======` :
- `>>>>>>>` :

**Qual pedaco veio de quem, e qual titulo voces decidiram manter:**

---

## Casa - Incidente na linha 3

**Hash do commit que quebrou o painel:**

**Hash do commit de revert:**

**Por que `git revert` e nao `git reset` neste caso:**
