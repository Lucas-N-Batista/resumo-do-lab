# Resumo do Lab DIO: Desafio Sharpe Ratio em JavaScript

## O que aprendi
Durante o desenvolvimento deste lab, explorei conceitos fundamentais de programação JavaScript no ambiente DIO, focando em leitura de entrada, processamento de dados e saída formatada. Aqui vai um resumo dos principais aprendizados:

- **Funções globais DIO**: `gets()` lê uma linha de entrada e `print()` exibe saída com quebra de linha. Cada teste é independente, com uma única linha por execução – evitei loops desnecessários para não travar.
- **Processamento de string**: Usei `trim()` para remover espaços extras, `split(',')` para separar valores por vírgula e `map(item => Number(item.trim()))` para converter em números, lidando com espaços comuns nos inputs.
- **Cálculo do Sharpe Ratio**: Fórmula `(retornoInvestimento - retornoLivreRisco) / desvioPadrao`, arredondada com `toFixed(2)`. Testes validados:
  | Entrada              | Saída |
  |----------------------|-------|
  | 0.10, 0.02, 0.05    | 1.60 |
  | 0.08, 0.01, 0.04    | 1.75 |
  | 0.10, 0.03, 0.02    | 3.50 |

- **Debug e boas práticas**: Identifiquei erros comuns como loop infinito (devido a EOF no DIO), validação de entrada vazia e robustez com `trim()`. Código final limpo e eficiente.

Esse lab reforçou minha habilidade em resolver desafios reais, alinhado à minha experiência como Analista e Desenvolvedor de Sistemas na BSN Tecnologia.

**Repositório criado em:** [Data atual]  
**Autor:** [Seu Nome/Usuário GitHub]
