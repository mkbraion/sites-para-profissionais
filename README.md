# 🌐 Sites para Profissionais

Coleção de **modelos de site prontos por nicho** — advogados, clínicas de estética, consultórios, personal trainers e mais. Cada modelo é **um único arquivo HTML**, responsivo e fácil de personalizar: é só trocar os textos entre `[colchetes]`, as cores e os contatos.

Faz parte do ecossistema **KAIA** e serve tanto como portfólio quanto como produto (sites sob encomenda).

## Modelos disponíveis

| Nicho | Pasta | Status |
|-------|-------|--------|
| Advocacia | [`templates/advogado`](templates/advogado/index.html) | ✅ Pronto |
| Clínica / Estética | [`templates/estetica`](templates/estetica/index.html) | ✅ Pronto |
| Saúde / Consultório | [site-psiquiatria](https://github.com/mkbraion/site-psiquiatria) | ✅ Pronto (repo próprio) |
| Personal / Fitness | — | 🔜 Em breve |
| Barbearia / Salão | — | 🔜 Em breve |
| Loja / Catálogo | — | 🔜 Em breve |

A [`index.html`](index.html) na raiz é a **landing que apresenta e vende** os modelos.

## Como usar um modelo

1. Abra a pasta do nicho (ex.: `templates/advogado`).
2. Edite o `index.html`: troque tudo que estiver entre `[colchetes]`, as cores (variáveis `--` no topo do `<style>`) e os links de WhatsApp/e-mail/Instagram.
3. Publique de graça no **GitHub Pages**, **Netlify** ou **Vercel**.

### Personalizar o WhatsApp
Procure por `wa.me/5500000000000` e troque pelo seu número com DDI/DDD (ex.: `5511987654321`).

## Rodar localmente

Abra qualquer `index.html` no navegador, ou sirva a pasta:

```bash
npx serve .
```

## Roadmap

- [ ] Modelos: personal trainer, barbearia/salão, loja/catálogo
- [ ] Gerador que preenche o modelo com textos via IA (integra com o [gerador-conteudo-ia](https://github.com/mkbraion/gerador-conteudo-ia))
- [ ] Seletor de tema/cor na própria landing

---

Feito por [@mkbraion](https://github.com/mkbraion).
