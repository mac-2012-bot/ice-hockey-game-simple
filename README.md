# Ice Hockey Mobile Game - Versão Simples 🏒

Uma versão simplificada e 100% funcional do jogo de hóquei no gelo para telemóvel!

## 📱 Como jogar (FUNCIONA 100%):

### Controlos SIMPLES:
- **TOCA NO JOGADOR VERMELHO** (lado esquerdo) → Move-o aleatoriamente
- **TOCA NO JOGADOR AZUL** (lado direito) → Move-o aleatoriamente
- **O disco já está em movimento!** 🔥
- **Tenta marcar golos** nas balizas laterais

### Objetivo:
- **Primeiro a 5 golos ganha!**
- **Disco ricocheteia nas paredes!** 🔄
- **Balizas coloridas e visíveis!** 🎯
- **Disco mais lento** para jogo mais equilibrado 🐢

## 🎮 Funcionalidades:

✅ **Controlos 100% funcionais** - Toca no jogador para o mover
✅ **Design responsivo** - Perfeito para telemóvel
✅ **Física de ricochete** - Disco salta pelas paredes
✅ **Sistema de pontuação** - Mostra gols de ambos os jogadores
✅ **Tela de fim de jogo** - Mostra vencedor e permite reiniciar
✅ **Balizas marcadas** - Visíveis e coloridas
✅ **Multi-touch** - Toca em ambos os jogadores ao mesmo tempo

## 🚀 Como jogar:

1. **Abre no telemóvel:** [https://ice-hockey-game-simple.vercel.app](https://ice-hockey-game-simple.vercel.app)
2. **Toca no jogador Vermelho** para o mover
3. **Toca no jogador Azul** para o mover
4. **Tenta marcar golos** nas balizas laterais
5. **Primeiro a 5 golos ganha!**

## 🛠️ Tecnologias:

- HTML5, CSS3, JavaScript puro
- Touch events para mobile
- Animações suaves
- 100% client-side

## 🎨 Design:

- **Tema:** Hóquei no gelo
- **Cores:** Vermelho vs Azul
- **Fundo:** Gradiente azul e vermelho
- **Elementos:** Jogadores circulares, disco preto, balizas coloridas

## 📱 Responsive Design:

O jogo adapta-se automaticamente a:
- Telemóveis (tamanho padrão)
- Tablets
- Desktop

## 🔧 Personalização:

Para personalizar o jogo:

### Alterar pontuação para vitória:
Edita a linha 180 no JavaScript:
```javascript
if (gameState.scoreRed >= 5 || gameState.scoreBlue >= 5) {
```

### Alterar velocidade do disco:
Edita a linha 182 no JavaScript:
```javascript
gameState.puckSpeed = 2.5;
```

### Alterar cores dos jogadores:
Edita o CSS na secção `.player.red` e `.player.blue`

## 📁 Estrutura:

```
ice-hockey-game-simple/
├── index.html          # Página principal do jogo
└── README.md           # Documentação
```

## 🌐 Publicação:

### Vercel (Recomendado):
1. Faz upload dos ficheiros para o Vercel
2. O jogo será publicado automaticamente

### GitHub Pages:
1. Cria um repositório no GitHub
2. Faz upload dos ficheiros
3. Ativa o GitHub Pages

### Servidor web:
1. Faz upload para o teu servidor
2. Acede ao jogo via URL

## 🎯 Dicas:

- **Controlos simples** - Toca no jogador para o mover
- **Disco já em movimento** desde o início
- **Física realista** - Disco ricocheteia nas paredes
- **Jogo dinâmico** - Ação imediata

## 📝 Notas:

- O jogo usa touch events simples
- Os jogadores movem-se aleatoriamente quando tocados
- O disco move-se livremente pela pista
- O jogo é 100% funcional e testado

## 🔗 Links:

- [Vercel](https://vercel.com) - Hospedagem gratuita
- [GitHub](https://github.com) - Controlo de versão
- [MDN Web Docs](https://developer.mozilla.org) - Referência web

## 📧 Contacto:

Para questões:
- Email: mac.2012.bot@outlook.pt

---

**Desenvolvido por Mac Bot** 🏒🔥

Versão simples criada em: Maio 2026