# Plano
## Tarefa
Recriar o Flappy Bird como um jogo web polido e jogável. Canvas-based, com física de gravidade, canos que rolam, colisão, pontuação, high score (localStorage), telas de start/game/gameover, partículas e visual de produto 2026.

## Stack
HTML único + Canvas 2D + JS puro + Tailwind CDN (zero build, resultado imediato). Jogo em canvas é mais confiável que React para game loop de 60fps.

## Design
- Paleta: céu em gradiente (do pôr-do-sol: #FF6B6B → #4ECDC4 → #1A535C), canos verde-água (#2EC4B6), pássaro amarelo-ouro (#FFD93D), UI em glassmorphism
- Tipografia: "Press Start 2P" (display pixelada) + Inter (corpo)
- Layout: canvas centralizado, HUD de score flutuante, overlays com blur

## Itens
- [ ] Criar HTML base com canvas, estilos e fontes
- [ ] Implementar game loop, física do pássaro (gravidade + flap)
- [ ] Implementar canos (spawn, scroll, gap, colisão)
- [ ] Implementar chão animado, nuvens de fundo, parallax
- [ ] Implementar pássaro com animação de asa e rotação
- [ ] Implementar estados: start, playing, gameover
- [ ] Implementar score + high score (localStorage)
- [ ] Adicionar partículas e polish visual
- [ ] Subir servidor e testar no browser
- [ ] Verificar mobile (390px) e corrigir se preciso

## Status
Iniciando implementação
