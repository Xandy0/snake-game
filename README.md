# 🐍 Snake Game

Um jogo clássico da cobrinha desenvolvido com **HTML5, CSS3 e JavaScript Vanilla**, com interface moderna, sistema de pontuação, recorde salvo localmente e jogabilidade simples e divertida.

---

## 🎮 Demonstração

O objetivo do jogador é controlar a cobra, coletar alimentos e aumentar sua pontuação sem colidir com as paredes ou com o próprio corpo.

### ✨ Recursos

- 🐍 Sistema clássico de movimentação da cobrinha
- 🍎 Geração aleatória de comida
- 🏆 Sistema de recorde utilizando Local Storage
- 🎯 Contador de pontuação em tempo real
- 💀 Tela de Game Over
- 🔄 Reinício rápido da partida
- 🎨 Interface moderna com tema escuro
- ⚡ Desenvolvido sem bibliotecas externas

---

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Canvas API

---

## 📂 Estrutura do Projeto

```text
SnakeGame/
│
├── JogoCobrinha.html
└── README.md
```

---

## 🎯 Mecânicas do Jogo

### Movimentação
Utilize as teclas direcionais do teclado:

| Tecla | Ação |
|--------|--------|
| ⬆️ | Mover para cima |
| ⬇️ | Mover para baixo |
| ⬅️ | Mover para esquerda |
| ➡️ | Mover para direita |

### Sistema de Pontuação

- Cada alimento coletado adiciona **1 ponto**.
- A cobra cresce ao consumir comida.
- O recorde é salvo automaticamente no navegador.

---

## 🏆 Sistema de Recordes

O jogo utiliza o recurso:

```javascript
localStorage
```

para armazenar a melhor pontuação do jogador entre sessões.

---

## 🎨 Interface

O projeto possui:

- Fundo escuro moderno
- Efeitos visuais suaves
- Canvas centralizado
- Menus de início e fim de partida
- Design responsivo para diferentes resoluções

---

## 🚀 Como Executar

### Método 1 — Abrir diretamente

1. Baixe o arquivo.
2. Abra o arquivo `JogoCobrinha.html`.
3. Execute em qualquer navegador moderno.

### Método 2 — Servidor Local

```bash
python -m http.server
```

Depois acesse:

```text
http://localhost:8000
```

---

## 📸 Funcionalidades Implementadas

✅ Sistema de colisão com paredes

✅ Sistema de colisão com o próprio corpo

✅ Geração segura de comida

✅ Crescimento progressivo da cobra

✅ Controle por teclado

✅ Game Over

✅ Reinício da partida

✅ Armazenamento de recorde

---

## 🔮 Melhorias Futuras

- 🎵 Efeitos sonoros
- 🏅 Sistema de conquistas
- 🌎 Ranking online
- ⚙️ Níveis de dificuldade
- 💎 Power-ups especiais
- 👾 Modo Boss Battle
- 🎨 Temas personalizáveis

---

## 👨‍💻 Autor

Projeto desenvolvido para fins de estudo e aprendizado em desenvolvimento web utilizando JavaScript puro.

---

## 📄 Licença

Este projeto pode ser utilizado livremente para fins educacionais e de estudo.
