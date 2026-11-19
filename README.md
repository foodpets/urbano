# Urbano Moto Service 🏍️💨

Site institucional da **Urbano Moto Service** — moto frete profissional em **Ribeirão Preto e região**.

> **Pediu. Buscou. Entregou.**

🌐 **Site:** https://entregasribeiraopreto.com.br/
📞 **WhatsApp:** (16) 99409-4229

## Serviços

- Entregas expressas
- Malotes e documentos
- Medicamentos
- Encomendas e compras
- Moto frete para empresas

## Estrutura

```
index.html                                   → página principal do site
cidades-atendidas/index.html                 → hub de cidades da região
entrega-rapida-por-motoboys-em-*/index.html  → página SEO por cidade (padrão Loggi)
css/style.css                                → estilos (tema escuro + amarelo)
js/main.js                                   → menu mobile, animações de scroll
sitemap.xml / robots.txt                     → SEO
.nojekyll                                    → evita processamento Jekyll no Pages
```

## Como editar

| O que | Onde |
|---|---|
| Telefone / WhatsApp | Buscar e substituir `5516994094229` e `(16) 99409-4229` em `index.html` e nas pastas de cidades |
| Textos e seções | `index.html` |
| Cores | Variáveis no topo do `css/style.css` |
| Bairros de Ribeirão Preto | `entrega-rapida-por-motoboys-em-ribeirao-preto/index.html` (regiões Norte, Leste, Oeste e Sul) |
| Cidades atendidas | Pastas `entrega-rapida-por-motoboys-em-*/` + seção "Áreas" no `index.html` + `sitemap.xml` |

## Publicação

O site é publicado automaticamente pelo **GitHub Pages** a partir da branch `main`.
Qualquer commit em `main` atualiza o site em poucos segundos.

O botão flutuante de WhatsApp abre a conversa com mensagem pré-preenchida
("Olá! Vim pelo site da Urbano Moto Service e quero solicitar uma entrega.").

#UrbanoMotoService #MotoFrete #Entregas #RibeirãoPreto #Motoboy #Delivery
