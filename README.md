# Super Trunfo de Cidades

Bem-vindo ao **Super Trunfo de Cidades**, um jogo interativo no qual cidades brasileiras competem entre si com base em características socioeconômicas e territoriais.

## Regras do Jogo

1. **Cadastro de Cartas:**

   - O jogador pode cadastrar até 8 cartas de cidades.
   - Cada carta contém informações detalhadas sobre uma cidade, incluindo:
     - Estado
     - Nome
     - Código (Ex.: A01, A02)
     - População
     - Área (em km²)
     - PIB (em reais)
     - Número de pontos turísticos
     - Densidade populacional
     - PIB per capita
     - Super poder calculado com base nos atributos anteriores.

2. **Visualização de Cartas:**

   - As cartas cadastradas podem ser visualizadas de forma completa ou apenas com nome e código.

3. **Batalhas:**

   - Escolha duas cidades para batalhar.
   - Escolha até 7 características para definir o vencedor, incluindo:
     1. População
     2. Área
     3. PIB
     4. Número de pontos turísticos
     5. Densidade populacional
     6. PIB per capita
     7. Super poder
   - O jogo apresenta o vencedor com base em cada característica comparada.
   - A cidade com mais pontos ao final das comparações vence a batalha.

4. **Empate:**

   - Se ambas as cidades obtiverem a mesma pontuação, ocorre um empate.

## Funcionalidades

- **Cadastro dinâmico:**
  - Permite ao jogador cadastrar cidades de forma iterativa.
- **Visualização flexível:**
  - Opção de exibir cartas completas ou apenas informações básicas.
- **Batalha personalizada:**
  - Escolha livre das características a serem comparadas.
- **Cálculo inteligente:**
  - Densidade populacional e PIB per capita são calculados automaticamente.
- **Super poder:**
  - Um atributo que combina múltiplas características para uma competição mais ampla.

## Exemplo de Carta

```
Estado: São Paulo
Nome: Campinas
Código: SP01
População: 1.223.237 pessoas
Área: 795.69 km²
PIB: R$ 128.987,32
Pontos turísticos: 5
Densidade populacional: 1536.48 pessoas por km²
PIB per capita: R$ 105.45 por pessoa
Super poder: 3000.00 pontos
```

## Como Jogar

1. Inicie o jogo executando o programa.
2. Cadastre suas cidades.
3. Visualize as cartas criadas.
4. Escolha duas cartas para batalhar.
5. Defina as características em disputa.
6. Acompanhe o resultado da batalha.
7. Escolha continuar batalhando ou cadastrar novas cidades.

## Notas Técnicas

- O programa foi desenvolvido em **C** com foco em manipulação de estruturas e funções.
- A função `ExibirCarta()` apresenta os dados completos de uma cidade.
- Funções auxiliares, como `ParaMaiuscula()` e `MostrarResultadoBatalha()`, ajudam na manipulação de strings e exibição de resultados.

## Melhorias Futuras

- Suporte para mais cidades.
- Interface gráfica.
- Opções de exportação de resultados.
- Adição de novas características para batalha.

Divirta-se com o Super Trunfo de Cidades e descubra qual cidade é a grande campeã!
