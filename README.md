# Plano de Aula Condensado: Bitcoin 101


## 1. Módulo 1: História e Fundamentos
- **Aula 1: O Cenário Pré e Pós-Bitcoin**  
 -   Discussão sobre a história econômica e tecnológica que levou à criação do Bitcoin.
- **Aula 2: O Nascimento do Bitcoin**  
○   Apresentação conceitual do whitepaper: o que é "peer-to-peer electronic cash".
○   Explicação do bloco gênesis.
- **Demonstração (Substituindo Desafios 1 e 2)**  
○	Demonstração rápida de um BlockExplorer público.  
○	Explicação do que é um nó (Node) e RPC, sem instalação.


## 2. Módulo 2: Criptografia e Wallets
-  **Aula 1: Conceitos de Criptografia**  
○	Panorama geral de onde a criptografia é usada.
- **Aula 2: Funções Hash**  
○	Explicação prática do que é uma função hash (input -> hash) e sua irreversibilidade.
- **Aula 3: Merkle Tree**  
○	Explicação visual de como a Merkle Tree é usada para resumir transações.
- **Aula 4: Chaves Públicas e Privadas**  
○	Foco no conceito de "propriedade" digital e a relação entre as chaves.
- **Demonstração (Substituindo Desafios 1 e 2)**
○	Demonstração de como uma wallet usa esses conceitos (chaves, saldo), sem codificar uma.


## 3. Módulo 3: Transações
- **Aula 1: UTXO**  
○	O que são (Unspent Transaction Outputs) e como formam o saldo.
- **Aula 2: UTXO vs. Account Model**  
○	Comparação direta entre o modelo do Bitcoin e o do Ethereum.
- **Aula 3: Ciclo de Vida de uma Transação**  
○	A jornada: Montar, Assinar, Propagar, Mempool, Minerada, Validada. (Usaremos o BlockExplorer da demo anterior para ilustrar).


## 4. Módulo 4: Blocos e Mineração
- **Aula 1: Mineração e Hashcash**  
○	Simulação conceitual do algoritmo Hashcash (prova de trabalho).
- **Aula 2: Anatomia de um Bloco**  
○	Explicação das características: header, body, nonce, hash, prevhash.
- **Aula 3: Halving e Dificuldade**  
○	Explicação do Halving, ajuste de dificuldade, hashrate e a evolução de CPU para ASICS.


## 5. Módulo 5: Consenso e Ataques
- **Aula 1: O Problema dos Generais Bizantinos (BFT)**  
○	Explicação do problema e como o Bitcoin (PoW) o resolve.
- **Aula 2: Proof-of-Work (PoW)**  
○	Revisão do PoW como algoritmo de consenso e prevenção a ataques Sybil.
- **Aula 3: PoW vs. PoS**  
○	Breve comparação de prós e contras entre os dois modelos.
- **Aula 4: Vetores de Ataque**  
○	Discussão conceitual: Gasto duplo (double spend), ataque de 51% e forks.
