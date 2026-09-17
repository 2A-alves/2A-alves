<div align="center">

# André Alves

### Engenharia de Controle e Automação — UFPE

**Automação + Software + Dados + Decisão**

Controle industrial (CLP/SCADA), software full-stack e IA aplicada — construído para
resolver problemas reais em máquinas reais, não só no papel.

[![Email](https://img.shields.io/badge/Email-andre.alves2aandrade%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:andre.alves2aandrade@gmail.com)

</div>

---

## Sobre

Trabalho em toda a cadeia de um sistema automatizado: a lógica de CLP e o cabeamento
de campo no chão de fábrica, o SCADA/HMI e os serviços de back-end que conversam com
ele, e o software — às vezes com apoio de IA — que transforma esses dados em algo que
uma pessoa possa usar para agir.

A maioria dos projetos abaixo nasceu de problemas reais, industriais ou de negócio: uma
máquina que precisava de um sistema de controle, um cliente que precisava monitorar seu
processo, uma equipe que precisava de uma ferramenta que ainda não existia. Alguns são
projetos pessoais, feitos sozinho, do início ao fim.

Todo repositório aqui foi revisado e higienizado para publicação — dados reais de
clientes, credenciais e informações pessoais de terceiros foram removidos ou
substituídos por placeholders antes da publicação. Quando um repositório documenta um
trabalho feito em equipe (frequentemente o caso em projetos de Empresa Júnior/acadêmicos,
onde o histórico do Git nem sempre reflete quem fez o quê), isso é declarado com clareza
no próprio README do repositório, sem disfarces.

## Áreas de foco

- 🏭 **Automação industrial** — programação de CLP (Rockwell Studio 5000 / Structured
  Text, Siemens S7), SCADA/HMI (Elipse E3, FactoryTalk View), integração EtherNet/IP
- 🪞 **Gêmeos digitais e simulação** — sincronização 3D em tempo real com CLPs físicos,
  frameworks de simulação de processos industriais em Python
- 🔌 **Embarcados e IoT** — ESP32/MicroPython, BLE, RFID/NFC, integração de hardware via
  GPIO/I2C/serial
- 🌐 **Back-end e full-stack** — APIs REST (Node.js/Express), frontends React, apps
  desktop com Electron, Android (Kotlin + Compose)
- 🤖 **IA aplicada** — orquestração de múltiplos provedores de LLM, automação de fluxos
  de trabalho com apoio de IA
- 📊 **Dados e relatórios** — geração automatizada de relatórios/documentos, detecção de
  anomalias, dashboards de apoio à decisão

## Projetos em destaque

| | |
|---|---|
| **[ascendos-personal-assistant](https://github.com/2A-alves/ascendos-personal-assistant)** | Assistente pessoal Android (Kotlin + Jetpack Compose) com back-end multi-provedor de LLM (Gemini/Groq/Cerebras/Mistral/OpenRouter). Projeto solo, arquitetura multi-módulo completa. |
| **[factory-simulation-library](https://github.com/2A-alves/factory-simulation-library)** | Framework Python para simulação de processos industriais, com modelo físico de separador trifásico, 134 testes automatizados e integração real com CLP. Projeto solo. |
| **[industrial-digital-twin](https://github.com/2A-alves/industrial-digital-twin)** | Gêmeo digital em Unity 3D sincronizado em tempo real com um CLP físico via EtherNet/IP (`libplctag`). |
| **[rockwell-plc-unwinder-control](https://github.com/2A-alves/rockwell-plc-unwinder-control)** | Projeto completo em Rockwell Studio 5000 + FactoryTalk View para uma desbobinadeira de fibra real — lógica de controle, HMI e sistema de receitas completos, publicado na íntegra com autorização do cliente original. |
| **[warehouse-rfid-locker-system](https://github.com/2A-alves/warehouse-rfid-locker-system)** | Sistema de armários inteligentes com RFID UHF / NFC: integração de hardware embarcado, API REST, frontend React. |

## Todos os projetos

### Automação industrial, CLP e SCADA

| Projeto | Descrição |
|---|---|
| [industrial-digital-twin](https://github.com/2A-alves/industrial-digital-twin) | Gêmeo digital em Unity 3D sincronizado com um CLP físico via EtherNet/IP |
| [factory-simulation-library](https://github.com/2A-alves/factory-simulation-library) | Framework de simulação de processos industriais em Python, com integração real de CLP |
| [rockwell-plc-unwinder-control](https://github.com/2A-alves/rockwell-plc-unwinder-control) | Projeto de controle em Rockwell Studio 5000 + FactoryTalk View para uma desbobinadeira de fibra |
| [s7-ethernet-plc-driver](https://github.com/2A-alves/s7-ethernet-plc-driver) | Driver C#/.NET para CLPs Siemens S7 via EtherNet/IP |
| [coil-winding-recipe-manager](https://github.com/2A-alves/coil-winding-recipe-manager) | Editor/enviador de receitas para o CLP Rockwell de uma bobinadeira |
| [hipervisorio-case-study](https://github.com/2A-alves/hipervisorio-case-study) | Estudo de caso de SCADA (Elipse E3): sistema supervisório de microrrede de recarga de veículos elétricos |

### Embarcados, IoT e integração de hardware

| Projeto | Descrição |
|---|---|
| [warehouse-rfid-locker-system](https://github.com/2A-alves/warehouse-rfid-locker-system) | Sistema de armários inteligentes com RFID UHF / NFC: hardware, API REST, frontend React |
| [esp32-ble-indoor-positioning](https://github.com/2A-alves/esp32-ble-indoor-positioning) | Posicionamento indoor via âncoras BLE-RSSI em ESP32 + serviço de trilateração em Python |
| [smart-coffee-station](https://github.com/2A-alves/smart-coffee-station) | Automação de máquina de café self-service: firmware ESP32, back-end Node.js, frontend React |
| [smart-home-automation](https://github.com/2A-alves/smart-home-automation) | Automação residencial: back-end Node.js + controlador de dispositivos ESP32 |

### IA aplicada

| Projeto | Descrição |
|---|---|
| [ascendos-personal-assistant](https://github.com/2A-alves/ascendos-personal-assistant) | Assistente Android (Kotlin + Compose) com back-end multi-provedor de LLM |
| [jarvis-media-pipeline](https://github.com/2A-alves/jarvis-media-pipeline) | Automação de edição de vídeo com apoio de IA: indexação, geração de plano de corte, exportação para o Premiere Pro |

### Aplicações de negócio, ERP e relatórios

| Projeto | Descrição |
|---|---|
| [avante-erp-platform](https://github.com/2A-alves/avante-erp-platform) | Estudo de caso: ERP em produção com controle de acesso, streaming de câmeras RTSP, fluxos com apoio de IA |
| [trade-erp-desktop](https://github.com/2A-alves/trade-erp-desktop) | ERP desktop em Electron + React: clientes, fornecedores, contratos, faturamento |
| [pos-consultation-mobile-app](https://github.com/2A-alves/pos-consultation-mobile-app) | App React Native / Expo: consulta de produto por QR code + geração de orçamento/proforma |
| [asset-tracking-system](https://github.com/2A-alves/asset-tracking-system) | Demo full-stack de checkout/rastreamento de ativos |
| [power-monitoring-report-generator](https://github.com/2A-alves/power-monitoring-report-generator) | Pipeline Python/pandas para monitoramento de energia elétrica: detecção de anomalias, gráficos, relatórios em LaTeX |
| [proforma-pdf-generator](https://github.com/2A-alves/proforma-pdf-generator) | Biblioteca Node.js para geração de documentos PDF de proforma/pedido |

### Utilitários

| Projeto | Descrição |
|---|---|
| [engineering-labs](https://github.com/2A-alves/engineering-labs) | Coleção de pequenos utilitários de engenharia: diário de equipe, dashboards, geradores de etiquetas QR |

## Tecnologias

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-100000?style=flat-square&logo=unity&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Rockwell Automation](https://img.shields.io/badge/Rockwell-Studio%205000-CC0000?style=flat-square)
![Siemens S7](https://img.shields.io/badge/Siemens-S7-009999?style=flat-square)
![Elipse E3](https://img.shields.io/badge/Elipse-E3-005A9C?style=flat-square)

## Contato

📧 [andre.alves2aandrade@gmail.com](mailto:andre.alves2aandrade@gmail.com)
