# **Dojo Bitcoin 101**

## **Semana 1 - Bitcoin 101**

- Explicar sobre a história do Bitcoin
- Mostrar whitepaper, repositorio, bloco genesis, site documentação, comunidade bitcoin
- Como compilar o node RegTest
- Com funciona o RPC

**Desafio: **
- criar conta na quicknode (ou provider)
- se concetar com RPC testnet
- Criar um Explorer que:
  - consulta blocos por numero
  - consulta transações por hash
  - consulta saldo de carteira por endereço


---

## **Semana 2 - Transações UTXO**

**Objetivo:** Compreender o funcionamento das transações no Bitcoin e manipular UTXOs.

- Aprender a montar, assinar e transmitir uma transação.
- Monitorar transações na mempool e verificar após serem mineradas.
- Consultar saldos via UTXO utilizando scripts ou ferramentas de API.

---

## **Semana 3 - Smart Contracts na BVM (Scripts)**

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
