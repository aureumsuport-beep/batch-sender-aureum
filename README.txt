
# AUR Batch (BSC) – Approve ilimitado + envio por lista

## Como usar
1. Abra `index.html` no navegador (Chrome/Brave com MetaMask).
2. Conecte na **BNB Smart Chain (ChainId 56)**.
3. Clique **Detectar símbolo/decimais** (lê do token AUR).
4. Clique **Aprovar (ilimitado)** (uma única vez) e confirme na MetaMask.
5. Cole a lista (uma por linha):
   ```
   0xEnd1, 0.00004
   0xEnd2, 0.00004
   ```
6. Clique **Enviar lote (batchERC20)**.
7. (Opcional) Ao terminar, clique **Revogar aprovação (zerar)**.

## Endereços pré-configurados
- **Token AUR (BSC):** `0x8FA01B8B65378d086CF0Ba122eC5813a3aDB6Ac1`
- **BatchTransfer:** `0xA83946b6C5Ec22F93B8303CE68E2f84D69b2DEb0`

## Observações
- Use **ponto** como separador decimal (ex.: `0.00004`).
- Faça primeiro um teste com 2–3 endereços e valores pequenos.
- Mantenha BNB para **gás**.
