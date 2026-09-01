# The Architecture and Fundamentals of Computer Networks

> Para fins de estudos e praticidade criando mini resumos sobre todo o contexto para aprimorar minha base em redes.

Projeto prático da DIO - Construindo um Caderno Temático com NotebookLM e Inteligência Artificial como ferramenta de aprendizagem ativa.

🔗 **Meu Caderno no NotebookLM:** `Foundations and Architecture of Computer Networks` - 5 fontes | 01 set. 2026

## 📸 Mapa Mental Gerado pela IA

![Mapa Mental do NotebookLM](NotebookLM%20Mind%20Map.png)

---

### 1. Contexto e Objetivos

**Tema Escolhido:** Fundamentos e Arquitetura de Redes de Computadores.

Escolhi este tema porque a área de redes é a base para qualquer profissional de TI / Infra / Cloud. O vídeo da Professora Nattane, que usei como fonte principal, apresenta uma visão panorâmica e didática que me ajudou a conectar os pontos que antes pareciam soltos e complexos.

**Objetivos de estudo com este material:**
- Diferenciar claramente o papel dos dispositivos físicos: HUB, SWITCH e Roteador.
- Entender os modelos lógicos OSI (7 camadas) e TCP/IP (4 camadas) e sua aplicação prática.
- Dominar os conceitos de Endereçamento IP (IPv4 vs IPv6) e dos protocolos essenciais do dia a dia: DNS e HTTP.
- Criar um material de revisão rápida para futuras entrevistas e certificações.

### 2. Curadoria de Fontes

As 5 fontes abertas que selecionei e carreguei no NotebookLM foram:

1.  **Diferença entre HUB, SWITCH e Roteador** (Vídeo YouTube)
2.  **Endereçamento IP explicado de uma forma simples** (Vídeo YouTube)
3.  **Modelo OSI e TCP/IP** (Vídeo YouTube)
4.  **Principais protocolos de rede - Aula completa** (Vídeo YouTube)
5.  **Redes de Computadores explicadas de forma simples** (Vídeo YouTube)

Todas as fontes foram utilizadas para gerar os artefatos do Estúdio: Flashcards, Mapa, Quiz, Relatórios e Infográfico.

### 3. Engenharia de Prompts e "Cicatrizes"

#### Prompt 1 - Resumo Estruturado
**Prompt que usei:** `Aja como um professor de redes. Com base nas 5 fontes, crie um resumo em 3 blocos: 1) Componentes Físicos e Meios de Conexão, 2) Modelos Lógicos (OSI e TCP/IP), 3) Protocolos Essenciais (DNS, HTTP, IP). Use analogias simples.`

**Cicatriz / Aprendizado:** No início usei `Resuma os vídeos` e a resposta veio muito genérica. Aprendi que dar persona + estrutura + objetivo resolve o problema de alucinação e superficialidade. Também precisei pedir para a IA citar a fonte do trecho.

#### Prompt 2 - Para Gerar o Mapa Mental que está neste repositório
**Prompt que usei:** `Crie um mapa mental hierárquico começando em "Redes de Computadores" e ramificando para Dispositivos Finais, Roteadores, Meios de Conexão, Camadas OSI/TCP-IP e Protocolos. Para cada protocolo, defina em 1 frase.`

**Resultado:** O arquivo `NotebookLM Mind Map.png` que está na raiz deste repositório.

#### Prompt 3 - Para Flashcards e Quiz
**Prompt que usei:** `Crie 10 flashcards no formato P: / R: focados em HUB vs SWITCH e IPv4 vs IPv6. Depois crie um Quiz de 5 questões sobre OSI e DNS para eu testar meu conhecimento.`

**Troubleshooting:** A IA estava criando perguntas muito fáceis. Adicionei `nível intermediário e com pegadinhas técnicas` e melhorou muito.

### 4. Miniguia de Estudo (Entrega Final)

#### Resumo Estruturado
**Redes** são dispositivos interconectados que trocam dados. O fluxo é:
**PC -> SWITCH (rede local) -> Roteador (sai para internet) -> DNS (traduz nome para IP) -> HTTP (busca o site)**
- **HUB:** Burro. Repete o sinal para todos. Gera colisão. Quase não se usa mais.
- **SWITCH:** Inteligente. Aprende o MAC e envia só para quem precisa. Usado dentro da rede local.
- **Roteador:** Conecta redes diferentes. Decide o melhor caminho usando IP.
- **OSI vs TCP/IP:** OSI é teórico (7 camadas) para estudo. TCP/IP é prático (4 camadas) e é o que roda a internet.
- **IPv4 vs IPv6:** IPv4 (32 bits, 192.168.0.1) está acabando. IPv6 (128 bits) é o futuro.
- **DNS + HTTP:** DNS é a agenda, HTTP é a linguagem da web.

#### Glossário
- **Dispositivos Finais:** PCs, celulares, servidores - ponta da rede.
- **Meios de Conexão:** Cabo de par trançado, fibra ótica, Wi-Fi.
- **Camada OSI:** Divisão em 7 níveis para organizar a comunicação.
- **TCP/IP:** Pilha de protocolos que sustenta a internet.
- **DNS:** Domain Name System - Traduz `dio.me` para `104.18.32.47`
- **HTTP/HTTPS:** HyperText Transfer Protocol - Protocolo para navegar na web.
- **Endereço IP:** Identidade lógica de um dispositivo na rede.

#### Prompts Reutilizáveis para Revisão
1.  `Explique como um pacote viaja do meu PC até o Instagram usando as 5 fontes.`
2.  `Crie uma tabela: HUB vs SWITCH vs Roteador | Colunas: Camada, Inteligência, Onde usa.`
3.  `Me dê um troubleshooting guiado: "Site não abre". Me faça perguntas para descobrir se é falha de DNS, IP ou Roteador.`

---
Desenvolvido por [nikolaspeixoto188-png] com auxílio de NotebookLM e IA Generativa.
