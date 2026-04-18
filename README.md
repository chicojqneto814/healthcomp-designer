# HealthComp Designer

Template HTML parametrizado para geração automatizada de arte com identidade HealthComp fiel.

## Como funciona

1. Cada slide recebe um JSON com os dados do conteúdo
2. O JSON é codificado em Base64 e passado como parâmetro `?data=` na URL
3. O template lê o JSON, preenche os slots e renderiza com identidade oficial
4. HTML/CSS to Image converte a URL em PNG pronto para Instagram

## URL base

```
https://chicojqneto814.github.io/healthcomp-designer/?data=BASE64_JSON
```

## Tipos de slide disponíveis

- `hero` — Slide de abertura com tag de data/alerta, headline grande, body e card de fonte
- `context` — Slide de contexto com eyebrow, headline e lista de 3 pontos com seta
- `stat` — Slide de estatística com número grande e headline secundária
- `action` — Slide de ação com lista numerada 1-4
- `cta` — Slide de fechamento com manifesto, botão e link

## Identidade visual

- Azul marinho oficial: `#1C1C4F`
- Verde acento oficial: `#108E5E`
- Tipografia: DM Sans (corpo) + Fraunces (display)
- Formato: 1080×1350 (vertical)

## Estrutura

```
/
├── index.html                    # Template parametrizado
├── assets/
│   ├── logo_horizontal_verde.png    # Logo sobre fundo escuro
│   ├── logo_horizontal.png          # Logo sobre fundo claro
│   ├── logo_icone_verde.png         # Ícone sobre fundo escuro
│   └── logo_icone.png               # Ícone sobre fundo claro
└── README.md
```

---

HealthComp · Grupo Ecomp · Natal / RN
