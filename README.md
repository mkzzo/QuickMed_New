# 🏥 Quickmed — Sistema Hospitalar Integrado de Triagem & Chamadas

Plataforma modular para automação de atendimento hospitalar baseada no **Protocolo de Manchester**. O projeto integra totem de senhas, triagem clínica com coleta de sinais vitais, painel de chamada audiovisual para recepção e controle de consultório médico.

---

## 🚀 O que há de novo? (Atualização do Projeto)

Este projeto nasceu originalmente como um protótipo acadêmico em **Linguagem C**, operando exclusivamente via **terminal CLI** com estruturas de dados em memória (filas circulares e listas encadeadas). 

Após um período de congelamento, o projeto foi totalmente reestruturado e modernizado:

* **Desacoplamento do Terminal:** A lógica pura de regras de fila, cálculo de espera e cascata de prioridades foi extraída do console e transformada em módulos reativos.
* **Interface Visual Moderna (Stitch UI + Tailwind CSS):** Substituição de menus textuais por telas responsivas e táteis, seguindo design clínico limpo e acessível (WCAG AA).
* **Expansão do Protocolo de Manchester (5 Níveis):** Evolução da triagem simples de 3 níveis para os 5 níveis clínicos canônicos (Emergência, Muito Urgente, Urgente, Pouco Urgente e Não Urgente).
* **Sincronização em Tempo Real Sem Servidor:** Implementação de barramento de eventos via `LocalStorage` e `StorageEvent`, permitindo comunicação instantânea entre diferentes abas, tablets e telões sem dependência de backend pago.
* **Sonoplastia Hospitalar:** Inclusão de sintetizador de áudio nativo (Web Audio API) para emissão automática do alerta sonoro de chamada (*ding-dong*) no telão.

---

## 🧩 Módulos do Sistema

| Módulo | Caminho | Descrição |
| :--- | :--- | :--- |
| **Portal Central** | `index.html` | Ponto de entrada com acesso rápido a todas as estações de trabalho. |
| **Painel TV** | `Painel_Chamadas/painelDeChamadas.html` | Exibição pública em tempo real, convocação visual monumental, sinal sonoro e histórico de atendimentos. |
| **Triagem Manchester** | `Triagem_Enfermeiro/autoAtendimentoEnf.html` | Estação de enfermagem para aferição de sinais vitais (PA, FC, Temp, EVA) e classificação por cores de risco. |
| **Totem de Entrada** | `Totem_AutoAtendimento/autoAtendimento.html` | Terminal touch para retirada de senhas gerais, preferenciais (Lei 14.624) e botão de socorro imediato. |
| **Médico (Desktop)** | `Visao_Medico/povDoutor.html` | Painel de consultório com fila clínica completa e prontuário da triagem. |
| **Médico (Mobile)** | `Visao_Medico_Mobile/povDoutorMobile.html` | Versão compacta para smartphone do médico plantonista com chamada e rechamada em um toque. |
| **Acompanhamento** | `Acompanhamento_Paciente/acompanhamentoPaciente.html` | Interface móvel para o paciente acompanhar a fila remotamente. |

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 & Vanilla JavaScript:** Lógica de negócio, sincronização entre janelas e manipulação de estado.
* **Tailwind CSS:** Estilização utilitária moderna e responsiva.
* **Web Audio API:** Geração de harmônicos sonoros para notificações hospitalares.
* **Linguagem C (Legado / Motor):** Estruturas de dados originais (filas de prioridade e listas ligadas de histórico).

---

## 💻 Como Rodar Localmente

1. Clone o repositório:
   ```bash
   git clone [https://github.com/SEU_USUARIO/quickmed-display.git](https://github.com/SEU_USUARIO/quickmed-display.git)
2. Acesse a pasta do projeto:
```bash
cd quickmed-display
```

3. Abra o arquivo `index.html` diretamente em seu navegador (ou utilize extensões como o **Live Server** do VS Code).

4. Abra o **Painel TV**, o **Totem** e a tela do **Médico** em abas separadas para testar a comunicação em tempo real.

---

## 🌐 Deploy

Este repositório está estruturado para deploy contínuo gratuito no **GitHub Pages** ou na **Vercel** com suporte nativo a HTTPS.
