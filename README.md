# Super Trunfo de Cidades

![Status do Projeto](https://img.shields.io/badge/Status-Em%20Desenvolvimento-blue?style=for-the-badge&logo=github&logoColor=white&color=blue&labelColor=black) 
![Linguagens](https://img.shields.io/badge/Linguagens-C%20|%20Outras-informational?style=for-the-badge&color=purple&labelColor=black) 
![Tamanho do Repositório](https://img.shields.io/badge/Tamanho%20do%20Repositório-2.3%20MB-success?style=for-the-badge&color=green&labelColor=black) 
![Pull Requests](https://img.shields.io/badge/Pull%20Requests-5-yellow?style=for-the-badge&color=orange&labelColor=black) 

> Um jogo interativo em que cidades brasileiras competem com base em características socioeconômicas e territoriais.

## Regras do Jogo

1. **Cadastro de Cartas:**

   - O jogador pode cadastrar até 8 cartas de cidades.
   - Cada carta contém informações detalhadas sobre uma cidade, incluindo:
     - Estado
     - Nome
     - Código (deve seguir o formato `<Estado><Cidade>`, onde `<Estado>` é uma letra de A a H e `<Cidade>` é um número de 01 a 02, por exemplo, `A01` ou `B02`).
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

## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

- Você instalou a versão mais recente de um compilador C (recomendado GCC).
- Compatível com sistemas Windows, Linux e macOS.
- Você leu a documentação do projeto.

## 🚀 Instalando Super Trunfo de Cidades

Para instalar o Super Trunfo de Cidades, siga estas etapas:

Linux e macOS:

```
gcc super_trunfo.c -o super_trunfo && ./super_trunfo
```

Windows:

```
gcc super_trunfo.c -o super_trunfo.exe
super_trunfo.exe
```

## ☕ Usando Super Trunfo de Cidades

Para usar o Super Trunfo de Cidades, siga estas etapas:

1. Execute o programa.
2. Cadastre suas cidades conforme as regras.
3. Visualize as cartas criadas.
4. Escolha duas cartas para batalhar.
5. Defina as características em disputa.
6. Acompanhe o resultado da batalha.
7. Escolha continuar batalhando ou cadastrar novas cidades.

## 📫 Contribuindo para Super Trunfo de Cidades

Para contribuir com Super Trunfo de Cidades, siga estas etapas:

1. Bifurque este repositório.
2. Crie um branch: `git checkout -b <nome_branch>`.
3. Faça suas alterações e confirme-as: `git commit -m '<mensagem_commit>'`
4. Envie para o branch original: `git push origin <nome_do_projeto>/<local>`
5. Crie a solicitação de pull.

Como alternativa, consulte a documentação do GitHub em [como criar uma solicitação pull](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

## 🤝 Colaboradores

Agradecemos às seguintes pessoas que contribuíram para este projeto:

<table>
  <tr>
    <td align="center">
      <a href="#" title="Gabriel">
        <img src="https://github.com/BLFenix" width="100px;" alt="https://avatars.githubusercontent.com/u/126727811?v=4"/><br>
        <sub>
          <b>Gabriel Ramos</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

## 😄 Seja um dos contribuidores

Quer fazer parte desse projeto? Clique [AQUI](CONTRIBUTING.md) e leia como contribuir.

## Exemplo de Carta

```
Estado: São Paulo
Nome: Campinas
Código: A01
População: 1.223.237 pessoas
Área: 795.69 km²
PIB: R$ 128.987,32
Pontos turísticos: 5
Densidade populacional: 1536.48 pessoas por km²
PIB per capita: R$ 105.45 por pessoa
Super poder: 3000.00 pontos
```

