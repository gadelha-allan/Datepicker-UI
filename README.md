# Datepicker UI 📅

Uma interface de usuário (UI) elegante, moderna e estática de um seletor de datas (Datepicker). Este projeto foi desenvolvido focado puramente na estruturação de layouts e estilização avançada, seguindo os desafios propostos pelo roadmap.sh

O objetivo principal foi praticar conceitos modernos de CSS, como alinhamento responsivo com Flexbox e construção de malhas complexas com CSS Grid, sem o uso de frameworks ou bibliotecas externas.

---

## 🎨 Funcionalidades e Detalhes Visuais

- **Layout Base Inteligente**: Estrutura centralizada utilizando Flexbox para perfeita exibição em qualquer tela.
- **Grade de Calendário Simétrica**: Construída com CSS Grid para alinhar perfeitamente os dias da semana e as colunas numéricas.
- **Estados Visuais Customizados**:
  - Dias do mês atual e dias esmaecidos para meses adjacentes (`.prev-month`, `.next-month`).
  - Destaque sutil para o dia atual (`.today`).
  - Destaque completo com sombra projetada para a data selecionada (`.selected`).
- **Design Moderno**: Cantos suavizados com raios de curvatura de `10px` e `20px` que se assemelham aos padrões das bibliotecas de UI atuais (como Tailwind e Shadcn).

---

## 📂 Estrutura de Arquivos

O projeto está modularizado de forma simples e direta:

```text
datepicker-ui/
├── index.html   # Estrutura semântica do componente
└── style.css    # Estilização completa e resets globais
