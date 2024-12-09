# **Dojo Bitcoin 101**

## **Semana 1 - Criando uma Carteira Bitcoin Básica**

**Objetivo:** Configurar o ambiente e entender os fundamentos da criação de chaves e endereços Bitcoin.

- Subir um nó local do Bitcoin (Bitcoin Core).
- Gerar chaves privadas usando o padrão BIP32 (Hierarchical Deterministic Wallets).
- Derivar chaves públicas a partir das chaves privadas geradas.
- Criar um endereço Bitcoin do tipo P2PKH (Pay-to-PubKey-Hash).

---

## **Semana 2 - Transações UTXO**

**Objetivo:** Compreender o funcionamento das transações no Bitcoin e manipular UTXOs.

- Aprender a montar, assinar e transmitir uma transação.
- Monitorar transações na mempool e verificar após serem mineradas.
- Consultar saldos via UTXO utilizando scripts ou ferramentas de API.

---

## **Semana 3 - Smart Contracts no BVM (Scripts)**

**Objetivo:** Entender como funcionam os Script no Bitcoin e como implementa-los.

- STACK e Scripts.
- OP_RETURN, P2PKH, P2PK, P2WPKH.
- Implementar uma carteira Multisig manualmente.
  - 2 de 3 assinaturas para validar transações.
  - 3 de 5 assinaturas para validar transações.
  - N de M assinaturas para validar transações.

---

## **Semana 4 - Lightning Network e Escalabilidade**

**Objetivo:** Explorar a Lightning Network como solução de segunda camada para escalabilidade.

- Subir um nó Lightning (ex.: `LND` ou `c-lightning`).
- Criar um canal de pagamento entre nós.
- Aprender a montar, assinar e transmitir uma transação na Lightning Network.
- Monitorar transações na rede Lightning.
- Consultar saldos via UTXO associados aos canais.

---

## **Semana 5 - Taproot**

**Objetivo:** Implementar scripts Taproot e explorar as melhorias trazidas por esta atualização.

- P2TR, MAST
- Gerar uma chave-pública agregada utilizando múltiplos signatários.
- Criar um script Taproot.
- Enviar fundos para um endereço Taproot.
- Gastar os fundos com Taproot revelando apenas o caminho de execução necessário.
