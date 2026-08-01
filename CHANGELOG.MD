# Changelog

## v 0.1.0 - 01/08/2026

- Página Inicial funcionando com HTML e CSS

## v0.2.0 - 01/08/2026

### Adicionado
- Tema claro/escuro utilizando JavaScript.
- Alternância dinâmica de classes CSS através de `classList.toggle()`.
- Sistema baseado na classe `dark`, permitindo alterações como `body.dark` e `body.dark .container`.
- Tema claro definido como padrão inicial da aplicação.

### Testado
- Acesso da aplicação em outro dispositivo móvel pela rede local.
- Descoberta do IP da máquina utilizando `hostname -I`.
- Execução de servidor local no Pop!_OS utilizando:
  ```bash
  python3 -m http.server 8000

