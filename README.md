# 🎰 Cassino do Felixo

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Live Demo](https://img.shields.io/badge/demo-online-brightgreen.svg)](https://felipe-alcantara.github.io/Cassino-do-felixo/)

> **"Os cassinos são justos?"** - Um amigo perguntou. Então eu fiz este site para provar que é perfeitamente possível criar um cassino **impossível** de ganhar! 🎲

## 🌐 Acesse o Projeto

### 🎮 **[JOGAR AGORA - Versão Web](https://felipe-alcantara.github.io/Cassino-do-felixo/)**

---

## 📖 Sobre o Projeto

Este é um **cassino educacional** criado como resposta a uma discussão entre amigos sobre a justiça dos cassinos online. Quando questionado se os cassinos eram honestos, decidi criar este projeto para demonstrar, de forma prática e bem-humorada, como é possível manipular completamente as probabilidades em um jogo de azar.

### 🎯 A Brincadeira

O **Cassino do Felixo** é um caça-níquel online com uma peculiaridade especial: **a chance de ganhar é de apenas 0,1%** (1 em 1000 tentativas). Isso mesmo, as probabilidades foram programadas para serem extremamente desfavoráveis ao jogador, ilustrando como cassinos digitais podem facilmente controlar os resultados.

### 💡 Propósito Educacional

Este projeto serve como:

- 📚 **Demonstração prática** de como probabilidades podem ser manipuladas em jogos online
- ⚠️ **Alerta educacional** sobre os riscos de jogos de azar
- 🎨 **Exemplo de desenvolvimento web** com HTML, CSS e JavaScript puro
- 🤔 **Reflexão** sobre a transparência (ou falta dela) em plataformas de apostas

---

## ✨ Características

### 🎨 Visual Moderno
- Design em tons de roxo e rosa com efeitos neon
- Animações suaves e responsivas
- Elementos flutuantes de cassino (cartas, dados, símbolos)
- Interface totalmente responsiva (desktop, tablet e mobile)

### 🎰 Mecânica do Jogo
- Sistema de caça-níquel com 3 rolos
- Animação realista de giro
- Símbolos temáticos: 🍒 🍋 🍊 🍉 💎 7️⃣ ⭐ 🔔
- Sistema de "pagamento" fake ao vencer
- **Chance de vitória: 0,1%** (propositalmente baixa)

### 🔧 Recursos Técnicos
- HTML5, CSS3 e JavaScript Vanilla (sem frameworks)
- Modais personalizados (sem `alert()`)
- 50+ elementos decorativos gerados dinamicamente
- Animações CSS com keyframes
- Google Fonts (Righteous e Poppins)

### ℹ️ Transparência
- Botão de informação que revela a verdadeira probabilidade de vitória
- Código-fonte aberto para análise e aprendizado
- Comentários explicativos no código

---

## 🚀 Como Executar Localmente

### Pré-requisitos
- Um navegador web moderno (Chrome, Firefox, Edge, Safari)
- Nenhuma dependência adicional necessária!

### Instalação

1. **Clone o repositório**
   ```bash
   git clone https://github.com/Felipe-Alcantara/Cassino-do-felixo.git
   ```

2. **Navegue até a pasta**
   ```bash
   cd Cassino-do-felixo
   ```

3. **Abra o arquivo no navegador**
   - Simplesmente abra o arquivo `index.html` no seu navegador
   - Ou use uma extensão como Live Server no VS Code

---

## 🎮 Como Jogar

1. 🌐 Acesse a **[versão web](https://felipe-alcantara.github.io/Cassino-do-felixo/)**
2. 💰 Clique no botão **"GIRAR E TENTAR A SORTE"**
3. 🎰 Assista os rolos girarem
4. 🍀 Torça para conseguir 3 símbolos iguais (boa sorte com 0,1%!)
5. ℹ️ Clique no botão azul **"?"** para ver a verdadeira probabilidade

---

## 📊 Estatísticas de Probabilidade

| Evento | Probabilidade | Descrição |
|--------|---------------|-----------|
| 🏆 **Vitória** | **0,1%** | 1 em 1000 tentativas |
| 😢 **Derrota** | **99,9%** | 999 em 1000 tentativas |

*Estes valores são programados no código-fonte e podem ser verificados na função `finalizarGiro()`.*

---

## 🛠️ Estrutura do Projeto

```
Cassino-do-felixo/
│
├── index.html          # Arquivo principal (HTML + CSS + JS)
├── LICENSE            # Licença MIT
└── README.md          # Este arquivo
```

### 🔍 Principais Funções

```javascript
// Função que determina o resultado (0,1% de chance de vitória)
function finalizarGiro() {
  const ganhou = Math.random() < 0.001; // 0,1% de chance
  // ...
}

// Geração dinâmica de 50 elementos decorativos
function criarElementosCassino() {
  // Cria elementos com posições, tamanhos e animações aleatórias
}
```

---

## 🎓 O Que Aprendi

Este projeto foi uma excelente oportunidade para:
- ✅ Demonstrar conceitos de **probabilidade e estatística**
- ✅ Praticar **animações CSS avançadas**
- ✅ Trabalhar com **geração dinâmica de elementos** via JavaScript
- ✅ Criar uma **UX envolvente e divertida**
- ✅ Implementar **design responsivo** sem frameworks
- ✅ Comprovar que **transparência importa** em jogos online

---

## ⚠️ Aviso Legal

> **Este é um projeto educacional e de entretenimento!**
> 
> - 🚫 Não envolve dinheiro real
> - 🚫 Não incentiva jogos de azar
> - ✅ Criado para fins educacionais e demonstrativos
> - ✅ Código aberto para aprendizado
> 
> **Jogos de azar podem causar dependência. Se você ou alguém que conhece tem problemas com apostas, procure ajuda profissional.**

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👨‍💻 Autor

**Felipe Alcântara**

- GitHub: [@Felipe-Alcantara](https://github.com/Felipe-Alcantara)
- Projeto: [Cassino do Felixo](https://github.com/Felipe-Alcantara/Cassino-do-felixo)
- Demo: [https://felipe-alcantara.github.io/Cassino-do-felixo/](https://felipe-alcantara.github.io/Cassino-do-felixo/)

---

## 🤝 Contribuições

Contribuições, issues e sugestões são bem-vindas!

1. Faça um Fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/NovaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/NovaFeature`)
5. Abra um Pull Request

---

## 🌟 Agradecimentos

- Ao amigo que fez a pergunta que inspirou este projeto
- A todos que testaram e se divertiram com o cassino impossível
- À comunidade open source por tornar o aprendizado acessível

---

<div align="center">

### 🎰 [EXPERIMENTE O CASSINO IMPOSSÍVEL](https://felipe-alcantara.github.io/Cassino-do-felixo/) 🎰

**Feito com 💜 e um pouco de malícia por Felipe Alcântara**

*"Provando que nem todos os cassinos são honestos... especialmente este!"* 😄
</div>