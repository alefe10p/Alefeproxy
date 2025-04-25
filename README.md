# Alefeproxy

Proxy multi-protocolo escrito em Rust com suporte a HTTP, HTTPS, SOCKS5, OpenVPN e muito mais.

## Recursos

- Modo 4 (status 101 + 200)
- Timeout e delay de handshake configuráveis
- Buffer ajustável dinamicamente
- Certificado SSL válido
- Multiplexador ativado
- Suporte a OpenVPN na porta 80
- Configuração simples via `config.toml`

## Instalação rápida

```bash
bash <(wget -qO- https://raw.githubusercontent.com/SEU_USUARIO_GITHUB/Alefeproxy/main/install.sh)
