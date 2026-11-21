# Landing Page Oficial • Beatriz Sanches (TennisBar)

Landing page de alta conversão para consultoria e venda de sneakers e streetwear da consultora oficial **Beatriz Sanches** na rede **TennisBar**.

## 🚀 Tecnologias e Recursos
- **HTML5 & CSS Moderno:** Desenvolvido com Tailwind CSS, Google Fonts (Syne, Plus Jakarta Sans, Space Grotesk) e design streetwear hype/dark mode.
- **Identidade Visual Streetwear:** Estética urbana e premium, foco total na cultura sneaker (Nike, Adidas, New Balance, Vans, Jordan) sem exibição de fotos pessoais da consultora.
- **Vitrine Interativa:** Filtros dinâmicos por marca (Nike, Adidas, New Balance, Vans, Jordan) e campo de busca rápida em JavaScript puro.
- **CTAs Inteligentes para WhatsApp:** Botões "Pedir no Zap" com mensagens pré-formatadas contendo o nome do modelo desejado e o link do WhatsApp (`5512982991954`).
- **Guia de Fôrma / Tamanhos:** Widget interativo que orienta o cliente sobre o tamanho ideal para cada silhueta de tênis.
- **FAQ Accordion & Prova Social:** Depoimentos de clientes verificados e dúvidas frequentes sanadas.
- **Deploy Containerizado:** Pronto para produção com `Dockerfile` Nginx Alpine leve, gzip ativado e headers de segurança configurados.

## 📁 Estrutura de Arquivos
```
/data/OpenBot/Shared/beatriz-sanches/
├── index.html           # Aplicação frontend completa e autocontida
├── Dockerfile           # Imagem leve baseada em nginx:alpine
├── nginx.conf           # Configuração de rotas, cache e compressão gzip
├── docker-compose.yml   # Execução rápida local ou via Compose
└── README.md            # Documentação técnica do projeto
```

## 🛠️ Como rodar localmente com Docker
```bash
docker compose up -d --build
```
Acesse em: `http://localhost`

## 🌐 Deploy no Easypanel
- **Projeto:** `henrique`
- **Serviço:** `beatriz-sanches`
- **Porta do Container:** 80
- **Domínio sugerido:** `beatriz-sanches.henrique.7osjvf.easypanel.host`
