# Anamnese de Marca, Do Feed ao Consultório

Ferramenta interativa da Aula 1 do curso Do Feed ao Consultório. O médico responde dez passos e recebe a anamnese de marca consolidada em uma página, mais um briefing pronto para gerar conteúdo.

Página única, estática, sem backend. As respostas ficam no `localStorage` do navegador de quem preenche.

## Rodar local

Qualquer servidor estático serve. Exemplo:

```bash
python3 -m http.server 4173
# abre em http://localhost:4173
```

Ou apenas abra o `index.html` no navegador.

## Modo demo (gravação de vídeo)

A página tem um autoplay que preenche tudo sozinho, para gravação de tela:

- `?demo=1` roda uma vez em velocidade natural
- `?demo=1&speed=1.4` acelera
- `?demo=1&loop=1` repete em loop

Mantenha a aba em foco durante a gravação, senão o navegador desacelera os timers.

## Publicação

Servido como site estático via GitHub Pages, a partir da branch `main`, na raiz do repositório.
