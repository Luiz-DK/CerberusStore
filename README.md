# Cerberus Store — Site de Loja de Roupas (Projeto Acadêmico)

[![UniRV](https://img.shields.io/badge/UniRV-Universidade%20de%20Rio%20Verde-red?style=for-the-badge)](#)
[![Disciplina](https://img.shields.io/badge/Disciplina-Empreendedorismo-blue?style=for-the-badge)](#)
[![Evento](https://img.shields.io/badge/Feira-Negócios%20Digitais-orange?style=for-the-badge)](#)
[![Valor](https://img.shields.io/badge/Avaliação-40%20Pontos-brightgreen?style=for-the-badge)](#)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)](#)

Este repositório contém o código da **Cerberus Store**, uma solução digital desenvolvida para o segmento de **Loja de Roupas** como parte do trabalho prático da disciplina de **Empreendedorismo** da **Universidade de Rio Verde (UniRV)** para a **Feira de Negócios Digitais**.

---

## 📌 Contexto Acadêmico

- **Instituição:** Universidade de Rio Verde (UniRV) — Campus Rio Verde
- **Disciplina:** Empreendedorismo
- **Atividade:** Feira de Negócios Digitais (Simulação de Empresa de Soluções Digitais)
- **Segmento Atendido por este Site:** Loja de Roupas (1 dos 4 segmentos obrigatórios do projeto)
- **Objetivo da Atividade:** Desenvolver sites para pequenos negócios aplicando conceitos de empreendedorismo, inovação, design responsivo, identificação de público-alvo e estratégias de vendas para apresentação em estande.

---

## 🎯 Solução Proposta: Cerberus Store

A **Cerberus Store** é a extensão de moda esportiva e *streetwear* da **Academia Cerberus**, localizada em Rio Verde - GO. O projeto une vestuário de treino de alta performance ao estilo urbano, oferecendo uma vitrine digital completa e interativa para o comércio local.

### 💡 Problemas que o site resolve:
- **Dificuldade de escolha de tamanho online:** Resolve o problema de trocas através de uma **Calculadora de Tamanho Ideal** interativa.
- **Visualização limitada de variações:** Permite ao cliente alternar e visualizar em tempo real as fotos do produto por cor (Preto, Vermelho, Branco).
- **Atendimento lento:** Direciona a jornada do cliente diretamente para conversas pré-formatadas no WhatsApp para fechamento rápido de vendas.
- **Falta de sinergia entre negócios:** Integra a loja de roupas à Academia Cerberus via o **Combo Cerberus** (descontos cruzados na matrícula/compras).

---

## ✨ Requisitos do Edital Atendidos

| Requisito do Trabalho | Implementação na Cerberus Store | Status |
| :--- | :--- | :---: |
| **Página Inicial / Hero Section** | Apresentação do conceito *"Treino pesado. Rua com atitude."* com prova social e indicadores. | ✅ |
| **Quem Somos / MVV** | Seção com Missão, Visão e Valores alinhados à proposta de marca. | ✅ |
| **Produtos / Serviços** | Catálogo interativo de roupas (dry-fit, shorts, moletom) e acessórios (bonés, bandanas, garrafas). | ✅ |
| **Galeria de Imagens / Lookbook** | Carrossel horizontal automático estilo *Lookbook* apresentando os modelos em movimento. | ✅ |
| **Informações de Contato** | Endereço físico em Rio Verde - GO, horários de atendimento e telefone. | ✅ |
| **Botão para WhatsApp (Simulado)** | Links dinâmicos com mensagens pré-formatadas para simulação de vendas no estande. | ✅ |
| **Localização (Simulada)** | Mapa interativo do Google Maps focado em Rio Verde - GO. | ✅ |
| **Layout Responsivo** | Adaptação completa para mobile, tablet e desktop com menu hambúrguer e breakpoints dinâmicos. | ✅ |

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 Semântico:** Estruturação otimizada para acessibilidade e SEO.
- **CSS3 Moderno:** Flexbox, CSS Grid, Variáveis CSS, Glassmorphism e animações suaves com suporte a `prefers-reduced-motion`.
- **JavaScript (Vanilla ES6+):** 
  - Lógica de alternância dinâmica das cores dos produtos.
  - Carrosséis autônomos com tempo de transição de 3 segundos e pausa em *hover/focus*.
  - Algoritmo da Calculadora de Tamanhos baseada em medidas corporais.

---

## 📁 Estrutura de Arquivos

```text
cerberus-store/
├── index.html              # Código unificado (HTML5, CSS3 e JS)
├── imagens/                # Fotos dos produtos, acessórios e modelos do Lookbook
└── README.md               # Documentação técnica e acadêmica do projeto
