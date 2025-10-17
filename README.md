Aqui está a versão corrigida do seu texto em português brasileiro, mantendo o formato em Markdown:

# **Bitcoin 101**

## **Módulo 1 - História**

- Aula 1: Explicar a história do pré e pós-Bitcoin do ponto de vista econômico e tecnológico.
- Aula 2: Apresentar o whitepaper, repositório, bloco gênesis, site de documentação e comunidade Bitcoin.
- Aula 3: Como rodar um nó Bitcoin na máquina (Node RegTest).

**Desafio 1**
- Criar uma conta na QuickNode (ou outro provedor).
- Conectar-se à RPC da testnet.
- Escrever um script em JavaScript ou Python que:
  - Consulte blocos por número.
  - Consulte transações por hash.
  - Consulte o saldo de uma carteira por endereço.

**Desafio 2: Construir um Frontend BlockExplorer e publicá-lo.**

---

## **Módulo 2 - Wallets**

- Aula 1: História da criptografia, aplicações e áreas em um panorama geral.
- Aula 2: Funções hash, tipos de funções usadas e não usadas no Bitcoin, demonstrar de forma prática o que são.
- Aula 3: Merkle Tree, explicar onde é utilizada em blockchains e no Bitcoin, demonstrar na prática como funciona.
- Aula 4: Chaves públicas, explicar o que são, quais curvas são usadas nas blockchains e focar no Bitcoin, criar de forma prática.

**Desafio 1**
- Criar uma conta offline via CLI.
- Obter alguns bitcoins da testnet.
- Enviar transações simples de transferência de valor.

**Desafio 2: Desenvolver uma wallet funcional para Bitcoin em Node.js + React que:**
- Permita criar contas.
- Receba bitcoins na testnet.
- Envie bitcoins na testnet.
- Consulte o saldo de qualquer carteira.

---

## **Módulo 3 - Transações**

- Aula 1: UTXO, o que são na teoria e como são usados para formar o saldo de cada carteira.
- Aula 2: Account Model vs. UTXO Model, comparar o modelo de contas do Bitcoin com o do Ethereum.
- Aula 3: Ciclo de vida de uma transação: montar, assinar, propagar (broadcast), mempool, minerada, validada (6 blocos).

**Desafio: Construir um script que monitore eventos/estados de novas transações.**

---

## **Módulo 4 - Blocos**

- Aula 1: Mineração, simulação do algoritmo Hashcash e como ele é usado para validar blocos.
- Aula 2: Blockchain, encadeamento de blocos e características técnicas dos blocos (header, body, nonce, hash, prevhash, etc.).
- Aula 3: Halving, como o cálculo ocorre, hashrate e dificuldade de mineração, comparação entre CPU, GPU e ASICs.

**Desafio: Construir um algoritmo de Hashcash em diferentes linguagens e realizar um benchmark para identificar qual é mais rápida.**

---

## **Módulo 5 - Consenso**

- Aula 1: BFT, o problema dos generais bizantinos e como o Bitcoin o resolve.
- Aula 2: PoW, simulação do algoritmo de consenso do Bitcoin e prevenção contra ataques Sybil.
- Aula 3: PoS, simulação do algoritmo de consenso e comparação de prós e contras com o PoW do Bitcoin.
- Aula 4: Ataques, apresentar os ataques mais comuns que um sistema distribuído usando PoW pode sofrer e como o Bitcoin lida com eles (double spend, ataque de 51%, forking).

**Desafio 1: Descobrir quantos nós a rede Bitcoin possui hoje usando o RPC dos nodes.**

**Desafio 2: Construir um CRUD que simule uma blockchain simples e se conecte com outros CRUDs, formando uma rede P2P e não um modelo cliente-servidor.**
