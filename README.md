# Le House Hostel SP — Site institucional one page

Site estático (HTML + CSS + JS + Tailwind via CDN), sem backend.

## Estrutura

```text
/
├── index.html
├── css/style.css
├── js/script.js
├── img/            # logo + fotos reais do hostel
├── assets/         # espelho de img/ (compatível com SPEC)
└── README.md
```

## Identidade visual

Extraída do logo vetorizado (`img/logo.svg`, redesenho digital do original em `.docs/img/`):

| Token | Cor | Uso |
|---|---|---|
| Ink `#2B343E` | grafite do texto do logo | header, footer, textos |
| Terracota `#DE7A3A` | bloco laranja da casinha | CTA principal, destaques |
| Coral `#D95A43` | bloco vermelho da casinha | gradientes, hover |
| Teal `#3F8F96` | blocos azul-petróleo | selos, ícones, foco |
| Cream `#FAF5EC` / Sand `#F0E6D6` | neutros quentes | fundos |

Tipografia: Sora (títulos) + Inter (texto).

## Como usar

Abra `index.html` no navegador — não requer build nem servidor.

O formulário de contato valida em JS e abre o WhatsApp (`5511943489008`) com a mensagem montada. Botão "Como chegar" abre busca do endereço no Google Maps.

## Dados

Somente informações reais fornecidas: endereço, telefone, horários (check-in 13:00 / check-out 12:00), preços de referência por plataforma e comodidades listadas. Nenhum dado inventado.
