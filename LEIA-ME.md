# Relógio CYD (ESP32 dual USB)

Hora de Brasília (UTC-3), sincronizada por NTP a cada 15 minutos. Não precisa de Arduino IDE.

## Gerar o instalador (uma vez só)
1. Crie uma conta em github.com e um repositório **público** novo.
2. Envie todos os arquivos desta pasta (Add file > Upload files), inclusive a pasta oculta `.github`.
3. Em Settings > Pages, escolha Source: **GitHub Actions**.
4. Aba Actions: espere o build terminar (uns 3 a 5 min). Se o deploy falhar por causa do Pages, clique em Re-run.
5. Abra `https://SEU-USUARIO.github.io/NOME-DO-REPO/` no Chrome/Edge e clique em Instalar.

## Uso
- Primeira vez: conecte o celular na rede `Relogio-CYD` e configure o Wi-Fi.
- BOOT curto: muda brilho. BOOT 5 s: abre a configuração (Wi-Fi, inverter cores, trocar vermelho/azul, girar tela).
