# Registro de testes — Aula 3

**Projeto:** Calculadora de Média  
**Objetivo:** verificar o preenchimento dos campos, a validação das notas, o cálculo da média e a classificação acadêmica.

> Preencha as colunas “Obtido” e “Status” depois de executar cada teste no navegador. Não marque um teste como aprovado antes de conferir o resultado.

| Caso | Dados de entrada | Resultado esperado | Obtido | Status |
|---|---|---|---|---|
| 1 | Nome vazio; notas 8, 7 e 9 | Preencha todos os campos. | Pendente de execução | Pendente |
| 2 | Nome Mariana; uma nota não numérica (teste temporário com campo `type="text"`) | Use notas entre 0 e 10. | Pendente de execução | Pendente |
| 3 | Nome Mariana; notas -1, 7 e 9 | Use notas entre 0 e 10. | Pendente de execução | Pendente |
| 4 | Nome Mariana; notas 5, 5 e 5 | Mariana: média 5.0. Situação: Recuperação. | Pendente de execução | Pendente |
| 5 | Nome Mariana; notas 7, 7 e 7 | Mariana: média 7.0. Situação: Aprovado. | Pendente de execução | Pendente |
| 6 | Nome Mariana; notas 4, 4 e 4 | Mariana: média 4.0. Situação: Reprovado. | Pendente de execução | Pendente |

## Como executar os testes

1. Abra `index.html` no navegador.
2. Preencha os campos com os dados de cada caso.
3. Clique em **Calcular média**.
4. Compare a mensagem exibida com o resultado esperado.
5. Registre a mensagem real na coluna “Obtido”.
6. Escreva **Passou** ou **Falhou** na coluna “Status”.

**Observação sobre o teste 2:** navegadores normalmente impedem letras em campos `type="number"`. Para testar um valor não numérico, altere temporariamente o campo de uma nota para `type="text"` no HTML. Depois, restaure `type="number"`.

## Conferência final

- [ ] Os quatro arquivos estão na mesma pasta.
- [ ] Os campos possuem rótulos e IDs corretos.
- [ ] O botão aciona o JavaScript.
- [ ] Campos vazios são rejeitados.
- [ ] Notas menores que 0 ou maiores que 10 são rejeitadas.
- [ ] A média é calculada corretamente.
- [ ] A classificação respeita os limites: aprovado (média >= 7), recuperação (5 <= média < 7) e reprovado (média < 5).
- [ ] O resultado aparece na própria página.
- [ ] Pelo menos cinco testes foram executados e documentados.
- [ ] O console não apresenta erros durante a execução normal.
