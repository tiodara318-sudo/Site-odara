# 🌟 Odara OSC | Cultura, Educação e Juventudes

> Transformando realidades através da arte, da educação e do protagonismo juvenil.

Este repositório contém o código-fonte oficial do site institucional da **Odara OSC**, uma organização dedicada a promover o desenvolvimento autônomo, a cultura e o incentivo à leitura para as juventudes brasileiras.

---

## 🚀 Sobre o Projeto

O site foi desenvolvido com foco em **responsividade, design moderno e facilidade de manutenção**, utilizando uma arquitetura baseada em dados centralizados (`CONFIG_ODARA`). Isso permite que qualquer membro da equipe atualize textos, membros de equipe, projetos, personagem do mês e pesquisas mensais de forma rápida direto no código JavaScript, sem precisar mexer na estrutura HTML.

### ✨ Principais Funcionalidades
* **Design Responsivo & Moderno:** Construído com **Tailwind CSS**, adaptando-se perfeitamente a celulares, tablets e computadores.
* **Modo Escuro (Dark Mode):** Alternância fluida entre o tema claro e escuro para melhor acessibilidade e conforto visual.
* **Painel de Setores & Equipe Interativo:** Cards dinâmicos e modais interativos para exibir os gestores, vice-gestores e integrantes de cada setor da ONG.
* **Liderança em Destaque:** Seção dedicada ao líder da empresa estrategicamente posicionada para maior destaque.
* **Curiosidades & Pesquisas Mensais ("A Arte que Transforma"):** Módulo dinâmico voltado para artigos, reflexões sobre arte e recomendações de museus em São Paulo.
* **Espaço Interativo & Indicações:** Seções dedicadas à "Vibe Cultural", livro do mês e indicações de lugares culturais.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5** (Estruturação semântica)
* **Tailwind CSS via CDN** (Estilização e responsividade)
* **JavaScript (Vanilla)** (Lógica, manipulação de DOM e dados dinâmicos)
* **Google Fonts (Plus Jakarta Sans)** (Tipografia)

---

## 📁 Estrutura do Código

Toda a customização e atualização de conteúdos do site é centralizada em um único objeto de configuração JavaScript no início do arquivo `index.html`:

```javascript
const CONFIG_ODARA = {
    instagramUrl: "[https://www.instagram.com/odara.osc/](https://www.instagram.com/odara.osc/)",
    hero: { ... },
    lideranca: { ... },
    sobre: { ... },
    setoresEquipe: { ... },
    personagemMes: { ... },
    pesquisaMes: { ... },
    projetos: [ ... ],
    livroMes: { ... },
    lugarMes: { ... }
};
