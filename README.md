# 🖥️ DtOS (Delta Operating System)

> *“O frio conserva. O frio protege. O frio é eterno.” — Protocolo ColdWall*

O **DtOS (v16.2)** é a interface de terminal legado da **Delta Corporation**. Desenvolvido como uma aplicação web de página única (Single-Page Application), ele simula um sistema operacional corporativo e militar imersivo, focado na gestão de ativos, recrutamento e banco de dados confidencial.

Construído com uma estética retrô-futurista (CRT scanlines, paleta cyan/âmbar e elementos minimalistas), o DtOS não é apenas uma interface, mas uma porta de entrada para a infraestrutura e os segredos da Delta.

---

## 🚀 Principais Funcionalidades

O sistema conta com diversos módulos integrados para a gestão completa das operações da Delta:

* 🔒 **Boot & Autenticação:** Sequência de inicialização imersiva com verificação de credenciais e efeitos de terminal clássico.
* 🎵 **Motor de Áudio Procedural:** Trilha sonora ambiente (*Drone/Pad*) e efeitos sonoros gerados dinamicamente via Web Audio API.
* 🛡️ **DSS (Security Contracts):** Geração e gestão de contratos temporários de segurança, controle de efetivo e monitoramento de status de combate (ACT, WIA, KIA, MIA).
* ⚔️ **DFF (Delta Fox Force):** Centro de recrutamento em massa ou manual, registro de IDs (HASH) permanentes e alocação estratégica de pelotões táticos.
* 🗄️ **Delta Files (Arquivo Central):** Banco de dados classificado contendo a documentação técnica, *lore* e anomalias da corporação (incluindo relatórios sobre *Spectrolita*, *Hemo-S* e *Nexus-T*).
* 🛠️ **Ferramentas de Produtividade:**
    * **DMail:** Sistema de comunicação por e-mail criptografado.
    * **Delta Comm:** Chat interno para comunicação segura entre agentes e esquadrões.
    * **Utilitários:** Calculadora Científica, Calendário de Eventos, Gerenciador de Lembretes e Bloco de Anotações integrado.

---

## 💻 Especificações Técnicas

O projeto foi desenvolvido de forma *Vanilla*, sem dependências externas pesadas, garantindo execução leve e imediata no navegador.

* **Markup & Estilização:** HTML5 e CSS3 (Animações nativas, variáveis CSS, CSS Grid/Flexbox e filtros de sombra para simular brilho/CRT).
* **Lógica do Sistema:** JavaScript puro (ES6) manipulando o estado do DOM e a navegação entre os painéis (módulos).
* **Áudio:** Implementação nativa da `Web Audio API` para osciladores, filtros biquadrados e controle de ganho dinâmico.
* **Tipografia:** Fontes importadas do Google Fonts (`Share Tech Mono` para dados e `VT323` para títulos).
