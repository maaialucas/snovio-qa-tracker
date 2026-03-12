[README-qa-tracker.md](https://github.com/user-attachments/files/25880253/README-qa-tracker.md)
# 🎫 QA Tracker · 
> Plataforma interna para rastreamento de tickets enviados ao QA — sem perder nenhum caso.

![Status](https://img.shields.io/badge/status-live-brightgreen) ![Made with](https://img.shields.io/badge/made%20with-HTML%20%2F%20CSS%20%2F%20JS-7B4FD4)

## 🔗 Acesso

**[https://maaialucas.github.io/snovio-qa-tracker/](https://maaialucas.github.io/snovio-qa-tracker/)**

---

## 📌 O que é

O QA Tracker resolve um problema simples: casos enviados ao QA se perdiam no Chat sem acompanhamento. Esta plataforma centraliza todos os tickets em um lugar, com links, prioridades, responsáveis e contador de dias automático.

---

## ✅ Funcionalidades

- **Criar tickets** com título, prioridade, nome do reporter e links
- **3 links por ticket** — Task, Chat e Ticket
- **Prioridade** — High 🔴 / Medium 🟡 / Low 🟢
- **Alerta visual de dias** — verde até 3d, amarelo 3–7d, vermelho +7d
- **Marcar como resolvido** com um clique
- **Filtros** por status (Abertos, Resolvidos, Urgentes) e por prioridade
- **Busca** por título, ID ou nome do reporter
- **Exportar CSV** com todos os tickets
- **Dados salvos no browser** — não some ao fechar

---

## 🏷 Prioridades

| Label | Quando usar |
|-------|-------------|
| 🔴 **High** | Bug crítico que afeta fluxo principal ou muitos usuários |
| 🟡 **Medium** | Bug que afeta parte dos usuários com workaround disponível |
| 🟢 **Low** | Problema visual ou edge case de baixo impacto |

---

## ⏱ Alerta de dias

| Cor | Tempo |
|-----|-------|
| 🟢 Verde | Até 3 dias |
| 🟡 Amarelo | Entre 3 e 7 dias |
| 🔴 Vermelho | Mais de 7 dias — requer atenção |

---

## 🛠 Tecnologias

- HTML5 / CSS3 / JavaScript puro
- LocalStorage para persistência dos dados
- Google Fonts — Nunito Sans + DM Mono
- Hospedado via GitHub Pages
- Zero dependências externas

---

## 🚀 Como atualizar

1. Edite o arquivo `index.html` diretamente no GitHub
2. Faça o commit — o site atualiza em menos de 2 minutos

---

## 🔮 Próximos passos planejados

- [ ] Integração com Chat via Apps Script
- [ ] Sincronização com Google Sheets como banco de dados central
- [ ] Notificação automática ao criar ticket

---

*Construído para uso interno — QA Team*
