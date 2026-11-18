# 🧬 Receita para recriar: Maikon Caldeira — Aplicativos

_Gerada sem IA, lendo 534 arquivo(s). Serve para remontar este app como HTML modular — com qualquer IA, um arquivo por vez._

## 1. O que é

- **Nome:** Maikon Caldeira — Aplicativos
- **Partes de código:** 503 (491 tela, 1 logica, 11 servidor, 0 dados, 0 estilo)
- **Tem servidor (rotas /api):** sim — veja o passo do servidor
- **Peças de fora (bibliotecas):**  + JSON.stringify(principal) + ,  + q + u + q + , ${comp.file}, ${mod}, @capacitor/cli, @expo/vector-icons, @neondatabase/serverless, @replit/vite-plugin-cartographer, @replit/vite-plugin-dev-banner, @replit/vite-plugin-runtime-error-modal, @shared/schema, @supabase/supabase-js, @tailwindcss/vite, @tanstack/react-query, @vitejs/plugin-react, @workspace/db, @workspace/sync-storage, axios, better-sqlite3, blob:https:, child_process, cors, crypto, dotenv, electron, electron-is-dev, esbuild, esbuild-plugin-pino, expo, expo-clipboard…

## 2. Estrutura modular proposta

```
index.html            ← a página; chama os módulos NA ORDEM
css/app.css           ← o visual
js/00-core.js         ← a "locomotiva": cria window.APP (registrar, guardar, avisar)
js/10-abrir.js        ← -*- coding: utf-8 -*- (era exe/abrir.py)
js/15-112.js          ← Raio-X de Projetos — Raio-X de Projetos (era 112.html)
js/20-122.js          ← 🔗 Teste APK + Termux — 🔗 Teste APK ↔ Termux (era 122.html)
js/25-211.js          ← Análise: snippets.ts — 🔬 snippets.ts (era 211.html)
js/30-266.js          ← Multi-Projetos PWA — Maikon Caldeira (era 266.html)
js/35-278.js          ← Análise: workspace.ts — 🔬 workspace.ts (era 278.html)
js/40-333.js          ← Análise: AIChat.tsx — 🔬 AIChat.tsx (era 333.html)
js/45-377.js          ← Painel Maikon Caldeira — Advocacia Digital — 🔧 PWA Analyzer - Detecto (era 377.html)
js/50-392.js          ← Análise: AIChat.tsx — 🔬 AIChat.tsx (era 392.html)
js/55-413.js          ← Blocos de assets/app (cópia).js — ✂️ assets/app (cópia).js — 1 blocos (era 413.html)
js/60-477.js          ← Markdown — Pacote do projeto &quot;artifacts6&quot; para a IA (era 477.html)
js/65-76.js           ← PLANO_RECUPERACAO.md — PLANO_RECUPERACAO.md (era 76.html)
js/70-1.js            ← Arrumador de Backups — 🗃 Arrumador de Backups (era 1.html)
js/75-10.js           ← Meu Projeto — Meu Projeto (era 10.html)
js/80-100.js          ← ⚙️ Replit Config Manager — ⚙️ Replit Config Manager (era 100.html)
js/85-101.js          ← 🧹 Project Cleaner — 🧹 Project Cleaner + Generator (era 101.html)
js/90-102.js          ← Iara Mapper Pro - Final — 🚀 Iara Mapper Pro (era 102.html)
js/91-103.js          ← SK-Code Editor Functions Explained (era 103.html)
js/92-104.js          ← SK-Details & Summary — Expandir/Colapsar (era 104.html)
js/93-105.js          ← SK-Iara Suite Checker (era 105.html)
js/94-106.js          ← Editor com Busca - Dr. Maikon (era 106.html)
js/95-107.js          ← Iara Mapper Pro (era 107.html)
js/96-108.js          ← Analisador de Projetos — 🔍 Analisador (era 108.html)
js/97-109.js          ← Visualizador de Markdown — Visualizador de Markdown (era 109.html)
js/98-11.js           ← Validador de Código + Testador de API — 🧪 Validador de Código + Testa (era 11.html)
js/98-110.js          ← Iara 2.0 - Mapeador Profissional de Dependências — 🕸️ Iara 2.0 — Mape (era 110.html)
js/98-111.js          ← 🧹 Limpador de Replit — 🧹 Limpador de Vínculos Replit (era 111.html)
js/98-113.js          ← Gerador de Ícones PRO - Maikon Caldeira — 🎨 Gerador de Ícones PRO (era 113.html)
js/98-114.js          ← PWA Jurídico — Maikon Caldeira — Filtrador Jurídico Avançado (Atualiza (era 114.html)
js/98-115.js          ← Teste Diff (Estático) (era 115.html)
js/98-116.js          ← Diff Simple Test (era 116.html)
js/98-117.js          ← projeto (era 117.html)
js/98-118.js          ← Analisador e Reparador PWA -> APK — 🛠️ Reparador PWA para APK (era 118.html)
js/98-119.js          ← 🔍 Analisador de Projetos — Analisador de Projetos — Detector de Probl (era 119.html)
js/98-12.js           ← Triagem de Código — Triagem de Código (era 12.html)
js/98-120.js          ← VOXIS — Assistente Pessoal — 🎙️ Estúdio de Voz (era 120.html)
js/98-121.js          ← 📱 Gerador EAS Build — 📱 Gerador de Configuração EAS Build (era 121.html)
js/98-123.js          ← Analisador de Logs GitHub Actions — 🔍 Analisador de Logs GitHub Actio (era 123.html)
js/98-124.js          ← Replicador de Projeto — ⚡ Replicador de Projeto (era 124.html)
js/98-125.js          ← Editor Visual — 🐝 Editor Visual (era 125.html)
js/98-126.js          ← 🐝 Editor Visual - Responsivo — 🐝 Editor Visual (era 126.html)
js/98-127.js          ← Editor Visual HTML - Tipo Firebug Simples — 🐝 Editor Visual HTML (era 127.html)
js/98-128.js          ← SK-Code Analyzer — Mapear Dependências (era 128.html)
js/98-129.js          ← SK-Code Formatter — Organize seu Código (era 129.html)
js/98-13.js           ← Teste — Teste (era 13.html)
js/98-130.js          ← Perito de Metadados — Perito de Metadados (era 130.html)
js/98-131.js          ← Multi-Projetos PWA — Maikon Caldeira (era 131.html)
js/98-132.js          ← Multi-Projetos PWA — Maikon Caldeira (era 132.html)
js/98-133.js          ← Multi-Projetos PWA — Maikon Caldeira (era 133.html)
js/98-134.js          ← Multi-Projetos PWA — Maikon Caldeira (era 134.html)
js/98-135.js          ← 📱 APK Builder - EAS — 📱 APK Builder - EAS (era 135.html)
js/98-136.js          ← 🚀 Setup Dashboard - Monorepo — 🚀 Setup Dashboard (era 136.html)
js/98-137.js          ← 🛠️ Workstation Completa — Maikon Caldeira (era 137.html)
js/98-138.js          ← modulo 2 — Meu PWA Jurídico (era 138.html)
js/98-139.js          ← IARA Suite — Importador & Editor Completo (era 139.html)
js/98-14.js           ← SK Mini Editor — SK Mini Editor (era 14.html)
js/98-140.js          ← Comparar Código (era 140.html)
js/98-141.js          ← SK-Docs Hub PT — Documentação em Português — Título (era 141.html)
js/98-142.js          ← Code Debugger — Dr. Maikon Caldeira (era 142.html)
js/98-143.js          ← Iara Mapper Pro — Dr. Maikon Caldeira (era 143.html)
js/98-144.js          ← Meu Projeto PWA — 🔍 Leitor de Projeto PRO (era 144.html)
js/98-145.js          ← manual-dev (1) — Manual para Desenvolvedores — Correções Necessárias n (era 145.html)
js/98-146.js          ← Auditoria Financeira - Assistente Jurídico — 📊 Auditoria Financeira (era 146.html)
js/98-147.js          ← HTML Playground - Editor de Codigo ao Vivo (era 147.html)
js/98-148.js          ← Auditoria Master - Dr. MAIKON DA ROCHA CALDEIRA — ⚖️ Auditoria Pericia (era 148.html)
js/98-149.js          ← Limpador de Processos — Limpador de Processos (era 149.html)
js/98-15.js           ← SK Mini Editor - Guia de Instalação Interativo — SK Mini Editor (era 15.html)
js/98-150.js          ← Painel Maikon Caldeira - Advogado — Maikon Caldeira (era 150.html)
js/98-151.js          ← Iara Suite v2.0 - Editor + Mapper Avançado — 🚀 Iara Suite v2.0 (era 151.html)
js/98-152.js          ← ⚖️ Robô Jurídico — ⚖️ Robô Jurídico (era 152.html)
js/98-153.js          ← Iara Suite v3.0 - Importador Universal — 🚀 Iara Suite v3.0 - Importad (era 153.html)
js/98-154.js          ← Gerador de Plano de Projeto — 📊 Gerador de Plano de Projeto (era 154.html)
js/98-155.js          ← Gerador de Ícones PWA - Maikon Caldeira — 🎨 Gerador de Ícones PWA (era 155.html)
js/98-156.js          ← 📱 Gerador EAS Build — 📱 Gerador de Configuração EAS Build (era 156.html)
js/98-157.js          ← Gerador de Documentação Automática — 📚 Gerador de Documentação Automá (era 157.html)
js/98-158.js          ← Extrator de Sites — 🛠️ Extrator de Sites (era 158.html)
js/98-159.js          ← SK-Combinar Apps — Unir Projetos (era 159.html)
js/98-16.js           ← SK Code Editor - GitHub Integration — SK Code Editor (era 16.html)
js/98-160.js          ← 🔧 ConstruAPK Pro — Analisador e Gerador — ConstruAPK Pro — Analisador (era 160.html)
js/98-161.js          ← 🎨 Playground + ⚖️ Assistente Jurídico - Maikon (era 161.html)
js/98-162.js          ← Juntador de Arquivos — 🧩 Juntador de Arquivos (era 162.html)
js/98-163.js          ← Maikon Caldeira — Aplicativos — MAIKON CALDEIRA (era 163.html)
js/98-164.js          ← AI Code Studio — 🤖 AI Code Studio (era 164.html)
js/98-165.js          ← 🚀 Setup Dashboard — 🚀 Setup Dashboard (era 165.html)
js/98-166.js          ← Gerador de Relatório + Extrator de Arquivos — 📋 Gerador de Relatório  (era 166.html)
js/98-167.js          ← Filtrador Jurídico Avançado (Atualizado) — Filtrador Jurídico Avançado (era 167.html)
js/98-168.js          ← SK-Chat — Painel de Regras (era 168.html)
js/98-169.js          ← SK-Master — Editor + Chat + Prompt Generator (era 169.html)
js/98-17.js           ← SK Mini Editor - Completo — SK Mini Editor (era 17.html)
js/98-170.js          ← SK-Code Analyzer v2 (era 170.html)
js/98-171.js          ← Peça (era 171.html)
js/98-172.js          ← CirurgiÃ£o de CÃ³digo 4.4 — ðŸ©º CirurgiÃ£o 4.4 (era 172.html)
js/98-173.js          ← Cirurgião de Código 4.3 — 🩺 Cirurgião 4.3 (era 173.html)
js/98-174.js          ← Juntador de Arquivos — 🧩 Juntador de Arquivos (era 174.html)
js/98-175.js          ← Maikon Caldeira - Advocacia Digital — Maikon Caldeira (era 175.html)
js/98-176.js          ← SK Editor v3 (era 176.html)
js/98-177.js          ← Conversor TJMG (Fator) → competencia/correcao_pct — Conversor TJMG (fa (era 177.html)
js/98-178.js          ← Iara Suite — ⚡ Iara Suite (era 178.html)
js/98-179.js          ← 🚀 Gerenciador PWA - Maikon Caldeira — 🚀 Gerenciador PWA Completo (era 179.html)
js/98-18.js           ← teste 2 onde txt 6 index (era 18.html)
js/98-180.js          ← Playground TSX - Maikon Caldeira — 🎨 Playground TSX/React (era 180.html)
js/98-181.js          ← 📱 Gerador DevMobile EAS — 📱 Gerador EAS Build — Baseado no DevMobile (era 181.html)
js/98-182.js          ← Extrator de Sites — 🛠️ Extrator de Sites (era 182.html)
js/98-183.js          ← Extrator Jurídico — Maikon Caldeira OAB/MG 183712 (era 183.html)
js/98-184.js          ← Iara Mapper — Dr. Maikon Caldeira (era 184.html)
js/98-185.js          ← SK-CSS/HTML Interactive Guide (era 185.html)
js/98-186.js          ← Demonstrativo de cálculo (era 186.html)
js/98-187.js          ← Corretor Automático Inteligente — 🔧 Corretor Automático Inteligente (era 187.html)
js/98-188.js          ← Comunicações Processuais — ⚖️ Comunicações Processuais (era 188.html)
js/98-189.js          ← Multi-Projetos PWA — Maikon Caldeira (era 189.html)
js/98-19.js           ← Playground Pro — Bem-vindo ao Playground Pro! 🚀 (era 19.html)
js/98-190.js          ← Consulta por OAB — Buscar por OAB (era 190.html)
js/98-191.js          ← lib pdf template (era 191.html)
js/98-192.js          ← indice_legal-assistant.tsx (2).md — indice_legal-assistant.tsx (2).md (era 192.html)
js/98-193.js          ← Meus Projetos (era 193.html)
js/98-194.js          ← Construtor Automático PWA - Maikon Caldeira — 🚀 Construtor Automático (era 194.html)
js/98-195.js          ← SK-Chat — Regras + Tokens (era 195.html)
js/98-196.js          ← Cirurgião de Código 4.0 — 🔬 CIRURGIÃO DE CÓDIGO 4.0 (era 196.html)
js/98-197.js          ← Cirurgião de Código 2.0 — 🔬 CIRURGIÃO DE CÓDIGO 2.0 (era 197.html)
js/98-198.js          ← Cirurgião de Código 4.4 — 🩺 Cirurgião 4.4 (era 198.html)
js/98-199.js          ← Cirurgião de Código 4.2 — 🩺 Cirurgião 4.2 (era 199.html)
js/98-2.js            ← Diagnóstico + Correção de Executáveis — 🔧 Diagnóstico + Correção de E (era 2.html)
js/98-20.js           ← 🚀 SK Mini Editor - Gerador de Arquivos — 🚀 SK Mini Editor (era 20.html)
js/98-200.js          ← Cirurgião de Código 4.1 — 🩺 Cirurgião 4.1 (era 200.html)
js/98-201.js          ← Chat IA Pro — Saulo — Chat IA Pro (era 201.html)
js/98-202.js          ← Chat — 💬 Chat (era 202.html)
js/98-203.js          ← Calculadora de Sentença — Calculadora de Sentença (era 203.html)
js/98-204.js          ← Calculadora de Sentença — Calculadora de Sentença (era 204.html)
js/98-205.js          ← Calculadora de Sentença — Calculadora de Sentença (era 205.html)
js/98-206.js          ← arquivo 2 (era 206.html)
js/98-207.js          ← Comparador Jurídico Completo — TJMG (Fator) + BCB (Juros) — Multi-Cená (era 207.html)
js/98-208.js          ← Chat IA Pro — Chat IA Pro (era 208.html)
js/98-209.js          ← Calculadora de Sentença — Calculadora de Sentença (era 209.html)
js/98-21.js           ← 🚀 SK Mini Editor - Setup Interativo — 🚀 SK Mini Editor - Setup Inter (era 21.html)
js/98-210.js          ← SK Oficina Jurídica v6 - Integrada — SK Oficina Jurídica v6 (era 210.html)
js/98-212.js          ← analise_Manual.tsx.html — analise_Manual.tsx.html (era 212.html)
js/98-213.js          ← Análise: keys.tsx — 🔬 keys.tsx (era 213.html)
js/98-214.js          ← Análise: export.tsx — 🔬 export.tsx (era 214.html)
js/98-215.js          ← Análise: EditorLayout.tsx — 🔬 EditorLayout.tsx (era 215.html)
js/98-216.js          ← analise_EditorLayout.tsx (1).md — analise_EditorLayout.tsx (1).md (era 216.html)
js/98-217.js          ← Análise: desktop.ts — 🔬 desktop.ts (era 217.html)
js/98-218.js          ← Análise: android.ts — 🔬 android.ts (era 218.html)
js/98-219.js          ← AI Code Studio — 🤖 AI Code Studio (era 219.html)
js/98-22.js           ← SK Mini Editor - TESTE — SK Mini Editor - TESTE (era 22.html)
js/98-220.js          ← Sem titulo — Bem-vindo ao HTML Playground (era 220.html)
js/98-221.js          ← Diagnóstico crise (era 221.html)
js/98-222.js          ← Calculadora Jurídica Monica — Importador Direto (era 222.html)
js/98-223.js          ← Comparador Jurídico Completo (Com Busca BCB) — Comparador Jurídico (BC (era 223.html)
js/98-224.js          ← Resumidor Jurídico Estruturado v2.0 — EMBARGOS DE DECLARAÇÃO (era 224.html)
js/98-225.js          ← Gerador de Petição: Vinculação e Enquadramento - Caso Adjair — ⚖️ Gera (era 225.html)
js/98-226.js          ← Siscajur - Perícia Bancária & Sentença (Capitalização Anual) (era 226.html)
js/98-227.js          ← Extrator Replit — Maikon — 🗂 Extrator de Projetos Replit (era 227.html)
js/98-228.js          ← Comparador JurÃ­dico â TJMG + BCB — Comparador Juridico â TJMG (Fa (era 228.html)
js/98-229.js          ← Extrator de Texto Pro — 📄 Extrator de Texto Pro (era 229.html)
js/98-23.js           ← SK Mini Editor - Editor de Código Online — SK Mini Editor (era 23.html)
js/98-230.js          ← Gerador de Peças Processuais — TRF6 (era 230.html)
js/98-231.js          ← Calculadora Judicial (TJMG + BCB + Capitalização Anual) — Calculadora  (era 231.html)
js/98-232.js          ← Analisador de Histórico — ZIP/TAR/TAZ — 📦 Analisador de Histórico — Z (era 232.html)
js/98-233.js          ← Gerador Jurídico Pro (PDF/DOCX + Dedup Inteligente) — EMBARGOS DE DECL (era 233.html)
js/98-234.js          ← Maikon Caldeira - Reconhecimentos Pretéritos (era 234.html)
js/98-235.js          ← Comparador Jurídico - Índices TJMG + BCB — Comparador Jurídico - Índic (era 235.html)
js/98-236.js          ← 📋 Gerador de Plano de Projeto — 📋 Gerador de Plano de Projeto (era 236.html)
js/98-237.js          ← SK Database Manager + IA (era 237.html)
js/98-238.js          ← Análise: Terminal.tsx — 🔬 Terminal.tsx (era 238.html)
js/98-239.js          ← Análise: settings.tsx — 🔬 settings.tsx (era 239.html)
js/98-24.js           ← SK Oficina de Busca, Extração & Exportação v7 (era 24.html)
js/98-240.js          ← Análise: Manual.tsx — 🔬 Manual.tsx (era 240.html)
js/98-241.js          ← Análise: legal-assistant.tsx — 🔬 legal-assistant.tsx (era 241.html)
js/98-242.js          ← analise_export.tsx.md — analise_export.tsx.md (era 242.html)
js/98-243.js          ← analise_desktop.ts (1).md — analise_desktop.ts (1).md (era 243.html)
js/98-244.js          ← Análise: DeployPanel.tsx — 🔬 DeployPanel.tsx (era 244.html)
js/98-245.js          ← Alquimia v.14 (era 245.html)
js/98-246.js          ← Extrator de Dados Jurídicos (era 246.html)
js/98-247.js          ← 🚨 RECURSO URGENTE - FUNCIONA — 📋 FERRAMENTAS JURÍDICAS - URGENTE (era 247.html)
js/98-248.js          ← 🚨 MEU RECURSO PREVIDÊNCIA - FUNCIONA — ⚖️ RECURSO PREVIDÊNCIA - 7 DIA (era 248.html)
js/98-249.js          ← Gerador de Cotejo Analítico (era 249.html)
js/98-25.js           ← SK Rastreador de Rotas & IA v6 - Maikon Caldeira (era 25.html)
js/98-250.js          ← Extrator BPC Netflix — 🎬 PLATAFORMA BPC TRF6 (era 250.html)
js/98-251.js          ← Maikon Caldeira - Advocacia — MAIKON CALDEIRA (era 251.html)
js/98-252.js          ← Extrair Texto com Filtros (era 252.html)
js/98-253.js          ← Parecer de Liquidação Judicial - Dr. Braulino (era 253.html)
js/98-254.js          ← Calculadora Judicial Completa — Calculadora Judicial Avançada (era 254.html)
js/98-255.js          ← 🚀 Gerenciador PWA - Maikon Caldeira — 🚀 Gerenciador PWA Completo (era 255.html)
js/98-256.js          ← Exported HTML — Extrator Universal de Variáveis (era 256.html)
js/98-257.js          ← Gerador de Peças Jurídicas - TRF6/JEF (era 257.html)
js/98-258.js          ← Calculadora Judicial Manhumirim - Proveito Econômico — Calculadora Jud (era 258.html)
js/98-259.js          ← Painel Consolidado – Petições, Tabelas e CTC — Painel Consolidado – Pe (era 259.html)
js/98-26.js           ← SK-Mini Playground (era 26.html)
js/98-260.js          ← Filtro Jurídico - Redução Real de Duplicatas — EMBARGOS DE DECLARAÇÃO (era 260.html)
js/98-261.js          ← PWA Scanner Multi-Formato + IA — 🔎 Scanner Multi-Formato + IA Jurídic (era 261.html)
js/98-262.js          ← Filtrador Jurídico Master — Maikon Caldeira — ⚖️ Filtrador Jurídico Ma (era 262.html)
js/98-263.js          ← Scanner — Detector de Dependências Replit — 🔍 Scanner de Dependências (era 263.html)
js/98-264.js          ← Manual SK Editor 4 — Completo — SK Editor 4 — Manual Completo (era 264.html)
js/98-265.js          ← Multi-Projetos PWA — Maikon Caldeira (era 265.html)
js/98-267.js          ← Filtrador Jurídico Avançado (Anti-repetição) — 🔍 Filtrador Jurídico A (era 267.html)
js/98-268.js          ← Multi-Projetos PWA — Maikon Caldeira (era 268.html)
js/98-269.js          ← MANUAL (2) — Assistente Jurídico IA — Manual Completo (era 269.html)
js/98-27.js           ← SK Oficina Jurídica v4 - Maikon Caldeira (era 27.html)
js/98-270.js          ← PLANO — 📋 Plano do projeto: artifacts teste (era 270.html)
js/98-271.js          ← Multi-Projetos PWA — Maikon Caldeira (era 271.html)
js/98-272.js          ← Cirurgião de Código 3.0 — 🔬 CIRURGIÃO DE CÓDIGO 3.0 (era 272.html)
js/98-273.js          ← Scanner — Detector de Dependências — 🔍 Scanner de Dependências (era 273.html)
js/98-274.js          ← Multi-Projetos PWA — Maikon Caldeira (era 274.html)
js/98-275.js          ← Painel Maikon Caldeira — Advocacia Digital — 📄 Importador de Markdown (era 275.html)
js/98-276.js          ← 3 Ferramentas Completas - Bugs, Versões e APK — 🛠️ 3 Ferramentas Comp (era 276.html)
js/98-277.js          ← Multi-Projetos PWA — Maikon Caldeira (era 277.html)
js/98-279.js          ← Análise: persistFiles.ts — 🔬 persistFiles.ts (era 279.html)
js/98-28.js           ← SK Decodificador & Comparador de Logs v6 (era 28.html)
js/98-280.js          ← analise_Manual.tsx.md — analise_Manual.tsx.md (era 280.html)
js/98-281.js          ← analise_legal-assistant.tsx.md — analise_legal-assistant.tsx.md (era 281.html)
js/98-282.js          ← analise_EditorLayout.tsx.md — analise_EditorLayout.tsx.md (era 282.html)
js/98-283.js          ← Análise: App.tsx — 🔬 App.tsx (era 283.html)
js/98-284.js          ← 200+ Códigos Jurídicos — 📂 200+ Códigos Auto-Listados (era 284.html)
js/98-285.js          ← Gerador PWA - Maikon Caldeira — 🚀 Gerador PWA - Maikon Caldeira (era 285.html)
js/98-286.js          ← Gerador de Arquivo .env - Assistente Jurídico — Gerador de Arquivo .en (era 286.html)
js/98-287.js          ← Calculadora Mike Definitiva (era 287.html)
js/98-288.js          ← Editor de Cotejo Analítico - Proporcionalidade de Danos — Editor de Co (era 288.html)
js/98-289.js          ← Guia de Recuperação e Configuração do Projeto Maikon — Guia de Recuper (era 289.html)
js/98-29.js           ← SK-Code Debugger — Verificar Código (era 29.html)
js/98-290.js          ← nova_ferramenta — Guia de Recuperação e Configuração do Projeto Maikon (era 290.html)
js/98-291.js          ← Auditoria Master - Dr. MAIKON DA ROCHA CALDEIRA — ⚖️ Auditoria Pericia (era 291.html)
js/98-292.js          ← Extrator de Texto Pro (era 292.html)
js/98-293.js          ← Monica Jurídico v7.0 - Comparador de Cenários (Perícia Bancária) (era 293.html)
js/98-294.js          ← A Oficina Digital do Mike da Galera — Oficina Digital:O Futuro do Dire (era 294.html)
js/98-295.js          ← Editor Jurídico Visual Law - Versão Final — Editor Jurídico Visual Law (era 295.html)
js/98-296.js          ← Calculadora Judicial Híbrida (Fixo vs Variável) — Calculadora Judicial (era 296.html)
js/98-297.js          ← Calculadora Pericial: Sentença vs Contrato (Cartão/Taxa Média) (era 297.html)
js/98-298.js          ← Calculadora de Liquidação & Proveito Econômico — Calculadora de Liquid (era 298.html)
js/98-299.js          ← Painel – Flexibilização de Renda — MAIKON DA ROCHA CALDEIRA - OAB/MG 1 (era 299.html)
js/98-3.js            ← Conversor NPM → CDN — 📦 Conversor NPM → CDN (era 3.html)
js/98-30.js           ← Cirurgião de Código 3.0 — 🔬 CIRURGIÃO DE CÓDIGO 3.0 (era 30.html)
js/98-300.js          ← Rastreador de Histórico Replit — PWA Jurídico — 📜 Rastreador de Histó (era 300.html)
js/98-301.js          ← Calculadora Judicial Premium - Mike da Galera (era 301.html)
js/98-302.js          ← Leitor de Projeto — 🔍 Leitor de Projeto (era 302.html)
js/98-303.js          ← MANUAL (3) — SK Jurídico — Manual Completo (era 303.html)
js/98-304.js          ← Filtrador Avançado de Documentos Jurídicos — 🔧 Filtrador de Documento (era 304.html)
js/98-305.js          ← 🔌 Testador de API — Com Proxy em Cascata — 🔌 Testador de API (era 305.html)
js/98-306.js          ← Editor HTML — Olá mundo! (era 306.html)
js/98-307.js          ← 🧩 Montador de Módulos — PWA Jurídico — 🧩 Montador de Módulos PWA JUR (era 307.html)
js/98-308.js          ← guia-completo-apk (2) — 📱 Guia Completo — Como Transformar Qualquer P (era 308.html)
js/98-309.js          ← 🔍 Scanner de Dependências — SK Editor — 🔍 Scanner de Dependências —  (era 309.html)
js/98-31.js           ← Navegador PWA com Proxys (era 31.html)
js/98-310.js          ← Extrator de Vínculos Previdenciários - Análise Processual — Extrator d (era 310.html)
js/98-311.js          ← Calculadora Jurídica - Juros e Correção — ⚖️ Calculadora Jurídica de J (era 311.html)
js/98-312.js          ← Playground Code Pro — Maikon Caldeira — Bem-vindo ao Playground Pro (era 312.html)
js/98-313.js          ← Chat IA — Chat IA (era 313.html)
js/98-314.js          ← Multi-Projetos PWA — Maikon Caldeira (era 314.html)
js/98-315.js          ← Filtrador Jurídico Avançado (Atualizado) — Filtrador Jurídico Avançado (era 315.html)
js/98-316.js          ← Multi-Projetos PWA — Maikon Caldeira (era 316.html)
js/98-317.js          ← Painel Maikon Caldeira — Advocacia Digital — 🔍 Analisador de Versões  (era 317.html)
js/98-318.js          ← RECEITA — 🧬 Receita para recriar: APK Builder (era 318.html)
js/98-319.js          ← Blocos de js/1.html.md.js — ✂️ js/1.html.md.js — 299 blocos (era 319.html)
js/98-32.js           ← Auditoria Financeira — Calculadora Sentença — Auditoria Financeira — C (era 32.html)
js/98-320.js          ← Gerador de APK — EAS Config — Gerador de Config EAS (era 320.html)
js/98-321.js          ← Análise: Terminal.tsx — 🔬 Terminal.tsx (era 321.html)
js/98-322.js          ← Análise: RealTerminal.tsx — 🔬 RealTerminal.tsx (era 322.html)
js/98-323.js          ← Análise: pwa.tsx — 🔬 pwa.tsx (era 323.html)
js/98-324.js          ← Análise: pacote-ia.txt.md — 🔬 pacote-ia.txt.md (era 324.html)
js/98-325.js          ← Análise: pacote-ia.txt.md — 🔬 pacote-ia.txt.md (era 325.html)
js/98-326.js          ← Análise: legal-assistant.tsx.recovered — 🔬 legal-assistant.tsx.recove (era 326.html)
js/98-327.js          ← Análise: keys.tsx — 🔬 keys.tsx (era 327.html)
js/98-328.js          ← Análise: github.tsx — 🔬 github.tsx (era 328.html)
js/98-329.js          ← Análise: EditorLayout.tsx — 🔬 EditorLayout.tsx (era 329.html)
js/98-33.js           ← Assistente Jurídico (era 33.html)
js/98-330.js          ← Análise: DatabasePanel.tsx — 🔬 DatabasePanel.tsx (era 330.html)
js/98-331.js          ← Análise: App.tsx — 🔬 App.tsx (era 331.html)
js/98-332.js          ← Análise: App.tsx — 🔬 App.tsx (era 332.html)
js/98-334.js          ← Cartao de Perfil (era 334.html)
js/98-335.js          ← Importar TJMG (era 335.html)
js/98-336.js          ← Painel Estruturado - Embargos & Cotejo — Painel Estruturado - Embargos (era 336.html)
js/98-337.js          ← Leitor de CNIS - Visual (era 337.html)
js/98-338.js          ← Rural Adjair (era 338.html)
js/98-339.js          ← Calculadora de Honorários & Liquidação (Anual vs Mensal) — Calculadora (era 339.html)
js/98-34.js           ← SK Editor Jurídico v2 - Seu Ambiente — 🔧 SK Editor Jurídico v2 (era 34.html)
js/98-340.js          ← manual-dev — Manual para Desenvolvedores — Correções Necessárias no Ap (era 340.html)
js/98-341.js          ← Sistema de Perícia Judicial Bancária - Dr. Manhumirim — JurisCalc Perí (era 341.html)
js/98-342.js          ← Extrator Jurídico - Contrato Falsificado (INSS/Estelionato) — Extrator (era 342.html)
js/98-343.js          ← Mike Legal AI - Importador Universal (era 343.html)
js/98-344.js          ← Code Merger Pro — Maikon Caldeira (era 344.html)
js/98-345.js          ← 🗄️ Painel de Banco de Dados (era 345.html)
js/98-346.js          ← Maikon Caldeira - Advocacia Digital — Maikon Caldeira (era 346.html)
js/98-347.js          ← ⚡ Iara Suite — Code Editor · APK Builder · Site Extractor — Olá, Mundo (era 347.html)
js/98-348.js          ← Exported HTML — PrevAnalítico Pro (era 348.html)
js/98-349.js          ← ObjectFactory (intercomunicacao 2.2.2 API) (era 349.html)
js/98-35.js           ← Playground Visual - Maikon Caldeira — 💻 Playground Visual - Maikon Ca (era 35.html)
js/98-350.js          ← Painel Maikon Caldeira — Advocacia Digital — 🔍 Analisador Automático  (era 350.html)
js/98-351.js          ← Multi-Projetos PWA — Maikon Caldeira (era 351.html)
js/98-352.js          ← Manual Completo — Extrator Jurídico + APK — Maikon Caldeira OAB/MG 183 (era 352.html)
js/98-353.js          ← Painel Maikon Caldeira — Advocacia Digital — 🚀 Analisador Inteligente (era 353.html)
js/98-354.js          ← Comparador Jurídico Profissional v2.0 — Comparador Jurídico Profission (era 354.html)
js/98-355.js          ← Painel Maikon Caldeira — Advocacia Digital — 🔍 Leitor de Projeto (era 355.html)
js/98-356.js          ← Manual Iara Suite v2.0 — Maikon Caldeira OAB/MG 183712 — IARA SUITE v2 (era 356.html)
js/98-357.js          ← Análise: TerminalTab.tsx — 🔬 TerminalTab.tsx (era 357.html)
js/98-358.js          ← Meus Códigos Jurídicos — 📂 Meus Códigos Jurídicos (era 358.html)
js/98-359.js          ← Conversão TJMG → Padronizado (era 359.html)
js/98-36.js           ← Menu Principal — 🚀 Menu Principal (era 36.html)
js/98-360.js          ← Leitor Visual de CNIS — 📄 Importador Visual de CNIS (era 360.html)
js/98-361.js          ← Extrator Jurídico BPC/LOAS com OCR e Exportação — Extrator Jurídico BP (era 361.html)
js/98-362.js          ← Comparador Jurídico Multi-Cenário (Com Integração BCB) — Comparador Ju (era 362.html)
js/98-363.js          ← 🛠️ Ferramentas Jurídico BPC — ⚖️ Ferramentas BPC/LOAS TRF6 (era 363.html)
js/98-364.js          ← Filtrador de Documentos Jurídicos (era 364.html)
js/98-365.js          ← Laudo de Auditoria - Dr. Braulino (era 365.html)
js/98-366.js          ← Gerador de Cotejo Analítico - Exportável para Word (era 366.html)
js/98-367.js          ← Calculadora de Custos de IA Avançada — Calculadora de Custos de IA Ava (era 367.html)
js/98-368.js          ← PWA Scanner ZIP Jurídico — 🔎 PWA Scanner ZIP Jurídico (era 368.html)
js/98-369.js          ← Calculadora Jurídica Definitiva - Dr. Manhumirim — Calculadora de Liqu (era 369.html)
js/98-37.js           ← Gerador de Ícone (era 37.html)
js/98-370.js          ← 🧩 Montador Multi-Projetos — PWA Jurídico — 🧩 Montador Multi-Projetos (era 370.html)
js/98-371.js          ← Maikon Caldeira - Reconhecimentos Pretéritos (era 371.html)
js/98-372.js          ← Modelo Editável de Peça (TRF6/JEF) — Endereçamento, Qualificação, Fund (era 372.html)
js/98-373.js          ← Comparador Jurídico Completo - TJMG + BCB — Comparador Jurídico Comple (era 373.html)
js/98-374.js          ← Filtro Jurídico Inteligente - Estrutura de Peças — EMBARGOS DE DECLARA (era 374.html)
js/98-375.js          ← Multi-Projetos PWA — Maikon Caldeira (era 375.html)
js/98-376.js          ← Multi-Projetos PWA — Maikon Caldeira (era 376.html)
js/98-378.js          ← Multi-Projetos PWA — Maikon Caldeira (era 378.html)
js/98-379.js          ← Meu Projeto PWA (era 379.html)
js/98-38.js           ← Construtor Automático PWA - Maikon Caldeira — 🚀 Construtor Automático (era 38.html)
js/98-380.js          ← Multi-Projetos PWA — Maikon Caldeira (era 380.html)
js/98-381.js          ← Multi-Projetos PWA — Maikon Caldeira (era 381.html)
js/98-382.js          ← Assistente Jurídico Pro (era 382.html)
js/98-383.js          ← Multi-Projetos PWA — Maikon Caldeira (era 383.html)
js/98-384.js          ← 📖 Gerador de Histórias com Voz — 📖✨ Gerador de Histórias com Sua Voz (era 384.html)
js/98-385.js          ← Gerador de package.json REAL - Só o que Funciona — ✅ Gerador de packag (era 385.html)
js/98-386.js          ← Cirurgião de Código 4.0 — 🩺 Cirurgião 4.0 (era 386.html)
js/98-387.js          ← analise_Terminal.tsx.md — analise_Terminal.tsx.md (era 387.html)
js/98-388.js          ← Análise: legal-assistant.tsx — 🔬 legal-assistant.tsx (era 388.html)
js/98-389.js          ← Análise: desktop.ts — 🔬 desktop.ts (era 389.html)
js/98-39.js           ← Editor de Peças Jurídicas — Estrutura + Preview — Editor de Peças — es (era 39.html)
js/98-390.js          ← Análise: App.tsx — 🔬 App.tsx (era 390.html)
js/98-391.js          ← Análise: ApkAnalyzer.tsx — 🔬 ApkAnalyzer.tsx (era 391.html)
js/98-393.js          ← Comparador de Juros Simples e Compostos — Comparador de Juros Simples  (era 393.html)
js/98-394.js          ← PDJd Token COJEF Centro (era 394.html)
js/98-395.js          ← 🔑 PDJD Token Generator - Portal Jus.br — ⚖️ PDJD Token Generator - Po (era 395.html)
js/98-396.js          ← COMO_BUILDAR — Assistente Jurídico — Como Gerar o APK (era 396.html)
js/98-397.js          ← Filtrador Universal de Documentos (era 397.html)
js/98-398.js          ← Analisador de Versões PWA Jurídico — 🔍 Analisador de Versões — PWA Ju (era 398.html)
js/98-399.js          ← Adjair Tempo Especial (era 399.html)
js/98-4.js            ← Playground Visual — 🎮 Playground Visual (era 4.html)
js/98-40.js           ← Comparador Jurídico Multi-Cenário — Cartão/Empréstimo (BCB + TJMG) — C (era 40.html)
js/98-400.js          ← Comparador Jurídico Master — Monica Especialista (era 400.html)
js/98-401.js          ← Painel – Flexibilização de Renda — MAIKON DA ROCHA CALDEIRA - OAB/MG 1 (era 401.html)
js/98-402.js          ← 🧩 Montador Multi-Projetos — PWA Jurídico — 🧩 Montador Multi-Projetos (era 402.html)
js/98-403.js          ← Painel de Confronto de Remunerações (CNIS/RAIS/CTC) — Painel de Confro (era 403.html)
js/98-404.js          ← Gerenciador de Links - Maikon Caldeira — 🔗 Gerenciador de Links (era 404.html)
js/98-405.js          ← Analisador de Código Gigante — 🔍 Analisador de Código Gigante (era 405.html)
js/98-406.js          ← MANUAL (1) — Assistente Jurídico IA — Manual Completo (era 406.html)
js/98-407.js          ← Dashboard de Monitoramento - Projeto Jurídico — 📊 Dashboard de Monito (era 407.html)
js/98-408.js          ← Filtrador Jurídico Avançado (Anti-repetição) — Filtrador Jurídico Avan (era 408.html)
js/98-409.js          ← 🔍 Comparador de Projetos — 🔍 Comparador de Projetos (era 409.html)
js/98-41.js           ← 🔪 Fatiador de Código — 🔪 Fatiador de Código (era 41.html)
js/98-410.js          ← Painel Maikon Caldeira — Advocacia Digital — 📚 Gerador de Documentaçã (era 410.html)
js/98-411.js          ← Multi-Projetos PWA — Maikon Caldeira (era 411.html)
js/98-412.js          ← Analisador de Projetos + Gerador .EXE — 📦 Analisador de Projetos + Ge (era 412.html)
js/98-414.js          ← Análise: TerminalTab.tsx — 🔬 TerminalTab.tsx (era 414.html)
js/98-415.js          ← analise_pacote-ia.txt.md.md — analise_pacote-ia.txt.md.md (era 415.html)
js/98-416.js          ← Análise: EditorLayout.tsx — 🔬 EditorLayout.tsx (era 416.html)
js/98-417.js          ← Análise: eas.ts — 🔬 eas.ts (era 417.html)
js/98-418.js          ← Análise: archive.ts — 🔬 archive.ts (era 418.html)
js/98-419.js          ← Análise: archive.ts — 🔬 archive.ts (era 419.html)
js/98-42.js           ← Playground Supabase — Playground conectado ao Supabase (era 42.html)
js/98-420.js          ← analise_App.tsx.md — analise_App.tsx.md (era 420.html)
js/98-421.js          ← Validar JWT com Chave Pública PEM — 🔍 Validador JWT - Chave Pública P (era 421.html)
js/98-422.js          ← ' + nomeCompleto + ' — MAIKON CALDEIRA (era 422.html)
js/98-423.js          ← Monica Assistente - Comparador de Cenários Judiciais — Comparador de E (era 423.html)
js/98-424.js          ← 🔑 JWT Generator PDJUD/PDPJ — ⚖️ JWT Generator - PDJUD/PDPJ Brasil (era 424.html)
js/98-425.js          ← Manual Básico: Variáveis de Ambiente e Chaves Secretas — Manual Básico (era 425.html)
js/98-426.js          ← Manual 1 — Manual Básico: Variáveis de Ambiente e Chaves Secretas (era 426.html)
js/98-427.js          ← Gerador de Cotejo Analítico (BPC/LOAS) — Export Word/Excel/JSON (era 427.html)
js/98-428.js          ← SK Oficina Jurídica v6 - Analyzer + Injector (era 428.html)
js/98-429.js          ← Extrair Texto (PDF/TXT/Imagem/DOCX) — Extrator de Texto (PDF / TXT / I (era 429.html)
js/98-43.js           ← Iara Suite — Editor — Iara Suite (era 43.html)
js/98-430.js          ← Filtrador Jurídico Completo (VIP + Word) — Filtrador Jurídico (era 430.html)
js/98-431.js          ← Filtrador Jurídico Avançado (Versão Mike) — Filtrador Jurídico Avançad (era 431.html)
js/98-432.js          ← Filtrador Genérico (Anti-repetição) — Jurídico — Filtrador genérico (a (era 432.html)
js/98-433.js          ← Leitor de Projeto PRO - Com Memória — 🔍 Leitor de Projeto PRO (era 433.html)
js/98-434.js          ← Extrator Jurídico - Processo Completo (Contrato Falsificado) — Extrato (era 434.html)
js/98-435.js          ← Comparador Jurídico — Correção + Juros (Simples/Compostos) por Competê (era 435.html)
js/98-436.js          ← 🔬 Cirurgião 3.0 — Scanner Inteligente — 🔬 Cirurgião 3.0 — Scanner In (era 436.html)
js/98-437.js          ← Multi-Projetos PWA — Maikon Caldeira (era 437.html)
js/98-438.js          ← Playground IA — Saulo — Playground IA — Saulo (era 438.html)
js/98-439.js          ← Multi-Projetos PWA — Maikon Caldeira (era 439.html)
js/98-44.js           ← Gerador de Estrutura - CORRIGIDO — 🗺️ Gerador de Estrutura - CORRIGID (era 44.html)
js/98-440.js          ← Multi-Projetos PWA — Maikon Caldeira (era 440.html)
js/98-441.js          ← analise_settings.tsx.md — analise_settings.tsx.md (era 441.html)
js/98-442.js          ← Análise: Manual.tsx — 🔬 Manual.tsx (era 442.html)
js/98-443.js          ← analise_keys.tsx (3).md — analise_keys.tsx (3).md (era 443.html)
js/98-444.js          ← Análise: eas.ts — 🔬 eas.ts (era 444.html)
js/98-445.js          ← Análise: BuildPanel.tsx — 🔬 BuildPanel.tsx (era 445.html)
js/98-446.js          ← Análise: android.ts — 🔬 android.ts (era 446.html)
js/98-447.js          ← Analisador Local de Projetos — V2 — Analisador Local de Projetos — V2 (era 447.html)
js/98-448.js          ← Comparar custo IA: barato vs caro — Comparar custo de IA: modelo barat (era 448.html)
js/98-449.js          ← Extrair Texto Completo (era 449.html)
js/98-45.js           ← 🐍 Python Explicado Visualmente — 🐍 Python Explicado Visualmente (era 45.html)
js/98-450.js          ← nova_ferramenta — Gerador de Arquivo .env (era 450.html)
js/98-451.js          ← nova_ferramenta (era 451.html)
js/98-452.js          ← Playground Pro - Maikon Caldeira (era 452.html)
js/98-453.js          ← Guia de recuperação  — Guia de Recuperação e Configuração do Projeto M (era 453.html)
js/98-454.js          ← Limpador de Embargos (Anti-Repetição) — Limpador de Embargos & Extrato (era 454.html)
js/98-455.js          ← 🔐 JWT RS256 - Front-end — 🔐 JWT RS256 Generator (era 455.html)
js/98-456.js          ← Comparador Jurídico — TJMG + BCB — Premium — Comparador Jurídico — TJM (era 456.html)
js/98-457.js          ← Extrator Jurídico - Contrato Falsificado (INSS/Estelionato) — Extrator (era 457.html)
js/98-458.js          ← Iara — Mapeador Visual (era 458.html)
js/98-459.js          ← Iara Dissecador — Extrator e Montador de Código — 🧩 Iara Dissecador — (era 459.html)
js/98-46.js           ← CodeLens (era 46.html)
js/98-460.js          ← Extrator Jurídico Avançado - Processo Completo com Links — Extrator Ju (era 460.html)
js/98-461.js          ← Analisador Automático + Debugger Visual — 🔍 Analisador Automático + D (era 461.html)
js/98-462.js          ← Comparador Jurídico — TJMG (Fator) + BCB (Juros) — Multi-Cenário — Com (era 462.html)
js/98-463.js          ← Painel Maikon Caldeira — Advocacia Digital — 🔧 SK Editor Jurídico v2 (era 463.html)
js/98-464.js          ← Playground Code Pro + IA — Maikon Caldeira — Bem-vindo ao Playground P (era 464.html)
js/98-465.js          ← Multi-Projetos PWA — Maikon Caldeira (era 465.html)
js/98-466.js          ← Multi-Projetos PWA — Maikon Caldeira (era 466.html)
js/98-467.js          ← Explorador de Versões e Bugs - Replit/ZIP — 🔍 Explorador de Versões e (era 467.html)
js/98-468.js          ← Diagnóstico de Executável com Problema — 🔧 Diagnóstico de Executável  (era 468.html)
js/98-469.js          ← Gerador Automático de package.json + Workflow — 📦 Gerador de package. (era 469.html)
js/98-47.js           ← Navegador PWA (era 47.html)
js/98-470.js          ← Mini SK — 🔗 Meus Links (era 470.html)
js/98-471.js          ← Analisador de Código — 🔍 Analisador de Código (era 471.html)
js/98-472.js          ← 11 — 11 (era 472.html)
js/98-473.js          ← ai-studio-backup-2026-10-24-15-47 — Relatório — 📂 ai-studio-backup-20 (era 473.html)
js/98-474.js          ← ai-studio-backup-2026-10-24-15-47 — Relatório — 📂 ai-studio-backup-20 (era 474.html)
js/98-475.js          ← Analisador de Código — 🔍 Analisador de Código (era 475.html)
js/98-476.js          ← analise_legal-assistant.tsx.md — analise_legal-assistant.tsx.md (era 476.html)
js/98-478.js          ← cdns (1) (era 478.html)
js/98-479.js          ← Guia dos Apps do Maikon — Guia dos seus apps (era 479.html)
js/98-48.js           ← Multi-Projetos PWA — Maikon Caldeira (era 48.html)
js/98-480.js          ← Blocos de colado.js — ✂️ colado.js — 48 blocos (era 480.html)
js/98-481.js          ← 🔬 Dissecador de Código — Iara Suite v2.0 — 🔬 Dissecador de Código —  (era 481.html)
js/98-482.js          ← SK Editor v3 (era 482.html)
js/98-483.js          ← Meu App — Meu App (era 483.html)
js/98-484.js          ← Instalador · Assistente Jurídico (no computador) — 📦 Assistente Juríd (era 484.html)
js/98-485.js          ← Instalador · Mini SK v09/10-b — 📦 Mini SK v09/10-b (era 485.html)
js/98-486.js          ← Instalador · Mini SK v15/10-a (site / celular / APK) — 📦 Mini SK v15/ (era 486.html)
js/98-487.js          ← Laboratório do Modular — Laboratório do Modular (era 487.html)
js/98-488.js          ← Playground HTML — 🚀 Playground HTML (era 488.html)
js/98-489.js          ← RECEITA — 🧬 Receita para recriar: JurisPro (era 489.html)
js/98-49.js           ← SK Scanner v2 — SK Scanner v2 (era 49.html)
js/98-490.js          ← ⚖️ Cofre de Configurações — 🔐 Cofre de Configurações (era 490.html)
js/98-491.js          ← Fatiador Universal de Código — Fatiador Universal de Código (era 491.html)
js/98-492.js          ← Instalador · Caça-Bug — 📦 Caça-Bug (era 492.html)
js/98-493.js          ← Arquivos juntados — Arquivos juntados (era 493.html)
js/98-494.js          ← Laboratório HTML — Advocacia Previdenciária (era 494.html)
js/98-495.js          ← 📂 Leitor Universal de Arquivos — Leitor Universal de Arquivos (era 495.html)
js/98-496.js          ← PLANO — Plano do projeto: juridico (era 496.html)
js/98-497.js          ← Planos.md — Planos.md (era 497.html)
js/98-498.js          ← 📦 Project Manager Pro - Terminal & NPM — 🚀
            Project Mana (era 498.html)
js/98-499.js          ← Sem título (1) — Bem-vindo ao HTML Playground (era 499.html)
js/98-5.js            ← Netlify Build + Testador API — 🚀 Netlify Build + Testador de API (era 5.html)
js/98-50.js           ← Relatório de metadados (era 50.html)
js/98-500.js          ← Manual do Maikon — 📘 Manual do Maikon (era 500.html)
js/98-51.js           ← RECEITA — 🧬 Receita para recriar: SK Jurídico — Assistente IA (era 51.html)
js/98-52.js           ← relatorio-AssistenteJuridico-PWA-8zip  714d7dd (3).md — relatorio-Assi (era 52.html)
js/98-53.js           ← relatorio-AssistenteJuridico-PWA-8zip 1AssistenteJ.md — relatorio-Assi (era 53.html)
js/98-54.js           ← 🔧 PWA Builder — Gerador de Instalação — 🔧 PWA Builder (era 54.html)
js/98-55.js           ← PWA Jurídico — Maikon Caldeira (era 55.html)
js/98-56.js           ← 🧩 Montador Multi-Projetos — PWA Jurídico — 🧩 Montador Multi-Projetos (era 56.html)
js/98-57.js           ← Live Code Runner (era 57.html)
js/98-58.js           ← SK-Prompt Manager — Templates + Histórico (era 58.html)
js/98-59.js           ← Projeto Lab (era 59.html)
js/98-6.js            ← Gerenciador de Portas e Projetos — 🔧 Gerenciador de Projetos (era 6.html)
js/98-60.js           ← Chat IA Profissional (era 60.html)
js/98-61.js           ← AI Code Studio — 🤖 AI Code Studio (era 61.html)
js/98-62.js           ← 🚀 Guia Interativo - Chat IA Profissional — 🚀 Chat IA Profissional v1 (era 62.html)
js/98-63.js           ← 🔧 ConstruAPK Pro — Analisador e Gerador — ConstruAPK Pro — Analisador (era 63.html)
js/98-64.js           ← 📱 Gerador DevMobile EAS — 📱 Gerador EAS Build — Baseado no DevMobile (era 64.html)
js/98-65.js           ← 📦 Build & Deploy — Build & Deploy (era 65.html)
js/98-66.js           ← Sistema Profissional - Modular — 📊 Sistema (era 66.html)
js/98-67.js           ← Gerador de Estrutura de Projeto — 🏗️ Gerador de Estrutura de Projeto (era 67.html)
js/98-68.js           ← Analisador de Projeto — 🔍 Analisador de Projeto (era 68.html)
js/98-69.js           ← Playground Code — Maikon Caldeira — Bem-vindo ao HTML Playground (era 69.html)
js/98-7.js            ← Corretor de Projetos — 🔧 Corretor de Projetos (era 7.html)
js/98-70.js           ← playground — 🚀 Playground (era 70.html)
js/98-71.js           ← Code Playground - HTML/CSS/JS/React/Python — Bem-vindo ao HTML Playgro (era 71.html)
js/98-72.js           ← Multi-Projetos PWA — Maikon Caldeira (era 72.html)
js/98-73.js           ← Playground — MeuIDE — 🚀 Playground (era 73.html)
js/98-74.js           ← Suite Jurídica + IA (era 74.html)
js/98-75.js           ← plano-SK-Editor-v3-SemReplit-9-1790894751105.md — plano-SK-Editor-v3-S (era 75.html)
js/98-77.js           ← Editor Visual — Bem-vindo! (era 77.html)
js/98-78.js           ← 🎨 Editor Visual - Funcional de Verdade (era 78.html)
js/98-79.js           ← 🐝 Editor Visual - Responsivo — 🐝 Editor Visual (era 79.html)
js/98-8.js            ← Guia do Terminal — 🖥️ Guia do Terminal & Python (era 8.html)
js/98-80.js           ← Editor Visual — 🎨 Editor Visual (era 80.html)
js/98-81.js           ← 🎨 Editor Visual - Funcional — 🎨 Editor Visual - Funcional (era 81.html)
js/98-82.js           ← 🎨 Editor Visual de Código — 🎨 Editor Visual de Código (era 82.html)
js/98-83.js           ← SK-HTML Magic Editor — Bem-vindo! (era 83.html)
js/98-84.js           ← SK-Build Guide — Entenda o Build (era 84.html)
js/98-85.js           ← SK-Build Unpacker — Desempacotar Build (era 85.html)
js/98-86.js           ← Perito de Metadados — Perito de Metadados (era 86.html)
js/98-87.js           ← Parser Markdown - Gerador de Projetos — 🚀 Parser Markdown (era 87.html)
js/98-88.js           ← Painel Maikon Caldeira — Advocacia Digital — Maikon Caldeira (era 88.html)
js/98-89.js           ← Organizador de Documentos — 📑 Organizador de Documentos (era 89.html)
js/98-9.js            ← Leitor de Memória — 📖 Leitor de Memória (era 9.html)
js/98-90.js           ← Extrator Universal BPC/LOAS - Análise Processual — Extrator Universal  (era 90.html)
js/98-91.js           ← Multi-Projetos PWA — Maikon Caldeira (era 91.html)
js/98-92.js           ← Multi-Projetos PWA — Maikon Caldeira (era 92.html)
js/98-93.js           ← Multi-Projetos PWA — Maikon Caldeira (era 93.html)
js/98-94.js           ← Multi-Projetos PWA — Maikon Caldeira (era 94.html)
js/98-95.js           ← Multi-Projetos PWA — Maikon Caldeira (era 95.html)
js/98-96.js           ← Multi-Projetos PWA — Maikon Caldeira (era 96.html)
js/98-97.js           ← Code Merger Pro — Maikon Caldeira (era 97.html)
js/98-98.js           ← Build React - Executável Funcional — ⚛️ Build React - Executável Funci (era 98.html)
js/98-99.js           ← 🏗️ Montador - Chat IA — 🏗️ Montador - Chat IA Profissional (era 99.html)
js/98-hub.js          ← codigos-numerados-2026-10-26 (1) — codigos-numerados-2026-10-26 (1) (era hub.html)
js/98-inicio.js       ← Maikon Caldeira — Aplicativos — MAIKON CALDEIRA (era index.html)
js/99-app.js          ← o último: monta a tela com o que embarcou
```

## 3. As partes, uma por uma

| # | Era | Vira | Tipo | O que faz | Usa |
|---|---|---|---|---|---|
| 1 | `exe/abrir.py` | `js/10-abrir.js` | logica | -*- coding: utf-8 -*- | — |
| 2 | `112.html` | `js/15-112.js` | servidor | Raio-X de Projetos — Raio-X de Projetos | importar, toolbar, chat |
| 3 | `122.html` | `js/20-122.js` | servidor | 🔗 Teste APK + Termux — 🔗 Teste APK ↔ Termux | — |
| 4 | `211.html` | `js/25-211.js` | servidor | Análise: snippets.ts — 🔬 snippets.ts | — |
| 5 | `266.html` | `js/30-266.js` | servidor | Multi-Projetos PWA — Maikon Caldeira | — |
| 6 | `278.html` | `js/35-278.js` | servidor | Análise: workspace.ts — 🔬 workspace.ts | — |
| 7 | `333.html` | `js/40-333.js` | servidor | Análise: AIChat.tsx — 🔬 AIChat.tsx | neon |
| 8 | `377.html` | `js/45-377.js` | servidor | Painel Maikon Caldeira — Advocacia Digital — 🔧 PWA Analyzer - Detector Inteligente | — |
| 9 | `392.html` | `js/50-392.js` | servidor | Análise: AIChat.tsx — 🔬 AIChat.tsx | neon |
| 10 | `413.html` | `js/55-413.js` | servidor | Blocos de assets/app (cópia).js — ✂️ assets/app (cópia).js — 1 blocos | — |
| 11 | `477.html` | `js/60-477.js` | servidor | Markdown — Pacote do projeto &quot;artifacts6&quot; para a IA | — |
| 12 | `76.html` | `js/65-76.js` | servidor | PLANO_RECUPERACAO.md — PLANO_RECUPERACAO.md | storage.js, novaRota |
| 13 | `1.html` | `js/70-1.js` | tela | Arrumador de Backups — 🗃 Arrumador de Backups | — |
| 14 | `10.html` | `js/75-10.js` | tela | Meu Projeto — Meu Projeto | — |
| 15 | `100.html` | `js/80-100.js` | tela | ⚙️ Replit Config Manager — ⚙️ Replit Config Manager | config-manager.js |
| 16 | `101.html` | `js/85-101.js` | tela | 🧹 Project Cleaner — 🧹 Project Cleaner + Generator | — |
| 17 | `102.html` | `js/90-102.js` | tela | Iara Mapper Pro - Final — 🚀 Iara Mapper Pro | — |
| 18 | `103.html` | `js/91-103.js` | tela | SK-Code Editor Functions Explained | — |
| 19 | `104.html` | `js/92-104.js` | tela | SK-Details & Summary — Expandir/Colapsar | — |
| 20 | `105.html` | `js/93-105.js` | tela | SK-Iara Suite Checker | — |
| 21 | `106.html` | `js/94-106.js` | tela | Editor com Busca - Dr. Maikon | — |
| 22 | `107.html` | `js/95-107.js` | tela | Iara Mapper Pro | — |
| 23 | `108.html` | `js/96-108.js` | tela | Analisador de Projetos — 🔍 Analisador | — |
| 24 | `109.html` | `js/97-109.js` | tela | Visualizador de Markdown — Visualizador de Markdown | — |
| 25 | `11.html` | `js/98-11.js` | tela | Validador de Código + Testador de API — 🧪 Validador de Código + Testador de API | — |
| 26 | `110.html` | `js/98-110.js` | tela | Iara 2.0 - Mapeador Profissional de Dependências — 🕸️ Iara 2.0 — Mapeador Profissional | — |
| 27 | `111.html` | `js/98-111.js` | tela | 🧹 Limpador de Replit — 🧹 Limpador de Vínculos Replit | — |
| 28 | `113.html` | `js/98-113.js` | tela | Gerador de Ícones PRO - Maikon Caldeira — 🎨 Gerador de Ícones PRO | — |
| 29 | `114.html` | `js/98-114.js` | tela | PWA Jurídico — Maikon Caldeira — Filtrador Jurídico Avançado (Atualizado) | — |
| 30 | `115.html` | `js/98-115.js` | tela | Teste Diff (Estático) | diff.js |
| 31 | `116.html` | `js/98-116.js` | tela | Diff Simple Test | diff.js |
| 32 | `117.html` | `js/98-117.js` | tela | projeto | — |
| 33 | `118.html` | `js/98-118.js` | tela | Analisador e Reparador PWA -> APK — 🛠️ Reparador PWA para APK | — |
| 34 | `119.html` | `js/98-119.js` | tela | 🔍 Analisador de Projetos — Analisador de Projetos — Detector de Problemas | — |
| 35 | `12.html` | `js/98-12.js` | tela | Triagem de Código — Triagem de Código | main.js |
| 36 | `120.html` | `js/98-120.js` | tela | VOXIS — Assistente Pessoal — 🎙️ Estúdio de Voz | style.css, memory.js, brain.js, voice.js |
| 37 | `121.html` | `js/98-121.js` | tela | 📱 Gerador EAS Build — 📱 Gerador de Configuração EAS Build | — |
| 38 | `123.html` | `js/98-123.js` | tela | Analisador de Logs GitHub Actions — 🔍 Analisador de Logs GitHub Actions | — |
| 39 | `124.html` | `js/98-124.js` | tela | Replicador de Projeto — ⚡ Replicador de Projeto | — |
| 40 | `125.html` | `js/98-125.js` | tela | Editor Visual — 🐝 Editor Visual | — |
| 41 | `126.html` | `js/98-126.js` | tela | 🐝 Editor Visual - Responsivo — 🐝 Editor Visual | — |
| 42 | `127.html` | `js/98-127.js` | tela | Editor Visual HTML - Tipo Firebug Simples — 🐝 Editor Visual HTML | — |
| 43 | `128.html` | `js/98-128.js` | tela | SK-Code Analyzer — Mapear Dependências | — |
| 44 | `129.html` | `js/98-129.js` | tela | SK-Code Formatter — Organize seu Código | — |
| 45 | `13.html` | `js/98-13.js` | tela | Teste — Teste | — |
| 46 | `130.html` | `js/98-130.js` | tela | Perito de Metadados — Perito de Metadados | — |
| 47 | `131.html` | `js/98-131.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 48 | `132.html` | `js/98-132.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 49 | `133.html` | `js/98-133.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 50 | `134.html` | `js/98-134.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 51 | `135.html` | `js/98-135.js` | tela | 📱 APK Builder - EAS — 📱 APK Builder - EAS | — |
| 52 | `136.html` | `js/98-136.js` | tela | 🚀 Setup Dashboard - Monorepo — 🚀 Setup Dashboard | — |
| 53 | `137.html` | `js/98-137.js` | tela | 🛠️ Workstation Completa — Maikon Caldeira | — |
| 54 | `138.html` | `js/98-138.js` | tela | modulo 2 — Meu PWA Jurídico | — |
| 55 | `139.html` | `js/98-139.js` | tela | IARA Suite — Importador & Editor Completo | — |
| 56 | `14.html` | `js/98-14.js` | tela | SK Mini Editor — SK Mini Editor | — |
| 57 | `140.html` | `js/98-140.js` | tela | Comparar Código | — |
| 58 | `141.html` | `js/98-141.js` | tela | SK-Docs Hub PT — Documentação em Português — Título | — |
| 59 | `142.html` | `js/98-142.js` | tela | Code Debugger — Dr. Maikon Caldeira | — |
| 60 | `143.html` | `js/98-143.js` | tela | Iara Mapper Pro — Dr. Maikon Caldeira | — |
| 61 | `144.html` | `js/98-144.js` | tela | Meu Projeto PWA — 🔍 Leitor de Projeto PRO | — |
| 62 | `145.html` | `js/98-145.js` | tela | manual-dev (1) — Manual para Desenvolvedores — Correções Necessárias no App Mobile | — |
| 63 | `146.html` | `js/98-146.js` | tela | Auditoria Financeira - Assistente Jurídico — 📊 Auditoria Financeira | — |
| 64 | `147.html` | `js/98-147.js` | tela | HTML Playground - Editor de Codigo ao Vivo | favicon.png, icon-192.png, manifest.json, index-5lQh8nvD.js |
| 65 | `148.html` | `js/98-148.js` | tela | Auditoria Master - Dr. MAIKON DA ROCHA CALDEIRA — ⚖️ Auditoria Pericial | — |
| 66 | `149.html` | `js/98-149.js` | tela | Limpador de Processos — Limpador de Processos | — |
| 67 | `15.html` | `js/98-15.js` | tela | SK Mini Editor - Guia de Instalação Interativo — SK Mini Editor | — |
| 68 | `150.html` | `js/98-150.js` | tela | Painel Maikon Caldeira - Advogado — Maikon Caldeira | manifest.json |
| 69 | `151.html` | `js/98-151.js` | tela | Iara Suite v2.0 - Editor + Mapper Avançado — 🚀 Iara Suite v2.0 | — |
| 70 | `152.html` | `js/98-152.js` | tela | ⚖️ Robô Jurídico — ⚖️ Robô Jurídico | — |
| 71 | `153.html` | `js/98-153.js` | tela | Iara Suite v3.0 - Importador Universal — 🚀 Iara Suite v3.0 - Importador Universal | — |
| 72 | `154.html` | `js/98-154.js` | tela | Gerador de Plano de Projeto — 📊 Gerador de Plano de Projeto | — |
| 73 | `155.html` | `js/98-155.js` | tela | Gerador de Ícones PWA - Maikon Caldeira — 🎨 Gerador de Ícones PWA | — |
| 74 | `156.html` | `js/98-156.js` | tela | 📱 Gerador EAS Build — 📱 Gerador de Configuração EAS Build | — |
| 75 | `157.html` | `js/98-157.js` | tela | Gerador de Documentação Automática — 📚 Gerador de Documentação Automática | — |
| 76 | `158.html` | `js/98-158.js` | tela | Extrator de Sites — 🛠️ Extrator de Sites | — |
| 77 | `159.html` | `js/98-159.js` | tela | SK-Combinar Apps — Unir Projetos | — |
| 78 | `16.html` | `js/98-16.js` | tela | SK Code Editor - GitHub Integration — SK Code Editor | style.css, github-service.js, github-panel.js, app.js |
| 79 | `160.html` | `js/98-160.js` | tela | 🔧 ConstruAPK Pro — Analisador e Gerador — ConstruAPK Pro — Analisador & Gerador | — |
| 80 | `161.html` | `js/98-161.js` | tela | 🎨 Playground + ⚖️ Assistente Jurídico - Maikon | favicon.png, icon-192.png, manifest.json, main.tsx |
| 81 | `162.html` | `js/98-162.js` | tela | Juntador de Arquivos — 🧩 Juntador de Arquivos | — |
| 82 | `163.html` | `js/98-163.js` | tela | Maikon Caldeira — Aplicativos — MAIKON CALDEIRA | manifest.json, icon-192.png |
| 83 | `164.html` | `js/98-164.js` | tela | AI Code Studio — 🤖 AI Code Studio | — |
| 84 | `165.html` | `js/98-165.js` | tela | 🚀 Setup Dashboard — 🚀 Setup Dashboard | manifest.json, setup-dashboard.css, setup-dashboard.js |
| 85 | `166.html` | `js/98-166.js` | tela | Gerador de Relatório + Extrator de Arquivos — 📋 Gerador de Relatório + Extrator de Arquiv | — |
| 86 | `167.html` | `js/98-167.js` | tela | Filtrador Jurídico Avançado (Atualizado) — Filtrador Jurídico Avançado (Atualizado) | — |
| 87 | `168.html` | `js/98-168.js` | tela | SK-Chat — Painel de Regras | — |
| 88 | `169.html` | `js/98-169.js` | tela | SK-Master — Editor + Chat + Prompt Generator | — |
| 89 | `17.html` | `js/98-17.js` | tela | SK Mini Editor - Completo — SK Mini Editor | — |
| 90 | `170.html` | `js/98-170.js` | tela | SK-Code Analyzer v2 | — |
| 91 | `171.html` | `js/98-171.js` | tela | Peça | — |
| 92 | `172.html` | `js/98-172.js` | tela | CirurgiÃ£o de CÃ³digo 4.4 — ðŸ©º CirurgiÃ£o 4.4 | — |
| 93 | `173.html` | `js/98-173.js` | tela | Cirurgião de Código 4.3 — 🩺 Cirurgião 4.3 | — |
| 94 | `174.html` | `js/98-174.js` | tela | Juntador de Arquivos — 🧩 Juntador de Arquivos | — |
| 95 | `175.html` | `js/98-175.js` | tela | Maikon Caldeira - Advocacia Digital — Maikon Caldeira | manifest.json, icon-192.png |
| 96 | `176.html` | `js/98-176.js` | tela | SK Editor v3 | icon-192.png, manifest.webmanifest, index-Cxjs0Gz5.js, vendor-lucide-f6q5Jl5b.js |
| 97 | `177.html` | `js/98-177.js` | tela | Conversor TJMG (Fator) → competencia/correcao_pct — Conversor TJMG (fator em colunas) → co | — |
| 98 | `178.html` | `js/98-178.js` | tela | Iara Suite — ⚡ Iara Suite | — |
| 99 | `179.html` | `js/98-179.js` | tela | 🚀 Gerenciador PWA - Maikon Caldeira — 🚀 Gerenciador PWA Completo | manifest.json, icon-192.png |
| 100 | `18.html` | `js/98-18.js` | tela | teste 2 onde txt 6 index | style.css, theme-dark.css, font-awesome.min.css, highlight.min.css |
| 101 | `180.html` | `js/98-180.js` | tela | Playground TSX - Maikon Caldeira — 🎨 Playground TSX/React | — |
| 102 | `181.html` | `js/98-181.js` | tela | 📱 Gerador DevMobile EAS — 📱 Gerador EAS Build — Baseado no DevMobile | — |
| 103 | `182.html` | `js/98-182.js` | tela | Extrator de Sites — 🛠️ Extrator de Sites | — |
| 104 | `183.html` | `js/98-183.js` | tela | Extrator Jurídico — Maikon Caldeira OAB/MG 183712 | — |
| 105 | `184.html` | `js/98-184.js` | tela | Iara Mapper — Dr. Maikon Caldeira | — |
| 106 | `185.html` | `js/98-185.js` | tela | SK-CSS/HTML Interactive Guide | — |
| 107 | `186.html` | `js/98-186.js` | tela | Demonstrativo de cálculo | — |
| 108 | `187.html` | `js/98-187.js` | tela | Corretor Automático Inteligente — 🔧 Corretor Automático Inteligente | — |
| 109 | `188.html` | `js/98-188.js` | tela | Comunicações Processuais — ⚖️ Comunicações Processuais | — |
| 110 | `189.html` | `js/98-189.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 111 | `19.html` | `js/98-19.js` | tela | Playground Pro — Bem-vindo ao Playground Pro! 🚀 | — |
| 112 | `190.html` | `js/98-190.js` | tela | Consulta por OAB — Buscar por OAB | — |
| 113 | `191.html` | `js/98-191.js` | tela | lib pdf template | — |
| 114 | `192.html` | `js/98-192.js` | tela | indice_legal-assistant.tsx (2).md — indice_legal-assistant.tsx (2).md | tiptap-editor, button, input, textarea |
| 115 | `193.html` | `js/98-193.js` | tela | Meus Projetos | — |
| 116 | `194.html` | `js/98-194.js` | tela | Construtor Automático PWA - Maikon Caldeira — 🚀 Construtor Automático PWA | manifest.json, sw-register.js |
| 117 | `195.html` | `js/98-195.js` | tela | SK-Chat — Regras + Tokens | — |
| 118 | `196.html` | `js/98-196.js` | tela | Cirurgião de Código 4.0 — 🔬 CIRURGIÃO DE CÓDIGO 4.0 | — |
| 119 | `197.html` | `js/98-197.js` | tela | Cirurgião de Código 2.0 — 🔬 CIRURGIÃO DE CÓDIGO 2.0 | — |
| 120 | `198.html` | `js/98-198.js` | tela | Cirurgião de Código 4.4 — 🩺 Cirurgião 4.4 | — |
| 121 | `199.html` | `js/98-199.js` | tela | Cirurgião de Código 4.2 — 🩺 Cirurgião 4.2 | — |
| 122 | `2.html` | `js/98-2.js` | tela | Diagnóstico + Correção de Executáveis — 🔧 Diagnóstico + Correção de Executáveis | — |
| 123 | `20.html` | `js/98-20.js` | tela | 🚀 SK Mini Editor - Gerador de Arquivos — 🚀 SK Mini Editor | style.css, responsive.css, sidebar.css, editor.css |
| 124 | `200.html` | `js/98-200.js` | tela | Cirurgião de Código 4.1 — 🩺 Cirurgião 4.1 | — |
| 125 | `201.html` | `js/98-201.js` | tela | Chat IA Pro — Saulo — Chat IA Pro | — |
| 126 | `202.html` | `js/98-202.js` | tela | Chat — 💬 Chat | — |
| 127 | `203.html` | `js/98-203.js` | tela | Calculadora de Sentença — Calculadora de Sentença | — |
| 128 | `204.html` | `js/98-204.js` | tela | Calculadora de Sentença — Calculadora de Sentença | — |
| 129 | `205.html` | `js/98-205.js` | tela | Calculadora de Sentença — Calculadora de Sentença | — |
| 130 | `206.html` | `js/98-206.js` | tela | arquivo 2 | — |
| 131 | `207.html` | `js/98-207.js` | tela | Comparador Jurídico Completo — TJMG (Fator) + BCB (Juros) — Multi-Cenário — Comparador Jur | — |
| 132 | `208.html` | `js/98-208.js` | tela | Chat IA Pro — Chat IA Pro | — |
| 133 | `209.html` | `js/98-209.js` | tela | Calculadora de Sentença — Calculadora de Sentença | — |
| 134 | `21.html` | `js/98-21.js` | tela | 🚀 SK Mini Editor - Setup Interativo — 🚀 SK Mini Editor - Setup Interativo | — |
| 135 | `210.html` | `js/98-210.js` | tela | SK Oficina Jurídica v6 - Integrada — SK Oficina Jurídica v6 | — |
| 136 | `212.html` | `js/98-212.js` | tela | analise_Manual.tsx.html — analise_Manual.tsx.html | virtual-fs, zip-service |
| 137 | `213.html` | `js/98-213.js` | tela | Análise: keys.tsx — 🔬 keys.tsx | — |
| 138 | `214.html` | `js/98-214.js` | tela | Análise: export.tsx — 🔬 export.tsx | — |
| 139 | `215.html` | `js/98-215.js` | tela | Análise: EditorLayout.tsx — 🔬 EditorLayout.tsx | — |
| 140 | `216.html` | `js/98-216.js` | tela | analise_EditorLayout.tsx (1).md — analise_EditorLayout.tsx (1).md | DatabasePanel, DeployPanel, virtual-fs, github-service |
| 141 | `217.html` | `js/98-217.js` | tela | Análise: desktop.ts — 🔬 desktop.ts | — |
| 142 | `218.html` | `js/98-218.js` | tela | Análise: android.ts — 🔬 android.ts | — |
| 143 | `219.html` | `js/98-219.js` | tela | AI Code Studio — 🤖 AI Code Studio | — |
| 144 | `22.html` | `js/98-22.js` | tela | SK Mini Editor - TESTE — SK Mini Editor - TESTE | — |
| 145 | `220.html` | `js/98-220.js` | tela | Sem titulo — Bem-vindo ao HTML Playground | — |
| 146 | `221.html` | `js/98-221.js` | tela | Diagnóstico crise | — |
| 147 | `222.html` | `js/98-222.js` | tela | Calculadora Jurídica Monica — Importador Direto | — |
| 148 | `223.html` | `js/98-223.js` | tela | Comparador Jurídico Completo (Com Busca BCB) — Comparador Jurídico (BCB Integrado) | — |
| 149 | `224.html` | `js/98-224.js` | tela | Resumidor Jurídico Estruturado v2.0 — EMBARGOS DE DECLARAÇÃO | — |
| 150 | `225.html` | `js/98-225.js` | tela | Gerador de Petição: Vinculação e Enquadramento - Caso Adjair — ⚖️ Gerador de Petição Previ | — |
| 151 | `226.html` | `js/98-226.js` | tela | Siscajur - Perícia Bancária & Sentença (Capitalização Anual) | — |
| 152 | `227.html` | `js/98-227.js` | tela | Extrator Replit — Maikon — 🗂 Extrator de Projetos Replit | — |
| 153 | `228.html` | `js/98-228.js` | tela | Comparador JurÃ­dico â TJMG + BCB — Comparador Juridico â TJMG (Fator) + BCB (Juros) | — |
| 154 | `229.html` | `js/98-229.js` | tela | Extrator de Texto Pro — 📄 Extrator de Texto Pro | — |
| 155 | `23.html` | `js/98-23.js` | tela | SK Mini Editor - Editor de Código Online — SK Mini Editor | mini-vfs.js, mini-filetree.js, mini-github.js, mini-editor.js |
| 156 | `230.html` | `js/98-230.js` | tela | Gerador de Peças Processuais — TRF6 | — |
| 157 | `231.html` | `js/98-231.js` | tela | Calculadora Judicial (TJMG + BCB + Capitalização Anual) — Calculadora Judicial Avançada | — |
| 158 | `232.html` | `js/98-232.js` | tela | Analisador de Histórico — ZIP/TAR/TAZ — 📦 Analisador de Histórico — ZIP/TAR/TAZ | — |
| 159 | `233.html` | `js/98-233.js` | tela | Gerador Jurídico Pro (PDF/DOCX + Dedup Inteligente) — EMBARGOS DE DECLARAÇÃO | — |
| 160 | `234.html` | `js/98-234.js` | tela | Maikon Caldeira - Reconhecimentos Pretéritos | — |
| 161 | `235.html` | `js/98-235.js` | tela | Comparador Jurídico - Índices TJMG + BCB — Comparador Jurídico - Índices TJMG + BCB | — |
| 162 | `236.html` | `js/98-236.js` | tela | 📋 Gerador de Plano de Projeto — 📋 Gerador de Plano de Projeto | — |
| 163 | `237.html` | `js/98-237.js` | tela | SK Database Manager + IA | — |
| 164 | `238.html` | `js/98-238.js` | tela | Análise: Terminal.tsx — 🔬 Terminal.tsx | — |
| 165 | `239.html` | `js/98-239.js` | tela | Análise: settings.tsx — 🔬 settings.tsx | — |
| 166 | `24.html` | `js/98-24.js` | tela | SK Oficina de Busca, Extração & Exportação v7 | — |
| 167 | `240.html` | `js/98-240.js` | tela | Análise: Manual.tsx — 🔬 Manual.tsx | — |
| 168 | `241.html` | `js/98-241.js` | tela | Análise: legal-assistant.tsx — 🔬 legal-assistant.tsx | — |
| 169 | `242.html` | `js/98-242.js` | tela | analise_export.tsx.md — analise_export.tsx.md | ProjectContext, android, eas |
| 170 | `243.html` | `js/98-243.js` | tela | analise_desktop.ts (1).md — analise_desktop.ts (1).md | archive, android |
| 171 | `244.html` | `js/98-244.js` | tela | Análise: DeployPanel.tsx — 🔬 DeployPanel.tsx | — |
| 172 | `245.html` | `js/98-245.js` | tela | Alquimia v.14 | — |
| 173 | `246.html` | `js/98-246.js` | tela | Extrator de Dados Jurídicos | — |
| 174 | `247.html` | `js/98-247.js` | tela | 🚨 RECURSO URGENTE - FUNCIONA — 📋 FERRAMENTAS JURÍDICAS - URGENTE | — |
| 175 | `248.html` | `js/98-248.js` | tela | 🚨 MEU RECURSO PREVIDÊNCIA - FUNCIONA — ⚖️ RECURSO PREVIDÊNCIA - 7 DIAS | — |
| 176 | `249.html` | `js/98-249.js` | tela | Gerador de Cotejo Analítico | — |
| 177 | `25.html` | `js/98-25.js` | tela | SK Rastreador de Rotas & IA v6 - Maikon Caldeira | — |
| 178 | `250.html` | `js/98-250.js` | tela | Extrator BPC Netflix — 🎬 PLATAFORMA BPC TRF6 | — |
| 179 | `251.html` | `js/98-251.js` | tela | Maikon Caldeira - Advocacia — MAIKON CALDEIRA | manifest.json, icon-192.png |
| 180 | `252.html` | `js/98-252.js` | tela | Extrair Texto com Filtros | — |
| 181 | `253.html` | `js/98-253.js` | tela | Parecer de Liquidação Judicial - Dr. Braulino | — |
| 182 | `254.html` | `js/98-254.js` | tela | Calculadora Judicial Completa — Calculadora Judicial Avançada | — |
| 183 | `255.html` | `js/98-255.js` | tela | 🚀 Gerenciador PWA - Maikon Caldeira — 🚀 Gerenciador PWA Completo | — |
| 184 | `256.html` | `js/98-256.js` | tela | Exported HTML — Extrator Universal de Variáveis | — |
| 185 | `257.html` | `js/98-257.js` | tela | Gerador de Peças Jurídicas - TRF6/JEF | — |
| 186 | `258.html` | `js/98-258.js` | tela | Calculadora Judicial Manhumirim - Proveito Econômico — Calculadora Judicial Manhumirim - H | — |
| 187 | `259.html` | `js/98-259.js` | tela | Painel Consolidado – Petições, Tabelas e CTC — Painel Consolidado – Petições, Tabelas e CT | — |
| 188 | `26.html` | `js/98-26.js` | tela | SK-Mini Playground | — |
| 189 | `260.html` | `js/98-260.js` | tela | Filtro Jurídico - Redução Real de Duplicatas — EMBARGOS DE DECLARAÇÃO | — |
| 190 | `261.html` | `js/98-261.js` | tela | PWA Scanner Multi-Formato + IA — 🔎 Scanner Multi-Formato + IA Jurídica | — |
| 191 | `262.html` | `js/98-262.js` | tela | Filtrador Jurídico Master — Maikon Caldeira — ⚖️ Filtrador Jurídico Master | — |
| 192 | `263.html` | `js/98-263.js` | tela | Scanner — Detector de Dependências Replit — 🔍 Scanner de Dependências Replit | — |
| 193 | `264.html` | `js/98-264.js` | tela | Manual SK Editor 4 — Completo — SK Editor 4 — Manual Completo | — |
| 194 | `265.html` | `js/98-265.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 195 | `267.html` | `js/98-267.js` | tela | Filtrador Jurídico Avançado (Anti-repetição) — 🔍 Filtrador Jurídico Avançado | — |
| 196 | `268.html` | `js/98-268.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 197 | `269.html` | `js/98-269.js` | tela | MANUAL (2) — Assistente Jurídico IA — Manual Completo | — |
| 198 | `27.html` | `js/98-27.js` | tela | SK Oficina Jurídica v4 - Maikon Caldeira | — |
| 199 | `270.html` | `js/98-270.js` | tela | PLANO — 📋 Plano do projeto: artifacts teste | — |
| 200 | `271.html` | `js/98-271.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 201 | `272.html` | `js/98-272.js` | tela | Cirurgião de Código 3.0 — 🔬 CIRURGIÃO DE CÓDIGO 3.0 | — |
| 202 | `273.html` | `js/98-273.js` | tela | Scanner — Detector de Dependências — 🔍 Scanner de Dependências | — |
| 203 | `274.html` | `js/98-274.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 204 | `275.html` | `js/98-275.js` | tela | Painel Maikon Caldeira — Advocacia Digital — 📄 Importador de Markdown | — |
| 205 | `276.html` | `js/98-276.js` | tela | 3 Ferramentas Completas - Bugs, Versões e APK — 🛠️ 3 Ferramentas Completas | — |
| 206 | `277.html` | `js/98-277.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 207 | `279.html` | `js/98-279.js` | tela | Análise: persistFiles.ts — 🔬 persistFiles.ts | — |
| 208 | `28.html` | `js/98-28.js` | tela | SK Decodificador & Comparador de Logs v6 | — |
| 209 | `280.html` | `js/98-280.js` | tela | analise_Manual.tsx.md — analise_Manual.tsx.md | virtual-fs, zip-service |
| 210 | `281.html` | `js/98-281.js` | tela | analise_legal-assistant.tsx.md — analise_legal-assistant.tsx.md | tiptap-editor, button, input, textarea |
| 211 | `282.html` | `js/98-282.js` | tela | analise_EditorLayout.tsx.md — analise_EditorLayout.tsx.md | DatabasePanel, DeployPanel, virtual-fs, github-service |
| 212 | `283.html` | `js/98-283.js` | tela | Análise: App.tsx — 🔬 App.tsx | — |
| 213 | `284.html` | `js/98-284.js` | tela | 200+ Códigos Jurídicos — 📂 200+ Códigos Auto-Listados | manifest.json |
| 214 | `285.html` | `js/98-285.js` | tela | Gerador PWA - Maikon Caldeira — 🚀 Gerador PWA - Maikon Caldeira | manifest.json |
| 215 | `286.html` | `js/98-286.js` | tela | Gerador de Arquivo .env - Assistente Jurídico — Gerador de Arquivo .env - Assistente Juríd | — |
| 216 | `287.html` | `js/98-287.js` | tela | Calculadora Mike Definitiva | — |
| 217 | `288.html` | `js/98-288.js` | tela | Editor de Cotejo Analítico - Proporcionalidade de Danos — Editor de Cotejo Analítico - Dan | — |
| 218 | `289.html` | `js/98-289.js` | tela | Guia de Recuperação e Configuração do Projeto Maikon — Guia de Recuperação e Configuração  | — |
| 219 | `29.html` | `js/98-29.js` | tela | SK-Code Debugger — Verificar Código | — |
| 220 | `290.html` | `js/98-290.js` | tela | nova_ferramenta — Guia de Recuperação e Configuração do Projeto Maikon | — |
| 221 | `291.html` | `js/98-291.js` | tela | Auditoria Master - Dr. MAIKON DA ROCHA CALDEIRA — ⚖️ Auditoria Pericial | — |
| 222 | `292.html` | `js/98-292.js` | tela | Extrator de Texto Pro | — |
| 223 | `293.html` | `js/98-293.js` | tela | Monica Jurídico v7.0 - Comparador de Cenários (Perícia Bancária) | — |
| 224 | `294.html` | `js/98-294.js` | tela | A Oficina Digital do Mike da Galera — Oficina Digital:O Futuro do Direito | — |
| 225 | `295.html` | `js/98-295.js` | tela | Editor Jurídico Visual Law - Versão Final — Editor Jurídico Visual Law | — |
| 226 | `296.html` | `js/98-296.js` | tela | Calculadora Judicial Híbrida (Fixo vs Variável) — Calculadora Judicial Híbrida | — |
| 227 | `297.html` | `js/98-297.js` | tela | Calculadora Pericial: Sentença vs Contrato (Cartão/Taxa Média) | — |
| 228 | `298.html` | `js/98-298.js` | tela | Calculadora de Liquidação & Proveito Econômico — Calculadora de Liquidação & Sucumbência | — |
| 229 | `299.html` | `js/98-299.js` | tela | Painel – Flexibilização de Renda — MAIKON DA ROCHA CALDEIRA - OAB/MG 183.712 | — |
| 230 | `3.html` | `js/98-3.js` | tela | Conversor NPM → CDN — 📦 Conversor NPM → CDN | ${info.cdn_css}, ${info.cdn} |
| 231 | `30.html` | `js/98-30.js` | tela | Cirurgião de Código 3.0 — 🔬 CIRURGIÃO DE CÓDIGO 3.0 | — |
| 232 | `300.html` | `js/98-300.js` | tela | Rastreador de Histórico Replit — PWA Jurídico — 📜 Rastreador de Histórico Replit | — |
| 233 | `301.html` | `js/98-301.js` | tela | Calculadora Judicial Premium - Mike da Galera | — |
| 234 | `302.html` | `js/98-302.js` | tela | Leitor de Projeto — 🔍 Leitor de Projeto | — |
| 235 | `303.html` | `js/98-303.js` | tela | MANUAL (3) — SK Jurídico — Manual Completo | — |
| 236 | `304.html` | `js/98-304.js` | tela | Filtrador Avançado de Documentos Jurídicos — 🔧 Filtrador de Documentos | — |
| 237 | `305.html` | `js/98-305.js` | tela | 🔌 Testador de API — Com Proxy em Cascata — 🔌 Testador de API | — |
| 238 | `306.html` | `js/98-306.js` | tela | Editor HTML — Olá mundo! | — |
| 239 | `307.html` | `js/98-307.js` | tela | 🧩 Montador de Módulos — PWA Jurídico — 🧩 Montador de Módulos PWA JURÍDICO — MAIKON CALDE | — |
| 240 | `308.html` | `js/98-308.js` | tela | guia-completo-apk (2) — 📱 Guia Completo — Como Transformar Qualquer Projeto em APK | — |
| 241 | `309.html` | `js/98-309.js` | tela | 🔍 Scanner de Dependências — SK Editor — 🔍 Scanner de Dependências — SK Editor | — |
| 242 | `31.html` | `js/98-31.js` | tela | Navegador PWA com Proxys | — |
| 243 | `310.html` | `js/98-310.js` | tela | Extrator de Vínculos Previdenciários - Análise Processual — Extrator de Vínculos Previdenc | — |
| 244 | `311.html` | `js/98-311.js` | tela | Calculadora Jurídica - Juros e Correção — ⚖️ Calculadora Jurídica de Juros e Correção Mone | — |
| 245 | `312.html` | `js/98-312.js` | tela | Playground Code Pro — Maikon Caldeira — Bem-vindo ao Playground Pro | — |
| 246 | `313.html` | `js/98-313.js` | tela | Chat IA — Chat IA | — |
| 247 | `314.html` | `js/98-314.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 248 | `315.html` | `js/98-315.js` | tela | Filtrador Jurídico Avançado (Atualizado) — Filtrador Jurídico Avançado (Atualizado) | — |
| 249 | `316.html` | `js/98-316.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 250 | `317.html` | `js/98-317.js` | tela | Painel Maikon Caldeira — Advocacia Digital — 🔍 Analisador de Versões — PWA Jurídico | — |
| 251 | `318.html` | `js/98-318.js` | tela | RECEITA — 🧬 Receita para recriar: APK Builder | — |
| 252 | `319.html` | `js/98-319.js` | tela | Blocos de js/1.html.md.js — ✂️ js/1.html.md.js — 299 blocos | — |
| 253 | `32.html` | `js/98-32.js` | tela | Auditoria Financeira — Calculadora Sentença — Auditoria Financeira — Calculadora de Senten | — |
| 254 | `320.html` | `js/98-320.js` | tela | Gerador de APK — EAS Config — Gerador de Config EAS | — |
| 255 | `321.html` | `js/98-321.js` | tela | Análise: Terminal.tsx — 🔬 Terminal.tsx | — |
| 256 | `322.html` | `js/98-322.js` | tela | Análise: RealTerminal.tsx — 🔬 RealTerminal.tsx | — |
| 257 | `323.html` | `js/98-323.js` | tela | Análise: pwa.tsx — 🔬 pwa.tsx | — |
| 258 | `324.html` | `js/98-324.js` | tela | Análise: pacote-ia.txt.md — 🔬 pacote-ia.txt.md | — |
| 259 | `325.html` | `js/98-325.js` | tela | Análise: pacote-ia.txt.md — 🔬 pacote-ia.txt.md | — |
| 260 | `326.html` | `js/98-326.js` | tela | Análise: legal-assistant.tsx.recovered — 🔬 legal-assistant.tsx.recovered | — |
| 261 | `327.html` | `js/98-327.js` | tela | Análise: keys.tsx — 🔬 keys.tsx | — |
| 262 | `328.html` | `js/98-328.js` | tela | Análise: github.tsx — 🔬 github.tsx | — |
| 263 | `329.html` | `js/98-329.js` | tela | Análise: EditorLayout.tsx — 🔬 EditorLayout.tsx | — |
| 264 | `33.html` | `js/98-33.js` | tela | Assistente Jurídico | — |
| 265 | `330.html` | `js/98-330.js` | tela | Análise: DatabasePanel.tsx — 🔬 DatabasePanel.tsx | — |
| 266 | `331.html` | `js/98-331.js` | tela | Análise: App.tsx — 🔬 App.tsx | — |
| 267 | `332.html` | `js/98-332.js` | tela | Análise: App.tsx — 🔬 App.tsx | — |
| 268 | `334.html` | `js/98-334.js` | tela | Cartao de Perfil | — |
| 269 | `335.html` | `js/98-335.js` | tela | Importar TJMG | — |
| 270 | `336.html` | `js/98-336.js` | tela | Painel Estruturado - Embargos & Cotejo — Painel Estruturado - Embargos & Cotejo | — |
| 271 | `337.html` | `js/98-337.js` | tela | Leitor de CNIS - Visual | — |
| 272 | `338.html` | `js/98-338.js` | tela | Rural Adjair | — |
| 273 | `339.html` | `js/98-339.js` | tela | Calculadora de Honorários & Liquidação (Anual vs Mensal) — Calculadora Judicial & Honorári | — |
| 274 | `34.html` | `js/98-34.js` | tela | SK Editor Jurídico v2 - Seu Ambiente — 🔧 SK Editor Jurídico v2 | — |
| 275 | `340.html` | `js/98-340.js` | tela | manual-dev — Manual para Desenvolvedores — Correções Necessárias no App Mobile | — |
| 276 | `341.html` | `js/98-341.js` | tela | Sistema de Perícia Judicial Bancária - Dr. Manhumirim — JurisCalc Perícia Pro | — |
| 277 | `342.html` | `js/98-342.js` | tela | Extrator Jurídico - Contrato Falsificado (INSS/Estelionato) — Extrator Jurídico - Contrato | — |
| 278 | `343.html` | `js/98-343.js` | tela | Mike Legal AI - Importador Universal | — |
| 279 | `344.html` | `js/98-344.js` | tela | Code Merger Pro — Maikon Caldeira | — |
| 280 | `345.html` | `js/98-345.js` | tela | 🗄️ Painel de Banco de Dados | — |
| 281 | `346.html` | `js/98-346.js` | tela | Maikon Caldeira - Advocacia Digital — Maikon Caldeira | manifest.json, icon-192.png |
| 282 | `347.html` | `js/98-347.js` | tela | ⚡ Iara Suite — Code Editor · APK Builder · Site Extractor — Olá, Mundo! | — |
| 283 | `348.html` | `js/98-348.js` | tela | Exported HTML — PrevAnalítico Pro | — |
| 284 | `349.html` | `js/98-349.js` | tela | ObjectFactory (intercomunicacao 2.2.2 API) | stylesheet.css |
| 285 | `35.html` | `js/98-35.js` | tela | Playground Visual - Maikon Caldeira — 💻 Playground Visual - Maikon Caldeira | manifest.json, style.css, script.js |
| 286 | `350.html` | `js/98-350.js` | tela | Painel Maikon Caldeira — Advocacia Digital — 🔍 Analisador Automático + Debugger Visual | — |
| 287 | `351.html` | `js/98-351.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 288 | `352.html` | `js/98-352.js` | tela | Manual Completo — Extrator Jurídico + APK — Maikon Caldeira OAB/MG 183712 — Manual Complet | — |
| 289 | `353.html` | `js/98-353.js` | tela | Painel Maikon Caldeira — Advocacia Digital — 🚀 Analisador Inteligente de Projetos | — |
| 290 | `354.html` | `js/98-354.js` | tela | Comparador Jurídico Profissional v2.0 — Comparador Jurídico Profissional v2.0 | — |
| 291 | `355.html` | `js/98-355.js` | tela | Painel Maikon Caldeira — Advocacia Digital — 🔍 Leitor de Projeto | — |
| 292 | `356.html` | `js/98-356.js` | tela | Manual Iara Suite v2.0 — Maikon Caldeira OAB/MG 183712 — IARA SUITE v2.0 | — |
| 293 | `357.html` | `js/98-357.js` | tela | Análise: TerminalTab.tsx — 🔬 TerminalTab.tsx | — |
| 294 | `358.html` | `js/98-358.js` | tela | Meus Códigos Jurídicos — 📂 Meus Códigos Jurídicos | — |
| 295 | `359.html` | `js/98-359.js` | tela | Conversão TJMG → Padronizado | — |
| 296 | `36.html` | `js/98-36.js` | tela | Menu Principal — 🚀 Menu Principal | — |
| 297 | `360.html` | `js/98-360.js` | tela | Leitor Visual de CNIS — 📄 Importador Visual de CNIS | — |
| 298 | `361.html` | `js/98-361.js` | tela | Extrator Jurídico BPC/LOAS com OCR e Exportação — Extrator Jurídico BPC/LOAS com OCR e Exp | — |
| 299 | `362.html` | `js/98-362.js` | tela | Comparador Jurídico Multi-Cenário (Com Integração BCB) — Comparador Jurídico | — |
| 300 | `363.html` | `js/98-363.js` | tela | 🛠️ Ferramentas Jurídico BPC — ⚖️ Ferramentas BPC/LOAS TRF6 | — |
| 301 | `364.html` | `js/98-364.js` | tela | Filtrador de Documentos Jurídicos | — |
| 302 | `365.html` | `js/98-365.js` | tela | Laudo de Auditoria - Dr. Braulino | — |
| 303 | `366.html` | `js/98-366.js` | tela | Gerador de Cotejo Analítico - Exportável para Word | — |
| 304 | `367.html` | `js/98-367.js` | tela | Calculadora de Custos de IA Avançada — Calculadora de Custos de IA Avançada | — |
| 305 | `368.html` | `js/98-368.js` | tela | PWA Scanner ZIP Jurídico — 🔎 PWA Scanner ZIP Jurídico | — |
| 306 | `369.html` | `js/98-369.js` | tela | Calculadora Jurídica Definitiva - Dr. Manhumirim — Calculadora de Liquidação Comparativa | — |
| 307 | `37.html` | `js/98-37.js` | tela | Gerador de Ícone | — |
| 308 | `370.html` | `js/98-370.js` | tela | 🧩 Montador Multi-Projetos — PWA Jurídico — 🧩 Montador Multi-Projetos PWA JURÍDICO — MAIK | — |
| 309 | `371.html` | `js/98-371.js` | tela | Maikon Caldeira - Reconhecimentos Pretéritos | — |
| 310 | `372.html` | `js/98-372.js` | tela | Modelo Editável de Peça (TRF6/JEF) — Endereçamento, Qualificação, Fundamentos com Subtítul | — |
| 311 | `373.html` | `js/98-373.js` | tela | Comparador Jurídico Completo - TJMG + BCB — Comparador Jurídico Completo - TJMG + BCB | — |
| 312 | `374.html` | `js/98-374.js` | tela | Filtro Jurídico Inteligente - Estrutura de Peças — EMBARGOS DE DECLARAÇÃO | — |
| 313 | `375.html` | `js/98-375.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 314 | `376.html` | `js/98-376.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 315 | `378.html` | `js/98-378.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 316 | `379.html` | `js/98-379.js` | tela | Meu Projeto PWA | — |
| 317 | `38.html` | `js/98-38.js` | tela | Construtor Automático PWA - Maikon Caldeira — 🚀 Construtor Automático PWA | manifest.json, sw-register.js |
| 318 | `380.html` | `js/98-380.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 319 | `381.html` | `js/98-381.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 320 | `382.html` | `js/98-382.js` | tela | Assistente Jurídico Pro | — |
| 321 | `383.html` | `js/98-383.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 322 | `384.html` | `js/98-384.js` | tela | 📖 Gerador de Histórias com Voz — 📖✨ Gerador de Histórias com Sua Voz | — |
| 323 | `385.html` | `js/98-385.js` | tela | Gerador de package.json REAL - Só o que Funciona — ✅ Gerador de package.json REAL | — |
| 324 | `386.html` | `js/98-386.js` | tela | Cirurgião de Código 4.0 — 🩺 Cirurgião 4.0 | — |
| 325 | `387.html` | `js/98-387.js` | tela | analise_Terminal.tsx.md — analise_Terminal.tsx.md | virtual-fs |
| 326 | `388.html` | `js/98-388.js` | tela | Análise: legal-assistant.tsx — 🔬 legal-assistant.tsx | — |
| 327 | `389.html` | `js/98-389.js` | tela | Análise: desktop.ts — 🔬 desktop.ts | — |
| 328 | `39.html` | `js/98-39.js` | tela | Editor de Peças Jurídicas — Estrutura + Preview — Editor de Peças — estrutura + preview (a | — |
| 329 | `390.html` | `js/98-390.js` | tela | Análise: App.tsx — 🔬 App.tsx | — |
| 330 | `391.html` | `js/98-391.js` | tela | Análise: ApkAnalyzer.tsx — 🔬 ApkAnalyzer.tsx | — |
| 331 | `393.html` | `js/98-393.js` | tela | Comparador de Juros Simples e Compostos — Comparador de Juros Simples e Compostos | — |
| 332 | `394.html` | `js/98-394.js` | tela | PDJd Token COJEF Centro | — |
| 333 | `395.html` | `js/98-395.js` | tela | 🔑 PDJD Token Generator - Portal Jus.br — ⚖️ PDJD Token Generator - Portal Jus.br (CNJ) | — |
| 334 | `396.html` | `js/98-396.js` | tela | COMO_BUILDAR — Assistente Jurídico — Como Gerar o APK | — |
| 335 | `397.html` | `js/98-397.js` | tela | Filtrador Universal de Documentos | — |
| 336 | `398.html` | `js/98-398.js` | tela | Analisador de Versões PWA Jurídico — 🔍 Analisador de Versões — PWA Jurídico | — |
| 337 | `399.html` | `js/98-399.js` | tela | Adjair Tempo Especial | — |
| 338 | `4.html` | `js/98-4.js` | tela | Playground Visual — 🎮 Playground Visual | — |
| 339 | `40.html` | `js/98-40.js` | tela | Comparador Jurídico Multi-Cenário — Cartão/Empréstimo (BCB + TJMG) — Comparador Jurídico M | — |
| 340 | `400.html` | `js/98-400.js` | tela | Comparador Jurídico Master — Monica Especialista | — |
| 341 | `401.html` | `js/98-401.js` | tela | Painel – Flexibilização de Renda — MAIKON DA ROCHA CALDEIRA - OAB/MG 183.712 | — |
| 342 | `402.html` | `js/98-402.js` | tela | 🧩 Montador Multi-Projetos — PWA Jurídico — 🧩 Montador Multi-Projetos | — |
| 343 | `403.html` | `js/98-403.js` | tela | Painel de Confronto de Remunerações (CNIS/RAIS/CTC) — Painel de Confronto de Remunerações | — |
| 344 | `404.html` | `js/98-404.js` | tela | Gerenciador de Links - Maikon Caldeira — 🔗 Gerenciador de Links | — |
| 345 | `405.html` | `js/98-405.js` | tela | Analisador de Código Gigante — 🔍 Analisador de Código Gigante | — |
| 346 | `406.html` | `js/98-406.js` | tela | MANUAL (1) — Assistente Jurídico IA — Manual Completo | — |
| 347 | `407.html` | `js/98-407.js` | tela | Dashboard de Monitoramento - Projeto Jurídico — 📊 Dashboard de Monitoramento | — |
| 348 | `408.html` | `js/98-408.js` | tela | Filtrador Jurídico Avançado (Anti-repetição) — Filtrador Jurídico Avançado (Anti-repetição | — |
| 349 | `409.html` | `js/98-409.js` | tela | 🔍 Comparador de Projetos — 🔍 Comparador de Projetos | — |
| 350 | `41.html` | `js/98-41.js` | tela | 🔪 Fatiador de Código — 🔪 Fatiador de Código | — |
| 351 | `410.html` | `js/98-410.js` | tela | Painel Maikon Caldeira — Advocacia Digital — 📚 Gerador de Documentação Automática | — |
| 352 | `411.html` | `js/98-411.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 353 | `412.html` | `js/98-412.js` | tela | Analisador de Projetos + Gerador .EXE — 📦 Analisador de Projetos + Gerador de Executável | — |
| 354 | `414.html` | `js/98-414.js` | tela | Análise: TerminalTab.tsx — 🔬 TerminalTab.tsx | — |
| 355 | `415.html` | `js/98-415.js` | tela | analise_pacote-ia.txt.md.md — analise_pacote-ia.txt.md.md | app, logger, health, ai-chat |
| 356 | `416.html` | `js/98-416.js` | tela | Análise: EditorLayout.tsx — 🔬 EditorLayout.tsx | — |
| 357 | `417.html` | `js/98-417.js` | tela | Análise: eas.ts — 🔬 eas.ts | — |
| 358 | `418.html` | `js/98-418.js` | tela | Análise: archive.ts — 🔬 archive.ts | — |
| 359 | `419.html` | `js/98-419.js` | tela | Análise: archive.ts — 🔬 archive.ts | — |
| 360 | `42.html` | `js/98-42.js` | tela | Playground Supabase — Playground conectado ao Supabase | — |
| 361 | `420.html` | `js/98-420.js` | tela | analise_App.tsx.md — analise_App.tsx.md | desktop, Terminal, archive, android |
| 362 | `421.html` | `js/98-421.js` | tela | Validar JWT com Chave Pública PEM — 🔍 Validador JWT - Chave Pública PEM | — |
| 363 | `422.html` | `js/98-422.js` | tela | ' + nomeCompleto + ' — MAIKON CALDEIRA | manifest.json, icon-192.png |
| 364 | `423.html` | `js/98-423.js` | tela | Monica Assistente - Comparador de Cenários Judiciais — Comparador de Evolução de Dívida | — |
| 365 | `424.html` | `js/98-424.js` | tela | 🔑 JWT Generator PDJUD/PDPJ — ⚖️ JWT Generator - PDJUD/PDPJ Brasil | — |
| 366 | `425.html` | `js/98-425.js` | tela | Manual Básico: Variáveis de Ambiente e Chaves Secretas — Manual Básico: Variáveis de Ambie | — |
| 367 | `426.html` | `js/98-426.js` | tela | Manual 1 — Manual Básico: Variáveis de Ambiente e Chaves Secretas | — |
| 368 | `427.html` | `js/98-427.js` | tela | Gerador de Cotejo Analítico (BPC/LOAS) — Export Word/Excel/JSON | — |
| 369 | `428.html` | `js/98-428.js` | tela | SK Oficina Jurídica v6 - Analyzer + Injector | — |
| 370 | `429.html` | `js/98-429.js` | tela | Extrair Texto (PDF/TXT/Imagem/DOCX) — Extrator de Texto (PDF / TXT / Imagem / DOCX) | — |
| 371 | `43.html` | `js/98-43.js` | tela | Iara Suite — Editor — Iara Suite | — |
| 372 | `430.html` | `js/98-430.js` | tela | Filtrador Jurídico Completo (VIP + Word) — Filtrador Jurídico | — |
| 373 | `431.html` | `js/98-431.js` | tela | Filtrador Jurídico Avançado (Versão Mike) — Filtrador Jurídico Avançado ✓ Salvo | — |
| 374 | `432.html` | `js/98-432.js` | tela | Filtrador Genérico (Anti-repetição) — Jurídico — Filtrador genérico (anti-repetição) | — |
| 375 | `433.html` | `js/98-433.js` | tela | Leitor de Projeto PRO - Com Memória — 🔍 Leitor de Projeto PRO | — |
| 376 | `434.html` | `js/98-434.js` | tela | Extrator Jurídico - Processo Completo (Contrato Falsificado) — Extrator Jurídico - Process | — |
| 377 | `435.html` | `js/98-435.js` | tela | Comparador Jurídico — Correção + Juros (Simples/Compostos) por Competência — Comparador Ju | — |
| 378 | `436.html` | `js/98-436.js` | tela | 🔬 Cirurgião 3.0 — Scanner Inteligente — 🔬 Cirurgião 3.0 — Scanner Inteligente | — |
| 379 | `437.html` | `js/98-437.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 380 | `438.html` | `js/98-438.js` | tela | Playground IA — Saulo — Playground IA — Saulo | — |
| 381 | `439.html` | `js/98-439.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 382 | `44.html` | `js/98-44.js` | tela | Gerador de Estrutura - CORRIGIDO — 🗺️ Gerador de Estrutura - CORRIGIDO | — |
| 383 | `440.html` | `js/98-440.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 384 | `441.html` | `js/98-441.js` | tela | analise_settings.tsx.md — analise_settings.tsx.md | SystemStatus, AIMemoryModal, CheckpointsModal, ProjectOverviewModal |
| 385 | `442.html` | `js/98-442.js` | tela | Análise: Manual.tsx — 🔬 Manual.tsx | — |
| 386 | `443.html` | `js/98-443.js` | tela | analise_keys.tsx (3).md — analise_keys.tsx (3).md | ProjectContext, keyDetector, neon |
| 387 | `444.html` | `js/98-444.js` | tela | Análise: eas.ts — 🔬 eas.ts | — |
| 388 | `445.html` | `js/98-445.js` | tela | Análise: BuildPanel.tsx — 🔬 BuildPanel.tsx | — |
| 389 | `446.html` | `js/98-446.js` | tela | Análise: android.ts — 🔬 android.ts | — |
| 390 | `447.html` | `js/98-447.js` | tela | Analisador Local de Projetos — V2 — Analisador Local de Projetos — V2 | — |
| 391 | `448.html` | `js/98-448.js` | tela | Comparar custo IA: barato vs caro — Comparar custo de IA: modelo barato vs modelo caro | — |
| 392 | `449.html` | `js/98-449.js` | tela | Extrair Texto Completo | — |
| 393 | `45.html` | `js/98-45.js` | tela | 🐍 Python Explicado Visualmente — 🐍 Python Explicado Visualmente | — |
| 394 | `450.html` | `js/98-450.js` | tela | nova_ferramenta — Gerador de Arquivo .env | — |
| 395 | `451.html` | `js/98-451.js` | tela | nova_ferramenta | — |
| 396 | `452.html` | `js/98-452.js` | tela | Playground Pro - Maikon Caldeira | — |
| 397 | `453.html` | `js/98-453.js` | tela | Guia de recuperação  — Guia de Recuperação e Configuração do Projeto Maikon | — |
| 398 | `454.html` | `js/98-454.js` | tela | Limpador de Embargos (Anti-Repetição) — Limpador de Embargos & Extrator de Texto (Anti-Rep | — |
| 399 | `455.html` | `js/98-455.js` | tela | 🔐 JWT RS256 - Front-end — 🔐 JWT RS256 Generator | — |
| 400 | `456.html` | `js/98-456.js` | tela | Comparador Jurídico — TJMG + BCB — Premium — Comparador Jurídico — TJMG + BCB — Multi-Cená | — |
| 401 | `457.html` | `js/98-457.js` | tela | Extrator Jurídico - Contrato Falsificado (INSS/Estelionato) — Extrator Jurídico - Contrato | — |
| 402 | `458.html` | `js/98-458.js` | tela | Iara — Mapeador Visual | — |
| 403 | `459.html` | `js/98-459.js` | tela | Iara Dissecador — Extrator e Montador de Código — 🧩 Iara Dissecador — Extrator e Montador | — |
| 404 | `46.html` | `js/98-46.js` | tela | CodeLens | manifest.json, icon-192.png, config.js, auth.js |
| 405 | `460.html` | `js/98-460.js` | tela | Extrator Jurídico Avançado - Processo Completo com Links — Extrator Jurídico Avançado - Pr | — |
| 406 | `461.html` | `js/98-461.js` | tela | Analisador Automático + Debugger Visual — 🔍 Analisador Automático + Debugger Visual | — |
| 407 | `462.html` | `js/98-462.js` | tela | Comparador Jurídico — TJMG (Fator) + BCB (Juros) — Multi-Cenário — Comparador Jurídico — T | — |
| 408 | `463.html` | `js/98-463.js` | tela | Painel Maikon Caldeira — Advocacia Digital — 🔧 SK Editor Jurídico v2 | — |
| 409 | `464.html` | `js/98-464.js` | tela | Playground Code Pro + IA — Maikon Caldeira — Bem-vindo ao Playground Pro | — |
| 410 | `465.html` | `js/98-465.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 411 | `466.html` | `js/98-466.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 412 | `467.html` | `js/98-467.js` | tela | Explorador de Versões e Bugs - Replit/ZIP — 🔍 Explorador de Versões e Bugs | — |
| 413 | `468.html` | `js/98-468.js` | tela | Diagnóstico de Executável com Problema — 🔧 Diagnóstico de Executável com Problema | — |
| 414 | `469.html` | `js/98-469.js` | tela | Gerador Automático de package.json + Workflow — 📦 Gerador de package.json + Workflow Comp | — |
| 415 | `47.html` | `js/98-47.js` | tela | Navegador PWA | — |
| 416 | `470.html` | `js/98-470.js` | tela | Mini SK — 🔗 Meus Links | manifest.json, favicon.ico, icon.svg, apple-touch-icon.png |
| 417 | `471.html` | `js/98-471.js` | tela | Analisador de Código — 🔍 Analisador de Código | — |
| 418 | `472.html` | `js/98-472.js` | tela | 11 — 11 | — |
| 419 | `473.html` | `js/98-473.js` | tela | ai-studio-backup-2026-10-24-15-47 — Relatório — 📂 ai-studio-backup-2026-10-24-15-47 | — |
| 420 | `474.html` | `js/98-474.js` | tela | ai-studio-backup-2026-10-24-15-47 — Relatório — 📂 ai-studio-backup-2026-10-24-15-47 | — |
| 421 | `475.html` | `js/98-475.js` | tela | Analisador de Código — 🔍 Analisador de Código | — |
| 422 | `476.html` | `js/98-476.js` | tela | analise_legal-assistant.tsx.md — analise_legal-assistant.tsx.md | tiptap-editor, button, input, textarea |
| 423 | `478.html` | `js/98-478.js` | tela | cdns (1) | — |
| 424 | `479.html` | `js/98-479.js` | tela | Guia dos Apps do Maikon — Guia dos seus apps | — |
| 425 | `48.html` | `js/98-48.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 426 | `480.html` | `js/98-480.js` | tela | Blocos de colado.js — ✂️ colado.js — 48 blocos | — |
| 427 | `481.html` | `js/98-481.js` | tela | 🔬 Dissecador de Código — Iara Suite v2.0 — 🔬 Dissecador de Código — Iara Suite v2.0 | — |
| 428 | `482.html` | `js/98-482.js` | tela | SK Editor v3 | icon-192.png, manifest.webmanifest, main.tsx |
| 429 | `483.html` | `js/98-483.js` | tela | Meu App — Meu App | manifest.json, icon-192.png |
| 430 | `484.html` | `js/98-484.js` | tela | Instalador · Assistente Jurídico (no computador) — 📦 Assistente Jurídico (no computador) | — |
| 431 | `485.html` | `js/98-485.js` | tela | Instalador · Mini SK v09/10-b — 📦 Mini SK v09/10-b | — |
| 432 | `486.html` | `js/98-486.js` | tela | Instalador · Mini SK v15/10-a (site / celular / APK) — 📦 Mini SK v15/10-a (site / celular | — |
| 433 | `487.html` | `js/98-487.js` | tela | Laboratório do Modular — Laboratório do Modular | — |
| 434 | `488.html` | `js/98-488.js` | tela | Playground HTML — 🚀 Playground HTML | — |
| 435 | `489.html` | `js/98-489.js` | tela | RECEITA — 🧬 Receita para recriar: JurisPro | — |
| 436 | `49.html` | `js/98-49.js` | tela | SK Scanner v2 — SK Scanner v2 | — |
| 437 | `490.html` | `js/98-490.js` | tela | ⚖️ Cofre de Configurações — 🔐 Cofre de Configurações | — |
| 438 | `491.html` | `js/98-491.js` | tela | Fatiador Universal de Código — Fatiador Universal de Código | — |
| 439 | `492.html` | `js/98-492.js` | tela | Instalador · Caça-Bug — 📦 Caça-Bug | — |
| 440 | `493.html` | `js/98-493.js` | tela | Arquivos juntados — Arquivos juntados | — |
| 441 | `494.html` | `js/98-494.js` | tela | Laboratório HTML — Advocacia Previdenciária | — |
| 442 | `495.html` | `js/98-495.js` | tela | 📂 Leitor Universal de Arquivos — Leitor Universal de Arquivos | — |
| 443 | `496.html` | `js/98-496.js` | tela | PLANO — Plano do projeto: juridico | — |
| 444 | `497.html` | `js/98-497.js` | tela | Planos.md — Planos.md | — |
| 445 | `498.html` | `js/98-498.js` | tela | 📦 Project Manager Pro - Terminal & NPM — 🚀
            Project Manager Pro | — |
| 446 | `499.html` | `js/98-499.js` | tela | Sem título (1) — Bem-vindo ao HTML Playground | — |
| 447 | `5.html` | `js/98-5.js` | tela | Netlify Build + Testador API — 🚀 Netlify Build + Testador de API | — |
| 448 | `50.html` | `js/98-50.js` | tela | Relatório de metadados | — |
| 449 | `500.html` | `js/98-500.js` | tela | Manual do Maikon — 📘 Manual do Maikon | — |
| 450 | `51.html` | `js/98-51.js` | tela | RECEITA — 🧬 Receita para recriar: SK Jurídico — Assistente IA | — |
| 451 | `52.html` | `js/98-52.js` | tela | relatorio-AssistenteJuridico-PWA-8zip  714d7dd (3).md — relatorio-AssistenteJuridico-PWA-8 | — |
| 452 | `53.html` | `js/98-53.js` | tela | relatorio-AssistenteJuridico-PWA-8zip 1AssistenteJ.md — relatorio-AssistenteJuridico-PWA-8 | — |
| 453 | `54.html` | `js/98-54.js` | tela | 🔧 PWA Builder — Gerador de Instalação — 🔧 PWA Builder | manifest.json, icon-192.png |
| 454 | `55.html` | `js/98-55.js` | tela | PWA Jurídico — Maikon Caldeira | — |
| 455 | `56.html` | `js/98-56.js` | tela | 🧩 Montador Multi-Projetos — PWA Jurídico — 🧩 Montador Multi-Projetos PWA JURÍDICO — MAIK | — |
| 456 | `57.html` | `js/98-57.js` | tela | Live Code Runner | favicon.ico |
| 457 | `58.html` | `js/98-58.js` | tela | SK-Prompt Manager — Templates + Histórico | — |
| 458 | `59.html` | `js/98-59.js` | tela | Projeto Lab | — |
| 459 | `6.html` | `js/98-6.js` | tela | Gerenciador de Portas e Projetos — 🔧 Gerenciador de Projetos | — |
| 460 | `60.html` | `js/98-60.js` | tela | Chat IA Profissional | manifest.json, icon-192x192.png, config-manager.js, gerenciador-ia.js |
| 461 | `61.html` | `js/98-61.js` | tela | AI Code Studio — 🤖 AI Code Studio | — |
| 462 | `62.html` | `js/98-62.js` | tela | 🚀 Guia Interativo - Chat IA Profissional — 🚀 Chat IA Profissional v1.1 | — |
| 463 | `63.html` | `js/98-63.js` | tela | 🔧 ConstruAPK Pro — Analisador e Gerador — ConstruAPK Pro — Analisador & Gerador | — |
| 464 | `64.html` | `js/98-64.js` | tela | 📱 Gerador DevMobile EAS — 📱 Gerador EAS Build — Baseado no DevMobile | — |
| 465 | `65.html` | `js/98-65.js` | tela | 📦 Build & Deploy — Build & Deploy | manifest.json, icon-192.png, main.tsx |
| 466 | `66.html` | `js/98-66.js` | tela | Sistema Profissional - Modular — 📊 Sistema | manifest.json |
| 467 | `67.html` | `js/98-67.js` | tela | Gerador de Estrutura de Projeto — 🏗️ Gerador de Estrutura de Projeto | — |
| 468 | `68.html` | `js/98-68.js` | tela | Analisador de Projeto — 🔍 Analisador de Projeto | — |
| 469 | `69.html` | `js/98-69.js` | tela | Playground Code — Maikon Caldeira — Bem-vindo ao HTML Playground | — |
| 470 | `7.html` | `js/98-7.js` | tela | Corretor de Projetos — 🔧 Corretor de Projetos | — |
| 471 | `70.html` | `js/98-70.js` | tela | playground — 🚀 Playground | — |
| 472 | `71.html` | `js/98-71.js` | tela | Code Playground - HTML/CSS/JS/React/Python — Bem-vindo ao HTML Playground | — |
| 473 | `72.html` | `js/98-72.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 474 | `73.html` | `js/98-73.js` | tela | Playground — MeuIDE — 🚀 Playground | — |
| 475 | `74.html` | `js/98-74.js` | tela | Suite Jurídica + IA | manifest.json, icon-192.png |
| 476 | `75.html` | `js/98-75.js` | tela | plano-SK-Editor-v3-SemReplit-9-1790894751105.md — plano-SK-Editor-v3-SemReplit-9-179089475 | — |
| 477 | `77.html` | `js/98-77.js` | tela | Editor Visual — Bem-vindo! | — |
| 478 | `78.html` | `js/98-78.js` | tela | 🎨 Editor Visual - Funcional de Verdade | — |
| 479 | `79.html` | `js/98-79.js` | tela | 🐝 Editor Visual - Responsivo — 🐝 Editor Visual | — |
| 480 | `8.html` | `js/98-8.js` | tela | Guia do Terminal — 🖥️ Guia do Terminal & Python | — |
| 481 | `80.html` | `js/98-80.js` | tela | Editor Visual — 🎨 Editor Visual | — |
| 482 | `81.html` | `js/98-81.js` | tela | 🎨 Editor Visual - Funcional — 🎨 Editor Visual - Funcional | — |
| 483 | `82.html` | `js/98-82.js` | tela | 🎨 Editor Visual de Código — 🎨 Editor Visual de Código | — |
| 484 | `83.html` | `js/98-83.js` | tela | SK-HTML Magic Editor — Bem-vindo! | — |
| 485 | `84.html` | `js/98-84.js` | tela | SK-Build Guide — Entenda o Build | utils.js |
| 486 | `85.html` | `js/98-85.js` | tela | SK-Build Unpacker — Desempacotar Build | — |
| 487 | `86.html` | `js/98-86.js` | tela | Perito de Metadados — Perito de Metadados | — |
| 488 | `87.html` | `js/98-87.js` | tela | Parser Markdown - Gerador de Projetos — 🚀 Parser Markdown | — |
| 489 | `88.html` | `js/98-88.js` | tela | Painel Maikon Caldeira — Advocacia Digital — Maikon Caldeira | — |
| 490 | `89.html` | `js/98-89.js` | tela | Organizador de Documentos — 📑 Organizador de Documentos | — |
| 491 | `9.html` | `js/98-9.js` | tela | Leitor de Memória — 📖 Leitor de Memória | — |
| 492 | `90.html` | `js/98-90.js` | tela | Extrator Universal BPC/LOAS - Análise Processual — Extrator Universal BPC/LOAS | — |
| 493 | `91.html` | `js/98-91.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 494 | `92.html` | `js/98-92.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 495 | `93.html` | `js/98-93.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 496 | `94.html` | `js/98-94.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 497 | `95.html` | `js/98-95.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 498 | `96.html` | `js/98-96.js` | tela | Multi-Projetos PWA — Maikon Caldeira | — |
| 499 | `97.html` | `js/98-97.js` | tela | Code Merger Pro — Maikon Caldeira | — |
| 500 | `98.html` | `js/98-98.js` | tela | Build React - Executável Funcional — ⚛️ Build React - Executável Funcional | — |
| 501 | `99.html` | `js/98-99.js` | tela | 🏗️ Montador - Chat IA — 🏗️ Montador - Chat IA Profissional | — |
| 502 | `hub.html` | `js/98-hub.js` | tela | codigos-numerados-2026-10-26 (1) — codigos-numerados-2026-10-26 (1) | hub.webmanifest, favicon.ico, icon.svg, apple-touch-icon.png |
| 503 | `index.html` | `js/98-inicio.js` | tela | Maikon Caldeira — Aplicativos — MAIKON CALDEIRA | manifest.json, favicon.ico, icon.svg, apple-touch-icon.png |

## 4. Montar passo a passo (cada bloco é um pedido pronto: 📋 Copiar → colar na IA)

### Passo 0 — combinar as regras com a IA

```text
Vamos recriar o app "Maikon Caldeira — Aplicativos" como HTML MODULAR, que abre pelo index.html, sem servidor e sem nada da Replit.
Regras: (1) index.html chama os arquivos js/ na ordem, antes do </body>; (2) js/00-core.js cria window.APP com APP.registrar(modulo), APP.guardar(chave, valor) em IndexedDB/localStorage e APP.avisar(texto); (3) cada arquivo js/NN-nome.js cuida de UM assunto, começa com (function (APP) { e termina com })(window.APP); (4) js/99-app.js vem por último e monta a tela com os módulos registrados; (5) textos em português do Brasil.
Vou pedir UM arquivo por vez. Responda só com o arquivo completo, sem cortar nada. Primeiro: crie index.html, css/app.css e js/00-core.js.
```

### Passo 1 — `js/10-abrir.js` (era `exe/abrir.py`, 118 linhas)

```text
Crie js/10-abrir.js. Ele faz: -*- coding: utf-8 -*-.
No app original ele tinha estas funções/partes: Pagina, __init__, send_head, end_headers, log_message, ja_ligado, abrir_janela, main.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 2 — `js/15-112.js` (era `112.html`, 1023 linhas)

```text
Crie js/15-112.js. Ele faz: Raio-X de Projetos — Raio-X de Projetos.
No app original ele tinha estas funções/partes: extOf, isTextPath, stripRoot, newProject, addFile, countLines, projectFromZip, projectFromFolder, projectFromObject, isMap, isMinified, isBuildPath, scan, snippetAt, maskSecret, stripJsonComments, parseJsonLoose, dirOf.
O original usava as bibliotecas @neondatabase/serverless, express, @workspace/db, mammoth, react, vite, path, @replit/vite-plugin-runtime-error-modal: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
No original isto era SERVIDOR com as rotas GET /api/ementas, POST /api/ementas, POST /api/documentos, POST /api/importar, POST /api/ai/stream. Em HTML, troque por funções que guardam no aparelho (APP.guardar) ou que chamam a IA direto.
Ele chamava estes endereços: /api/documentos, /api/ementas/${id}, /api/export/docx, /api/ai/stream. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 3 — `js/20-122.js` (era `122.html`, 443 linhas)

```text
Crie js/20-122.js. Ele faz: 🔗 Teste APK + Termux — 🔗 Teste APK ↔ Termux.
No app original ele tinha estas funções/partes: addLog, setStatus, showResult, testarConexaoSimples, testarConexaoComDados, testarComandoTermux, testarMultiplas, limparLogs.
O original usava as bibliotecas express: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
No original isto era SERVIDOR com as rotas GET /teste, POST /dados, GET /comando. Em HTML, troque por funções que guardam no aparelho (APP.guardar) ou que chamam a IA direto.
Ele chamava estes endereços: http://localhost:8080/teste, http://localhost:8080/dados, http://localhost:8080/comando. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 4 — `js/25-211.js` (era `211.html`, 107 linhas)

```text
Crie js/25-211.js. Ele faz: Análise: snippets.ts — 🔬 snippets.ts.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 5 — `js/30-266.js` (era `266.html`, 3468 linhas)

```text
Crie js/30-266.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: mostrarToast, mudarAba, mostrarHistorico, fecharModal, API, Auth, carregarTemplate, gerarCodigoCustom, exemplo, corrigirCodigo, refatorarCodigo, validarCodigo, formatarCodigo, analisarCodigo, salvarArquivo, salvarHistorico, carregarHistorico, renderizarHistorico.
O original usava as bibliotecas express: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
No original isto era SERVIDOR com as rotas GET /api/data. Em HTML, troque por funções que guardam no aparelho (APP.guardar) ou que chamam a IA direto.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 6 — `js/35-278.js` (era `278.html`, 376 linhas)

```text
Crie js/35-278.js. Ele faz: Análise: workspace.ts — 🔬 workspace.ts.
No app original ele tinha estas funções/partes: ensureWorkspace, walk.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 7 — `js/40-333.js` (era `333.html`, 2734 linhas)

```text
Crie js/40-333.js. Ele faz: Análise: AIChat.tsx — 🔬 AIChat.tsx.
No app original ele tinha estas funções/partes: CopyBtn, MdCodeBlock, makeMdComponents, VoicePicker, EmptyChatState, MessageBubble, AIChat, initDb.
O original usava as bibliotecas @neondatabase/serverless, @supabase/supabase-js, dotenv, pg, better-sqlite3, mysql2: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
No original isto era SERVIDOR com as rotas GET /api/processos. Em HTML, troque por funções que guardam no aparelho (APP.guardar) ou que chamam a IA direto.
Ele chamava estes endereços: ${API_BASE_VOICE}/voice/speak, /api/search?q=${encodeURIComponent(q)}. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 8 — `js/45-377.js` (era `377.html`, 5874 linhas)

```text
Crie js/45-377.js. Ele faz: Painel Maikon Caldeira — Advocacia Digital — 🔧 PWA Analyzer - Detector Inteligente.
No app original ele tinha estas funções/partes: mostrarToast, mostrarModal, fecharModal, mudarAba, atualizarConfigIA, salvarConfigIA, carregarConfigIA, testarConexaoIA, chamarIA, carregarProjeto, processarZIP, processarTAR, processarHTML, ehTexto, detectarAPIs, analisarAPIsComIA, detectarBugs, analisarBugsComIA.
O original usava as bibliotecas express: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
No original isto era SERVIDOR com as rotas GET /api/data. Em HTML, troque por funções que guardam no aparelho (APP.guardar) ou que chamam a IA direto.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 9 — `js/50-392.js` (era `392.html`, 2734 linhas)

```text
Crie js/50-392.js. Ele faz: Análise: AIChat.tsx — 🔬 AIChat.tsx.
No app original ele tinha estas funções/partes: CopyBtn, MdCodeBlock, makeMdComponents, VoicePicker, EmptyChatState, MessageBubble, AIChat, initDb.
O original usava as bibliotecas @neondatabase/serverless, @supabase/supabase-js, dotenv, pg, better-sqlite3, mysql2: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
No original isto era SERVIDOR com as rotas GET /api/processos. Em HTML, troque por funções que guardam no aparelho (APP.guardar) ou que chamam a IA direto.
Ele chamava estes endereços: ${API_BASE_VOICE}/voice/speak, /api/search?q=${encodeURIComponent(q)}. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 10 — `js/55-413.js` (era `413.html`, 2821 linhas)

```text
Crie js/55-413.js. Ele faz: Blocos de assets/app (cópia).js — ✂️ assets/app (cópia).js — 1 blocos.
No app original ele tinha estas funções/partes: which.
Ele chamava estes endereços: https://api.github.com/repos/${t}/${r}/contents/${n}, https://api.github.com/repos/${t}/${r}/contents/${h}, ${mM}/voice/speak, ${Cr}/voice/speak, /api/search?q=${encodeURIComponent(pe)}, https://registry.npmjs.org/-/v1/search?text=${encodeURIComponent(K)}&amp;size=20, https://registry.npmjs.org/${encodeURIComponent(M)}/latest, ${Pf}/drive/list, ${Pf}/drive/upload, ${Pf}/drive/delete/${I}, ${V}/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 11 — `js/60-477.js` (era `477.html`, 1422 linhas)

```text
Crie js/60-477.js. Ele faz: Markdown — Pacote do projeto &quot;artifacts6&quot; para a IA.
No app original ele tinha estas funções/partes: App, getCohortColor, EngagementSection, KPIHeader, RevenueSection, UsersSection, Badge, ButtonGroup, ButtonGroupText, ButtonGroupSeparator, Calendar, CalendarDayButton, useCarousel, useChart, getPayloadConfigFromPayload, Empty, EmptyHeader, EmptyMedia.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 12 — `js/65-76.js` (era `76.html`, 16089 linhas)

```text
Crie js/65-76.js. Ele faz: PLANO_RECUPERACAO.md — PLANO_RECUPERACAO.md.
No app original ele tinha estas funções/partes: getInstallScope, App.
O original usava as bibliotecas @workspace/sync-storage: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
No original isto era SERVIDOR com as rotas GET /nova-rota. Em HTML, troque por funções que guardam no aparelho (APP.guardar) ou que chamam a IA direto.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 13 — `js/70-1.js` (era `1.html`, 404 linhas)

```text
Crie js/70-1.js. Ele faz: Arrumador de Backups — 🗃 Arrumador de Backups.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 14 — `js/75-10.js` (era `10.html`, 32 linhas)

```text
Crie js/75-10.js. Ele faz: Meu Projeto — Meu Projeto.
No app original ele tinha estas funções/partes: App.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 15 — `js/80-100.js` (era `100.html`, 523 linhas)

```text
Crie js/80-100.js. Ele faz: ⚙️ Replit Config Manager — ⚙️ Replit Config Manager.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 16 — `js/85-101.js` (era `101.html`, 315 linhas)

```text
Crie js/85-101.js. Ele faz: 🧹 Project Cleaner — 🧹 Project Cleaner + Generator.
No app original ele tinha estas funções/partes: log, status, analyzeProject, startAnalysis, cleanProject, generateFiles.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 17 — `js/90-102.js` (era `102.html`, 298 linhas)

```text
Crie js/90-102.js. Ele faz: Iara Mapper Pro - Final — 🚀 Iara Mapper Pro.
No app original ele tinha estas funções/partes: obterLinguagem, atualizarListaArquivos, selecionarArquivo, limparTudo, toggleSidebar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 18 — `js/91-103.js` (era `103.html`, 906 linhas)

```text
Crie js/91-103.js. Ele faz: SK-Code Editor Functions Explained.
No app original ele tinha estas funções/partes: toggleSidebar, setPM, togglePreviewMin, startVDrag, onVDrag, stopVDrag, mTab, initTabs, loadTopic.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 19 — `js/92-104.js` (era `104.html`, 1023 linhas)

```text
Crie js/92-104.js. Ele faz: SK-Details & Summary — Expandir/Colapsar.
No app original ele tinha estas funções/partes: loadTopic.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 20 — `js/93-105.js` (era `105.html`, 862 linhas)

```text
Crie js/93-105.js. Ele faz: SK-Iara Suite Checker.
No app original ele tinha estas funções/partes: qsa, lsSet, esc, evPrevent, getExt, DETECT, loadCheck.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 21 — `js/94-106.js` (era `106.html`, 168 linhas)

```text
Crie js/94-106.js. Ele faz: Editor com Busca - Dr. Maikon.
No app original ele tinha estas funções/partes: abrirArquivo, salvarArquivo, buscarProximo, substituir.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 22 — `js/95-107.js` (era `107.html`, 801 linhas)

```text
Crie js/95-107.js. Ele faz: Iara Mapper Pro.
No app original ele tinha estas funções/partes: esc, toast, setStatus, getExt, getLang, getIcon, fmtSize, countLines, detectEncoding, readFileAsText, readFileAsArrayBuffer, processarZIP, handleImport, renderSidebar, selectFile, updateLineNumbers, syncScroll, updateInfoPanel.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 23 — `js/96-108.js` (era `108.html`, 1680 linhas)

```text
Crie js/96-108.js. Ele faz: Analisador de Projetos — 🔍 Analisador.
No app original ele tinha estas funções/partes: setupEventListeners, mudarPagina, carregarPagina, renderUpload, renderAnalise, renderEstrutura, renderTerminal, renderExportar, processarArquivos, processarArquivoSimples, processarZip, adicionarCodigoColado, analisarProjeto, gerarEstrutura, gerarComandosTerminal, exportarZip, exportarMarkdown, exportarJSON.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 24 — `js/97-109.js` (era `109.html`, 779 linhas)

```text
Crie js/97-109.js. Ele faz: Visualizador de Markdown — Visualizador de Markdown.
No app original ele tinha estas funções/partes: loadFile, readFile, render, buildTOC, bindCodeCopies, copySection, copySectionMD, extractText, extractMarkdownSection, exportHTML, toggleSearch, clearSearch, doSearch, walkAndHighlight, searchKey, toggleTOC, escapeHTML, escapeAttr.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 25 — `js/98-11.js` (era `11.html`, 933 linhas)

```text
Crie js/98-11.js. Ele faz: Validador de Código + Testador de API — 🧪 Validador de Código + Testador de API.
No app original ele tinha estas funções/partes: handleFile, validateCode, detectAPIs, displayResults, switchTab, openApiTest, testAPI, analyzeResponse, closeApiModal, escapeHtml.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 26 — `js/98-110.js` (era `110.html`, 865 linhas)

```text
Crie js/98-110.js. Ele faz: Iara 2.0 - Mapeador Profissional de Dependências — 🕸️ Iara 2.0 — Mapeador Profissional.
No app original ele tinha estas funções/partes: resizeCanvas, loadFiles, loadZip, loadTarGz, loadTar, isCodeFile, addFile, finishLoading, parseImports, resolveImportedBy, resolveImport, detectCycles, dfs, buildNodes, layoutGraph, simulateForce, draw, drawEdge.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 27 — `js/98-111.js` (era `111.html`, 404 linhas)

```text
Crie js/98-111.js. Ele faz: 🧹 Limpador de Replit — 🧹 Limpador de Vínculos Replit.
No app original ele tinha estas funções/partes: processarZip, limparArquivo, baixarZipLimpo, log, mostrarLog, atualizarEstatisticas.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 28 — `js/98-113.js` (era `113.html`, 1004 linhas)

```text
Crie js/98-113.js. Ele faz: Gerador de Ícones PRO - Maikon Caldeira — 🎨 Gerador de Ícones PRO.
No app original ele tinha estas funções/partes: mudarTab, mudarForma, aplicarCor, aplicarGradiente, atualizarGradientePreview, gerarIcone, desenharIcone, baixarIcone, baixarTodos, limpar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 29 — `js/98-114.js` (era `114.html`, 3749 linhas)

```text
Crie js/98-114.js. Ele faz: PWA Jurídico — Maikon Caldeira — Filtrador Jurídico Avançado (Atualizado).
No app original ele tinha estas funções/partes: loadState, saveState, setStatus, download, enviarParaNuvem, cleanMarkdownNoise, splitParagraphs, normalizeForCompare, makeShingles, signature, jaccard, parseLines, buildRegexList, extractTextFromPDF, extractTextFromDOCX, extractTextFromJSON, walk, applyBanRules.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 30 — `js/98-115.js` (era `115.html`, 180 linhas)

```text
Crie js/98-115.js. Ele faz: Teste Diff (Estático).
No app original ele tinha estas funções/partes: log, rebuildButtons.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 31 — `js/98-116.js` (era `116.html`, 80 linhas)

```text
Crie js/98-116.js. Ele faz: Diff Simple Test.
No app original ele tinha estas funções/partes: log.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 32 — `js/98-117.js` (era `117.html`, 74 linhas)

```text
Crie js/98-117.js. Ele faz: projeto.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 33 — `js/98-118.js` (era `118.html`, 221 linhas)

```text
Crie js/98-118.js. Ele faz: Analisador e Reparador PWA -> APK — 🛠️ Reparador PWA para APK.
No app original ele tinha estas funções/partes: analyzeFiles, fixAll, downloadZip.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 34 — `js/98-119.js` (era `119.html`, 1383 linhas)

```text
Crie js/98-119.js. Ele faz: 🔍 Analisador de Projetos — Analisador de Projetos — Detector de Problemas.
No app original ele tinha estas funções/partes: showTab, analisar, analisarMulti, detectarArquivos, extrairBlocos, tentarParse, identificarTipo, detectarTipoTexto, processarResultados, analisarArquivo, detectarReferenciasReplit, renderCard, toggleCard, renderCorrigidos, gerarAppJsonCorrigido, gerarPackageJsonMobileCorrigido, gerarEasJsonCorrigido, gerarTsconfigCorrigido.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 35 — `js/98-12.js` (era `12.html`, 1555 linhas)

```text
Crie js/98-12.js. Ele faz: Triagem de Código — Triagem de Código.
No app original ele tinha estas funções/partes: renderLista, abrirConversa, conversaAtiva, renderMensagens, enviarMensagem, formatarHora, salvar, extOf, normPath, findPaths, compatible, sniffType, looksWindows, extForType, fnNames, computeSig, jaccard, speakerOf.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 36 — `js/98-120.js` (era `120.html`, 972 linhas)

```text
Crie js/98-120.js. Ele faz: VOXIS — Assistente Pessoal — 🎙️ Estúdio de Voz.
No app original ele tinha estas funções/partes: switchTab, updateTimer, startRecording, stopRecording, saveRecording, renderRecordings, deleteRecording, drawVisualizer, draw, clearCanvas, loadVoices, applyEffect, speak, stopSpeak.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 37 — `js/98-121.js` (era `121.html`, 993 linhas)

```text
Crie js/98-121.js. Ele faz: 📱 Gerador EAS Build — 📱 Gerador de Configuração EAS Build.
No app original ele tinha estas funções/partes: switchTab, autoId, atualizar, importarProjeto, preencherDados, gerarTudo, renderArquivos, copiar, exportarZip, fileIcon, esc, escHtml, loadJSZ.
O original usava as bibliotecas @capacitor/cli: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 38 — `js/98-123.js` (era `123.html`, 1090 linhas)

```text
Crie js/98-123.js. Ele faz: Analisador de Logs GitHub Actions — 🔍 Analisador de Logs GitHub Actions.
No app original ele tinha estas funções/partes: carregarMemoria, salvarNaMemoria, atualizarListaMemoria, carregarDaMemoria, limparMemoria, analisarLog, analisarTexto, extrairTitulo, detectarProblemasComuns, exibirResultados, mudarAba, limparTudo, baixarRelatorioJSON, baixarRelatorioCSV, baixarRelatorioPDF.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 39 — `js/98-124.js` (era `124.html`, 496 linhas)

```text
Crie js/98-124.js. Ele faz: Replicador de Projeto — ⚡ Replicador de Projeto.
No app original ele tinha estas funções/partes: run, analyze, detectRoot, detectTechs, detectType, renderProjectType, renderDeps, renderPackageJson, renderCommands, renderTree, print, copyText, downloadText, toast.
Ele chamava estes endereços: https://registry.npmjs.org/${encodeURIComponent(pkg)}/latest. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 40 — `js/98-125.js` (era `125.html`, 165 linhas)

```text
Crie js/98-125.js. Ele faz: Editor Visual — 🐝 Editor Visual.
No app original ele tinha estas funções/partes: setStatus, toggleCodigo, toggleProps, salvar, colar, importar, lerArquivo, renderizar, prepararClique, montarProps, editarTexto, editarEstilo, duplicar, remover, sincronizar, copiar, baixar, desfazer.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 41 — `js/98-126.js` (era `126.html`, 654 linhas)

```text
Crie js/98-126.js. Ele faz: 🐝 Editor Visual - Responsivo — 🐝 Editor Visual.
No app original ele tinha estas funções/partes: setStatus, togglePainelCodigo, togglePainelProps, salvarEstado, colarDaAreaTransferencia, abrirImportador, importarArquivo, renderizarCodigo, prepararCliqueVisual, podeSelecionar, selecionarElemento, montarPainel, editarTexto, editarEstilo, duplicarElemento, removerElemento, sincronizar, copiarCodigo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 42 — `js/98-127.js` (era `127.html`, 813 linhas)

```text
Crie js/98-127.js. Ele faz: Editor Visual HTML - Tipo Firebug Simples — 🐝 Editor Visual HTML.
No app original ele tinha estas funções/partes: setStatus, salvarEstado, colarDaAreaTransferencia, abrirImportador, importarArquivo, renderizarCodigo, prepararCliqueVisual, podeSelecionar, selecionarElemento, montarPainel, editarTexto, editarAtributo, editarClasse, editarEstilo, duplicarElemento, removerElemento, sincronizarCodigoDoIframe, copiarCodigo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 43 — `js/98-128.js` (era `128.html`, 825 linhas)

```text
Crie js/98-128.js. Ele faz: SK-Code Analyzer — Mapear Dependências.
No app original ele tinha estas funções/partes: extractImports, getFileExtension, handleZipUpload, handlePasteCode, buildDependencyGraph, filterFiles, renderFilesList, selectFile, renderGraph, highlightInGraph, renderDetails, downloadFile, exportAnalysis, openPasteModal, closePasteModal, clearAll.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 44 — `js/98-129.js` (era `129.html`, 603 linhas)

```text
Crie js/98-129.js. Ele faz: SK-Code Formatter — Organize seu Código.
No app original ele tinha estas funções/partes: formatCode, formatHTML, formatJSON, formatCSS, formatJavaScript, indentCode, sortCSSProperties, displayOutput, updateStats, escapeHtml, updateOptions, handleFileImport, pasteCode, clearInput, copyOutput, downloadFormatted.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 45 — `js/98-13.js` (era `13.html`, 150 linhas)

```text
Crie js/98-13.js. Ele faz: Teste — Teste.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 46 — `js/98-130.js` (era `130.html`, 1113 linhas)

```text
Crie js/98-130.js. Ele faz: Perito de Metadados — Perito de Metadados.
No app original ele tinha estas funções/partes: EMBUTIDO, esc, latin1, deLatin1, juntar, utf8, decTexto, tamanhoTxt, sha256js, sha256, inflar, inflarZlib, mkData, dataPdf, dataExif, dataIso, difTxt, num.
Ele chamava estes endereços: https://nominatim.openstreetmap.org/search?format=json&limit=1&countrycodes=br&q=. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 47 — `js/98-131.js` (era `131.html`, 1999 linhas)

```text
Crie js/98-131.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: showTab, loadZip, loadFromGitHub, processZip, renderFileList, openFile, filterFiles, openPreview, generateBrain, generateProjectPlan, runDiagnosis, saveToken, nome, limpar, carregarArquivo, analisarTextoColado, analisarCodigo, tentarOrganizarCodigo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 48 — `js/98-132.js` (era `132.html`, 1313 linhas)

```text
Crie js/98-132.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: updateCount, importFile, saveFile, downloadFile, togglePreview, updatePreview, openFullscreen, closeFullscreen, openApiModal, closeApiModal, saveApiKey, addMsg, sendMessage, updateModelLabel, handleKey, showLoading, hideLoading, callGemini.
Ele chamava estes endereços: https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash:generateContent?key=${apiKey}, https://api.openai.com/v1/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 49 — `js/98-133.js` (era `133.html`, 1953 linhas)

```text
Crie js/98-133.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: processarZip, limparArquivo, baixarZipLimpo, log, mostrarLog, atualizarEstatisticas, carregarProjeto, carregarZIP, mostrarInfo, verificarBotaoComparar, compararProjetos, realizarComparacao, compararArquivos, mostrarResultado, mostrarResumo, mostrarArquivos, verArquivo, gerarSugestoes.
O original usava as bibliotecas vite, @vitejs/plugin-react: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 50 — `js/98-134.js` (era `134.html`, 4971 linhas)

```text
Crie js/98-134.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: App, init, loadState, saveState, setupEventListeners, switchMode, switchTab, updateTabVisibility, updateEditors, updateLineNumbers, highlightSearchResults, updatePreview, buildHtmlDocument, buildReactDocument, runPython, handleFileImport, openFullscreen, copyCode.
Ele chamava estes endereços: /api/code/run, https://api.openai.com/v1/chat/completions, https://api.anthropic.com/v1/messages, https://generativelanguage.googleapis.com/v1beta/models/${model}:generateContent?key=${apiKey}, https://api.groq.com/openai/v1/chat/completions, https://openrouter.ai/api/v1/chat/completions, ${url}/api/chat, https://google.serper.dev/search. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 51 — `js/98-135.js` (era `135.html`, 406 linhas)

```text
Crie js/98-135.js. Ele faz: 📱 APK Builder - EAS — 📱 APK Builder - EAS.
No app original ele tinha estas funções/partes: switchTab, log, status, generateAPK, publishPages, createRepository, clearForm.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 52 — `js/98-136.js` (era `136.html`, 797 linhas)

```text
Crie js/98-136.js. Ele faz: 🚀 Setup Dashboard - Monorepo — 🚀 Setup Dashboard.
No app original ele tinha estas funções/partes: addTerminalLine, clearTerminal, copyCommand, copyAllCommands, showModal, closeModal, confirmAction, setupProject, startProject, buildExe, setupAll, buildAll.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 53 — `js/98-137.js` (era `137.html`, 1026 linhas)

```text
Crie js/98-137.js. Ele faz: 🛠️ Workstation Completa — Maikon Caldeira.
No app original ele tinha estas funções/partes: getModulos, setModulos, getSelected, setSelected, trocarAba, analisarCodigo, extrairFuncoes, encontrarFimFuncao, extrairEstilos, extrairElementos, extrairScripts, renderAnalise, extrairTudo, copiarParaPlayground, salvarComoModulo, salvarModulo, limparModulo, renderModulos.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 54 — `js/98-138.js` (era `138.html`, 16 linhas)

```text
Crie js/98-138.js. Ele faz: modulo 2 — Meu PWA Jurídico.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 55 — `js/98-139.js` (era `139.html`, 316 linhas)

```text
Crie js/98-139.js. Ele faz: IARA Suite — Importador & Editor Completo.
No app original ele tinha estas funções/partes: showToast, showModal, closeModal, triggerFileUpload, handleZipUpload, renderFileTree, openFile, updateLineNumbers, updateFileTreeSelection, searchInCode, highlightMatch, changeEncoding, exportFile, clearAll.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 56 — `js/98-14.js` (era `14.html`, 779 linhas)

```text
Crie js/98-14.js. Ele faz: SK Mini Editor — SK Mini Editor.
No app original ele tinha estas funções/partes: extractYouTubeID, getYouTubeEmbed, getFileIcon, renderTree, toggleFolder, addFile, selectFile, renderTabs, closeTab, updateFile, updatePreview, showCodePreview, teste.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 57 — `js/98-140.js` (era `140.html`, 329 linhas)

```text
Crie js/98-140.js. Ele faz: Comparar Código.
No app original ele tinha estas funções/partes: updateLN, syncLN, onEditorChange, doSearch, renderResults, goToMatch, nextMatch, prevMatch, clearAll, copyEditor, downloadCode, copyLine, setStatus, toast, escHtml, escAttr.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 58 — `js/98-141.js` (era `141.html`, 835 linhas)

```text
Crie js/98-141.js. Ele faz: SK-Docs Hub PT — Documentação em Português — Título.
No app original ele tinha estas funções/partes: minhaFuncao, search, filterByType, renderResults, selectDoc, renderContent, copyExample, copyContent, clearSearch, escapeHtml.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 59 — `js/98-142.js` (era `142.html`, 334 linhas)

```text
Crie js/98-142.js. Ele faz: Code Debugger — Dr. Maikon Caldeira.
No app original ele tinha estas funções/partes: qsa, toast, handleFileUpload, updateLineNumbers, performSearch, renderResults, selectResult, copyToClipboard, escapeHtml, toggleFilter, clearSearch.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 60 — `js/98-143.js` (era `143.html`, 954 linhas)

```text
Crie js/98-143.js. Ele faz: Iara Mapper Pro — Dr. Maikon Caldeira.
No app original ele tinha estas funções/partes: qsa, toast, getExt, detectLang, detectEncoding, updateLineNums, syncScroll, handleFileUpload, handleSingleFile, handleZip, renderFilesList, selectFile, updateInfo, updatePreview, toggleSidebar, toggleBottom, clearAll, exportFile.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 61 — `js/98-144.js` (era `144.html`, 2422 linhas)

```text
Crie js/98-144.js. Ele faz: Meu Projeto PWA — 🔍 Leitor de Projeto PRO.
No app original ele tinha estas funções/partes: lerArquivo, analisarCodigo, analisarFuncoes, analisarHTML, analisarCSS, pegarCorpo, isCerebro, isImportante, explicarFuncao, explicarHTML, explicarCSS, renderizarElementos, toggleCorpo, copiar, copiarTudo, filtrar, filtrarBusca, salvarNaMemoria.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 62 — `js/98-145.js` (era `145.html`, 174 linhas)

```text
Crie js/98-145.js. Ele faz: manual-dev (1) — Manual para Desenvolvedores — Correções Necessárias no App Mobile.
No app original ele tinha estas funções/partes: clonarRepositorio, construirArvore, ordenarFilhos, executarComandoOffline, syncTudo, syncArquivoAtivo, marca, copiar.
Ele chamava estes endereços: https://api.github.com/repos/${owner}/${repo}/git/trees/${branch}?recursive=1, https://api.github.com/repos/${owner}/${repo}/contents/${arquivo.path}?ref=${branch}, /api/sync, /api/workspace/write. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 63 — `js/98-146.js` (era `146.html`, 35 linhas)

```text
Crie js/98-146.js. Ele faz: Auditoria Financeira - Assistente Jurídico — 📊 Auditoria Financeira.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 64 — `js/98-147.js` (era `147.html`, 24 linhas)

```text
Crie js/98-147.js. Ele faz: HTML Playground - Editor de Codigo ao Vivo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 65 — `js/98-148.js` (era `148.html`, 259 linhas)

```text
Crie js/98-148.js. Ele faz: Auditoria Master - Dr. MAIKON DA ROCHA CALDEIRA — ⚖️ Auditoria Pericial.
No app original ele tinha estas funções/partes: buscarBCB, parseTJMG, getPrevKey, processarAuditoria.
Ele chamava estes endereços: https://api.bcb.gov.br/dados/serie/bcdata.sgs.${s}/dados?formato=json. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 66 — `js/98-149.js` (era `149.html`, 654 linhas)

```text
Crie js/98-149.js. Ele faz: Limpador de Processos — Limpador de Processos.
No app original ele tinha estas funções/partes: esc, fmt, linhasDaPagina, lerPdf, lerTxt, progresso, adicionar, regrasAtivas, minhasRegras, normLinha, acharRepetidas, limparPagina, processar, montarRegras, montarRepetidas, aplicar, faixas, verPagina.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 67 — `js/98-15.js` (era `15.html`, 1203 linhas)

```text
Crie js/98-15.js. Ele faz: SK Mini Editor - Guia de Instalação Interativo — SK Mini Editor.
No app original ele tinha estas funções/partes: MiniVFS, sort, MiniFileTree, MiniEditor, close, showStep, nextStep, previousStep, updateStep, updateProgressBar, copyCode.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 68 — `js/98-150.js` (era `150.html`, 502 linhas)

```text
Crie js/98-150.js. Ele faz: Painel Maikon Caldeira - Advogado — Maikon Caldeira.
No app original ele tinha estas funções/partes: renderizarApps, abrirModal, fecharModal, limparFormulario, adicionarApp, gerarManifest, gerarServiceWorker, baixarArquivo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 69 — `js/98-151.js` (era `151.html`, 1295 linhas)

```text
Crie js/98-151.js. Ele faz: Iara Suite v2.0 - Editor + Mapper Avançado — 🚀 Iara Suite v2.0.
No app original ele tinha estas funções/partes: init, saveToStorage, loadFromStorage, saveAPIConfig, loadAPIConfig, switchTab, newFile, newFolder, loadFile, saveFile, renameFile, deleteFile, renderFileTree, togglePreview, updatePreview, downloadAsMarkdown, copyToClipboard, exportProject.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 70 — `js/98-152.js` (era `152.html`, 572 linhas)

```text
Crie js/98-152.js. Ele faz: ⚖️ Robô Jurídico — ⚖️ Robô Jurídico.
No app original ele tinha estas funções/partes: carregarVozes, frasAleatoria, roboFala, falarTTS, alternarFala, adicionarMensagem, enviarMensagem, processarEntrada, atualizarHumor, setStatus, teclaEnter, alternarMic.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 71 — `js/98-153.js` (era `153.html`, 1256 linhas)

```text
Crie js/98-153.js. Ele faz: Iara Suite v3.0 - Importador Universal — 🚀 Iara Suite v3.0 - Importador Universal.
No app original ele tinha estas funções/partes: init, saveToStorage, loadFromStorage, switchTab, newFile, newFolder, loadFile, saveFile, renameFile, deleteFile, renderFileTree, togglePreview, updatePreview, downloadAsMarkdown, copyToClipboard, openImportModal, closeImportModal, importFromModal.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 72 — `js/98-154.js` (era `154.html`, 796 linhas)

```text
Crie js/98-154.js. Ele faz: Gerador de Plano de Projeto — 📊 Gerador de Plano de Projeto.
No app original ele tinha estas funções/partes: getFileType, getFileIcon, formatFileSize, toast, analyzeFileContent, importZip, renderTree, renderNode, renderFilesList, generatePlan, renderPlan, downloadPlan, copyPlan.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 73 — `js/98-155.js` (era `155.html`, 657 linhas)

```text
Crie js/98-155.js. Ele faz: Gerador de Ícones PWA - Maikon Caldeira — 🎨 Gerador de Ícones PWA.
No app original ele tinha estas funções/partes: gerarIcone, aplicarCor, baixarIcone, baixarTodos, desenharIcone, limpar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 74 — `js/98-156.js` (era `156.html`, 654 linhas)

```text
Crie js/98-156.js. Ele faz: 📱 Gerador EAS Build — 📱 Gerador de Configuração EAS Build.
No app original ele tinha estas funções/partes: switchTab, autoId, atualizar, importarProjeto, preencherDados, gerarTudo, renderArquivos, copiar, exportarZip, fileIcon, esc, escHtml, loadJSZ.
O original usava as bibliotecas @capacitor/cli: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 75 — `js/98-157.js` (era `157.html`, 1139 linhas)

```text
Crie js/98-157.js. Ele faz: Gerador de Documentação Automática — 📚 Gerador de Documentação Automática.
No app original ele tinha estas funções/partes: handleFile, generateDocumentation, analyzeJSFile, analyzeFileStructure, generateGettingStarted, generateFileTree, buildTree, generateArchitecture, displayDocumentation, App, switchTab, exportDocs, exportMarkdown, exportHTML, exportJSON, exportPDF, downloadFile, escapeHtml.
O original usava as bibliotecas ${comp.file}: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 76 — `js/98-158.js` (era `158.html`, 265 linhas)

```text
Crie js/98-158.js. Ele faz: Extrator de Sites — 🛠️ Extrator de Sites.
No app original ele tinha estas funções/partes: esc, LEITOR, hist, salvarHist, renderHist, status, buscar, absoluto, analisar, addRec, extrair, realce, conteudoAba, mostrar, copiar, baixar, nomeBase, CRC.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 77 — `js/98-159.js` (era `159.html`, 948 linhas)

```text
Crie js/98-159.js. Ele faz: SK-Combinar Apps — Unir Projetos.
No app original ele tinha estas funções/partes: uid, emptyApp, loadData, saveData, addApp, removeApp, updateApp, fetchRepoFiles, generatePrompt, copyPrompt, sendPrompt, clearAll, updateButtonStates, renderAppCard, render.
Ele chamava estes endereços: https://api.github.com/repos/${owner}/${repo}/git/trees/HEAD?recursive=1. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 78 — `js/98-16.js` (era `16.html`, 109 linhas)

```text
Crie js/98-16.js. Ele faz: SK Code Editor - GitHub Integration — SK Code Editor.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 79 — `js/98-160.js` (era `160.html`, 1209 linhas)

```text
Crie js/98-160.js. Ele faz: 🔧 ConstruAPK Pro — Analisador e Gerador — ConstruAPK Pro — Analisador & Gerador.
No app original ele tinha estas funções/partes: importZip, importFolder, afterImport, decodeText, renderTree, buildTree, renderNode, hasProblems, cntF, toggleF, expandAll, collapseAll, toggleSidebar, fIcon, fmtSz, esc, openFile, closeTab.
O original usava as bibliotecas @capacitor/cli, vite, @vitejs/plugin-react, path: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 80 — `js/98-161.js` (era `161.html`, 24 linhas)

```text
Crie js/98-161.js. Ele faz: 🎨 Playground + ⚖️ Assistente Jurídico - Maikon.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 81 — `js/98-162.js` (era `162.html`, 430 linhas)

```text
Crie js/98-162.js. Ele faz: Juntador de Arquivos — 🧩 Juntador de Arquivos.
No app original ele tinha estas funções/partes: esc, uid, toast, ext, lang, isTexto, bytesFmt, linhas, decode, pareceBinario, b64, unb64, inflate, lerZip, CRC, crc32, escreverZip, textoDocx.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 82 — `js/98-163.js` (era `163.html`, 136 linhas)

```text
Crie js/98-163.js. Ele faz: Maikon Caldeira — Aplicativos — MAIKON CALDEIRA.
No app original ele tinha estas funções/partes: lerInfo, procurar, pintar, abrir, fechar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 83 — `js/98-164.js` (era `164.html`, 1858 linhas)

```text
Crie js/98-164.js. Ele faz: AI Code Studio — 🤖 AI Code Studio.
No app original ele tinha estas funções/partes: MODULE_Provider, onChange, updateSelect, current, MODULE_Storage, save, load, setupAutoSave, exportAll, importBackup, handleImport, _download, MODULE_Brain, toggle, render, addManual, closeMemoryModal, saveManual.
Ele chamava estes endereços: https://api.openai.com/v1/chat/completions, https://api.anthropic.com/v1/messages, https://generativelanguage.googleapis.com/v1beta/models/${model}:generateContent?key=${apiKey}, https://api.groq.com/openai/v1/chat/completions, https://openrouter.ai/api/v1/chat/completions, ${url}/api/chat, https://google.serper.dev/search. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 84 — `js/98-165.js` (era `165.html`, 68 linhas)

```text
Crie js/98-165.js. Ele faz: 🚀 Setup Dashboard — 🚀 Setup Dashboard.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 85 — `js/98-166.js` (era `166.html`, 847 linhas)

```text
Crie js/98-166.js. Ele faz: Gerador de Relatório + Extrator de Arquivos — 📋 Gerador de Relatório + Extrator de Arquivos.
No app original ele tinha estas funções/partes: handleFile, getFileType, displayReport, filterFiles, viewFile, analyzeFile, downloadFile, downloadCurrentFile, copyCurrentFile, closeModal, exportReport, escapeHtml.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 86 — `js/98-167.js` (era `167.html`, 753 linhas)

```text
Crie js/98-167.js. Ele faz: Filtrador Jurídico Avançado (Atualizado) — Filtrador Jurídico Avançado (Atualizado).
No app original ele tinha estas funções/partes: loadState, saveState, setStatus, download, enviarParaNuvem, cleanMarkdownNoise, splitParagraphs, normalizeForCompare, makeShingles, signature, jaccard, parseLines, buildRegexList, extractTextFromPDF, extractTextFromDOCX, extractTextFromJSON, walk, applyBanRules.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 87 — `js/98-168.js` (era `168.html`, 675 linhas)

```text
Crie js/98-168.js. Ele faz: SK-Chat — Painel de Regras.
No app original ele tinha estas funções/partes: loadRules, saveRules, addRule, deleteRule, renderRules, openAddRuleModal, closeAddRuleModal, loadMessages, saveMessages, sendMessage, renderMessages.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 88 — `js/98-169.js` (era `169.html`, 895 linhas)

```text
Crie js/98-169.js. Ele faz: SK-Master — Editor + Chat + Prompt Generator.
No app original ele tinha estas funções/partes: switchTab, saveProject, clearEditor, exportProject, loadProject, loadMessages, saveMessages, sendChatMessage, renderMessages, toggleRecording, openPromptGenerator, closePromptModal, copyPrompt, searchInternet.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 89 — `js/98-17.js` (era `17.html`, 1194 linhas)

```text
Crie js/98-17.js. Ele faz: SK Mini Editor - Completo — SK Mini Editor.
No app original ele tinha estas funções/partes: MiniVFSRobusto, sort, MiniFileTree, MiniEditor, close.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 90 — `js/98-170.js` (era `170.html`, 408 linhas)

```text
Crie js/98-170.js. Ele faz: SK-Code Analyzer v2.
No app original ele tinha estas funções/partes: extractImports, buildDependencyGraph, findDependents, handleZipUpload, handlePasteCode, filterFiles, selectFile, clearAll, renderFilesList, renderGraph, renderDetails, downloadFile, render, openPasteModal, closePasteModal.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 91 — `js/98-171.js` (era `171.html`, 12 linhas)

```text
Crie js/98-171.js. Ele faz: Peça.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 92 — `js/98-172.js` (era `172.html`, 2818 linhas)

```text
Crie js/98-172.js. Ele faz: CirurgiÃ£o de CÃ³digo 4.4 — ðŸ©º CirurgiÃ£o 4.4.
No app original ele tinha estas funções/partes: esc, fmtB, fmtN, usd, agora, pausa, tokensDe, extDe, decode, pareceBinario, inflate, lerZip, CRC, crc32, escreverZip, baixar, copiar, status.
O original usava as bibliotecas ${mod}: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: ${c.base}/models/${encodeURIComponent(c.modelo)}:generateContent, ${c.base}/messages, ${c.base}/chat/completions, https://registry.npmjs.org/, https://registry.npmjs.org/-/v1/search?size=20&text=, https://pypi.org/pypi/. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 93 — `js/98-173.js` (era `173.html`, 2784 linhas)

```text
Crie js/98-173.js. Ele faz: Cirurgião de Código 4.3 — 🩺 Cirurgião 4.3.
No app original ele tinha estas funções/partes: esc, fmtB, fmtN, usd, agora, pausa, tokensDe, extDe, decode, pareceBinario, inflate, lerZip, CRC, crc32, escreverZip, baixar, copiar, status.
O original usava as bibliotecas ${mod}: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: ${c.base}/models/${encodeURIComponent(c.modelo)}:generateContent, ${c.base}/messages, ${c.base}/chat/completions, https://registry.npmjs.org/, https://registry.npmjs.org/-/v1/search?size=20&text=, https://pypi.org/pypi/. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 94 — `js/98-174.js` (era `174.html`, 437 linhas)

```text
Crie js/98-174.js. Ele faz: Juntador de Arquivos — 🧩 Juntador de Arquivos.
No app original ele tinha estas funções/partes: esc, uid, toast, ext, lang, isTexto, bytesFmt, linhas, decode, pareceBinario, b64, unb64, inflate, lerZip, CRC, crc32, escreverZip, textoDocx.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 95 — `js/98-175.js` (era `175.html`, 1128 linhas)

```text
Crie js/98-175.js. Ele faz: Maikon Caldeira - Advocacia Digital — Maikon Caldeira.
No app original ele tinha estas funções/partes: inicializarSlots, renderizarApps, renderizarListaApps, atualizarSelectSlots, mudarAba, abrirModal, fecharModal, limparFormulario, adicionarApp, editarApp, atualizarApp, removerApp, preencherSlot, gerarManifest, gerarServiceWorker, gerarIcones, baixarTudo, baixarArquivo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 96 — `js/98-176.js` (era `176.html`, 49 linhas)

```text
Crie js/98-176.js. Ele faz: SK Editor v3.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 97 — `js/98-177.js` (era `177.html`, 623 linhas)

```text
Crie js/98-177.js. Ele faz: Conversor TJMG (Fator) → competencia/correcao_pct — Conversor TJMG (fator em colunas) → competencia/correcao_pct.
No app original ele tinha estas funções/partes: tick, setStatus, normNumToken, toNumberBR, pad2, parseYear12FromText, parseYearMonthFactorFromText, parseAuto, ymKey, dedupeAndSort, computeMonthlyPctFromFactors, renderTable, toCSV, download, tryFixText, convertNow, readPDF, readExcel.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 98 — `js/98-178.js` (era `178.html`, 143 linhas)

```text
Crie js/98-178.js. Ele faz: Iara Suite — ⚡ Iara Suite.
No app original ele tinha estas funções/partes: qsa, lsSet, esc, getExt, toast, dlBlob, FICON, initTabs, toggleSidebar, setPM, startDrag, onDrag, stopDrag, refreshPreview, openPrevTab, DETECT, getActive, updateProvInfo.
Ele chamava estes endereços: https://api.anthropic.com/v1/messages, https://generativelanguage.googleapis.com/v1beta/models/${model}:generateContent?key=${s.key}, ${base}/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 99 — `js/98-179.js` (era `179.html`, 864 linhas)

```text
Crie js/98-179.js. Ele faz: 🚀 Gerenciador PWA - Maikon Caldeira — 🚀 Gerenciador PWA Completo.
No app original ele tinha estas funções/partes: carregarArquivoHtml, carregarIcone, adicionarApp, renderizarApps, removerApp, editarApp, limparFormulario, gerarIconesSVG, gerarIndexHTML, gerarManifestJSON, gerarServiceWorker, gerarPWACompleto, previewIndex, previewManifest, escapeHtml.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 100 — `js/98-18.js` (era `18.html`, 32 linhas)

```text
Crie js/98-18.js. Ele faz: teste 2 onde txt 6 index.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 101 — `js/98-180.js` (era `180.html`, 1555 linhas)

```text
Crie js/98-180.js. Ele faz: Playground TSX - Maikon Caldeira — 🎨 Playground TSX/React.
No app original ele tinha estas funções/partes: executarCodigo, mudarPreview, carregarExemplo, App.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 102 — `js/98-181.js` (era `181.html`, 618 linhas)

```text
Crie js/98-181.js. Ele faz: 📱 Gerador DevMobile EAS — 📱 Gerador EAS Build — Baseado no DevMobile.
No app original ele tinha estas funções/partes: switchTab, atualizar, autoPackage, gerarTudo, renderArquivos, copiar, showToast, exportarZip, fIcon, esc, escHtml, loadJSZ.
O original usava as bibliotecas expo: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 103 — `js/98-182.js` (era `182.html`, 262 linhas)

```text
Crie js/98-182.js. Ele faz: Extrator de Sites — 🛠️ Extrator de Sites.
No app original ele tinha estas funções/partes: esc, LEITOR, hist, salvarHist, renderHist, status, buscar, absoluto, analisar, addRec, extrair, realce, conteudoAba, mostrar, copiar, baixar, nomeBase, CRC.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 104 — `js/98-183.js` (era `183.html`, 920 linhas)

```text
Crie js/98-183.js. Ele faz: Extrator Jurídico — Maikon Caldeira OAB/MG 183712.
No app original ele tinha estas funções/partes: qsa, esc, copyText, dlBlob, toast, loadKeyFromStorage, detectKeyProvider, detectProvider, saveKey, updateKeyHint, callAI, toggleAI, clearAI, openKeyModal, closeKeyModal, addMsg, sendAI, sendWithScripts.
Ele chamava estes endereços: https://api.anthropic.com/v1/messages, https://generativelanguage.googleapis.com/v1beta/models/${model||, ${base}/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 105 — `js/98-184.js` (era `184.html`, 807 linhas)

```text
Crie js/98-184.js. Ele faz: Iara Mapper — Dr. Maikon Caldeira.
No app original ele tinha estas funções/partes: qsa, toast, updateLineNums, syncScroll, handleFileUpload, handleHtmlFile, handleZipFile, extractSearchableContent, renderResults, selectResult, showChangePreview, applyChange, confirmApply, cancelChange, exportCode.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 106 — `js/98-185.js` (era `185.html`, 935 linhas)

```text
Crie js/98-185.js. Ele faz: SK-CSS/HTML Interactive Guide.
No app original ele tinha estas funções/partes: loadTopic, renderControls, updateProperty, updatePreview, updateCodeDisplay.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 107 — `js/98-186.js` (era `186.html`, 1 linhas)

```text
Crie js/98-186.js. Ele faz: Demonstrativo de cálculo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 108 — `js/98-187.js` (era `187.html`, 1097 linhas)

```text
Crie js/98-187.js. Ele faz: Corretor Automático Inteligente — 🔧 Corretor Automático Inteligente.
No app original ele tinha estas funções/partes: handleFile, generateFixes, generateJSFixes, getData, generateJSONFixes, generateHTMLFixes, displayResults, switchTab, toggleFix, updateSelectedCount, selectAllFixes, deselectAllFixes, selectAutoFixes, applySelectedFixes, displayApplyResults, downloadCorrectedFiles, downloadCorrectionReport, previewFile.
Ele chamava estes endereços: /api/data. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 109 — `js/98-188.js` (era `188.html`, 287 linhas)

```text
Crie js/98-188.js. Ele faz: Comunicações Processuais — ⚖️ Comunicações Processuais.
No app original ele tinha estas funções/partes: esc, carregarDados, iso, periodo, limpar, fData, parse, chave, status, montarParams, buscar, render, baixar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 110 — `js/98-189.js` (era `189.html`, 3968 linhas)

```text
Crie js/98-189.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: nome, salvarMemoria, detectarProvedor, toggleVerChave, carregarArquivo, carregarZIP, renderizarListaArquivos, filtrarArquivos, abrirArquivoDoZip, abrirColagem, processarCodigo, buscarNoCodigo, buscarReplit, irParaLinha, detectarReplit, mostrarFunctions, encontrada, extrairFuncaoEspecifica.
Ele chamava estes endereços: , , ${provedor.url}/chat/completions, ,. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 111 — `js/98-19.js` (era `19.html`, 676 linhas)

```text
Crie js/98-19.js. Ele faz: Playground Pro — Bem-vindo ao Playground Pro! 🚀.
No app original ele tinha estas funções/partes: showStatus, toggleTheme, applyTheme, abrirConfig, fecharConfig, salvarConfig, abrirPagina, abrirChat, fecharChat, enviarMensagem.
Ele chamava estes endereços: https://api.anthropic.com/v1/messages. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 112 — `js/98-190.js` (era `190.html`, 52 linhas)

```text
Crie js/98-190.js. Ele faz: Consulta por OAB — Buscar por OAB.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 113 — `js/98-191.js` (era `191.html`, 335 linhas)

```text
Crie js/98-191.js. Ele faz: lib pdf template.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 114 — `js/98-192.js` (era `192.html`, 126 linhas)

```text
Crie js/98-192.js. Ele faz: indice_legal-assistant.tsx (2).md — indice_legal-assistant.tsx (2).md.
O original usava as bibliotecas react, wouter, @tanstack/react-query: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 115 — `js/98-193.js` (era `193.html`, 627 linhas)

```text
Crie js/98-193.js. Ele faz: Meus Projetos.
No app original ele tinha estas funções/partes: showTab, loadFrame, updateClock.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 116 — `js/98-194.js` (era `194.html`, 860 linhas)

```text
Crie js/98-194.js. Ele faz: Construtor Automático PWA - Maikon Caldeira — 🚀 Construtor Automático PWA.
No app original ele tinha estas funções/partes: createWindow, print, executarComando, limparTerminal, atualizarArvore, selecionarArquivo, limparEditor, copiarCodigo, baixarProjeto, escapeHtml.
O original usava as bibliotecas electron, path, vite: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 117 — `js/98-195.js` (era `195.html`, 805 linhas)

```text
Crie js/98-195.js. Ele faz: SK-Chat — Regras + Tokens.
No app original ele tinha estas funções/partes: loadRules, saveRules, addRule, deleteRule, renderRules, openAddRuleModal, closeAddRuleModal, loadMessages, saveMessages, calculateTokens, getTotalTokens, getMaxTokens, updateTokenDisplay, sendMessage, renderMessages.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 118 — `js/98-196.js` (era `196.html`, 922 linhas)

```text
Crie js/98-196.js. Ele faz: Cirurgião de Código 4.0 — 🔬 CIRURGIÃO DE CÓDIGO 4.0.
No app original ele tinha estas funções/partes: getProv, toggleChave, abrirModal, fecharModal, confirmarColar, carregar, carregarZIP, renderListaArqs, filtrarArqs, abrirArqZip, processar, buscar, buscarReplit, buscarBugs, irLinha, detectarReplit, detectarBugs, detectarConflitos.
Ele chamava estes endereços: ))                 tags+=, )||t.includes(, ,, ${prov.url}/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 119 — `js/98-197.js` (era `197.html`, 1137 linhas)

```text
Crie js/98-197.js. Ele faz: Cirurgião de Código 2.0 — 🔬 CIRURGIÃO DE CÓDIGO 2.0.
No app original ele tinha estas funções/partes: nome, salvarMemoria, detectarProvedor, toggleVerChave, carregarArquivo, carregarZIP, renderizarListaArquivos, filtrarArquivos, abrirArquivoDoZip, abrirColagem, processarCodigo, buscarNoCodigo, buscarReplit, irParaLinha, detectarReplit, mostrarFunctions, encontrada, extrairFuncaoEspecifica.
Ele chamava estes endereços: )) tags += , ) || limpada.includes(, , , );
  const temGemini = /gemini/i.test(codigoOriginal);
  const temGPT = /openai|gpt-/i.test(codigoOriginal);
  const temReplit = /replit\.com|replit\.dev|REPL_ID/i.test(codigoOriginal);
  const temCapacitor = /capacitor/i.test(codigoOriginal);
  const temElectron = /electron/i.test(codigoOriginal);

  manual += , ${provedor.url}/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 120 — `js/98-198.js` (era `198.html`, 2817 linhas)

```text
Crie js/98-198.js. Ele faz: Cirurgião de Código 4.4 — 🩺 Cirurgião 4.4.
No app original ele tinha estas funções/partes: esc, fmtB, fmtN, usd, agora, pausa, tokensDe, extDe, decode, pareceBinario, inflate, lerZip, CRC, crc32, escreverZip, baixar, copiar, status.
O original usava as bibliotecas ${mod}: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: ${c.base}/models/${encodeURIComponent(c.modelo)}:generateContent, ${c.base}/messages, ${c.base}/chat/completions, https://registry.npmjs.org/, https://registry.npmjs.org/-/v1/search?size=20&text=, https://pypi.org/pypi/. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 121 — `js/98-199.js` (era `199.html`, 2360 linhas)

```text
Crie js/98-199.js. Ele faz: Cirurgião de Código 4.2 — 🩺 Cirurgião 4.2.
No app original ele tinha estas funções/partes: esc, fmtB, fmtN, usd, agora, pausa, tokensDe, extDe, decode, pareceBinario, inflate, lerZip, CRC, crc32, escreverZip, baixar, copiar, status.
O original usava as bibliotecas ${mod}: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: ${c.base}/models/${encodeURIComponent(c.modelo)}:generateContent, ${c.base}/messages, ${c.base}/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 122 — `js/98-2.js` (era `2.html`, 584 linhas)

```text
Crie js/98-2.js. Ele faz: Diagnóstico + Correção de Executáveis — 🔧 Diagnóstico + Correção de Executáveis.
No app original ele tinha estas funções/partes: mudarAba, copiarScript, notificacao.
O original usava as bibliotecas electron, path: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 123 — `js/98-20.js` (era `20.html`, 616 linhas)

```text
Crie js/98-20.js. Ele faz: 🚀 SK Mini Editor - Gerador de Arquivos — 🚀 SK Mini Editor.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 124 — `js/98-200.js` (era `200.html`, 2335 linhas)

```text
Crie js/98-200.js. Ele faz: Cirurgião de Código 4.1 — 🩺 Cirurgião 4.1.
No app original ele tinha estas funções/partes: esc, fmtB, fmtN, usd, agora, pausa, tokensDe, extDe, decode, pareceBinario, inflate, lerZip, CRC, crc32, escreverZip, baixar, copiar, status.
O original usava as bibliotecas ${mod}: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: ${c.base}/models/${encodeURIComponent(c.modelo)}:generateContent, ${c.base}/messages, ${c.base}/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 125 — `js/98-201.js` (era `201.html`, 1096 linhas)

```text
Crie js/98-201.js. Ele faz: Chat IA Pro — Saulo — Chat IA Pro.
No app original ele tinha estas funções/partes: detectProvider, getSysPrompt, applyPreset, saveSystemPrompt, initSysPanel, toggleFeedback, addFeedbackBar, saveFeedback, openDB, dbPut, dbGetAll, dbGet, dbDelete, boot, restoreUI, autoSave, scheduleSave, autoSaveDraft.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 126 — `js/98-202.js` (era `202.html`, 17 linhas)

```text
Crie js/98-202.js. Ele faz: Chat — 💬 Chat.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 127 — `js/98-203.js` (era `203.html`, 669 linhas)

```text
Crie js/98-203.js. Ele faz: Calculadora de Sentença — Calculadora de Sentença.
No app original ele tinha estas funções/partes: EMBUTIDO, esc, num, valor, brl, pct, fat, chave, mesTxt, proxMes, mesDe, meses, dataBR, mesPorNome, lerTabela, fecha, tipoTabela, aplicarTabela.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 128 — `js/98-204.js` (era `204.html`, 593 linhas)

```text
Crie js/98-204.js. Ele faz: Calculadora de Sentença — Calculadora de Sentença.
No app original ele tinha estas funções/partes: EMBUTIDO, esc, num, brl, pct, fat, chave, mesTxt, proxMes, mesDe, meses, dataBR, mesPorNome, lerTabela, fecha, tipoTabela, aplicarTabela, fatorTabela.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 129 — `js/98-205.js` (era `205.html`, 557 linhas)

```text
Crie js/98-205.js. Ele faz: Calculadora de Sentença — Calculadora de Sentença.
No app original ele tinha estas funções/partes: EMBUTIDO, esc, num, brl, pct, fat, chave, mesTxt, proxMes, mesDe, meses, dataBR, mesPorNome, lerTabela, tipoTabela, aplicarTabela, fatorTabela, fatorCorr.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 130 — `js/98-206.js` (era `206.html`, 440 linhas)

```text
Crie js/98-206.js. Ele faz: arquivo 2.
No app original ele tinha estas funções/partes: mostrarErro, Guarda.
O original usava as bibliotecas react, react-dom, blob:https:: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 131 — `js/98-207.js` (era `207.html`, 974 linhas)

```text
Crie js/98-207.js. Ele faz: Comparador Jurídico Completo — TJMG (Fator) + BCB (Juros) — Multi-Cenário — Comparador Jurídico — TJMG (Fator) + BCB (Juros) — Multi-Cenário.
No app original ele tinha estas funções/partes: setClock, setStatus, fmtBRL, toNumberBR, escapeHtml, parseDateBR, dateToYM, listMonths, download, parseCSV, split, parseIndicesText, extractYearRowsFromTJText, loadTJFactorsAsMonthlyCorrections, formatDateBR, fetchBCBSeriesMonthlyLastValue, addScenario, resetScenarios.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 132 — `js/98-208.js` (era `208.html`, 1386 linhas)

```text
Crie js/98-208.js. Ele faz: Chat IA Pro — Chat IA Pro.
No app original ele tinha estas funções/partes: detectProvider, openDB, dbPut, dbGetAll, dbGet, dbDelete, boot, restoreUI, autoSave, scheduleSave, autoSaveDraft, togglePanel, onKeyInput, updateProvBadge, updateCfgStatus, toggleShowKey, saveKey, renderSavedKeys.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 133 — `js/98-209.js` (era `209.html`, 565 linhas)

```text
Crie js/98-209.js. Ele faz: Calculadora de Sentença — Calculadora de Sentença.
No app original ele tinha estas funções/partes: EMBUTIDO, esc, num, brl, pct, fat, chave, mesTxt, proxMes, mesDe, meses, dataBR, mesPorNome, lerTabela, tipoTabela, aplicarTabela, fatorTabela, fatorCorr.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 134 — `js/98-21.js` (era `21.html`, 518 linhas)

```text
Crie js/98-21.js. Ele faz: 🚀 SK Mini Editor - Setup Interativo — 🚀 SK Mini Editor - Setup Interativo.
No app original ele tinha estas funções/partes: copiarParaArea, downloadFile, downloadAllAsZip.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 135 — `js/98-210.js` (era `210.html`, 276 linhas)

```text
Crie js/98-210.js. Ele faz: SK Oficina Jurídica v6 - Integrada — SK Oficina Jurídica v6.
No app original ele tinha estas funções/partes: hasReplitRef, cleanReplitRefs, parseAxml, handleFile, extractInfo, renderApkInfo, renderFileList, filterFileList, openFile, saveFile, cleanAndDownload, runFullScan, showSection.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 136 — `js/98-212.js` (era `212.html`, 3520 linhas)

```text
Crie js/98-212.js. Ele faz: analise_Manual.tsx.html — analise_Manual.tsx.html.
No app original ele tinha estas funções/partes: Manual, initDb.
O original usava as bibliotecas react, jszip, file-saver, dotenv, @neondatabase/serverless, fs: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 137 — `js/98-213.js` (era `213.html`, 1438 linhas)

```text
Crie js/98-213.js. Ele faz: Análise: keys.tsx — 🔬 keys.tsx.
No app original ele tinha estas funções/partes: uid, statusColor, statusLabel, ManualModal, CreateTableModal, addCol, removeCol, setColName, setColType, run, KeysScreen, pickManual, addKey, testKey, testAll, testNeon, runSql, runAiDb.
Ele chamava estes endereços: ${base}/chat/completions, ${base}/api/healthz. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 138 — `js/98-214.js` (era `214.html`, 668 linhas)

```text
Crie js/98-214.js. Ele faz: Análise: export.tsx — 🔬 export.tsx.
No app original ele tinha estas funções/partes: ExportScreen, handleGenerate, handleShare, handleEasBuild, openEasDashboard, Field.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 139 — `js/98-215.js` (era `215.html`, 3024 linhas)

```text
Crie js/98-215.js. Ele faz: Análise: EditorLayout.tsx — 🔬 EditorLayout.tsx.
No app original ele tinha estas funções/partes: NameInputModal, buildAsciiTree, sortKeys, render, generateDocs, explainFile, explainFolder, generateSystemInfo, EditorLayout.
O original usava as bibliotecas node-fetch, axios, fs: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 140 — `js/98-216.js` (era `216.html`, 5805 linhas)

```text
Crie js/98-216.js. Ele faz: analise_EditorLayout.tsx (1).md — analise_EditorLayout.tsx (1).md.
No app original ele tinha estas funções/partes: NameInputModal, buildAsciiTree, sortKeys, render, generateDocs, explainFile, explainFolder, generateSystemInfo, EditorLayout.
O original usava as bibliotecas react, lucide-react, node-fetch, axios, fs: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: https://api.exemplo.com, https://api.github.com/users/nome, /api/workspace/write, /api/workspace/sync, /api/db/query. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 141 — `js/98-217.js` (era `217.html`, 631 linhas)

```text
Crie js/98-217.js. Ele faz: Análise: desktop.ts — 🔬 desktop.ts.
No app original ele tinha estas funções/partes: strToAb, genElectronPackageJson, genElectronMain, createWindow, genElectronPreload, genNpmRc, genDesktopWorkflow, genDesktopReadme, buildDesktopFilesForGithub, buildDesktopZip.
O original usava as bibliotecas electron, path: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 142 — `js/98-218.js` (era `218.html`, 543 linhas)

```text
Crie js/98-218.js. Ele faz: Análise: android.ts — 🔬 android.ts.
No app original ele tinha estas funções/partes: selectWebFiles, buildAndroidZip, MainActivity.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 143 — `js/98-219.js` (era `219.html`, 1721 linhas)

```text
Crie js/98-219.js. Ele faz: AI Code Studio — 🤖 AI Code Studio.
No app original ele tinha estas funções/partes: est, uid, isMobile, escapeHtml, copyText, activeConv, MODULE_Storage, save, saveSoon, load, normMemory, stamp, download, exportAll, importBackup, handleImport, MODULE_Provider, models.
Ele chamava estes endereços: https://api.anthropic.com/v1/messages, https://api.anthropic.com/v1/models?limit=100, https://google.serper.dev/search. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 144 — `js/98-22.js` (era `22.html`, 424 linhas)

```text
Crie js/98-22.js. Ele faz: SK Mini Editor - TESTE — SK Mini Editor - TESTE.
No app original ele tinha estas funções/partes: addFile, renderFiles, selectFile, renderTabs, closeTab, updateFile, updatePreview.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 145 — `js/98-220.js` (era `220.html`, 49 linhas)

```text
Crie js/98-220.js. Ele faz: Sem titulo — Bem-vindo ao HTML Playground.
No app original ele tinha estas funções/partes: testarAPI.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 146 — `js/98-221.js` (era `221.html`, 137 linhas)

```text
Crie js/98-221.js. Ele faz: Diagnóstico crise.
No app original ele tinha estas funções/partes: salvarCaso, renderizarCasos.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 147 — `js/98-222.js` (era `222.html`, 242 linhas)

```text
Crie js/98-222.js. Ele faz: Calculadora Jurídica Monica — Importador Direto.
No app original ele tinha estas funções/partes: lerArquivoExcel, buscarBCB, calcular.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 148 — `js/98-223.js` (era `223.html`, 404 linhas)

```text
Crie js/98-223.js. Ele faz: Comparador Jurídico Completo (Com Busca BCB) — Comparador Jurídico (BCB Integrado).
No app original ele tinha estas funções/partes: toMoney, toNum, parseDate, dateToYM, formatDateBR, fetchBCBSerieToText, renderTable.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 149 — `js/98-224.js` (era `224.html`, 338 linhas)

```text
Crie js/98-224.js. Ele faz: Resumidor Jurídico Estruturado v2.0 — EMBARGOS DE DECLARAÇÃO.
No app original ele tinha estas funções/partes: lerArquivos, lerTXT, lerDOCX, lerPDF, calcularSimilaridade, editDistance, processarTexto, limparTudo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 150 — `js/98-225.js` (era `225.html`, 298 linhas)

```text
Crie js/98-225.js. Ele faz: Gerador de Petição: Vinculação e Enquadramento - Caso Adjair — ⚖️ Gerador de Petição Previdenciária.
No app original ele tinha estas funções/partes: initChart, updateDoc, copyToClipboard.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 151 — `js/98-226.js` (era `226.html`, 360 linhas)

```text
Crie js/98-226.js. Ele faz: Siscajur - Perícia Bancária & Sentença (Capitalização Anual).
No app original ele tinha estas funções/partes: importarTJMG, buscarBacen, calcular.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 152 — `js/98-227.js` (era `227.html`, 542 linhas)

```text
Crie js/98-227.js. Ele faz: Extrator Replit — Maikon — 🗂 Extrator de Projetos Replit.
No app original ele tinha estas funções/partes: carregarCSV, processarArquivo, parseCSVCompleto, lerLinha, filtrar, renderizarLista, abrirProjeto, renderizarPreview, mudarAba, montarHTML, baixarProjeto, abrirNovaAba, copiarProjeto, baixarTodos, proximo, limpar, limparNome, baixarBlob.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 153 — `js/98-228.js` (era `228.html`, 494 linhas)

```text
Crie js/98-228.js. Ele faz: Comparador JurÃ­dico â TJMG + BCB — Comparador Juridico â TJMG (Fator) + BCB (Juros).
No app original ele tinha estas funções/partes: setClock, setStatus, fmtBRL, toNumberBR, parseDateBR, dateToYM, listMonths, addScenario, renderScenarios, renderTable.
Ele chamava estes endereços: https://api.bcb.gov.br/dados/serie/bcdata.sgs.. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 154 — `js/98-229.js` (era `229.html`, 739 linhas)

```text
Crie js/98-229.js. Ele faz: Extrator de Texto Pro — 📄 Extrator de Texto Pro.
No app original ele tinha estas funções/partes: toggleTheme, showNotification, updateStats, preventDefaults, handleFileSelect, formatFileSize, showProgress, cleanFooter, extractText, extractFromPDF, extractFromImage, extractFromDOCX, downloadText, downloadPDF, downloadDOCX, downloadMarkdown, downloadFile, copyText.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 155 — `js/98-23.js` (era `23.html`, 663 linhas)

```text
Crie js/98-23.js. Ele faz: SK Mini Editor - Editor de Código Online — SK Mini Editor.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 156 — `js/98-230.js` (era `230.html`, 770 linhas)

```text
Crie js/98-230.js. Ele faz: Gerador de Peças Processuais — TRF6.
No app original ele tinha estas funções/partes: escapeHtml, nl2br, updateDoc, adicionarTopico, removerTopico, renderTopicosExtras, exportarWord, limparTudo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 157 — `js/98-231.js` (era `231.html`, 544 linhas)

```text
Crie js/98-231.js. Ele faz: Calculadora Judicial (TJMG + BCB + Capitalização Anual) — Calculadora Judicial Avançada.
No app original ele tinha estas funções/partes: fmtMoney, fmtNum, parseBRL, toYM, processData, updateSelects, fill, fetchBCB, fmt, rebuildCSV, calculate, exportCSV.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 158 — `js/98-232.js` (era `232.html`, 848 linhas)

```text
Crie js/98-232.js. Ele faz: Analisador de Histórico — ZIP/TAR/TAZ — 📦 Analisador de Histórico — ZIP/TAR/TAZ.
No app original ele tinha estas funções/partes: handleFile, processZip, processTar, shouldExtractContent, displayAnalysis, analyzeFileStructure, analyzeCodeContent, generateFolderStructure, getImportantFiles, escapeHtml, switchTab, exportAsJSON, exportAsMarkdown, exportAsHTML, downloadFile.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 159 — `js/98-233.js` (era `233.html`, 693 linhas)

```text
Crie js/98-233.js. Ele faz: Gerador Jurídico Pro (PDF/DOCX + Dedup Inteligente) — EMBARGOS DE DECLARAÇÃO.
No app original ele tinha estas funções/partes: showLoading, hideLoading, extractTextFromPDF, extractTextFromDOCX, processarTexto, inserirNoDocumento, atualizarCabecalho, limparCampos, exportarWord, htmlToDocx, exportarJSON.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 160 — `js/98-234.js` (era `234.html`, 597 linhas)

```text
Crie js/98-234.js. Ele faz: Maikon Caldeira - Reconhecimentos Pretéritos.
No app original ele tinha estas funções/partes: autoSave, salvarNoStorage, coletarDados, carregarDados, adicionarReconhecimento, removerReconhecimento, importarCnisPdf, interpretarCnis, converterData, inferirTipo, exportarJSON, importarJSON, limparTudo, formatarData, gerarDocumento, enviarGmail.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 161 — `js/98-235.js` (era `235.html`, 902 linhas)

```text
Crie js/98-235.js. Ele faz: Comparador Jurídico - Índices TJMG + BCB — Comparador Jurídico - Índices TJMG + BCB.
No app original ele tinha estas funções/partes: setClock, setStatus, parseCSV, splitCSVLine, toNumber, fmtBRL, parseDateBR, dateToYM, listMonthsFromDates, download, convertTJMGIndices, addScenario, removeScenario, renderScenarios, escapeHtml, parseIndices, formatDateBR, fetchBCBSerieToMonthlyMap.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 162 — `js/98-236.js` (era `236.html`, 1121 linhas)

```text
Crie js/98-236.js. Ele faz: 📋 Gerador de Plano de Projeto — 📋 Gerador de Plano de Projeto.
No app original ele tinha estas funções/partes: carregarProjeto, carregarZIP, analisarProjeto, mostrarStats, gerarPlano, gerarMarkdown, gerarArvore, renderizar, gerarSecoes, analisarComIA, mostrarPlano, mostrarLoading, copiarPlanoCompleto, copiarSecao, baixarMarkdown.
Ele chamava estes endereços: ${provedor.url}/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 163 — `js/98-237.js` (era `237.html`, 808 linhas)

```text
Crie js/98-237.js. Ele faz: SK Database Manager + IA.
No app original ele tinha estas funções/partes: detectarChave, chamarIA, enviarIA, perguntarRapido, adicionarMensagemIA, copiarSQL, mostrarTyping, limparChat, enviarResultadoParaIA, parseConn, runQuery, conectar, desconectar, setStatus, listarTabelas, executarSQL, renderTabela, verEsquema.
Ele chamava estes endereços: https://api.groq.com/openai/v1/chat/completions, https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${aiKey}, https://api.x.ai/v1/chat/completions, https://api.anthropic.com/v1/messages, https://${info.host}/sql. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 164 — `js/98-238.js` (era `238.html`, 1785 linhas)

```text
Crie js/98-238.js. Ele faz: Análise: Terminal.tsx — 🔬 Terminal.tsx.
No app original ele tinha estas funções/partes: simulateInstallDelay, Terminal, createTables, testConnection, setupDatabase, query, getClient, signUp, signIn, signOut, getUser, getAll, getById, insert, update, remove, uploadFile, subscribeToTable.
O original usava as bibliotecas firebase, firebas<, ytdl-core, fs, fluent-ffmpeg, better-sqlite3, pg, mongoose, ${mod}, @supabase/supabase-js, path: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 165 — `js/98-239.js` (era `239.html`, 2094 linhas)

```text
Crie js/98-239.js. Ele faz: Análise: settings.tsx — 🔬 settings.tsx.
No app original ele tinha estas funções/partes: SectionHeader, SettingRow, SettingsScreen.
O original usava as bibliotecas express, cors, child_process: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 166 — `js/98-24.js` (era `24.html`, 345 linhas)

```text
Crie js/98-24.js. Ele faz: SK Oficina de Busca, Extração & Exportação v7.
No app original ele tinha estas funções/partes: showLoader, hideLoader, performSearch, renderFileList, openFile, escapeHTML, saveCurrentFile, copyForMonica, exportProject.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 167 — `js/98-240.js` (era `240.html`, 2217 linhas)

```text
Crie js/98-240.js. Ele faz: Análise: Manual.tsx — 🔬 Manual.tsx.
No app original ele tinha estas funções/partes: Manual, initDb.
O original usava as bibliotecas dotenv, @neondatabase/serverless, fs: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: /api/twa-files?url=${encodeURIComponent(url)}, /api/pwa-check?url=${encodeURIComponent(url)}. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 168 — `js/98-241.js` (era `241.html`, 5980 linhas)

```text
Crie js/98-241.js. Ele faz: Análise: legal-assistant.tsx — 🔬 legal-assistant.tsx.
No app original ele tinha estas funções/partes: LegalAssistant.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 169 — `js/98-242.js` (era `242.html`, 1209 linhas)

```text
Crie js/98-242.js. Ele faz: analise_export.tsx.md — analise_export.tsx.md.
No app original ele tinha estas funções/partes: ExportScreen, handleGenerate, handleShare, handleEasBuild, openEasDashboard, Field.
O original usava as bibliotecas @expo/vector-icons, expo-file-system, expo-sharing, expo-linking, expo-router, react, react-native-safe-area-context, react-native: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 170 — `js/98-243.js` (era `243.html`, 1069 linhas)

```text
Crie js/98-243.js. Ele faz: analise_desktop.ts (1).md — analise_desktop.ts (1).md.
No app original ele tinha estas funções/partes: strToAb, genElectronPackageJson, genElectronMain, createWindow, genElectronPreload, genNpmRc, genDesktopWorkflow, genDesktopReadme, buildDesktopFilesForGithub, buildDesktopZip.
O original usava as bibliotecas jszip, electron, path: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 171 — `js/98-244.js` (era `244.html`, 1120 linhas)

```text
Crie js/98-244.js. Ele faz: Análise: DeployPanel.tsx — 🔬 DeployPanel.tsx.
No app original ele tinha estas funções/partes: copyText, CodeBlock, uint32LE, uint16LE, crc32, buildZip, buildZipBlob, DeployPanel, downloadBlob, verificarAssinatura.
O original usava as bibliotecas express, cors, @supabase/supabase-js, stripe: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: http://localhost:3001/api/dados, /api/criar-checkout. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 172 — `js/98-245.js` (era `245.html`, 26 linhas)

```text
Crie js/98-245.js. Ele faz: Alquimia v.14.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 173 — `js/98-246.js` (era `246.html`, 41 linhas)

```text
Crie js/98-246.js. Ele faz: Extrator de Dados Jurídicos.
No app original ele tinha estas funções/partes: extrair.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 174 — `js/98-247.js` (era `247.html`, 52 linhas)

```text
Crie js/98-247.js. Ele faz: 🚨 RECURSO URGENTE - FUNCIONA — 📋 FERRAMENTAS JURÍDICAS - URGENTE.
No app original ele tinha estas funções/partes: salvarCodigos.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 175 — `js/98-248.js` (era `248.html`, 65 linhas)

```text
Crie js/98-248.js. Ele faz: 🚨 MEU RECURSO PREVIDÊNCIA - FUNCIONA — ⚖️ RECURSO PREVIDÊNCIA - 7 DIAS.
No app original ele tinha estas funções/partes: salvarTudo, limparTudo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 176 — `js/98-249.js` (era `249.html`, 152 linhas)

```text
Crie js/98-249.js. Ele faz: Gerador de Cotejo Analítico.
No app original ele tinha estas funções/partes: add, limparTabela, exportarWord.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 177 — `js/98-25.js` (era `25.html`, 381 linhas)

```text
Crie js/98-25.js. Ele faz: SK Rastreador de Rotas & IA v6 - Maikon Caldeira.
No app original ele tinha estas funções/partes: showLoader, hideLoader, startDeepScan, renderSuspiciousList, openSuspiciousFile, saveFileChanges, downloadCleanProject.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 178 — `js/98-250.js` (era `250.html`, 13 linhas)

```text
Crie js/98-250.js. Ele faz: Extrator BPC Netflix — 🎬 PLATAFORMA BPC TRF6.
No app original ele tinha estas funções/partes: extrair, calc, tabela, copiar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 179 — `js/98-251.js` (era `251.html`, 228 linhas)

```text
Crie js/98-251.js. Ele faz: Maikon Caldeira - Advocacia — MAIKON CALDEIRA.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 180 — `js/98-252.js` (era `252.html`, 191 linhas)

```text
Crie js/98-252.js. Ele faz: Extrair Texto com Filtros.
No app original ele tinha estas funções/partes: showTab, cleanFooter, extractTextAuto, downloadText, downloadPDF, downloadDOCX, downloadMarkdown, copyText, loadTextManual, customFilter, applyCustomFilter, downloadTextManual, downloadPDFManual.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 181 — `js/98-253.js` (era `253.html`, 237 linhas)

```text
Crie js/98-253.js. Ele faz: Parecer de Liquidação Judicial - Dr. Braulino.
No app original ele tinha estas funções/partes: buscarBCB, parseTJMG, processarTudo, getPrevKey, gerarPDF.
Ele chamava estes endereços: https://api.bcb.gov.br/dados/serie/bcdata.sgs.${s}/dados?formato=json. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 182 — `js/98-254.js` (era `254.html`, 376 linhas)

```text
Crie js/98-254.js. Ele faz: Calculadora Judicial Completa — Calculadora Judicial Avançada.
No app original ele tinha estas funções/partes: fmtMoney, toYM, processData, fillSelect, fetchBCB, fmt, calculate, calcularHonorarios.
Ele chamava estes endereços: https://api.bcb.gov.br/dados/serie/bcdata.sgs.${code}/dados?formato=json&dataInicial=${fmt(ini)}&dataFinal=${fmt(fim)}. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 183 — `js/98-255.js` (era `255.html`, 446 linhas)

```text
Crie js/98-255.js. Ele faz: 🚀 Gerenciador PWA - Maikon Caldeira — 🚀 Gerenciador PWA Completo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 184 — `js/98-256.js` (era `256.html`, 246 linhas)

```text
Crie js/98-256.js. Ele faz: Exported HTML — Extrator Universal de Variáveis.
No app original ele tinha estas funções/partes: extrairTextoPDF, reprocessar, mostrarTextoBruto, adicionarVariavel, removerVar, exportarExcel.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 185 — `js/98-257.js` (era `257.html`, 329 linhas)

```text
Crie js/98-257.js. Ele faz: Gerador de Peças Jurídicas - TRF6/JEF.
No app original ele tinha estas funções/partes: addBlock, removeBlock, updateBlockContent, renderBlocksInputs, renderDoc, exportWord.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 186 — `js/98-258.js` (era `258.html`, 473 linhas)

```text
Crie js/98-258.js. Ele faz: Calculadora Judicial Manhumirim - Proveito Econômico — Calculadora Judicial Manhumirim - Híbrida.
No app original ele tinha estas funções/partes: toBRL, buscarBacen, processarImportacao, getValor, calcularTudo, exportarCSV, exportarXLSX, exportarPDF, exportarJSON, exportarDOCX.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 187 — `js/98-259.js` (era `259.html`, 590 linhas)

```text
Crie js/98-259.js. Ele faz: Painel Consolidado – Petições, Tabelas e CTC — Painel Consolidado – Petições, Tabelas e CTC.
No app original ele tinha estas funções/partes: show, togglePet, moedaParaNumero, baixarWord, limparTabela, pad2, exportarTexto, escapeHtml, gerarMS, gerarCon, gerarRev, adicionarRem, exportarRem, importarRemBatch, adicionarVin, exportarVin, importarVinBatch, adicionarCTC.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 188 — `js/98-26.js` (era `26.html`, 583 linhas)

```text
Crie js/98-26.js. Ele faz: SK-Mini Playground.
No app original ele tinha estas funções/partes: updateLineNumbers, syncScroll, searchCode, highlightMatches, handleFileImport, downloadCode, clearCode, runCode, openPasteModal, closePasteModal, handlePaste.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 189 — `js/98-260.js` (era `260.html`, 794 linhas)

```text
Crie js/98-260.js. Ele faz: Filtro Jurídico - Redução Real de Duplicatas — EMBARGOS DE DECLARAÇÃO.
No app original ele tinha estas funções/partes: setStatus, showLoad, hideLoad, extrairPDF, extrairWord, normalizar, shingles, jaccard, assinatura, splitParagrafos, limparMarlon, isDireito, isFatoRelevante, esc, processar, distribuir, atualizarDados, limpar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 190 — `js/98-261.js` (era `261.html`, 985 linhas)

```text
Crie js/98-261.js. Ele faz: PWA Scanner Multi-Formato + IA — 🔎 Scanner Multi-Formato + IA Jurídica.
No app original ele tinha estas funções/partes: atualizarTamanho, sincronizarTamanho, atualizarRespostaIA, sincronizarRespostaIA, mudarAba, mostrarModal, fecharModal, mostrarOpcoesSaida, carregarArquivo, processarZIP, processarTAR, processarHTML, ehTexto, renderArquivos, abrirArquivo, buscarTermos, temArquivo, temConteudo.
Ele chamava estes endereços: https://api.openai.com/v1/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 191 — `js/98-262.js` (era `262.html`, 847 linhas)

```text
Crie js/98-262.js. Ele faz: Filtrador Jurídico Master — Maikon Caldeira — ⚖️ Filtrador Jurídico Master.
No app original ele tinha estas funções/partes: saveState, loadState, setStatus, setImportProgress, switchTab, updateStats, download, escapeHtml, limparLixoImagem, extractTextFromPDF, ocrPDF, loadScript, extractTextFromDOCX, extractTextFromJSON, walk, cleanMarkdownNoise, splitParagraphs, normalizeForCompare.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 192 — `js/98-263.js` (era `263.html`, 98 linhas)

```text
Crie js/98-263.js. Ele faz: Scanner — Detector de Dependências Replit — 🔍 Scanner de Dependências Replit.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 193 — `js/98-264.js` (era `264.html`, 636 linhas)

```text
Crie js/98-264.js. Ele faz: Manual SK Editor 4 — Completo — SK Editor 4 — Manual Completo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 194 — `js/98-265.js` (era `265.html`, 13214 linhas)

```text
Crie js/98-265.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: lerArquivo, analisarCodigo, analisarFuncoes, analisarHTML, analisarCSS, pegarCorpo, isCerebro, isImportante, explicarFuncao, explicarHTML, explicarCSS, renderizarElementos, toggleCorpo, copiar, copiarTudo, filtrar, filtrarBusca, salvarNaMemoria.
Ele chamava estes endereços: https://api.openai.com/v1/chat/completions, https://generativelanguage.googleapis.com/v1beta/models/gemini-pro:generateContent?key=${aiSettings.apiKey}, https://api.anthropic.com/v1/messages, https://api.duckduckgo.com/?q=${encodeURIComponent(query)}&amp;amp;format=json&amp;amp;no_html=1&amp;amp;skip_disambig=1, ${baseUrl}/chat/completions, https://www.googleapis.com/drive/v3/about?fields=user, https://www.googleapis.com/upload/drive/v3/files?uploadType=multipart, https://google.serper.dev/search, https://api.search.brave.com/res/v1/web/search?q=${encodeURIComponent(query)}&amp;amp;count=${numResults}, https://api.tavily.com/search. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 195 — `js/98-267.js` (era `267.html`, 844 linhas)

```text
Crie js/98-267.js. Ele faz: Filtrador Jurídico Avançado (Anti-repetição) — 🔍 Filtrador Jurídico Avançado.
No app original ele tinha estas funções/partes: loadState, saveState, setStatus, download, cleanMarkdownNoise, smartSplitParagraph, splitParagraphs, normalizeForCompare, makeShingles, signature, jaccard, parseLines, buildRegexList, extractTextFromPDF, extractTextFromDOCX, extractTextFromJSON, walk, applyCaptureRules.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 196 — `js/98-268.js` (era `268.html`, 7656 linhas)

```text
Crie js/98-268.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: qsa, lsSet, showToast, openModal, closeModal, initEditor, saudacao, renderFileList, getFileIcon, openFile, onCodeChange, updatePreview, handleTab, newFile, createNewFile, deleteFile, saveProject, downloadProject.
Ele chamava estes endereços: https://api.anthropic.com/v1/messages, https://generativelanguage.googleapis.com/v1beta/models/${model}:generateContent?key=${key}, https://api.openai.com/v1/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 197 — `js/98-269.js` (era `269.html`, 288 linhas)

```text
Crie js/98-269.js. Ele faz: MANUAL (2) — Assistente Jurídico IA — Manual Completo.
No app original ele tinha estas funções/partes: marca, copiar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 198 — `js/98-27.js` (era `27.html`, 867 linhas)

```text
Crie js/98-27.js. Ele faz: SK Oficina Jurídica v4 - Maikon Caldeira.
No app original ele tinha estas funções/partes: showSection, showLoader, hideLoader, processZip, loadFromGitHub, renderFileList, checkSingleFileIsDirty, openFile, filterFiles, saveCurrentFileChanges, downloadModifiedZip, setExtractorUrl, fetchViaProxy, runWebExtractor, showExtSubTab, renderExtractorOverview, renderExtractorScripts, renderExtractorText.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 199 — `js/98-270.js` (era `270.html`, 440 linhas)

```text
Crie js/98-270.js. Ele faz: PLANO — 📋 Plano do projeto: artifacts teste.
No app original ele tinha estas funções/partes: marca, copiar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 200 — `js/98-271.js` (era `271.html`, 1800 linhas)

```text
Crie js/98-271.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: importMarkdowns, importZip, updateFileList, removeFile, moveUp, moveDown, previewOutput, downloadMarkdown, copyToClipboard, clearAll, convertMarkdownToHtml, extractReferences, updateReferences, copyReference, copyAllReferences, downloadHtml, copyHtmlToClipboard, loadSample.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 201 — `js/98-272.js` (era `272.html`, 1335 linhas)

```text
Crie js/98-272.js. Ele faz: Cirurgião de Código 3.0 — 🔬 CIRURGIÃO DE CÓDIGO 3.0.
No app original ele tinha estas funções/partes: nome, salvarMemoria, detectarProvedor, toggleVerChave, abrirModal, fecharModal, confirmarColagem, carregarArquivo, carregarZIP, renderizarListaArquivos, filtrarArquivos, abrirArquivoDoZip, processarCodigo, buscarNoCodigo, buscarReplit, buscarBugsRapido, irParaLinha, detectarReplit.
Ele chamava estes endereços: )) tags += , ) || limpada.includes(, ,, ${provedor.url}/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 202 — `js/98-273.js` (era `273.html`, 243 linhas)

```text
Crie js/98-273.js. Ele faz: Scanner — Detector de Dependências — 🔍 Scanner de Dependências.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 203 — `js/98-274.js` (era `274.html`, 2869 linhas)

```text
Crie js/98-274.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: createPlan, addPoint, updateUI, updatePlansList, selectPlan, deletePlan, generateMarkdown, generateJson, downloadPlans, generateMarkdownContent, copyOutput, clearForm, clearPlans, convertMarkdownToHtml, extractReferences, updateReferences, copyReference, copyAllReferences.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 204 — `js/98-275.js` (era `275.html`, 1772 linhas)

```text
Crie js/98-275.js. Ele faz: Painel Maikon Caldeira — Advocacia Digital — 📄 Importador de Markdown.
No app original ele tinha estas funções/partes: importMarkdowns, importZip, updateFileList, removeFile, moveUp, moveDown, previewOutput, downloadMarkdown, copyToClipboard, clearAll, importJson, convertToMarkdown, convertArray, convertObject, convertNested, traverse, convertMarkdownToHtml, extractReferences.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 205 — `js/98-276.js` (era `276.html`, 966 linhas)

```text
Crie js/98-276.js. Ele faz: 3 Ferramentas Completas - Bugs, Versões e APK — 🛠️ 3 Ferramentas Completas.
No app original ele tinha estas funções/partes: extrairBugs, percorrer, gerarRelatorioVersoes, desenharGrafico, gerarScriptAPK, compararVersoes, mudarTab, copiar, baixarScript.
O original usava as bibliotecas fs, path: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 206 — `js/98-277.js` (era `277.html`, 4633 linhas)

```text
Crie js/98-277.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: carregarDados, salvarDados, adicionarLink, limparFormulario, atualizarLista, alternarLink, removerLink, marcarTodos, desmarcarTodos, limparTudo, atualizarEstatisticas, abrirSelecionados, abrirVisualizador, alternarTelaCheia, proximoLink, linkAnterior, fecharVisualizador, escHtml.
Ele chamava estes endereços: https://api.openai.com/v1/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 207 — `js/98-279.js` (era `279.html`, 246 linhas)

```text
Crie js/98-279.js. Ele faz: Análise: persistFiles.ts — 🔬 persistFiles.ts.
No app original ele tinha estas funções/partes: dbSaveFile, dbDeleteFile, dbDeleteAllFiles, restoreProjectFromDb, ensureProjectOnDisk, dbSaveDirectoryTree, walk.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 208 — `js/98-28.js` (era `28.html`, 274 linhas)

```text
Crie js/98-28.js. Ele faz: SK Decodificador & Comparador de Logs v6.
No app original ele tinha estas funções/partes: switchTab, decodeLog, compareLogs.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 209 — `js/98-280.js` (era `280.html`, 4180 linhas)

```text
Crie js/98-280.js. Ele faz: analise_Manual.tsx.md — analise_Manual.tsx.md.
No app original ele tinha estas funções/partes: Manual, initDb.
O original usava as bibliotecas react, jszip, file-saver, dotenv, @neondatabase/serverless, fs: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: /api/twa-files?url=${encodeURIComponent(url)}, /api/pwa-check?url=${encodeURIComponent(url)}. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 210 — `js/98-281.js` (era `281.html`, 10987 linhas)

```text
Crie js/98-281.js. Ele faz: analise_legal-assistant.tsx.md — analise_legal-assistant.tsx.md.
No app original ele tinha estas funções/partes: LegalAssistant.
O original usava as bibliotecas react, wouter, @tanstack/react-query, @shared/schema, lucide-react: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: /api/demo-key-status, /api/demo-key-config, /api/tts, /api/voice-chat, /api/doc-templates/upload-docx, /api/export/word-with-template, /api/jurisprudencia/buscar, /api/code-assistant, /api/import/url, /api/upload/extract-text, /api/upload/transcribe, /api/ai/process, /api/ai/refine, /api/git-push, /api/ai-usage-summary, /api/ai-usage-credit, /api/demo-key-test. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 211 — `js/98-282.js` (era `282.html`, 5804 linhas)

```text
Crie js/98-282.js. Ele faz: analise_EditorLayout.tsx.md — analise_EditorLayout.tsx.md.
No app original ele tinha estas funções/partes: NameInputModal, buildAsciiTree, sortKeys, render, generateDocs, explainFile, explainFolder, generateSystemInfo, EditorLayout.
O original usava as bibliotecas react, lucide-react, node-fetch, axios, fs: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: https://api.exemplo.com, https://api.github.com/users/nome, /api/workspace/write, /api/workspace/sync, /api/db/query. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 212 — `js/98-283.js` (era `283.html`, 3706 linhas)

```text
Crie js/98-283.js. Ele faz: Análise: App.tsx — 🔬 App.tsx.
No app original ele tinha estas funções/partes: callAI, detectAIProvider, uploadToDrive, downloadBlob, FileTree, App, handleFileImport, handleImportAssistenteJuridico, handleImportSkCodeEditor, handleImportApkBuilder, onFileInput, onDrop, restoreSession, handleGhImport, handleGhCustomImport, handlePublicRepoImport, handleUrlImport, handleEASDeploy.
Ele chamava estes endereços: ${base}/chat/completions, ${domain}/api/healthz, https://api.github.com/repos/${ghUser.login}/${repoName}/actions/workflows/build-apk.yml/dispatches, https://api.github.com/repos/${ghUser.login}/${repoName}/actions/runs?per_page=1, https://api.github.com/repos/${ciRepoOwner}/${ciRepoName}/actions/workflows/build-apk.yml/dispatches, https://api.github.com/repos/${ciRepoOwner}/${ciRepoName}/actions/runs?per_page=1, https://api.github.com/repos/${ghUser.login}/${repoName}/actions/workflows/build-desktop.yml/dispatches, https://${p.host}/sql. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 213 — `js/98-284.js` (era `284.html`, 85 linhas)

```text
Crie js/98-284.js. Ele faz: 200+ Códigos Jurídicos — 📂 200+ Códigos Auto-Listados.
No app original ele tinha estas funções/partes: carregar200, adicionarLink, temLink.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 214 — `js/98-285.js` (era `285.html`, 239 linhas)

```text
Crie js/98-285.js. Ele faz: Gerador PWA - Maikon Caldeira — 🚀 Gerador PWA - Maikon Caldeira.
No app original ele tinha estas funções/partes: adicionarApp, atualizarLista, removerApp, limparCampos, gerarIndex, gerarManifest, gerarSW, gerarTudo, mostrarPreview.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 215 — `js/98-286.js` (era `286.html`, 207 linhas)

```text
Crie js/98-286.js. Ele faz: Gerador de Arquivo .env - Assistente Jurídico — Gerador de Arquivo .env - Assistente Jurídico.
No app original ele tinha estas funções/partes: addEntry.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 216 — `js/98-287.js` (era `287.html`, 211 linhas)

```text
Crie js/98-287.js. Ele faz: Calculadora Mike Definitiva.
No app original ele tinha estas funções/partes: lerCSV, calcular, fmt.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 217 — `js/98-288.js` (era `288.html`, 162 linhas)

```text
Crie js/98-288.js. Ele faz: Editor de Cotejo Analítico - Proporcionalidade de Danos — Editor de Cotejo Analítico - Danos.
No app original ele tinha estas funções/partes: gerarResumo, formatarProcesso, download.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 218 — `js/98-289.js` (era `289.html`, 224 linhas)

```text
Crie js/98-289.js. Ele faz: Guia de Recuperação e Configuração do Projeto Maikon — Guia de Recuperação e Configuração do Projeto Maikon.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 219 — `js/98-29.js` (era `29.html`, 691 linhas)

```text
Crie js/98-29.js. Ele faz: SK-Code Debugger — Verificar Código.
No app original ele tinha estas funções/partes: toggleSidebar, setPM, togglePreviewMin, startVDrag, onVDrag, stopVDrag, mTab, initTabs, analyzeCode, renderAnalysis, renderIssues, renderFixes, renderFunctions, escapeHtml, switchTab, handleFileImport, pasteCode, clearInput.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 220 — `js/98-290.js` (era `290.html`, 241 linhas)

```text
Crie js/98-290.js. Ele faz: nova_ferramenta — Guia de Recuperação e Configuração do Projeto Maikon.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 221 — `js/98-291.js` (era `291.html`, 258 linhas)

```text
Crie js/98-291.js. Ele faz: Auditoria Master - Dr. MAIKON DA ROCHA CALDEIRA — ⚖️ Auditoria Pericial.
No app original ele tinha estas funções/partes: buscarBCB, parseTJMG, getPrevKey, processarAuditoria.
Ele chamava estes endereços: https://api.bcb.gov.br/dados/serie/bcdata.sgs.${s}/dados?formato=json. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 222 — `js/98-292.js` (era `292.html`, 430 linhas)

```text
Crie js/98-292.js. Ele faz: Extrator de Texto Pro.
No app original ele tinha estas funções/partes: preventDefaults, handleDrop, updateFileName, cleanFooter, toggleLoading, extractText, finalizeExtraction, downloadText, downloadPDF, downloadDOCX, downloadMarkdown, saveFile, copyText, toggleTheme.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 223 — `js/98-293.js` (era `293.html`, 303 linhas)

```text
Crie js/98-293.js. Ele faz: Monica Jurídico v7.0 - Comparador de Cenários (Perícia Bancária).
No app original ele tinha estas funções/partes: setLog, buscarBCB, lerExcel, processarCenarios.
Ele chamava estes endereços: https://api.bcb.gov.br/dados/serie/bcdata.sgs.${sgs}/dados?formato=json&dataInicial=${di}/${mi}/${ai}&dataFinal=${df}/${mf}/${af}. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 224 — `js/98-294.js` (era `294.html`, 310 linhas)

```text
Crie js/98-294.js. Ele faz: A Oficina Digital do Mike da Galera — Oficina Digital:O Futuro do Direito.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 225 — `js/98-295.js` (era `295.html`, 402 linhas)

```text
Crie js/98-295.js. Ele faz: Editor Jurídico Visual Law - Versão Final — Editor Jurídico Visual Law.
No app original ele tinha estas funções/partes: saveData, addBlock, removeBlock, updateBlock, moveBlock, render, renderPreview, exportWord, clearAll.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 226 — `js/98-296.js` (era `296.html`, 458 linhas)

```text
Crie js/98-296.js. Ele faz: Calculadora Judicial Híbrida (Fixo vs Variável) — Calculadora Judicial Híbrida.
No app original ele tinha estas funções/partes: toBRL, parseDataBR, dataParaTexto, processarImportacao, buscarBacen, limparImportacao, getValor, calcularTudo, exportarCSV.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 227 — `js/98-297.js` (era `297.html`, 377 linhas)

```text
Crie js/98-297.js. Ele faz: Calculadora Pericial: Sentença vs Contrato (Cartão/Taxa Média).
No app original ele tinha estas funções/partes: processCSV, populateSelects, selectOptionContains, calculate, exportResults.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 228 — `js/98-298.js` (era `298.html`, 475 linhas)

```text
Crie js/98-298.js. Ele faz: Calculadora de Liquidação & Proveito Econômico — Calculadora de Liquidação & Sucumbência.
No app original ele tinha estas funções/partes: parseMoney, formatMoney, parseIndices, calcular, renderTable, exportData, importData, exportCSV.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 229 — `js/98-299.js` (era `299.html`, 442 linhas)

```text
Crie js/98-299.js. Ele faz: Painel – Flexibilização de Renda — MAIKON DA ROCHA CALDEIRA - OAB/MG 183.712.
No app original ele tinha estas funções/partes: lerMoeda, ativarMascara, addRow, importCSV, recalc, sum, calcPerCapita, avaliarConformidade, getState, pickRows, setState, saveLocal, loadLocal, exportJSON, exportCSV, toCSV.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 230 — `js/98-3.js` (era `3.html`, 1026 linhas)

```text
Crie js/98-3.js. Ele faz: Conversor NPM → CDN — 📦 Conversor NPM → CDN.
No app original ele tinha estas funções/partes: evOver, evLeave, evDrop, lerZip, analisarPkg, renderAnalise, renderPacote, renderPopulares, buscarPacote, buscarPacoteNome, gerarHTML, App, copiarHTML, baixarHTML, renderTabela.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 231 — `js/98-30.js` (era `30.html`, 1475 linhas)

```text
Crie js/98-30.js. Ele faz: Cirurgião de Código 3.0 — 🔬 CIRURGIÃO DE CÓDIGO 3.0.
No app original ele tinha estas funções/partes: nome, salvarMemoria, detectarProvedor, toggleVerChave, abrirModal, fecharModal, confirmarColagem, carregarArquivo, carregarZIP, renderizarListaArquivos, filtrarArquivos, abrirArquivoDoZip, processarCodigo, gerarReadmeGitHub, buscarNoCodigo, buscarReplit, buscarBugsRapido, irParaLinha.
Ele chamava estes endereços: )) tags += , ) || limpada.includes(, ,, ${provedor.url}/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 232 — `js/98-300.js` (era `300.html`, 766 linhas)

```text
Crie js/98-300.js. Ele faz: Rastreador de Histórico Replit — PWA Jurídico — 📜 Rastreador de Histórico Replit.
No app original ele tinha estas funções/partes: handleFile, analyzeVersions, analyzeStructure, analyzeFileContent, parseVersionDate, displayTimeline, formatDate, escapeHtml, exportTimeline, downloadFile.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 233 — `js/98-301.js` (era `301.html`, 507 linhas)

```text
Crie js/98-301.js. Ele faz: Calculadora Judicial Premium - Mike da Galera.
No app original ele tinha estas funções/partes: fmtBRL, parseData, toggleJurosInput, buscarSerie, calcular, renderTable, renderChart, exportarRelatorio.
Ele chamava estes endereços: https://api.bcb.gov.br/dados/serie/bcdata.sgs.${codigo}/dados?formato=json. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 234 — `js/98-302.js` (era `302.html`, 623 linhas)

```text
Crie js/98-302.js. Ele faz: Leitor de Projeto — 🔍 Leitor de Projeto.
No app original ele tinha estas funções/partes: lerArquivo, analisarCodigo, pegarCorpo, classificar, explicar, renderizarFuncoes, toggleCorpo, copiar, filtrar, filtrarBusca, escaparHtml.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 235 — `js/98-303.js` (era `303.html`, 179 linhas)

```text
Crie js/98-303.js. Ele faz: MANUAL (3) — SK Jurídico — Manual Completo.
No app original ele tinha estas funções/partes: marca, copiar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 236 — `js/98-304.js` (era `304.html`, 729 linhas)

```text
Crie js/98-304.js. Ele faz: Filtrador Avançado de Documentos Jurídicos — 🔧 Filtrador de Documentos.
No app original ele tinha estas funções/partes: mostrarToast, atualizarProgresso, adicionarFiltro, removerFiltro, carregarArquivos, lerArquivo, processar, obterFiltros, limparTexto, quebrarParagrafos, filtrarDuplicatas, normalizar, calcularSimilaridade, deveIncluir, exportar, limparTudo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 237 — `js/98-305.js` (era `305.html`, 882 linhas)

```text
Crie js/98-305.js. Ele faz: 🔌 Testador de API — Com Proxy em Cascata — 🔌 Testador de API.
No app original ele tinha estas funções/partes: carregarTemplates, selecionarTemplate, testarAPI, testarTodosProxies, testarPlayground, atualizarUI, mostrarStatus.
Ele chamava estes endereços: https://api.groq.com/openai/v1/chat/completions, https://api.neon.tech/v1/databases, https://api.openai.com/v1/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 238 — `js/98-306.js` (era `306.html`, 449 linhas)

```text
Crie js/98-306.js. Ele faz: Editor HTML — Olá mundo!.
No app original ele tinha estas funções/partes: carregarPadroesTheoMiguel, renderizarListaVariaveis, restaurarPadrao, extrairTextoPDF, extrairTextoWord, reprocessar, mostrarTextoBruto, adicionarVariavel, removerVar, verificarDados, exportarExcel, exportarPDF, exportarJSON, exportarWord.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 239 — `js/98-307.js` (era `307.html`, 635 linhas)

```text
Crie js/98-307.js. Ele faz: 🧩 Montador de Módulos — PWA Jurídico — 🧩 Montador de Módulos PWA JURÍDICO — MAIKON CALDEIRA.
No app original ele tinha estas funções/partes: getModules, setModules, getSelected, setSelected, showSection, showToast, saveModule, clearForm, renderModules, filterModules, deleteModule, copyModule, viewModule, editModule, renderBuildChecklist, toggleSelect, selectAll, deselectAll.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 240 — `js/98-308.js` (era `308.html`, 388 linhas)

```text
Crie js/98-308.js. Ele faz: guia-completo-apk (2) — 📱 Guia Completo — Como Transformar Qualquer Projeto em APK.
No app original ele tinha estas funções/partes: marca, copiar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 241 — `js/98-309.js` (era `309.html`, 1044 linhas)

```text
Crie js/98-309.js. Ele faz: 🔍 Scanner de Dependências — SK Editor — 🔍 Scanner de Dependências — SK Editor.
No app original ele tinha estas funções/partes: loadPatterns, savePatterns, resetPatterns, addCustomPattern, removeCustomPattern, renderPatternsList, getAllPatterns, escapeRegex, escHtml, switchTab, onDragOver, onDragLeave, onDrop, onFileSelected, importarArquivo, importarGitHub, fetchComTimeout, scanTexto.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 242 — `js/98-31.js` (era `31.html`, 794 linhas)

```text
Crie js/98-31.js. Ele faz: Navegador PWA com Proxys.
No app original ele tinha estas funções/partes: init, setupEventListeners, navigate, tentarProxyCascata, goBack, goForward, reload, carregarFavoritos, salvarFavoritosLocal, renderizarFavoritos, adicionarFavorito, removerFavorito, atualizarBotaoFavorito, traduzirConteudo, mostrarErro.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 243 — `js/98-310.js` (era `310.html`, 672 linhas)

```text
Crie js/98-310.js. Ele faz: Extrator de Vínculos Previdenciários - Análise Processual — Extrator de Vínculos Previdenciários.
No app original ele tinha estas funções/partes: extrairTextoPDF, extrairTextoWord, reprocessar, gerarResumoMinuta, renderizarVariaveis, mostrarTextoBruto, copiarTexto, copiarResumo, adicionarVariavel, removerVar, mostrarManualRegex, fecharManual, exportarMinutaWord, exportarResumoTXT, exportarExcel.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 244 — `js/98-311.js` (era `311.html`, 975 linhas)

```text
Crie js/98-311.js. Ele faz: Calculadora Jurídica - Juros e Correção — ⚖️ Calculadora Jurídica de Juros e Correção Monetária.
No app original ele tinha estas funções/partes: setStatus, formatarMoeda, formatarPercentual, parseData, getMesesEntre, calcularJurosSimples, calcularJurosCompostosMensal, calcularJurosCompostosAnual, calcularCorrecao, calcularCenario, exibirResultados, parseCSV, exibirIndices.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 245 — `js/98-312.js` (era `312.html`, 891 linhas)

```text
Crie js/98-312.js. Ele faz: Playground Code Pro — Maikon Caldeira — Bem-vindo ao Playground Pro.
No app original ele tinha estas funções/partes: App, updateLineNumbers, updateCursorPosition, jumpToLine, openGotoLine, closeGotoLine, gotoLine, saveCurrentTab, loadEditorContent, switchTab, updateTabs, switchMode, debouncePreview, buildDocument, main, updatePreview, autoSave, copyCode.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 246 — `js/98-313.js` (era `313.html`, 1066 linhas)

```text
Crie js/98-313.js. Ele faz: Chat IA — Chat IA.
No app original ele tinha estas funções/partes: detectProvider, boot, toggleCfg, toggleKeys, onKeyInput, updateProvBadge, updateCfgStatus, toggleShowKey, saveKey, renderSavedKeys, loadKey, deleteKey, handleKey, adjustHeight, setPrompt, send, abortStream, appendMsg.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 247 — `js/98-314.js` (era `314.html`, 2581 linhas)

```text
Crie js/98-314.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: atualizarProvedor, testarConexaoIA, carregarArquivo, processarZIP, processarTAR, processarHTML, ehTexto, renderArquivos, abrirArquivo, detectarReplit, detectarAPIs, detectarFuncoes, detectarBugs, detectarDependencias, mostrarResultados, filtrarResultados, renderizarPagina, proximaPagina.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 248 — `js/98-315.js` (era `315.html`, 703 linhas)

```text
Crie js/98-315.js. Ele faz: Filtrador Jurídico Avançado (Atualizado) — Filtrador Jurídico Avançado (Atualizado).
No app original ele tinha estas funções/partes: loadState, saveState, setStatus, download, cleanMarkdownNoise, splitParagraphs, normalizeForCompare, makeShingles, signature, jaccard, parseLines, buildRegexList, extractTextFromPDF, extractTextFromDOCX, extractTextFromJSON, walk, applyBanRules, applyCaptureRules.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 249 — `js/98-316.js` (era `316.html`, 1790 linhas)

```text
Crie js/98-316.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: showSection, showLoader, hideLoader, processZip, loadFromGitHub, renderFileList, checkSingleFileIsDirty, openFile, filterFiles, saveCurrentFileChanges, downloadModifiedZip, setExtractorUrl, fetchViaProxy, runWebExtractor, showExtSubTab, renderExtractorOverview, renderExtractorScripts, renderExtractorText.
O original usava as bibliotecas vite, @vitejs/plugin-react: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 250 — `js/98-317.js` (era `317.html`, 3574 linhas)

```text
Crie js/98-317.js. Ele faz: Painel Maikon Caldeira — Advocacia Digital — 🔍 Analisador de Versões — PWA Jurídico.
No app original ele tinha estas funções/partes: handleFiles, displayAnalysis, handleFile, processZip, processTar, shouldExtractContent, analyzeFileStructure, analyzeCodeContent, generateFolderStructure, getImportantFiles, escapeHtml, switchTab, exportAsJSON, exportAsMarkdown, exportAsHTML, downloadFile, analyzeVersions, analyzeStructure.
O original usava as bibliotecas ${comp.file}: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 251 — `js/98-318.js` (era `318.html`, 2116 linhas)

```text
Crie js/98-318.js. Ele faz: RECEITA — 🧬 Receita para recriar: APK Builder.
No app original ele tinha estas funções/partes: marca, copiar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 252 — `js/98-319.js` (era `319.html`, 15724 linhas)

```text
Crie js/98-319.js. Ele faz: Blocos de js/1.html.md.js — ✂️ js/1.html.md.js — 299 blocos.
No app original ele tinha estas funções/partes: resizePreview, exportarProjeto, getFileColor, MiniVFSRobusto, MiniFileTree, MiniEditor, toggleSidebar, renderizarApps, renderizarListaApps, abrirModal, fecharModal, limparFormulario, adicionarApp, removerApp, gerarManifest, gerarServiceWorker, gerarIcones, baixarTudo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 253 — `js/98-32.js` (era `32.html`, 1034 linhas)

```text
Crie js/98-32.js. Ele faz: Auditoria Financeira — Calculadora Sentença — Auditoria Financeira — Calculadora de Sentença.
No app original ele tinha estas funções/partes: setClock, log, fmtBRL, fmtPct, fmtFator, toNum, parseDateBR, dateToYM, listMonths, ymToLabel, fetchBCB, fetchTJMG, getTJMGCorrection, calcularRecursal, calcular, renderParecer, salvarDados.
Ele chamava estes endereços: https://api.bcb.gov.br/dados/serie/bcdata.sgs., /api/tjmg/fatores?startYear=, /api/share/parecer, /api/export/word. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 254 — `js/98-320.js` (era `320.html`, 370 linhas)

```text
Crie js/98-320.js. Ele faz: Gerador de APK — EAS Config — Gerador de Config EAS.
No app original ele tinha estas funções/partes: loadZip, processZipFile, autoSlug, autoPackage, selectBuild, generateFiles.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 255 — `js/98-321.js` (era `321.html`, 1785 linhas)

```text
Crie js/98-321.js. Ele faz: Análise: Terminal.tsx — 🔬 Terminal.tsx.
No app original ele tinha estas funções/partes: simulateInstallDelay, Terminal, createTables, testConnection, setupDatabase, query, getClient, signUp, signIn, signOut, getUser, getAll, getById, insert, update, remove, uploadFile, subscribeToTable.
O original usava as bibliotecas firebase, firebas<, ytdl-core, fs, fluent-ffmpeg, better-sqlite3, pg, mongoose, ${mod}, @supabase/supabase-js, path: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 256 — `js/98-322.js` (era `322.html`, 863 linhas)

```text
Crie js/98-322.js. Ele faz: Análise: RealTerminal.tsx — 🔬 RealTerminal.tsx.
No app original ele tinha estas funções/partes: detectMissingPkg, RealTerminal, sendCmd, explainErrorPt.
Ele chamava estes endereços: https://registry.npmjs.org/-/v1/search?text=${encodeURIComponent(query)}&amp;size=8, https://pypi.org/pypi/${encodeURIComponent(n)}/json. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 257 — `js/98-323.js` (era `323.html`, 881 linhas)

```text
Crie js/98-323.js. Ele faz: Análise: pwa.tsx — 🔬 pwa.tsx.
No app original ele tinha estas funções/partes: PwaScreen.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 258 — `js/98-324.js` (era `324.html`, 3910 linhas)

```text
Crie js/98-324.js. Ele faz: Análise: pacote-ia.txt.md — 🔬 pacote-ia.txt.md.
No app original ele tinha estas funções/partes: buildAll, detectTermMode, App, _resolveComponent, PreviewRenderer, loadComponent, component, getBasePath, getPreviewExamplePath, Gallery, getPreviewPath, setCors, readBody, handleAIChat, handleHealth, detectPort, proxyRequest, startServer.
O original usava as bibliotecas node:path, node:url, @capacitor/cli, node:module, http, url, electron, fs, path, child_process, os: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: ${GEMINI_BASE}/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 259 — `js/98-325.js` (era `325.html`, 3910 linhas)

```text
Crie js/98-325.js. Ele faz: Análise: pacote-ia.txt.md — 🔬 pacote-ia.txt.md.
No app original ele tinha estas funções/partes: buildAll, detectTermMode, App, _resolveComponent, PreviewRenderer, loadComponent, component, getBasePath, getPreviewExamplePath, Gallery, getPreviewPath, setCors, readBody, handleAIChat, handleHealth, detectPort, proxyRequest, startServer.
O original usava as bibliotecas node:path, node:url, @capacitor/cli, node:module, http, url, electron, fs, path, child_process, os: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: ${GEMINI_BASE}/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 260 — `js/98-326.js` (era `326.html`, 4226 linhas)

```text
Crie js/98-326.js. Ele faz: Análise: legal-assistant.tsx.recovered — 🔬 legal-assistant.tsx.recovered.
No app original ele tinha estas funções/partes: LegalAssistant.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 261 — `js/98-327.js` (era `327.html`, 1438 linhas)

```text
Crie js/98-327.js. Ele faz: Análise: keys.tsx — 🔬 keys.tsx.
No app original ele tinha estas funções/partes: uid, statusColor, statusLabel, ManualModal, CreateTableModal, addCol, removeCol, setColName, setColType, run, KeysScreen, pickManual, addKey, testKey, testAll, testNeon, runSql, runAiDb.
Ele chamava estes endereços: ${base}/chat/completions, ${base}/api/healthz. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 262 — `js/98-328.js` (era `328.html`, 1126 linhas)

```text
Crie js/98-328.js. Ele faz: Análise: github.tsx — 🔬 github.tsx.
No app original ele tinha estas funções/partes: Field, ToggleRow, GitHubScreen, doPublicImport, doImport, loadRepoTree, loadFileContent, importFromAnalyze, publishAsApp, doPush, saveConfig, generateSystemReport.
Ele chamava estes endereços: https://api.github.com/repos/${owner}/${name}/git/trees/${repo.default_branch}?recursive=1, https://api.github.com/repos/${owner}/${name}/contents/${path}, https://api.github.com/repos/${owner}/${rname}/pages. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 263 — `js/98-329.js` (era `329.html`, 3015 linhas)

```text
Crie js/98-329.js. Ele faz: Análise: EditorLayout.tsx — 🔬 EditorLayout.tsx.
No app original ele tinha estas funções/partes: NameInputModal, buildAsciiTree, sortKeys, render, generateDocs, explainFile, explainFolder, generateSystemInfo, EditorLayout.
O original usava as bibliotecas node-fetch, axios, fs: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 264 — `js/98-33.js` (era `33.html`, 1281 linhas)

```text
Crie js/98-33.js. Ele faz: Assistente Jurídico.
No app original ele tinha estas funções/partes: loadLS, saveLS, detectProvider, getChaveResumo, getChaveGeracao, getModelo, salvarChaves, limparChaves, atualizarBadge, testarChaves, atualizarEsforco, atualizarVerbosity, toggleVerbosity, toggleConfig, mudarAba, importarArquivo, extrairPDF, extrairDOCX.
Ele chamava estes endereços: ${baseUrl}/chat/completions, https://api.anthropic.com/v1/messages. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 265 — `js/98-330.js` (era `330.html`, 1132 linhas)

```text
Crie js/98-330.js. Ele faz: Análise: DatabasePanel.tsx — 🔬 DatabasePanel.tsx.
No app original ele tinha estas funções/partes: loadSavedConnections, saveSavedConnections, neonErrorMsg, runNeonQuery, CodeBlock, QueryResultTable, NeonTab, SQLiteTab, GuiasTab, testar, CredenciaisTab, DatabasePanel.
O original usava as bibliotecas @neondatabase/serverless, pg, @supabase/supabase-js, better-sqlite3, mysql2, dotenv, fs: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 266 — `js/98-331.js` (era `331.html`, 2687 linhas)

```text
Crie js/98-331.js. Ele faz: Análise: App.tsx — 🔬 App.tsx.
No app original ele tinha estas funções/partes: callAI, detectAIProvider, uploadToDrive, downloadBlob, App, handleFileImport, applyCustomName, handleImportAssistenteJuridico, onFileInput, onDrop, restoreSession, handleGhImport, handleGhCustomImport, handlePublicRepoImport, handleUrlImport, handleEASDeploy, handleFullDeploy, handleCiBuild.
Ele chamava estes endereços: ${base}/chat/completions, ${domain}/api/healthz, ${import.meta.env.BASE_URL}assistente-juridico-pwa.zip, https://api.github.com/repos/${ghUser.login}/${repoName}/actions/workflows/build-apk.yml/dispatches, https://api.github.com/repos/${ghUser.login}/${repoName}/actions/runs?per_page=1, https://api.github.com/repos/${ciRepoOwner}/${ciRepoName}/actions/workflows/build-apk.yml/dispatches, https://api.github.com/repos/${ciRepoOwner}/${ciRepoName}/actions/runs?per_page=1. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 267 — `js/98-332.js` (era `332.html`, 3706 linhas)

```text
Crie js/98-332.js. Ele faz: Análise: App.tsx — 🔬 App.tsx.
No app original ele tinha estas funções/partes: callAI, detectAIProvider, uploadToDrive, downloadBlob, FileTree, App, handleFileImport, handleImportAssistenteJuridico, handleImportSkCodeEditor, handleImportApkBuilder, onFileInput, onDrop, restoreSession, handleGhImport, handleGhCustomImport, handlePublicRepoImport, handleUrlImport, handleEASDeploy.
Ele chamava estes endereços: ${base}/chat/completions, ${domain}/api/healthz, https://api.github.com/repos/${ghUser.login}/${repoName}/actions/workflows/build-apk.yml/dispatches, https://api.github.com/repos/${ghUser.login}/${repoName}/actions/runs?per_page=1, https://api.github.com/repos/${ciRepoOwner}/${ciRepoName}/actions/workflows/build-apk.yml/dispatches, https://api.github.com/repos/${ciRepoOwner}/${ciRepoName}/actions/runs?per_page=1, https://api.github.com/repos/${ghUser.login}/${repoName}/actions/workflows/build-desktop.yml/dispatches, https://${p.host}/sql. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 268 — `js/98-334.js` (era `334.html`, 38 linhas)

```text
Crie js/98-334.js. Ele faz: Cartao de Perfil.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 269 — `js/98-335.js` (era `335.html`, 83 linhas)

```text
Crie js/98-335.js. Ele faz: Importar TJMG.
No app original ele tinha estas funções/partes: renderizarTabela.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 270 — `js/98-336.js` (era `336.html`, 102 linhas)

```text
Crie js/98-336.js. Ele faz: Painel Estruturado - Embargos & Cotejo — Painel Estruturado - Embargos & Cotejo.
No app original ele tinha estas funções/partes: extrair, validar, exportWord.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 271 — `js/98-337.js` (era `337.html`, 185 linhas)

```text
Crie js/98-337.js. Ele faz: Leitor de CNIS - Visual.
No app original ele tinha estas funções/partes: mostrarStatus, lerCNIS, extrairVinculos, mostrarNaTela.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 272 — `js/98-338.js` (era `338.html`, 264 linhas)

```text
Crie js/98-338.js. Ele faz: Rural Adjair.
No app original ele tinha estas funções/partes: adicionarPeriodo, removerPeriodo, formatarData, gerarEImprimir, limparTudo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 273 — `js/98-339.js` (era `339.html`, 356 linhas)

```text
Crie js/98-339.js. Ele faz: Calculadora de Honorários & Liquidação (Anual vs Mensal) — Calculadora Judicial & Honorários.
No app original ele tinha estas funções/partes: parseDataInput, toBRL, calcular.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 274 — `js/98-34.js` (era `34.html`, 255 linhas)

```text
Crie js/98-34.js. Ele faz: SK Editor Jurídico v2 - Seu Ambiente — 🔧 SK Editor Jurídico v2.
No app original ele tinha estas funções/partes: showTab, loadZip, loadFromGitHub, processZip, renderFileList, openFile, filterFiles, openPreview, generateBrain, generateProjectPlan, runDiagnosis, saveToken.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 275 — `js/98-340.js` (era `340.html`, 174 linhas)

```text
Crie js/98-340.js. Ele faz: manual-dev — Manual para Desenvolvedores — Correções Necessárias no App Mobile.
No app original ele tinha estas funções/partes: clonarRepositorio, construirArvore, ordenarFilhos, executarComandoOffline, syncTudo, syncArquivoAtivo, marca, copiar.
Ele chamava estes endereços: https://api.github.com/repos/${owner}/${repo}/git/trees/${branch}?recursive=1, https://api.github.com/repos/${owner}/${repo}/contents/${arquivo.path}?ref=${branch}, /api/sync, /api/workspace/write. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 276 — `js/98-341.js` (era `341.html`, 421 linhas)

```text
Crie js/98-341.js. Ele faz: Sistema de Perícia Judicial Bancária - Dr. Manhumirim — JurisCalc Perícia Pro.
No app original ele tinha estas funções/partes: fetchBCB, switchTab, executarPericia, renderChart.
Ele chamava estes endereços: https://api.bcb.gov.br/dados/serie/bcdata.sgs.${code}/dados?formato=json. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 277 — `js/98-342.js` (era `342.html`, 422 linhas)

```text
Crie js/98-342.js. Ele faz: Extrator Jurídico - Contrato Falsificado (INSS/Estelionato) — Extrator Jurídico - Contrato Falsificado.
No app original ele tinha estas funções/partes: loadState, saveState, renderizarListaVariaveis, adicionarVariavel, removerVar, restaurarPadrao, extrairTextoPDF, extrairTextoWord, mostrarTextoBruto, reprocessar, exportarJSON, exportarExcel, exportarXML, escapeXml, exportarPDF, exportarWord, download.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 278 — `js/98-343.js` (era `343.html`, 469 linhas)

```text
Crie js/98-343.js. Ele faz: Mike Legal AI - Importador Universal.
No app original ele tinha estas funções/partes: lerExcel, lerTextoPDF, processarMatriz, parseMes, derivarIndicesMensais, calcular, fmtKey, fmtBRL, setStatus, exportarRelatorio.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 279 — `js/98-344.js` (era `344.html`, 1019 linhas)

```text
Crie js/98-344.js. Ele faz: Code Merger Pro — Maikon Caldeira.
No app original ele tinha estas funções/partes: generateId, saveState, addProject, deleteProject, selectProject, updateProjectCode, analyzeHTML, renderProjects, moveUp, moveDown, openImportModal, closeImportModal, importCode, importFromFile, analyzeCode, mergeAll, generateMergedCode, updatePreview.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 280 — `js/98-345.js` (era `345.html`, 774 linhas)

```text
Crie js/98-345.js. Ele faz: 🗄️ Painel de Banco de Dados.
No app original ele tinha estas funções/partes: testar, switchTab, togglePassword, testConnection, runQuery, runQuickQuery, initSQLite, loadSQLiteFile, runSQLiteQuery, addCredential, renderCredentials, useCredential, deleteCredential, showResult, copyCode, updateStatusBadge.
O original usava as bibliotecas dotenv, pg: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 281 — `js/98-346.js` (era `346.html`, 789 linhas)

```text
Crie js/98-346.js. Ele faz: Maikon Caldeira - Advocacia Digital — Maikon Caldeira.
No app original ele tinha estas funções/partes: renderizarApps, renderizarListaApps, abrirModal, fecharModal, limparFormulario, adicionarApp, removerApp, gerarManifest, gerarServiceWorker, gerarIcones, baixarTudo, baixarArquivo, mostrarAlerta.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 282 — `js/98-347.js` (era `347.html`, 1320 linhas)

```text
Crie js/98-347.js. Ele faz: ⚡ Iara Suite — Code Editor · APK Builder · Site Extractor — Olá, Mundo!.
No app original ele tinha estas funções/partes: qsa, lsSet, escHtml, showToast, dlBlob, copyText, switchTab, initEditor, renderFileList, fileIcon, openFile, onCodeChange, saveFile, newFile, downloadZip, uploadZip, handleZipUpload, handleTabKey.
O original usava as bibliotecas electron, path: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 283 — `js/98-348.js` (era `348.html`, 690 linhas)

```text
Crie js/98-348.js. Ele faz: Exported HTML — PrevAnalítico Pro.
No app original ele tinha estas funções/partes: navigate, toggleMobileMenu, switchReqTab, initOverviewChart, updateTCSim, initSpecialChart, initRMIChart, updateRMICalc.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 284 — `js/98-349.js` (era `349.html`, 451 linhas)

```text
Crie js/98-349.js. Ele faz: ObjectFactory (intercomunicacao 2.2.2 API).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 285 — `js/98-35.js` (era `35.html`, 578 linhas)

```text
Crie js/98-35.js. Ele faz: Playground Visual - Maikon Caldeira — 💻 Playground Visual - Maikon Caldeira.
No app original ele tinha estas funções/partes: importarZip, criarProjetoNovo, atualizarArvore, abrirArquivo, atualizarAbas, fecharAba, atualizarPreview, salvarProjeto, exportarZip, exportarNetlify, novoArquivo, abrirNovaAba, mostrarUpload.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 286 — `js/98-350.js` (era `350.html`, 4659 linhas)

```text
Crie js/98-350.js. Ele faz: Painel Maikon Caldeira — Advocacia Digital — 🔍 Analisador Automático + Debugger Visual.
No app original ele tinha estas funções/partes: handleFile, analyzeProject, analyzeConfig, analyzeDependencies, analyzeEndpoints, analyzeReplitBindings, analyzeErrors, analyzeDataFlow, analyzeSecurity, displayResults, switchTab, calculateHealth, exportReport, downloadFile, escapeHtml, generateFixes, generateJSFixes, getData.
Ele chamava estes endereços: /api/data, https://api.groq.com/openai/v1/chat/completions, https://api.neon.tech/v1/databases, https://api.openai.com/v1/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 287 — `js/98-351.js` (era `351.html`, 1720 linhas)

```text
Crie js/98-351.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: handleFile, processZip, processTar, shouldExtractContent, displayAnalysis, analyzeFileStructure, analyzeCodeContent, generateFolderStructure, getImportantFiles, escapeHtml, switchTab, exportAsJSON, exportAsMarkdown, exportAsHTML, downloadFile, analyzeVersions, analyzeStructure, analyzeFileContent.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 288 — `js/98-352.js` (era `352.html`, 926 linhas)

```text
Crie js/98-352.js. Ele faz: Manual Completo — Extrator Jurídico + APK — Maikon Caldeira OAB/MG 183712 — Manual Completo.
No app original ele tinha estas funções/partes: createWindow, calc.
O original usava as bibliotecas electron, path: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 289 — `js/98-353.js` (era `353.html`, 4512 linhas)

```text
Crie js/98-353.js. Ele faz: Painel Maikon Caldeira — Advocacia Digital — 🚀 Analisador Inteligente de Projetos.
No app original ele tinha estas funções/partes: handleFiles, handleZip, handleSingleFile, handleTarGz, handleTar, getFileType, displayReport, openTab, updateTabs, selectTab, closeTab, analyzeWithAI, detectErrors, generateSuggestions, detectKeywords, globalSearch, filterFiles, viewFullFile.
Ele chamava estes endereços: https://api.openai.com/v1/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 290 — `js/98-354.js` (era `354.html`, 1485 linhas)

```text
Crie js/98-354.js. Ele faz: Comparador Jurídico Profissional v2.0 — Comparador Jurídico Profissional v2.0.
No app original ele tinha estas funções/partes: init, setupEventListeners, setupAutoSave, setupDragDrop, loadZip, loadZipFile, normalPath, compareZips, renderList, showDiff, diffLines, esc, analyzeProject, analyzeComparison, renderAnalysis, populateFileSelector, showSideBySide, switchTab.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 291 — `js/98-355.js` (era `355.html`, 21040 linhas)

```text
Crie js/98-355.js. Ele faz: Painel Maikon Caldeira — Advocacia Digital — 🔍 Leitor de Projeto.
No app original ele tinha estas funções/partes: lerArquivo, analisarCodigo, pegarCorpo, classificar, explicar, renderizarFuncoes, toggleCorpo, copiar, filtrar, filtrarBusca, escaparHtml, testar, switchTab, togglePassword, testConnection, runQuery, runQuickQuery, initSQLite.
O original usava as bibliotecas dotenv, pg: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: https://api.groq.com/openai/v1/chat/completions, https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${aiKey}, https://api.x.ai/v1/chat/completions, https://api.anthropic.com/v1/messages, https://${info.host}/sql, https://api.openai.com/v1/chat/completions, https://generativelanguage.googleapis.com/v1beta/models/gemini-pro:generateContent?key=${aiSettings.apiKey}, https://api.duckduckgo.com/?q=${encodeURIComponent(query)}&amp;amp;format=json&amp;amp;no_html=1&amp;amp;skip_disambig=1, , , ${provedor.url}/chat/completions, ,. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 292 — `js/98-356.js` (era `356.html`, 528 linhas)

```text
Crie js/98-356.js. Ele faz: Manual Iara Suite v2.0 — Maikon Caldeira OAB/MG 183712 — IARA SUITE v2.0.
No app original ele tinha estas funções/partes: calc.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 293 — `js/98-357.js` (era `357.html`, 983 linhas)

```text
Crie js/98-357.js. Ele faz: Análise: TerminalTab.tsx — 🔬 TerminalTab.tsx.
No app original ele tinha estas funções/partes: line, sline, proxyFetch, analyzePWA, genElectronPackage, genElectronMain, createWindow, TerminalTab, runCommand, onKey.
O original usava as bibliotecas electron, path: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 294 — `js/98-358.js` (era `358.html`, 88 linhas)

```text
Crie js/98-358.js. Ele faz: Meus Códigos Jurídicos — 📂 Meus Códigos Jurídicos.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 295 — `js/98-359.js` (era `359.html`, 125 linhas)

```text
Crie js/98-359.js. Ele faz: Conversão TJMG → Padronizado.
No app original ele tinha estas funções/partes: mostrarTabela, renderizarTabela, exportarTabela.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 296 — `js/98-36.js` (era `36.html`, 160 linhas)

```text
Crie js/98-36.js. Ele faz: Menu Principal — 🚀 Menu Principal.
No app original ele tinha estas funções/partes: abrirPagina.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 297 — `js/98-360.js` (era `360.html`, 141 linhas)

```text
Crie js/98-360.js. Ele faz: Leitor Visual de CNIS — 📄 Importador Visual de CNIS.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 298 — `js/98-361.js` (era `361.html`, 138 linhas)

```text
Crie js/98-361.js. Ele faz: Extrator Jurídico BPC/LOAS com OCR e Exportação — Extrator Jurídico BPC/LOAS com OCR e Exportação.
No app original ele tinha estas funções/partes: exportToWord, exportToExcel, exportToPDF.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 299 — `js/98-362.js` (era `362.html`, 114 linhas)

```text
Crie js/98-362.js. Ele faz: Comparador Jurídico Multi-Cenário (Com Integração BCB) — Comparador Jurídico.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 300 — `js/98-363.js` (era `363.html`, 110 linhas)

```text
Crie js/98-363.js. Ele faz: 🛠️ Ferramentas Jurídico BPC — ⚖️ Ferramentas BPC/LOAS TRF6.
No app original ele tinha estas funções/partes: extrairProcessos, calcularPerCapita, gerarTabela, copiarTabela.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 301 — `js/98-364.js` (era `364.html`, 207 linhas)

```text
Crie js/98-364.js. Ele faz: Filtrador de Documentos Jurídicos.
No app original ele tinha estas funções/partes: processarTexto, limparCampos, exportarResultado.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 302 — `js/98-365.js` (era `365.html`, 181 linhas)

```text
Crie js/98-365.js. Ele faz: Laudo de Auditoria - Dr. Braulino.
No app original ele tinha estas funções/partes: buscarBCB, parseTJMG, processar, getPrevKey.
Ele chamava estes endereços: https://api.bcb.gov.br/dados/serie/bcdata.sgs.${s}/dados?formato=json. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 303 — `js/98-366.js` (era `366.html`, 205 linhas)

```text
Crie js/98-366.js. Ele faz: Gerador de Cotejo Analítico - Exportável para Word.
No app original ele tinha estas funções/partes: adicionarLinha, limpar, baixarWord.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 304 — `js/98-367.js` (era `367.html`, 265 linhas)

```text
Crie js/98-367.js. Ele faz: Calculadora de Custos de IA Avançada — Calculadora de Custos de IA Avançada.
No app original ele tinha estas funções/partes: calculateCost.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 305 — `js/98-368.js` (era `368.html`, 371 linhas)

```text
Crie js/98-368.js. Ele faz: PWA Scanner ZIP Jurídico — 🔎 PWA Scanner ZIP Jurídico.
No app original ele tinha estas funções/partes: ehTexto, carregarZip, renderArquivos, abrirArquivo, buscarTermos, temArquivo, temConteudo, diagnosticar, gerarRelatorio, limparTudo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 306 — `js/98-369.js` (era `369.html`, 289 linhas)

```text
Crie js/98-369.js. Ele faz: Calculadora Jurídica Definitiva - Dr. Manhumirim — Calculadora de Liquidação Comparativa.
No app original ele tinha estas funções/partes: executarCalculoMaster, recalculaSucumbencia, formatMA.
Ele chamava estes endereços: https://api.bcb.gov.br/dados/serie/bcdata.sgs.${serie}/dados?formato=json&dataInicial=${dInic.toLocaleDateString(. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 307 — `js/98-37.js` (era `37.html`, 44 linhas)

```text
Crie js/98-37.js. Ele faz: Gerador de Ícone.
No app original ele tinha estas funções/partes: baixar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 308 — `js/98-370.js` (era `370.html`, 442 linhas)

```text
Crie js/98-370.js. Ele faz: 🧩 Montador Multi-Projetos — PWA Jurídico — 🧩 Montador Multi-Projetos PWA JURÍDICO — MAIKON CALDEIRA.
No app original ele tinha estas funções/partes: salvarProjetos, carregarProjetos, renderizarSalvos, testarProjeto, limparProjeto, copiarCodigo, importarArquivo, gerarHtmlFinal, trocar, exportarBackup, importarBackup, escHtml, mostrarToast.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 309 — `js/98-371.js` (era `371.html`, 439 linhas)

```text
Crie js/98-371.js. Ele faz: Maikon Caldeira - Reconhecimentos Pretéritos.
No app original ele tinha estas funções/partes: autoSave, salvarNoStorage, coletarDados, carregarDados, adicionarReconhecimento, removerReconhecimento, exportarJSON, importarJSON, limparTudo, formatarData, gerarDocumento, enviarGmail.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 310 — `js/98-372.js` (era `372.html`, 734 linhas)

```text
Crie js/98-372.js. Ele faz: Modelo Editável de Peça (TRF6/JEF) — Endereçamento, Qualificação, Fundamentos com Subtítulos e Jurisprudência — MODELO EDITÁVEL (TRF6/JEF) — reutilizável.
No app original ele tinha estas funções/partes: gid, aplicarPreset, adicionarFundamento, removerFundamento, limparFundamentos, renderFundamentosPainel, editarFundamento, adicionarCitacao, removerCitacao, limparCitacoes, renderCitacoesPainel, editarCitacao, atualizar, exportarDOCX, pJust, pNoIndent, center, centerBold.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 311 — `js/98-373.js` (era `373.html`, 893 linhas)

```text
Crie js/98-373.js. Ele faz: Comparador Jurídico Completo - TJMG + BCB — Comparador Jurídico Completo - TJMG + BCB.
No app original ele tinha estas funções/partes: setClock, setStatus, parseCSV, splitCSVLine, toNumber, fmtBRL, parseDateBR, dateToYM, listMonthsFromDates, download, escapeHtml, convertTJMGIndices, readFile, readPDF, readExcel, parseIndices, formatDateBR, fetchBCBSerieToMonthlyMap.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 312 — `js/98-374.js` (era `374.html`, 944 linhas)

```text
Crie js/98-374.js. Ele faz: Filtro Jurídico Inteligente - Estrutura de Peças — EMBARGOS DE DECLARAÇÃO.
No app original ele tinha estas funções/partes: showOverlay, hideOverlay, extrairTextoPDF, extrairTextoWord, processarTexto, normalizeTextForCompare, calcularSimilaridade, distribuirTexto, atualizarDados, limparTudo, exportarWord, exportarJSON.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 313 — `js/98-375.js` (era `375.html`, 3105 linhas)

```text
Crie js/98-375.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: carregarProjeto, carregarZIP, analisarProjeto, mostrarStats, gerarPlano, gerarMarkdown, gerarArvore, renderizar, gerarSecoes, analisarComIA, mostrarPlano, mostrarLoading, copiarPlanoCompleto, copiarSecao, baixarMarkdown, loadFile, readFile, render.
Ele chamava estes endereços: ${provedor.url}/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 314 — `js/98-376.js` (era `376.html`, 2089 linhas)

```text
Crie js/98-376.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: showSection, processZip, renderFileList, openFile, filterFiles, copyCode, loadFromGitHub, createEmptyApp, saveCombinerState, loadCombinerState, renderAppCards, addAppCard, removeAppCard, updateAppField, clearAllCombiner, generateSuperPrompt, copyGeneratedPrompt, showLoader.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 315 — `js/98-378.js` (era `378.html`, 6511 linhas)

```text
Crie js/98-378.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: carregarDados, salvarDados, adicionarLink, limparFormulario, atualizarLista, alternarLink, removerLink, marcarTodos, desmarcarTodos, limparTudo, atualizarEstatisticas, abrirSelecionados, abrirVisualizador, alternarTelaCheia, proximoLink, linkAnterior, fecharVisualizador, escHtml.
Ele chamava estes endereços: https://api.openai.com/v1/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 316 — `js/98-379.js` (era `379.html`, 885 linhas)

```text
Crie js/98-379.js. Ele faz: Meu Projeto PWA.
No app original ele tinha estas funções/partes: showSection, showLoader, hideLoader, processZip, loadFromGitHub, renderFileList, checkSingleFileIsDirty, openFile, filterFiles, saveCurrentFileChanges, downloadModifiedZip, setExtractorUrl, fetchViaProxy, runWebExtractor, showExtSubTab, renderExtractorOverview, renderExtractorScripts, renderExtractorText.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 317 — `js/98-38.js` (era `38.html`, 757 linhas)

```text
Crie js/98-38.js. Ele faz: Construtor Automático PWA - Maikon Caldeira — 🚀 Construtor Automático PWA.
No app original ele tinha estas funções/partes: createWindow, print, executarComando, limparTerminal, atualizarArvore, selecionarArquivo, limparEditor, copiarCodigo, baixarProjeto, escapeHtml.
O original usava as bibliotecas electron, vite: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 318 — `js/98-380.js` (era `380.html`, 8525 linhas)

```text
Crie js/98-380.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: carregarDados, salvarDados, adicionarLink, limparFormulario, atualizarLista, alternarLink, removerLink, marcarTodos, desmarcarTodos, limparTudo, atualizarEstatisticas, abrirSelecionados, abrirVisualizador, alternarTelaCheia, proximoLink, linkAnterior, fecharVisualizador, carregarCSV.
Ele chamava estes endereços: ${baseUrl}/chat/completions, https://api.anthropic.com/v1/messages, https://www.googleapis.com/drive/v3/about?fields=user, https://www.googleapis.com/upload/drive/v3/files?uploadType=multipart, https://google.serper.dev/search, https://api.search.brave.com/res/v1/web/search?q=${encodeURIComponent(query)}&amp;amp;count=${numResults}, https://api.tavily.com/search. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 319 — `js/98-381.js` (era `381.html`, 3663 linhas)

```text
Crie js/98-381.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: App, updateLineNumbers, saveCurrentTab, loadEditorContent, switchTab, updateTabs, switchMode, startQuickEdit, applyQuickEdit, cancelQuickEdit, togglePreviewSize, buildDocument, run, updatePreview, toggleAuto, autoSave, getSnippets, setSnippets.
Ele chamava estes endereços: https://api.openai.com/v1/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 320 — `js/98-382.js` (era `382.html`, 4420 linhas)

```text
Crie js/98-382.js. Ele faz: Assistente Jurídico Pro.
No app original ele tinha estas funções/partes: loadLS, saveLS, detectProvider, getChaveResumo, getChaveGeracao, getModelo, getPromptGlobal, salvarChaves, salvarPromptGlobal, limparChaves, atualizarBadge, testarChaves, atualizarEsforco, atualizarVerbosity, toggleVerbosity, toggleConfig, mudarAba, importarArquivo.
Ele chamava estes endereços: ${baseUrl}/chat/completions, https://api.anthropic.com/v1/messages, https://www.googleapis.com/drive/v3/about?fields=user, https://www.googleapis.com/upload/drive/v3/files?uploadType=multipart, https://google.serper.dev/search, https://api.search.brave.com/res/v1/web/search?q=${encodeURIComponent(query)}&count=${numResults}, https://api.tavily.com/search. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 321 — `js/98-383.js` (era `383.html`, 2093 linhas)

```text
Crie js/98-383.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: importarArquivo, processarArquivo, processarCSV, detectarSeparador, parseLinha, processarJSON, processarXML, renderizarTabela, atualizarContador, filtrarTabela, ordenarPor, copiarTabela, copiarBruto, baixarCSV, baixarJSON, baixarArquivo, trocarAba, limparTudo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 322 — `js/98-384.js` (era `384.html`, 634 linhas)

```text
Crie js/98-384.js. Ele faz: 📖 Gerador de Histórias com Voz — 📖✨ Gerador de Histórias com Sua Voz.
No app original ele tinha estas funções/partes: switchTab, generateStory, generatePreview, generateTimeline, editPart, playPreview, exportVideo, downloadAudio, showStatus, showProgress, hideProgress.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 323 — `js/98-385.js` (era `385.html`, 679 linhas)

```text
Crie js/98-385.js. Ele faz: Gerador de package.json REAL - Só o que Funciona — ✅ Gerador de package.json REAL.
No app original ele tinha estas funções/partes: atualizarOpcoes, gerarPackageJson, gerarAnalise, mudarTab, copiar, baixarPackageJson, verificarConclusao.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 324 — `js/98-386.js` (era `386.html`, 1928 linhas)

```text
Crie js/98-386.js. Ele faz: Cirurgião de Código 4.0 — 🩺 Cirurgião 4.0.
No app original ele tinha estas funções/partes: esc, fmtB, fmtN, usd, agora, pausa, tokensDe, extDe, decode, pareceBinario, inflate, lerZip, CRC, crc32, escreverZip, baixar, copiar, status.
Ele chamava estes endereços: ${c.base}/models/${encodeURIComponent(c.modelo)}:generateContent, ${c.base}/messages, ${c.base}/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 325 — `js/98-387.js` (era `387.html`, 3138 linhas)

```text
Crie js/98-387.js. Ele faz: analise_Terminal.tsx.md — analise_Terminal.tsx.md.
No app original ele tinha estas funções/partes: simulateInstallDelay, Terminal, createTables, testConnection, setupDatabase, query, getClient, signUp, signIn, signOut, getUser, getAll, getById, insert, update, remove, uploadFile, subscribeToTable.
O original usava as bibliotecas react, lucide-react, firebase, firebas<, ytdl-core, fs, fluent-ffmpeg, better-sqlite3, pg, mongoose, ${mod}, @supabase/supabase-js, path: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 326 — `js/98-388.js` (era `388.html`, 5980 linhas)

```text
Crie js/98-388.js. Ele faz: Análise: legal-assistant.tsx — 🔬 legal-assistant.tsx.
No app original ele tinha estas funções/partes: LegalAssistant.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 327 — `js/98-389.js` (era `389.html`, 631 linhas)

```text
Crie js/98-389.js. Ele faz: Análise: desktop.ts — 🔬 desktop.ts.
No app original ele tinha estas funções/partes: strToAb, genElectronPackageJson, genElectronMain, createWindow, genElectronPreload, genNpmRc, genDesktopWorkflow, genDesktopReadme, buildDesktopFilesForGithub, buildDesktopZip.
O original usava as bibliotecas electron, path: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 328 — `js/98-39.js` (era `39.html`, 650 linhas)

```text
Crie js/98-39.js. Ele faz: Editor de Peças Jurídicas — Estrutura + Preview — Editor de Peças — estrutura + preview (auto-save).
No app original ele tinha estas funções/partes: nowISO, setStatus, save, load, renderAutosaveInfo, uid, escapeHtml, download, addBlock, duplicateBlock, removeBlock, moveBlock, setType, updateText, render, renderList, presets, renderPreviewOnly.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 329 — `js/98-390.js` (era `390.html`, 3400 linhas)

```text
Crie js/98-390.js. Ele faz: Análise: App.tsx — 🔬 App.tsx.
No app original ele tinha estas funções/partes: callAI, detectAIProvider, uploadToDrive, downloadBlob, FileTree, App, handleFileImport, handleImportAssistenteJuridico, handleImportSkCodeEditor, handleImportApkBuilder, onFileInput, onDrop, restoreSession, handleGhImport, handleGhCustomImport, handlePublicRepoImport, handleUrlImport, handleEASDeploy.
Ele chamava estes endereços: ${base}/chat/completions, ${domain}/api/healthz, https://api.github.com/repos/${ghUser.login}/${repoName}/actions/workflows/build-apk.yml/dispatches, https://api.github.com/repos/${ghUser.login}/${repoName}/actions/runs?per_page=1, https://api.github.com/repos/${ciRepoOwner}/${ciRepoName}/actions/workflows/build-apk.yml/dispatches, https://api.github.com/repos/${ciRepoOwner}/${ciRepoName}/actions/runs?per_page=1, https://api.github.com/repos/${ghUser.login}/${repoName}/actions/workflows/build-desktop.yml/dispatches, https://${p.host}/sql. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 330 — `js/98-391.js` (era `391.html`, 493 linhas)

```text
Crie js/98-391.js. Ele faz: Análise: ApkAnalyzer.tsx — 🔬 ApkAnalyzer.tsx.
No app original ele tinha estas funções/partes: parseAxml, hasReplitRef, cleanReplitRefs, extractInfo, ApkAnalyzer, cleanApk.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 331 — `js/98-393.js` (era `393.html`, 86 linhas)

```text
Crie js/98-393.js. Ele faz: Comparador de Juros Simples e Compostos — Comparador de Juros Simples e Compostos.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 332 — `js/98-394.js` (era `394.html`, 105 linhas)

```text
Crie js/98-394.js. Ele faz: PDJd Token COJEF Centro.
No app original ele tinha estas funções/partes: gerarToken, gerarJWT, trocarJWTporBearer, buscarPortariasCojef.
Ele chamava estes endereços: https://api.pdjdtj.mg.gov.br/v1/auth/token. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 333 — `js/98-395.js` (era `395.html`, 120 linhas)

```text
Crie js/98-395.js. Ele faz: 🔑 PDJD Token Generator - Portal Jus.br — ⚖️ PDJD Token Generator - Portal Jus.br (CNJ).
No app original ele tinha estas funções/partes: gerarTokenPDJD.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 334 — `js/98-396.js` (era `396.html`, 56 linhas)

```text
Crie js/98-396.js. Ele faz: COMO_BUILDAR — Assistente Jurídico — Como Gerar o APK.
No app original ele tinha estas funções/partes: marca, copiar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 335 — `js/98-397.js` (era `397.html`, 244 linhas)

```text
Crie js/98-397.js. Ele faz: Filtrador Universal de Documentos.
No app original ele tinha estas funções/partes: lerArquivos, processar, copiarResultado, limparTudo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 336 — `js/98-398.js` (era `398.html`, 331 linhas)

```text
Crie js/98-398.js. Ele faz: Analisador de Versões PWA Jurídico — 🔍 Analisador de Versões — PWA Jurídico.
No app original ele tinha estas funções/partes: handleFiles, displayAnalysis.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 337 — `js/98-399.js` (era `399.html`, 256 linhas)

```text
Crie js/98-399.js. Ele faz: Adjair Tempo Especial.
No app original ele tinha estas funções/partes: adicionarReconhecimento, formatarData, gerarDocumento, enviarGmail.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 338 — `js/98-4.js` (era `4.html`, 903 linhas)

```text
Crie js/98-4.js. Ele faz: Playground Visual — 🎮 Playground Visual.
No app original ele tinha estas funções/partes: novoId, detectarTipo, corTipo, emojiTipo, abrirArquivos, carregarArquivos, evLeave, evDrop, novoArquivo, App, renderAbas, ativarAba, fecharAba, onEdit, tabEditor, atualizarStatus, copiarEditor, salvarArquivo.
O original usava as bibliotecas react: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 339 — `js/98-40.js` (era `40.html`, 763 linhas)

```text
Crie js/98-40.js. Ele faz: Comparador Jurídico Multi-Cenário — Cartão/Empréstimo (BCB + TJMG) — Comparador Jurídico Multi-Cenário — Cartão/Empréstimo (BCB + TJMG).
No app original ele tinha estas funções/partes: setClock, setStatus, parseCSV, splitCSVLine, toNumber, fmtBRL, parseDateBR, dateToYM, listMonthsFromDates, download, addScenario, removeScenario, renderScenarios, escapeHtml, parseIndices, formatDateBR, fetchBCBSerieToMonthlyMap, calcScenario.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 340 — `js/98-400.js` (era `400.html`, 321 linhas)

```text
Crie js/98-400.js. Ele faz: Comparador Jurídico Master — Monica Especialista.
No app original ele tinha estas funções/partes: fMoeda, fNum, setStatus, lerTJ, buscarBCB, executarCalculo, salvarLocal, carregarLocal, limparTudo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 341 — `js/98-401.js` (era `401.html`, 438 linhas)

```text
Crie js/98-401.js. Ele faz: Painel – Flexibilização de Renda — MAIKON DA ROCHA CALDEIRA - OAB/MG 183.712.
No app original ele tinha estas funções/partes: lerMoeda, ativarMascara, addRow, importCSV, recalc, sum, calcPerCapita, avaliarConformidade, getState, pickRows, setState, saveLocal, loadLocal, exportJSON, exportCSV, toCSV.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 342 — `js/98-402.js` (era `402.html`, 561 linhas)

```text
Crie js/98-402.js. Ele faz: 🧩 Montador Multi-Projetos — PWA Jurídico — 🧩 Montador Multi-Projetos.
No app original ele tinha estas funções/partes: mudarAba, salvarProjetos, carregarProjetos, renderizarEditor, adicionarProjeto, removerProjeto, extrairNomeDoHtml, renderizarSalvos, testarProjeto, fecharTestador, copiarCodigo, importarArquivo, abrirModalNomeDownload, fecharModal, gerarHtmlFinal, trocarProjeto, escHtml, exportarBackup.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 343 — `js/98-403.js` (era `403.html`, 376 linhas)

```text
Crie js/98-403.js. Ele faz: Painel de Confronto de Remunerações (CNIS/RAIS/CTC) — Painel de Confronto de Remunerações.
No app original ele tinha estas funções/partes: moedaParaNumero, extrairTodasOcorrencias, reprocessar, extrairTextoPDF, mostrarTextoBruto, exportarExcel, exportarJSON, exportarPDF, exportarWord.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 344 — `js/98-404.js` (era `404.html`, 740 linhas)

```text
Crie js/98-404.js. Ele faz: Gerenciador de Links - Maikon Caldeira — 🔗 Gerenciador de Links.
No app original ele tinha estas funções/partes: carregarDados, salvarDados, adicionarLink, limparFormulario, atualizarLista, alternarLink, removerLink, marcarTodos, desmarcarTodos, limparTudo, atualizarEstatisticas, abrirSelecionados, abrirVisualizador, alternarTelaCheia, proximoLink, linkAnterior, fecharVisualizador, escHtml.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 345 — `js/98-405.js` (era `405.html`, 797 linhas)

```text
Crie js/98-405.js. Ele faz: Analisador de Código Gigante — 🔍 Analisador de Código Gigante.
No app original ele tinha estas funções/partes: byId, escaparHtml, carregarArquivo, limparTudo, analisar, extrairTags, detectarRegex, detectarJsonPossivel, criarItem, linhaDoIndice, adicionarBlocos, renderStats, renderManual, nome, manualItem, renderBlocos, explicarBloco, mostrarBloco.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 346 — `js/98-406.js` (era `406.html`, 190 linhas)

```text
Crie js/98-406.js. Ele faz: MANUAL (1) — Assistente Jurídico IA — Manual Completo.
No app original ele tinha estas funções/partes: marca, copiar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 347 — `js/98-407.js` (era `407.html`, 1028 linhas)

```text
Crie js/98-407.js. Ele faz: Dashboard de Monitoramento - Projeto Jurídico — 📊 Dashboard de Monitoramento.
No app original ele tinha estas funções/partes: handleFile, analyzeProjectForMonitoring, updateDashboard, switchTab, refreshDashboard.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 348 — `js/98-408.js` (era `408.html`, 602 linhas)

```text
Crie js/98-408.js. Ele faz: Filtrador Jurídico Avançado (Anti-repetição) — Filtrador Jurídico Avançado (Anti-repetição).
No app original ele tinha estas funções/partes: loadState, saveState, setStatus, download, cleanMarkdownNoise, splitParagraphs, normalizeForCompare, makeShingles, signature, jaccard, parseLines, buildRegexList, extractTextFromPDF, extractTextFromDOCX, extractTextFromJSON, walk, applyBanRules, applyCaptureRules.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 349 — `js/98-409.js` (era `409.html`, 1026 linhas)

```text
Crie js/98-409.js. Ele faz: 🔍 Comparador de Projetos — 🔍 Comparador de Projetos.
No app original ele tinha estas funções/partes: carregarProjeto, carregarZIP, mostrarInfo, verificarBotaoComparar, compararProjetos, realizarComparacao, compararArquivos, mostrarResultado, mostrarResumo, mostrarArquivos, verArquivo, gerarSugestoes, gerarRelatorio, mudarTab, limparTudo, baixarTexto.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 350 — `js/98-41.js` (era `41.html`, 407 linhas)

```text
Crie js/98-41.js. Ele faz: 🔪 Fatiador de Código — 🔪 Fatiador de Código.
No app original ele tinha estas funções/partes: fatiar, extrairFuncoes, extrairClasses, extrairObjetos, extrairCSS, extrairHTML, renderizarResultado, criarModuloHTML, copiarModulo, escapeHtml, limpar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 351 — `js/98-410.js` (era `410.html`, 4619 linhas)

```text
Crie js/98-410.js. Ele faz: Painel Maikon Caldeira — Advocacia Digital — 📚 Gerador de Documentação Automática.
No app original ele tinha estas funções/partes: handleFile, generateDocumentation, analyzeJSFile, analyzeFileStructure, generateGettingStarted, generateFileTree, buildTree, generateArchitecture, displayDocumentation, App, switchTab, exportDocs, exportMarkdown, exportHTML, exportJSON, exportPDF, downloadFile, escapeHtml.
O original usava as bibliotecas ${comp.file}: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 352 — `js/98-411.js` (era `411.html`, 3812 linhas)

```text
Crie js/98-411.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: salvarProjetos, carregarProjetos, renderizarSalvos, testarProjeto, limparProjeto, copiarCodigo, importarArquivo, gerarHtmlFinal, trocarProjeto, exportarBackup, importarBackup, escHtml, mostrarToast, trocar, mudarAba, renderizarEditor, adicionarProjeto, removerProjeto.
Ele chamava estes endereços: https://api.openai.com/v1/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 353 — `js/98-412.js` (era `412.html`, 794 linhas)

```text
Crie js/98-412.js. Ele faz: Analisador de Projetos + Gerador .EXE — 📦 Analisador de Projetos + Gerador de Executável.
No app original ele tinha estas funções/partes: handleDragOver, handleDragLeave, handleDrop, handleFileSelect, exibirListaArquivos, analisarProjeto, abrirModalConfig, fecharModal, gerarArquivos, downloadJSON, downloadText, gerarComOllama.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 354 — `js/98-414.js` (era `414.html`, 983 linhas)

```text
Crie js/98-414.js. Ele faz: Análise: TerminalTab.tsx — 🔬 TerminalTab.tsx.
No app original ele tinha estas funções/partes: line, sline, proxyFetch, analyzePWA, genElectronPackage, genElectronMain, createWindow, TerminalTab, runCommand, onKey.
O original usava as bibliotecas electron, path: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 355 — `js/98-415.js` (era `415.html`, 7355 linhas)

```text
Crie js/98-415.js. Ele faz: analise_pacote-ia.txt.md.md — analise_pacote-ia.txt.md.md.
No app original ele tinha estas funções/partes: buildAll, detectTermMode, App, _resolveComponent, PreviewRenderer, loadComponent, component, getBasePath, getPreviewExamplePath, Gallery, getPreviewPath, setCors, readBody, handleAIChat, handleHealth, detectPort, proxyRequest.
O original usava as bibliotecas node:module, node:path, node:url, esbuild, esbuild-plugin-pino, node:fs, node:child_process, nod<, http, ws, express, vite, @vitejs/plugin-react, @tailwindcss/vite, path, @replit/vite-plugin-runtime-error-modal, react-dom, react, @capacitor/cli, child_process, @replit/vite-plugin-cartographer, @replit/vite-plugin-dev-banner, url, electron, fs, os: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: ${GEMINI_BASE}/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 356 — `js/98-416.js` (era `416.html`, 3024 linhas)

```text
Crie js/98-416.js. Ele faz: Análise: EditorLayout.tsx — 🔬 EditorLayout.tsx.
No app original ele tinha estas funções/partes: NameInputModal, buildAsciiTree, sortKeys, render, generateDocs, explainFile, explainFolder, generateSystemInfo, EditorLayout.
O original usava as bibliotecas node-fetch, axios, fs: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 357 — `js/98-417.js` (era `417.html`, 250 linhas)

```text
Crie js/98-417.js. Ele faz: Análise: eas.ts — 🔬 eas.ts.
No app original ele tinha estas funções/partes: gql, easGetMe, easEnsureApp, easGetUploadUrl, easUploadTarball, easCreateBuild, easGetBuild.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 358 — `js/98-418.js` (era `418.html`, 410 linhas)

```text
Crie js/98-418.js. Ele faz: Análise: archive.ts — 🔬 archive.ts.
No app original ele tinha estas funções/partes: isBinary, getEncoding, decodeText, readString, parseTar, extractArchive, guessConfig, decode, buildFileTree, sortNode.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 359 — `js/98-419.js` (era `419.html`, 410 linhas)

```text
Crie js/98-419.js. Ele faz: Análise: archive.ts — 🔬 archive.ts.
No app original ele tinha estas funções/partes: isBinary, getEncoding, decodeText, readString, parseTar, extractArchive, guessConfig, decode, buildFileTree, sortNode.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 360 — `js/98-42.js` (era `42.html`, 813 linhas)

```text
Crie js/98-42.js. Ele faz: Playground Supabase — Playground conectado ao Supabase.
No app original ele tinha estas funções/partes: setStatus, getEditorData, setEditorData, ensureConnection, connectSupabase, loadProjects, renderProjects, saveProject, updateProject, deleteProject, newProject, escapeScript, updatePreview, searchInCode, csvEscape, makeCsv, downloadFile, exportCsv.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 361 — `js/98-420.js` (era `420.html`, 6367 linhas)

```text
Crie js/98-420.js. Ele faz: analise_App.tsx.md — analise_App.tsx.md.
No app original ele tinha estas funções/partes: callAI, detectAIProvider, uploadToDrive, downloadBlob, FileTree, App, handleFileImport, handleImportAssistenteJuridico, handleImportSkCodeEditor, handleImportApkBuilder, onFileInput, onDrop, restoreSession, handleGhImport, handleGhCustomImport, handlePublicRepoImport, handleUrlImport, handleEASDeploy.
O original usava as bibliotecas react: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: ${base}/chat/completions, https://www.googleapis.com/upload/drive/v3/files?uploadType=multipart, ${domain}/api/healthz, https://api.github.com/rate_limit, /apk-builder/assistente-juridico-pwa.zip, /apk-builder/sk-code-editor.zip, /apk-builder/apk-builder-source.zip, https://api.github.com/repos/${ghUser.login}/${repoName}/actions/workflows/build-apk.yml/dispatches, https://api.github.com/repos/${ghUser.login}/${repoName}/actions/runs?per_page=1, https://api.github.com/repos/${ciRepoOwner}/${ciRepoName}/actions/workflows/build-apk.yml/dispatches, https://api.github.com/repos/${ciRepoOwner}/${ciRepoName}/actions/runs?per_page=1, https://api.github.com/repos/${ghUser.login}/${repoName}/actions/workflows/build-desktop.yml/dispatches, https://${p.host}/sql. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 362 — `js/98-421.js` (era `421.html`, 156 linhas)

```text
Crie js/98-421.js. Ele faz: Validar JWT com Chave Pública PEM — 🔍 Validador JWT - Chave Pública PEM.
No app original ele tinha estas funções/partes: validarJWT, decodificarJWT, limpar, b64UrlDecode, stringToArrayBuffer.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 363 — `js/98-422.js` (era `422.html`, 169 linhas)

```text
Crie js/98-422.js. Ele faz: ' + nomeCompleto + ' — MAIKON CALDEIRA.
No app original ele tinha estas funções/partes: gerarManifestJSON, gerarServiceWorker, gerarPWACompleto, previewIndex, previewManifest, escapeHtml.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 364 — `js/98-423.js` (era `423.html`, 183 linhas)

```text
Crie js/98-423.js. Ele faz: Monica Assistente - Comparador de Cenários Judiciais — Comparador de Evolução de Dívida.
No app original ele tinha estas funções/partes: calcularTudo, calcularHonorarios.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 365 — `js/98-424.js` (era `424.html`, 215 linhas)

```text
Crie js/98-424.js. Ele faz: 🔑 JWT Generator PDJUD/PDPJ — ⚖️ JWT Generator - PDJUD/PDPJ Brasil.
No app original ele tinha estas funções/partes: base64urlEncode, base64urlDecode, sha256, rotate, gerarJWT.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 366 — `js/98-425.js` (era `425.html`, 202 linhas)

```text
Crie js/98-425.js. Ele faz: Manual Básico: Variáveis de Ambiente e Chaves Secretas — Manual Básico: Variáveis de Ambiente e Chaves Secretas.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 367 — `js/98-426.js` (era `426.html`, 218 linhas)

```text
Crie js/98-426.js. Ele faz: Manual 1 — Manual Básico: Variáveis de Ambiente e Chaves Secretas.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 368 — `js/98-427.js` (era `427.html`, 520 linhas)

```text
Crie js/98-427.js. Ele faz: Gerador de Cotejo Analítico (BPC/LOAS) — Export Word/Excel/JSON.
No app original ele tinha estas funções/partes: uid, atualizarCabecalhos, adicionarLinha, renderLinha, removerLinha, limparTabela, exportarJSON, exportarExcel, exportarWord, cellHead, cellBody, joinTxtLoc, escapeHtml, nl2br.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 369 — `js/98-428.js` (era `428.html`, 414 linhas)

```text
Crie js/98-428.js. Ele faz: SK Oficina Jurídica v6 - Analyzer + Injector.
No app original ele tinha estas funções/partes: showSection, showLoader, hideLoader, logAction, parseAxml, extractApkInfo, renderApkInfo, hasReplitRef, renderFileList, openFile, saveCurrentFileChanges, updateScannerStats, cleanReplitStrings, injectEssentialFiles, executeCleanAndInject.
O original usava as bibliotecas vite, @vitejs/plugin-react: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 370 — `js/98-429.js` (era `429.html`, 592 linhas)

```text
Crie js/98-429.js. Ele faz: Extrair Texto (PDF/TXT/Imagem/DOCX) — Extrator de Texto (PDF / TXT / Imagem / DOCX).
No app original ele tinha estas funções/partes: setStatus, setProgress, setDownloadsEnabled, prettyBytes, cleanFooter, updateFileUI, clearAll, extractFromTXT, extractFromImage, extractFromPDF, extractFromDOCX, decodeXmlEntities, fileToDataURL, extractText, downloadText, downloadPDF, downloadDOCX, downloadMarkdown.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 371 — `js/98-43.js` (era `43.html`, 436 linhas)

```text
Crie js/98-43.js. Ele faz: Iara Suite — Editor — Iara Suite.
No app original ele tinha estas funções/partes: toast, dlBlob, copyText, getActive, updateProvInfo, callAI, openKeysModal, closeKeysModal, renderSlots, autoDetect, toggleSlot, saveKeys, FICON, initEditor, renderFiles, openFile, saveFile, newFile.
Ele chamava estes endereços: https://api.anthropic.com/v1/messages, https://generativelanguage.googleapis.com/v1beta/models/. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 372 — `js/98-430.js` (era `430.html`, 572 linhas)

```text
Crie js/98-430.js. Ele faz: Filtrador Jurídico Completo (VIP + Word) — Filtrador Jurídico.
No app original ele tinha estas funções/partes: loadState, saveState, cleanText, getLines, getShingles, calculateSimilarity, processText, handleFiles, extractStringsFromJson, downloadFile, exportWord, exportJson, exportTxt, showStatus.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 373 — `js/98-431.js` (era `431.html`, 457 linhas)

```text
Crie js/98-431.js. Ele faz: Filtrador Jurídico Avançado (Versão Mike) — Filtrador Jurídico Avançado ✓ Salvo.
No app original ele tinha estas funções/partes: saveState, loadState, setStatus, download, renderRemovedSample, extractTextFromPDF, extractTextFromDOCX, splitParagraphs, isOcrNoise, filterText.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 374 — `js/98-432.js` (era `432.html`, 576 linhas)

```text
Crie js/98-432.js. Ele faz: Filtrador Genérico (Anti-repetição) — Jurídico — Filtrador genérico (anti-repetição).
No app original ele tinha estas funções/partes: loadState, saveState, setStatus, download, cleanMarkdownNoise, splitParagraphs, normalizeForCompare, makeShingles, signature, jaccard, parseLines, buildRegexList, extractTextFromPDF, extractTextFromDOCX, extractTextFromJSON, walk, applyBanRules, filterText.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 375 — `js/98-433.js` (era `433.html`, 988 linhas)

```text
Crie js/98-433.js. Ele faz: Leitor de Projeto PRO - Com Memória — 🔍 Leitor de Projeto PRO.
No app original ele tinha estas funções/partes: lerArquivo, analisarCodigo, analisarFuncoes, analisarHTML, analisarCSS, pegarCorpo, isCerebro, isImportante, explicarFuncao, explicarHTML, explicarCSS, renderizarElementos, toggleCorpo, copiar, copiarTudo, filtrar, filtrarBusca, salvarNaMemoria.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 376 — `js/98-434.js` (era `434.html`, 548 linhas)

```text
Crie js/98-434.js. Ele faz: Extrator Jurídico - Processo Completo (Contrato Falsificado) — Extrator Jurídico - Processo Completo.
No app original ele tinha estas funções/partes: loadState, saveState, renderizarListaVariaveis, adicionarVariavel, removerVar, restaurarPadrao, extrairTextoPDFPorPagina, extrairTextoWord, mostrarTextoBruto, encontrarPagina, reprocessar, exportarJSON, exportarExcel, exportarXML, escapeXml, exportarPDF, exportarWord, gerarDadosExportacao.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 377 — `js/98-435.js` (era `435.html`, 880 linhas)

```text
Crie js/98-435.js. Ele faz: Comparador Jurídico — Correção + Juros (Simples/Compostos) por Competência — Comparador Jurídico — Evolução mensal (correção + juros) e diferença pós-sentença.
No app original ele tinha estas funções/partes: setClock, setStatus, download, parseCSV, splitCSVLine, toNumber, fmtBRL, ymValid, ymToDate, dateToYM, listMonths, loadIndexFile, loadPayFile, fetchSGS, sgsToYM, calcScenario, applyPay, applyCorr.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 378 — `js/98-436.js` (era `436.html`, 1324 linhas)

```text
Crie js/98-436.js. Ele faz: 🔬 Cirurgião 3.0 — Scanner Inteligente — 🔬 Cirurgião 3.0 — Scanner Inteligente.
No app original ele tinha estas funções/partes: switchTab, showToast, importarArquivo, importarZip, importarTar, parsearTar, decompressGzip, importarArquivoSimples, importarCodigo, limparImportacao, filtrarArquivos, renderizarArquivos, abrirArquivo, mostrarEstatisticas, buscarTermos, diagnosticar, analisarComIA, mostrarErros.
Ele chamava estes endereços: ) || linha.includes(. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 379 — `js/98-437.js` (era `437.html`, 3432 linhas)

```text
Crie js/98-437.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: switchTab, showToast, importarArquivo, importarZip, importarTar, parsearTar, decompressGzip, importarArquivoSimples, importarCodigo, limparImportacao, filtrarArquivos, renderizarArquivos, abrirArquivo, mostrarEstatisticas, buscarTermos, diagnosticar, analisarComIA, mostrarErros.
Ele chamava estes endereços: ) || linha.includes(, ${p.url}?key=${chave}. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 380 — `js/98-438.js` (era `438.html`, 1173 linhas)

```text
Crie js/98-438.js. Ele faz: Playground IA — Saulo — Playground IA — Saulo.
No app original ele tinha estas funções/partes: App, updateLineNumbers, saveCurrentTab, loadEditorContent, switchTab, updateTabs, switchMode, startQuickEdit, applyQuickEdit, cancelQuickEdit, togglePreviewSize, buildDocument, run, updatePreview, toggleAuto, autoSave, getSnippets, setSnippets.
Ele chamava estes endereços: https://api.openai.com/v1/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 381 — `js/98-439.js` (era `439.html`, 5293 linhas)

```text
Crie js/98-439.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: switchTab, showToast, importarArquivo, importarZip, importarTar, parsearTar, decompressGzip, importarArquivoSimples, importarCodigo, limparImportacao, filtrarArquivos, renderizarArquivos, abrirArquivo, mostrarEstatisticas, buscarTermos, diagnosticar, analisarComIA, mostrarErros.
Ele chamava estes endereços: ) || linha.includes(, , , ${provedor.url}/chat/completions, ,. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 382 — `js/98-44.js` (era `44.html`, 429 linhas)

```text
Crie js/98-44.js. Ele faz: Gerador de Estrutura - CORRIGIDO — 🗺️ Gerador de Estrutura - CORRIGIDO.
No app original ele tinha estas funções/partes: handleZip, mostrarResultado, renderizarArvore, renderizarNode, gerarComandos, copiarComandos.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 383 — `js/98-440.js` (era `440.html`, 7197 linhas)

```text
Crie js/98-440.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: detectProvider, openDB, dbPut, dbGetAll, dbGet, dbDelete, boot, restoreUI, autoSave, scheduleSave, autoSaveDraft, togglePanel, onKeyInput, updateProvBadge, updateCfgStatus, toggleShowKey, saveKey, renderSavedKeys.
Ele chamava estes endereços: ${baseUrl}/chat/completions, https://api.anthropic.com/v1/messages, https://www.googleapis.com/drive/v3/about?fields=user, https://www.googleapis.com/upload/drive/v3/files?uploadType=multipart, https://google.serper.dev/search, https://api.search.brave.com/res/v1/web/search?q=${encodeURIComponent(query)}&amp;count=${numResults}, https://api.tavily.com/search. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 384 — `js/98-441.js` (era `441.html`, 3991 linhas)

```text
Crie js/98-441.js. Ele faz: analise_settings.tsx.md — analise_settings.tsx.md.
No app original ele tinha estas funções/partes: SectionHeader, SettingRow, SettingsScreen.
O original usava as bibliotecas @expo/vector-icons, expo-clipboard, expo-haptics, react, react-native-safe-area-context, react-native, express, cors, child_process: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: https://api.github.com/user. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 385 — `js/98-442.js` (era `442.html`, 2217 linhas)

```text
Crie js/98-442.js. Ele faz: Análise: Manual.tsx — 🔬 Manual.tsx.
No app original ele tinha estas funções/partes: Manual, initDb.
O original usava as bibliotecas dotenv, @neondatabase/serverless, fs: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: /api/twa-files?url=${encodeURIComponent(url)}, /api/pwa-check?url=${encodeURIComponent(url)}. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 386 — `js/98-443.js` (era `443.html`, 2477 linhas)

```text
Crie js/98-443.js. Ele faz: analise_keys.tsx (3).md — analise_keys.tsx (3).md.
No app original ele tinha estas funções/partes: uid, statusColor, statusLabel, ManualModal, CreateTableModal, addCol, removeCol, setColName, setColType, run, KeysScreen, pickManual, addKey, testKey, testAll, testNeon, runSql, runAiDb.
O original usava as bibliotecas @expo/vector-icons, react, react-native-safe-area-context, react-native: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: ${base}/chat/completions, ${base}/api/healthz, https://httpbin.org/get, https://api.github.com/user. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 387 — `js/98-444.js` (era `444.html`, 283 linhas)

```text
Crie js/98-444.js. Ele faz: Análise: eas.ts — 🔬 eas.ts.
No app original ele tinha estas funções/partes: gql, easGetMe, easEnsureApp, easGetUploadUrl, easUploadTarball, easCreateBuild, easGetBuild.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 388 — `js/98-445.js` (era `445.html`, 1414 linhas)

```text
Crie js/98-445.js. Ele faz: Análise: BuildPanel.tsx — 🔬 BuildPanel.tsx.
No app original ele tinha estas funções/partes: CodeBlock, cleanDeps, parseVfsPkg, makeCleanPkg, getAllVfsFiles, generatePlatformZip, createWindow, BuildPanel, sortK, renderT.
O original usava as bibliotecas @capacitor/cli, electron, path: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 389 — `js/98-446.js` (era `446.html`, 480 linhas)

```text
Crie js/98-446.js. Ele faz: Análise: android.ts — 🔬 android.ts.
No app original ele tinha estas funções/partes: selectWebFiles, buildAndroidZip, MainActivity.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 390 — `js/98-447.js` (era `447.html`, 1480 linhas)

```text
Crie js/98-447.js. Ele faz: Analisador Local de Projetos — V2 — Analisador Local de Projetos — V2.
No app original ele tinha estas funções/partes: extension, normalize, setStatus, formatBytes, importFiles, renderFileList, openFile, updateEditorInfo, scheduleSave, saveProject, restoreProject, pasteCode, newFile, downloadCurrent, downloadBlob, createElement, heading, card.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 391 — `js/98-448.js` (era `448.html`, 87 linhas)

```text
Crie js/98-448.js. Ele faz: Comparar custo IA: barato vs caro — Comparar custo de IA: modelo barato vs modelo caro.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 392 — `js/98-449.js` (era `449.html`, 197 linhas)

```text
Crie js/98-449.js. Ele faz: Extrair Texto Completo.
No app original ele tinha estas funções/partes: cleanFooter, extractText, downloadText, downloadPDF, downloadDOCX, downloadMarkdown, copyText.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 393 — `js/98-45.js` (era `45.html`, 1066 linhas)

```text
Crie js/98-45.js. Ele faz: 🐍 Python Explicado Visualmente — 🐍 Python Explicado Visualmente.
No app original ele tinha estas funções/partes: saudar, somar, mostrarConteudo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 394 — `js/98-450.js` (era `450.html`, 219 linhas)

```text
Crie js/98-450.js. Ele faz: nova_ferramenta — Gerador de Arquivo .env.
No app original ele tinha estas funções/partes: addEntry.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 395 — `js/98-451.js` (era `451.html`, 230 linhas)

```text
Crie js/98-451.js. Ele faz: nova_ferramenta.
No app original ele tinha estas funções/partes: update, baixar, limparTudo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 396 — `js/98-452.js` (era `452.html`, 261 linhas)

```text
Crie js/98-452.js. Ele faz: Playground Pro - Maikon Caldeira.
No app original ele tinha estas funções/partes: salvarNoBanco, carregarDoBanco, limparBanco, update, updatePreview, baixar, limparTudo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 397 — `js/98-453.js` (era `453.html`, 241 linhas)

```text
Crie js/98-453.js. Ele faz: Guia de recuperação  — Guia de Recuperação e Configuração do Projeto Maikon.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 398 — `js/98-454.js` (era `454.html`, 323 linhas)

```text
Crie js/98-454.js. Ele faz: Limpador de Embargos (Anti-Repetição) — Limpador de Embargos & Extrator de Texto (Anti-Repetição).
No app original ele tinha estas funções/partes: handleFiles, readPDF, readDocx, readFileAsText, processText, filterLogic, getSimilarity, clearAll, downloadText, copyOutput.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 399 — `js/98-455.js` (era `455.html`, 331 linhas)

```text
Crie js/98-455.js. Ele faz: 🔐 JWT RS256 - Front-end — 🔐 JWT RS256 Generator.
No app original ele tinha estas funções/partes: switchTab, generateKeys, generateRS256, verifyRS256, importKey, signRS256, pemToBuffer, exportKey, base64UrlEncode, base64UrlDecode, showResult.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 400 — `js/98-456.js` (era `456.html`, 569 linhas)

```text
Crie js/98-456.js. Ele faz: Comparador Jurídico — TJMG + BCB — Premium — Comparador Jurídico — TJMG + BCB — Multi-Cenário.
No app original ele tinha estas funções/partes: setClock, setStatus, fmtBRL, toNumberBR, parseDateBR, dateToYM, listMonths, snapshotToObject, saveToLS, loadFromLS, applySnapshot, extractTJ, renderScenarios, addScenario, removeScenario, updateScen, calcular, renderTable.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 401 — `js/98-457.js` (era `457.html`, 374 linhas)

```text
Crie js/98-457.js. Ele faz: Extrator Jurídico - Contrato Falsificado (INSS/Estelionato) — Extrator Jurídico - Contrato Falsificado.
No app original ele tinha estas funções/partes: loadState, saveState, renderizarListaVariaveis, adicionarVariavel, removerVar, restaurarPadrao, extrairTextoPDF, extrairTextoWord, mostrarTextoBruto, reprocessar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 402 — `js/98-458.js` (era `458.html`, 751 linhas)

```text
Crie js/98-458.js. Ele faz: Iara — Mapeador Visual.
No app original ele tinha estas funções/partes: resizeCanvas, onDragOver, onDragLeave, onDrop, loadZip, processZip, shouldSkip, normPath, sleep, buildGraph, extractImports, resolveImport, classifyType, getColor, getRadius, layoutGraph, forceStep, applyGraph.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 403 — `js/98-459.js` (era `459.html`, 751 linhas)

```text
Crie js/98-459.js. Ele faz: Iara Dissecador — Extrator e Montador de Código — 🧩 Iara Dissecador — Extrator e Montador de Código.
No app original ele tinha estas funções/partes: readFile, dissect, extractDeps, renderFileList, setActiveFile, renderIndex, renderBlock, updateSelCount, toggleSelect, selectAllVisible, selectAllInFile, deselectAll, addSelectedToAssembler, addOneToAssembler, findBlock, renderAssembler, removeFromAssembler, clearAssembler.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 404 — `js/98-46.js` (era `46.html`, 398 linhas)

```text
Crie js/98-46.js. Ele faz: CodeLens.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 405 — `js/98-460.js` (era `460.html`, 632 linhas)

```text
Crie js/98-460.js. Ele faz: Extrator Jurídico Avançado - Processo Completo com Links — Extrator Jurídico Avançado - Processo Completo.
No app original ele tinha estas funções/partes: renderizarCategorias, toggleCategoria, selecionarTodas, desselecionarTodas, filtrarCategorias, extrairTextoPDFPorPagina, encontrarPagina, mostrarTextoBruto, reprocessar, renderizarResultados, abrirPagina, exportarHTML, exportarExcel, exportarJSON, exportarXML, escapeXml, download.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 406 — `js/98-461.js` (era `461.html`, 1164 linhas)

```text
Crie js/98-461.js. Ele faz: Analisador Automático + Debugger Visual — 🔍 Analisador Automático + Debugger Visual.
No app original ele tinha estas funções/partes: handleFile, analyzeProject, analyzeConfig, analyzeDependencies, analyzeEndpoints, analyzeReplitBindings, analyzeErrors, analyzeDataFlow, analyzeSecurity, displayResults, switchTab, calculateHealth, exportReport, downloadFile, escapeHtml.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 407 — `js/98-462.js` (era `462.html`, 1132 linhas)

```text
Crie js/98-462.js. Ele faz: Comparador Jurídico — TJMG (Fator) + BCB (Juros) — Multi-Cenário — Comparador Jurídico — TJMG (Fator) + BCB (Juros) — Multi-Cenário.
No app original ele tinha estas funções/partes: snapshotToObject, loadSnapshotObject, autosave, scheduleAutosave, setClock, setStatus, fmtBRL, toNumberBR, escapeHtml, parseDateBR, dateToYM, listMonths, download, parseCSV, split, parseIndicesText, extractYearRowsFromTJText, loadTJFactorsAsMonthlyCorrections.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 408 — `js/98-463.js` (era `463.html`, 3276 linhas)

```text
Crie js/98-463.js. Ele faz: Painel Maikon Caldeira — Advocacia Digital — 🔧 SK Editor Jurídico v2.
No app original ele tinha estas funções/partes: showSection, processZip, renderFileList, openFile, filterFiles, copyCode, loadFromGitHub, createEmptyApp, saveCombinerState, loadCombinerState, renderAppCards, addAppCard, removeAppCard, updateAppField, clearAllCombiner, generateSuperPrompt, copyGeneratedPrompt, showLoader.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 409 — `js/98-464.js` (era `464.html`, 1265 linhas)

```text
Crie js/98-464.js. Ele faz: Playground Code Pro + IA — Maikon Caldeira — Bem-vindo ao Playground Pro.
No app original ele tinha estas funções/partes: App, updateLineNumbers, updateCursorPosition, jumpToLine, openGotoLine, closeGotoLine, gotoLine, saveCurrentTab, loadEditorContent, switchTab, updateTabs, switchMode, debouncePreview, buildDocument, main, updatePreview, autoSave, copyCode.
Ele chamava estes endereços: https://api.openai.com/v1/chat/completions, https://generativelanguage.googleapis.com/v1beta/models/gemini-pro:generateContent?key=${aiSettings.apiKey}, https://api.anthropic.com/v1/messages, https://api.duckduckgo.com/?q=${encodeURIComponent(query)}&format=json&no_html=1&skip_disambig=1. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 410 — `js/98-465.js` (era `465.html`, 5033 linhas)

```text
Crie js/98-465.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: getModulos, setModulos, getSelected, setSelected, trocarAba, analisarCodigo, extrairFuncoes, encontrarFimFuncao, extrairEstilos, extrairElementos, extrairScripts, renderAnalise, extrairTudo, copiarParaPlayground, salvarComoModulo, salvarModulo, limparModulo, renderModulos.
Ele chamava estes endereços: https://api.openai.com/v1/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 411 — `js/98-466.js` (era `466.html`, 5004 linhas)

```text
Crie js/98-466.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: switchTab, showToast, importarArquivo, importarZip, importarTar, parsearTar, decompressGzip, importarArquivoSimples, importarCodigo, limparImportacao, filtrarArquivos, renderizarArquivos, abrirArquivo, mostrarEstatisticas, buscarTermos, diagnosticar, analisarComIA, mostrarErros.
Ele chamava estes endereços: ) || linha.includes(, , , ${provedor.url}/chat/completions, ,. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 412 — `js/98-467.js` (era `467.html`, 836 linhas)

```text
Crie js/98-467.js. Ele faz: Explorador de Versões e Bugs - Replit/ZIP — 🔍 Explorador de Versões e Bugs.
No app original ele tinha estas funções/partes: extrairZip, listarArquivos, buscarBugs, extrair_zip, listar_arquivos, buscar_bugs, mudarTab, carregarZip, buscarEmZip, analisarBugs, compararVersoes, gerarBuildOtimizado, gerarScriptAPK, copiar.
O original usava as bibliotecas fs, path, unzipper: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 413 — `js/98-468.js` (era `468.html`, 782 linhas)

```text
Crie js/98-468.js. Ele faz: Diagnóstico de Executável com Problema — 🔧 Diagnóstico de Executável com Problema.
No app original ele tinha estas funções/partes: conectar_servidor, diagnosticar, exibirDiagnostico, mudarTab, verificarSolucao, copiar, baixarCodigo, gerarDocumentoProcon.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 414 — `js/98-469.js` (era `469.html`, 653 linhas)

```text
Crie js/98-469.js. Ele faz: Gerador Automático de package.json + Workflow — 📦 Gerador de package.json + Workflow Completo.
No app original ele tinha estas funções/partes: atualizarOpcoes, gerarPackageJson, gerarWorkflow, gerarScripts, mudarTab, copiar, baixarJson.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 415 — `js/98-47.js` (era `47.html`, 669 linhas)

```text
Crie js/98-47.js. Ele faz: Navegador PWA.
No app original ele tinha estas funções/partes: init, setupEventListeners, navigate, goBack, goForward, reload, carregarFavoritos, salvarFavoritosLocal, renderizarFavoritos, adicionarFavorito, removerFavorito, atualizarBotaoFavorito, traduzirConteudo, mostrarErro.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 416 — `js/98-470.js` (era `470.html`, 11646 linhas)

```text
Crie js/98-470.js. Ele faz: Mini SK — 🔗 Meus Links.
No app original ele tinha estas funções/partes: modal, done, openDB, reqP, nada, extOf, baseName, dirName, norm, typeOf, decodeBytes, looksBinary, toBase64, fromBase64, recordFromBytes, saveNow, touch, getDir.
O original usava as bibliotecas  + q + u + q + , react, react-dom,  + JSON.stringify(principal) + , http, fs, path, os, electron, crypto, url: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: dados.json, https://api.anthropic.com/v1/models?limit=100, http://127.0.0.1:11434/api/version, https://registry.npmjs.org, https://api.npms.io/v2/search?size=15&q=, sw.js, https://api.github.com, ./, https://api.github.com/repos/, https://api.expo.dev/graphql. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 417 — `js/98-471.js` (era `471.html`, 728 linhas)

```text
Crie js/98-471.js. Ele faz: Analisador de Código — 🔍 Analisador de Código.
No app original ele tinha estas funções/partes: renderizarSlots, atualizarCodigo, importarArquivo, contarLinhas, limparTudo, detectarTipos, detectarCDNs, detectarFuncoes, detectarDuplicatas, analisarTudo, gerarManual, extrairCDNsTag, extrairCSS, extrairJS, extrairBody, gerarHTMLUnificado, trocarAba, baixarFinal.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 418 — `js/98-472.js` (era `472.html`, 1 linhas)

```text
Crie js/98-472.js. Ele faz: 11 — 11.
No app original ele tinha estas funções/partes: renderLista, abrirConversa, conversaAtiva, renderMensagens, enviarMensagem, formatarHora, salvar, extOf, normPath, findPaths, compatible, sniffType, looksWindows, extForType, fnNames, computeSig, jaccard, speakerOf.
O original usava as bibliotecas @capacitor/cli, vite, @vitejs/plugin-react, path, express: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: https://api.anthropic.com/v1/messages, https://api.anthropic.com/v1/models?limit=100, ${url}/rest/v1/, http://localhost:8080/teste, http://localhost:8080/dados, http://localhost:8080/comando. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 419 — `js/98-473.js` (era `473.html`, 256 linhas)

```text
Crie js/98-473.js. Ele faz: ai-studio-backup-2026-10-24-15-47 — Relatório — 📂 ai-studio-backup-2026-10-24-15-47.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 420 — `js/98-474.js` (era `474.html`, 256 linhas)

```text
Crie js/98-474.js. Ele faz: ai-studio-backup-2026-10-24-15-47 — Relatório — 📂 ai-studio-backup-2026-10-24-15-47.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 421 — `js/98-475.js` (era `475.html`, 729 linhas)

```text
Crie js/98-475.js. Ele faz: Analisador de Código — 🔍 Analisador de Código.
No app original ele tinha estas funções/partes: renderizarSlots, atualizarCodigo, importarArquivo, contarLinhas, limparTudo, detectarTipos, detectarCDNs, detectarFuncoes, detectarDuplicatas, analisarTudo, gerarManual, extrairCDNsTag, extrairCSS, extrairJS, extrairBody, gerarHTMLUnificado, trocarAba, baixarFinal.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 422 — `js/98-476.js` (era `476.html`, 11011 linhas)

```text
Crie js/98-476.js. Ele faz: analise_legal-assistant.tsx.md — analise_legal-assistant.tsx.md.
No app original ele tinha estas funções/partes: LegalAssistant.
O original usava as bibliotecas react, wouter, @tanstack/react-query, @shared/schema, lucide-react: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: /api/demo-key-status, /api/demo-key-config, /api/tts, /api/voice-chat, /api/doc-templates/upload-docx, /api/export/word-with-template, /api/jurisprudencia/buscar, /api/code-assistant, /api/import/url, /api/upload/extract-text, /api/upload/transcribe, /api/ai/process, /api/ai/refine, /api/git-push, /api/ai-usage-summary, /api/ai-usage-credit, /api/demo-key-test. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 423 — `js/98-478.js` (era `478.html`, 11 linhas)

```text
Crie js/98-478.js. Ele faz: cdns (1).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 424 — `js/98-479.js` (era `479.html`, 252 linhas)

```text
Crie js/98-479.js. Ele faz: Guia dos Apps do Maikon — Guia dos seus apps.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 425 — `js/98-48.js` (era `48.html`, 4409 linhas)

```text
Crie js/98-48.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: mostrarToast, atualizarTamanho, sincronizarTamanho, atualizarRespostaIA, sincronizarRespostaIA, atualizarContexto, sincronizarContexto, mudarAba, mostrarModal, fecharModal, mostrarOpcoesSaida, atualizarConfigIA, toggleSenha, salvarConfigIA, carregarConfigIA, testarConexaoIA, atualizarInfoModelo, chamarIA.
Ele chamava estes endereços: https://api.openai.com/v1/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 426 — `js/98-480.js` (era `480.html`, 14394 linhas)

```text
Crie js/98-480.js. Ele faz: Blocos de colado.js — ✂️ colado.js — 48 blocos.
No app original ele tinha estas funções/partes: Fun, modal, openDB, typeOf, decodeBytes, looksBinary, toBase64, fromBase64, recordFromBytes, touch, ensureParents, commonRoot, crc32, streamThrough, read, write, lerTar, readAny.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 427 — `js/98-481.js` (era `481.html`, 1098 linhas)

```text
Crie js/98-481.js. Ele faz: 🔬 Dissecador de Código — Iara Suite v2.0 — 🔬 Dissecador de Código — Iara Suite v2.0.
No app original ele tinha estas funções/partes: processarArquivo, mostrarInfoArquivo, detectarTipo, formatarTamanho, analisarArquivo, gerarIndice, renderizarIndice, selecionarIndice, rastrearDependencias, renderizarDependencias, atualizarBadges, dissecaBloco, renderizarBlocos, filtrarIndice, filtrarPorTipo, copiarBloco, exportarBloco, exportarTudo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 428 — `js/98-482.js` (era `482.html`, 22 linhas)

```text
Crie js/98-482.js. Ele faz: SK Editor v3.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 429 — `js/98-483.js` (era `483.html`, 28 linhas)

```text
Crie js/98-483.js. Ele faz: Meu App — Meu App.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 430 — `js/98-484.js` (era `484.html`, 54 linhas)

```text
Crie js/98-484.js. Ele faz: Instalador · Assistente Jurídico (no computador) — 📦 Assistente Jurídico (no computador).
No app original ele tinha estas funções/partes: arquivo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 431 — `js/98-485.js` (era `485.html`, 54 linhas)

```text
Crie js/98-485.js. Ele faz: Instalador · Mini SK v09/10-b — 📦 Mini SK v09/10-b.
No app original ele tinha estas funções/partes: arquivo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 432 — `js/98-486.js` (era `486.html`, 54 linhas)

```text
Crie js/98-486.js. Ele faz: Instalador · Mini SK v15/10-a (site / celular / APK) — 📦 Mini SK v15/10-a (site / celular / APK).
No app original ele tinha estas funções/partes: arquivo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 433 — `js/98-487.js` (era `487.html`, 394 linhas)

```text
Crie js/98-487.js. Ele faz: Laboratório do Modular — Laboratório do Modular.
No app original ele tinha estas funções/partes: esc, PADRAO, avisarPai, montarHTML, traduzir, pintarRelato, pintarTrem, pintarLista, pintarArquivos, rodar, copiar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 434 — `js/98-488.js` (era `488.html`, 64 linhas)

```text
Crie js/98-488.js. Ele faz: Playground HTML — 🚀 Playground HTML.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 435 — `js/98-489.js` (era `489.html`, 832 linhas)

```text
Crie js/98-489.js. Ele faz: RECEITA — 🧬 Receita para recriar: JurisPro.
No app original ele tinha estas funções/partes: properly, marca, copiar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 436 — `js/98-49.js` (era `49.html`, 265 linhas)

```text
Crie js/98-49.js. Ele faz: SK Scanner v2 — SK Scanner v2.
No app original ele tinha estas funções/partes: scanText, processFiles, scanGitHub, showResults, downloadReport, clearResults.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 437 — `js/98-490.js` (era `490.html`, 673 linhas)

```text
Crie js/98-490.js. Ele faz: ⚖️ Cofre de Configurações — 🔐 Cofre de Configurações.
No app original ele tinha estas funções/partes: init, salvar, render, renderTabs, renderItems, renderStats, setAba, salvarAba, deletarAba, openModal, closeModal, preencherSelectAbas, salvarItem, editarItem, deletarItem, toggleOcultar, copiarValor, copiarExport.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 438 — `js/98-491.js` (era `491.html`, 1372 linhas)

```text
Crie js/98-491.js. Ele faz: Fatiador Universal de Código — Fatiador Universal de Código.
No app original ele tinha estas funções/partes: setStatus, normalizePath, getExtension, formatBytes, importFiles, pasteFile, newFile, renderFileList, openFile, updateInfo, scheduleSave, saveProject, restoreProject, splitCurrent, splitByLines, splitByChars, getStructurePattern, splitByStructure.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 439 — `js/98-492.js` (era `492.html`, 54 linhas)

```text
Crie js/98-492.js. Ele faz: Instalador · Caça-Bug — 📦 Caça-Bug.
No app original ele tinha estas funções/partes: arquivo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 440 — `js/98-493.js` (era `493.html`, 1 linhas)

```text
Crie js/98-493.js. Ele faz: Arquivos juntados — Arquivos juntados.
No app original ele tinha estas funções/partes: resizePreview, exportarProjeto, getFileColor, MiniVFSRobusto, sort, MiniFileTree, MiniEditor, close, toggleSidebar, renderizarApps, renderizarListaApps, abrirModal, fecharModal, limparFormulario, adicionarApp, removerApp, gerarManifest, gerarServiceWorker.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 441 — `js/98-494.js` (era `494.html`, 823 linhas)

```text
Crie js/98-494.js. Ele faz: Laboratório HTML — Advocacia Previdenciária.
No app original ele tinha estas funções/partes: separar, ler, cssDosAjustes, regra, completo, guardar, caminho, limpo, info, marcar, pagina, quemE, hex, transparente, num, montar, carregar, enviar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 442 — `js/98-495.js` (era `495.html`, 1262 linhas)

```text
Crie js/98-495.js. Ele faz: 📂 Leitor Universal de Arquivos — Leitor Universal de Arquivos.
No app original ele tinha estas funções/partes: processFile, detectFormat, renderAll, renderAIStudio, renderMsg, renderChatGPT, renderMessages, renderGenericJSON, renderText, renderRaw, showTab, toggleConv, resetApp, esc, escJS, fmtDate, formatBytes, infoBox.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 443 — `js/98-496.js` (era `496.html`, 305 linhas)

```text
Crie js/98-496.js. Ele faz: PLANO — Plano do projeto: juridico.
No app original ele tinha estas funções/partes: marca, copiar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 444 — `js/98-497.js` (era `497.html`, 1128 linhas)

```text
Crie js/98-497.js. Ele faz: Planos.md — Planos.md.
Ele chamava estes endereços: dados.json. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 445 — `js/98-498.js` (era `498.html`, 1187 linhas)

```text
Crie js/98-498.js. Ele faz: 📦 Project Manager Pro - Terminal & NPM — 🚀
            Project Manager Pro.
No app original ele tinha estas funções/partes: setupDragDrop, processFiles, extractZip, getFileType, updateFileTree, renderFileTree, renderTree, analyzeProject, extractDependencies, addAllDetected, searchNpm, selectNpmPackage, addDependency, removeDependency, updateUI, updateStats, generatePackageJson, copyPackageJson.
Ele chamava estes endereços: https://registry.npmjs.org/-/v1/search?text=${encodeURIComponent(query)}&size=30. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 446 — `js/98-499.js` (era `499.html`, 9 linhas)

```text
Crie js/98-499.js. Ele faz: Sem título (1) — Bem-vindo ao HTML Playground.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 447 — `js/98-5.js` (era `5.html`, 1121 linhas)

```text
Crie js/98-5.js. Ele faz: Netlify Build + Testador API — 🚀 Netlify Build + Testador de API.
No app original ele tinha estas funções/partes: cp2, baixarEl, baixarTexto, selMetodo, carregarUrl, testarApi, mostrarResposta, statusTexto, gerarDiagnostico, adicionarHistorico, renderHistorico, carregarHistorico, limparTeste, limparHistorico, analisarErro, gerarTudo.
O original usava as bibliotecas vite, @vitejs/plugin-react, cors: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 448 — `js/98-50.js` (era `50.html`, 1 linhas)

```text
Crie js/98-50.js. Ele faz: Relatório de metadados.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 449 — `js/98-500.js` (era `500.html`, 245 linhas)

```text
Crie js/98-500.js. Ele faz: Manual do Maikon — 📘 Manual do Maikon.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 450 — `js/98-51.js` (era `51.html`, 763 linhas)

```text
Crie js/98-51.js. Ele faz: RECEITA — 🧬 Receita para recriar: SK Jurídico — Assistente IA.
No app original ele tinha estas funções/partes: properly, marca, copiar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 451 — `js/98-52.js` (era `52.html`, 432 linhas)

```text
Crie js/98-52.js. Ele faz: relatorio-AssistenteJuridico-PWA-8zip  714d7dd (3).md — relatorio-AssistenteJuridico-PWA-8zip  714d7dd (3).md.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 452 — `js/98-53.js` (era `53.html`, 879 linhas)

```text
Crie js/98-53.js. Ele faz: relatorio-AssistenteJuridico-PWA-8zip 1AssistenteJ.md — relatorio-AssistenteJuridico-PWA-8zip 1AssistenteJ.md.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 453 — `js/98-54.js` (era `54.html`, 837 linhas)

```text
Crie js/98-54.js. Ele faz: 🔧 PWA Builder — Gerador de Instalação — 🔧 PWA Builder.
No app original ele tinha estas funções/partes: toggleProjectOptions, updateIconPreview, generateManifest, generateSW, generateHTML, generateIconBlob, downloadFile, downloadManifest, downloadSW, downloadHTML, generateAll, showOutput, showAlert.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 454 — `js/98-55.js` (era `55.html`, 1581 linhas)

```text
Crie js/98-55.js. Ele faz: PWA Jurídico — Maikon Caldeira.
No app original ele tinha estas funções/partes: getModulos, setModulos, getSelected, setSelected, trocarAba, analisarCodigo, extrairFuncoes, encontrarFimFuncao, extrairEstilos, extrairElementos, extrairScripts, renderAnalise, extrairTudo, copiarParaPlayground, salvarComoModulo, salvarModulo, limparModulo, renderModulos.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 455 — `js/98-56.js` (era `56.html`, 424 linhas)

```text
Crie js/98-56.js. Ele faz: 🧩 Montador Multi-Projetos — PWA Jurídico — 🧩 Montador Multi-Projetos PWA JURÍDICO — MAIKON CALDEIRA.
No app original ele tinha estas funções/partes: salvarProjetos, carregarProjetos, renderizarSalvos, testarProjeto, limparProjeto, copiarCodigo, importarArquivo, gerarHtmlFinal, extrairConteudo, trocarProjeto, exportarBackup, importarBackup, escHtml, mostrarToast.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 456 — `js/98-57.js` (era `57.html`, 18 linhas)

```text
Crie js/98-57.js. Ele faz: Live Code Runner.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 457 — `js/98-58.js` (era `58.html`, 804 linhas)

```text
Crie js/98-58.js. Ele faz: SK-Prompt Manager — Templates + Histórico.
No app original ele tinha estas funções/partes: loadData, savePrompts, saveTemplates, selectTemplate, loadTemplate, generatePrompt, copyPrompt, savePrompt, saveAsTemplate, viewHistorico, loadPromptFromHistorico, deletePrompt, closeHistorico, clearForm, openNewPrompt, exportAll.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 458 — `js/98-59.js` (era `59.html`, 2006 linhas)

```text
Crie js/98-59.js. Ele faz: Projeto Lab.
No app original ele tinha estas funções/partes: esc, tick, fmtSize, fmtDate, normPath, dirname, basename, extOf, joinPath, hex, inflate, mask, lineFinder, parseLenientJSON, langOf, sniff, zipEntries, parsePax.
Ele chamava estes endereços: https://api.anthropic.com/v1/messages, https://api.anthropic.com/v1/models?limit=100. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 459 — `js/98-6.js` (era `6.html`, 754 linhas)

```text
Crie js/98-6.js. Ele faz: Gerenciador de Portas e Projetos — 🔧 Gerenciador de Projetos.
No app original ele tinha estas funções/partes: criarJanela, cp2, baixarTxt, gerarCmdsPorta, selecionarPorta, gerarConfig, gerarPkgExe.
O original usava as bibliotecas electron, path, child_process, vite, @vitejs/plugin-react, express, http, fs: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 460 — `js/98-60.js` (era `60.html`, 2388 linhas)

```text
Crie js/98-60.js. Ele faz: Chat IA Profissional.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 461 — `js/98-61.js` (era `61.html`, 1704 linhas)

```text
Crie js/98-61.js. Ele faz: AI Code Studio — 🤖 AI Code Studio.
No app original ele tinha estas funções/partes: init, saveToStorage, loadFromStorage, setupAutoSave, newConversation, loadConversation, deleteConversation, renderConversations, renderMessages, appendMessageToDOM, formatMessage, escapeHtml, cleanCodeOutput, copyCodeBlock, sendMessage, addLoadingMessage, callAI, buildContextMessages.
Ele chamava estes endereços: https://api.openai.com/v1/chat/completions, https://api.anthropic.com/v1/messages, https://generativelanguage.googleapis.com/v1beta/models/${model}:generateContent?key=${apiKey}, https://api.groq.com/openai/v1/chat/completions, https://openrouter.ai/api/v1/chat/completions, ${url}/api/chat, https://google.serper.dev/search. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 462 — `js/98-62.js` (era `62.html`, 2000 linhas)

```text
Crie js/98-62.js. Ele faz: 🚀 Guia Interativo - Chat IA Profissional — 🚀 Chat IA Profissional v1.1.
No app original ele tinha estas funções/partes: inicializarGuia, renderizarSteps, renderizarConteudo, renderizarMenu, irParaPasso, irParaProximoPasso, verificarStepCompleto, marcarStepCompleto, atualizarProgress, copiarCodigo, mostrarNotificacao, finalizarGuia.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 463 — `js/98-63.js` (era `63.html`, 1757 linhas)

```text
Crie js/98-63.js. Ele faz: 🔧 ConstruAPK Pro — Analisador e Gerador — ConstruAPK Pro — Analisador & Gerador.
No app original ele tinha estas funções/partes: importZip, importFolder, afterImport, decodeText, renderTree, buildTree, renderNode, hasProblems, cntF, toggleF, expandAll, collapseAll, toggleSidebar, fIcon, fmtSz, esc, openFile, closeTab.
O original usava as bibliotecas @capacitor/cli, vite, @vitejs/plugin-react, path: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 464 — `js/98-64.js` (era `64.html`, 969 linhas)

```text
Crie js/98-64.js. Ele faz: 📱 Gerador DevMobile EAS — 📱 Gerador EAS Build — Baseado no DevMobile.
No app original ele tinha estas funções/partes: switchTab, atualizar, autoPackage, gerarTudo, renderArquivos, copiar, showToast, exportarZip, fIcon, esc, escHtml, loadJSZ.
O original usava as bibliotecas expo: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 465 — `js/98-65.js` (era `65.html`, 1087 linhas)

```text
Crie js/98-65.js. Ele faz: 📦 Build & Deploy — Build & Deploy.
No app original ele tinha estas funções/partes: salvar, carregarCfg, cfg, importarZip, atualizarProjInfo, renderPlats, toggle, getBody, baixarZip, baixarTodos, cleanDeps, viteConfig, pkgClean, gerarZip, createWindow, salvarBlob, toast, esc.
O original usava as bibliotecas vite, @vitejs/plugin-react, @tailwindcss/vite, path, @capacitor/cli, electron: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 466 — `js/98-66.js` (era `66.html`, 1202 linhas)

```text
Crie js/98-66.js. Ele faz: Sistema Profissional - Modular — 📊 Sistema.
No app original ele tinha estas funções/partes: App, SupabaseManager, abrirConexao, fecharModal, conectarSupabase, desconectarSupabase, mostrarAlerta, abrirNovoProjet, abrirNovaTarefa, abrirNovoUsuario.
Ele chamava estes endereços: ${url}/rest/v1/. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 467 — `js/98-67.js` (era `67.html`, 1446 linhas)

```text
Crie js/98-67.js. Ele faz: Gerador de Estrutura de Projeto — 🏗️ Gerador de Estrutura de Projeto.
No app original ele tinha estas funções/partes: processarZip, extrairDependencias, exibirEstrutura, renderizarArvore, calcularEstatisticas, contar, exibirDependencias, gerarPackageJson, gerarScripts, gerarConfiguracoes, gerarBat, gerarBatAvancado, mudarAba, mudarConfiguracao, copiarParaClipboard, baixarArquivo, baixarPackageJson, analisarProjeto.
O original usava as bibliotecas vite, @vitejs/plugin-react: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 468 — `js/98-68.js` (era `68.html`, 481 linhas)

```text
Crie js/98-68.js. Ele faz: Analisador de Projeto — 🔍 Analisador de Projeto.
No app original ele tinha estas funções/partes: analyze, runAnalysis, detectRoot, buildStats, buildTree, extBadge, printTree, buildPlano, buildCommands, buildFilesContent, detectTechs, describeStructure, getKeyFiles, guessFunction, getDeps, getScripts, getObservations, copyEl.
Ele chamava estes endereços: https://registry.npmjs.org/${pkg}/latest. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 469 — `js/98-69.js` (era `69.html`, 779 linhas)

```text
Crie js/98-69.js. Ele faz: Playground Code — Maikon Caldeira — Bem-vindo ao HTML Playground.
No app original ele tinha estas funções/partes: App, debouncePreview, updateLineNumbers, saveCurrentTab, loadEditorContent, switchTab, updateTabs, switchMode, buildDocument, main, updatePreview, autoSave, copyCode, downloadFile, toggleFullscreen, importFile, toggleEditor, clearCode.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 470 — `js/98-7.js` (era `7.html`, 608 linhas)

```text
Crie js/98-7.js. Ele faz: Corretor de Projetos — 🔧 Corretor de Projetos.
No app original ele tinha estas funções/partes: carregarArquivo, processarArquivo, mostrarResultado, analisarPackageJson, detectarProblemas, detectarPorta, gerarPackageCorrigido, gerarPackageJsonNovo, criarCard, formatarTamanho, copiarJson, baixarJson.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 471 — `js/98-70.js` (era `70.html`, 18 linhas)

```text
Crie js/98-70.js. Ele faz: playground — 🚀 Playground.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 472 — `js/98-71.js` (era `71.html`, 1357 linhas)

```text
Crie js/98-71.js. Ele faz: Code Playground - HTML/CSS/JS/React/Python — Bem-vindo ao HTML Playground.
No app original ele tinha estas funções/partes: App, init, loadState, saveState, setupEventListeners, switchMode, switchTab, updateTabVisibility, updateEditors, updateLineNumbers, highlightSearchResults, updatePreview, buildHtmlDocument, buildReactDocument, runPython, handleFileImport, openFullscreen, copyCode.
Ele chamava estes endereços: /api/code/run. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 473 — `js/98-72.js` (era `72.html`, 3045 linhas)

```text
Crie js/98-72.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: App, debouncePreview, updateLineNumbers, saveCurrentTab, loadEditorContent, switchTab, updateTabs, switchMode, buildDocument, main, updatePreview, autoSave, copyCode, downloadFile, toggleFullscreen, importFile, toggleEditor, clearCode.
Ele chamava estes endereços: https://api.openai.com/v1/chat/completions, https://generativelanguage.googleapis.com/v1beta/models/gemini-pro:generateContent?key=${aiSettings.apiKey}, https://api.anthropic.com/v1/messages, https://api.duckduckgo.com/?q=${encodeURIComponent(query)}&amp;format=json&amp;no_html=1&amp;skip_disambig=1. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 474 — `js/98-73.js` (era `73.html`, 1034 linhas)

```text
Crie js/98-73.js. Ele faz: Playground — MeuIDE — 🚀 Playground.
No app original ele tinha estas funções/partes: init, applyTheme, updateLineNumbers, buildDoc, escapeHtml, loadSnippets, loadLocalSnippets, renderSnippets, toast.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 475 — `js/98-74.js` (era `74.html`, 403 linhas)

```text
Crie js/98-74.js. Ele faz: Suite Jurídica + IA.
No app original ele tinha estas funções/partes: showPage.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 476 — `js/98-75.js` (era `75.html`, 2133 linhas)

```text
Crie js/98-75.js. Ele faz: plano-SK-Editor-v3-SemReplit-9-1790894751105.md — plano-SK-Editor-v3-SemReplit-9-1790894751105.md.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 477 — `js/98-77.js` (era `77.html`, 1000 linhas)

```text
Crie js/98-77.js. Ele faz: Editor Visual — Bem-vindo!.
No app original ele tinha estas funções/partes: status, togglePainel, trocarAba, colarCodigo, importarArquivo, lerArquivo, renderizar, ativarCliques, podeSelecionar, selecionarElemento, montarPainelProps, editarTexto, editarAttr, editarClasse, editarEstilo, duplicarElemento, removerElemento, sincronizarCodigo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 478 — `js/98-78.js` (era `78.html`, 195 linhas)

```text
Crie js/98-78.js. Ele faz: 🎨 Editor Visual - Funcional de Verdade.
No app original ele tinha estas funções/partes: colarCodigo, importarArquivo, carregarArquivo, renderizar, selecionar, mostrarPropriedades, mudarEstilo, mudarTexto, remover, atualizarCodigo, copiarCodigo, salvarArquivo, rgbToHex.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 479 — `js/98-79.js` (era `79.html`, 937 linhas)

```text
Crie js/98-79.js. Ele faz: 🐝 Editor Visual - Responsivo — 🐝 Editor Visual.
No app original ele tinha estas funções/partes: setStatus, togglePainelCodigo, togglePainelProps, salvarEstado, colarDaAreaTransferencia, abrirImportador, importarArquivo, renderizarCodigo, prepararCliqueVisual, podeSelecionar, selecionarElemento, montarPainel, editarTexto, editarAtributo, editarClasse, editarEstilo, duplicarElemento, removerElemento.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 480 — `js/98-8.js` (era `8.html`, 777 linhas)

```text
Crie js/98-8.js. Ele faz: Guia do Terminal — 🖥️ Guia do Terminal & Python.
No app original ele tinha estas funções/partes: trocarPagina, copiarCmd, mostrarResposta, verificar1, verificar2, verificar3, verificar4.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 481 — `js/98-80.js` (era `80.html`, 641 linhas)

```text
Crie js/98-80.js. Ele faz: Editor Visual — 🎨 Editor Visual.
No app original ele tinha estas funções/partes: importarArquivo, abrirColar, fecharColar, confirmarColar, renderizar, adicionarListeners, selecionar, mostrarProps, atualizarTexto, sincronizarCodigo, copiarCodigo, salvarArquivo, limpar, status, hex.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 482 — `js/98-81.js` (era `81.html`, 725 linhas)

```text
Crie js/98-81.js. Ele faz: 🎨 Editor Visual - Funcional — 🎨 Editor Visual - Funcional.
No app original ele tinha estas funções/partes: abrirModalColar, fecharModal, confirmarColar, abrirImportador, importarArquivo, renderizarPreview, adicionarListeners, selecionarElemento, mostrarPropriedades, atualizarEstilo, atualizarPropriedade, atualizarTexto, removerElemento, atualizarCodigoFonte, copiarCodigoFinal, salvarCodigoFinal, rgbToHex, hex.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 483 — `js/98-82.js` (era `82.html`, 577 linhas)

```text
Crie js/98-82.js. Ele faz: 🎨 Editor Visual de Código — 🎨 Editor Visual de Código.
No app original ele tinha estas funções/partes: importarCodigo, renderizarPreview, adicionarListeners, selecionarElemento, mostrarPropriedades, atualizarEstilo, atualizarPropriedade, atualizarTexto, atualizarCodigoFonte, copiarCodigo, salvarCodigo, limparTudo, hexToColor, hex.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 484 — `js/98-83.js` (era `83.html`, 692 linhas)

```text
Crie js/98-83.js. Ele faz: SK-HTML Magic Editor — Bem-vindo!.
No app original ele tinha estas funções/partes: updatePreview, addClickListeners, selectElement, updateInspector, updateStyle, updateAttribute, updateHTMLCode, hexToColor, handleFileImport, downloadHTML, openPasteModal, closePasteModal, handlePaste.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 485 — `js/98-84.js` (era `84.html`, 907 linhas)

```text
Crie js/98-84.js. Ele faz: SK-Build Guide — Entenda o Build.
No app original ele tinha estas funções/partes: sum, loadTopic.
O original usava as bibliotecas fs: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 486 — `js/98-85.js` (era `85.html`, 802 linhas)

```text
Crie js/98-85.js. Ele faz: SK-Build Unpacker — Desempacotar Build.
No app original ele tinha estas funções/partes: unpackBuild, extractHTML, extractJavaScript, extractCSS, extractGeneric, formatCode, formatJavaScript, formatCSS, formatHTML, renderTabs, renderFilesList, selectTab, updateStats, escapeHtml, handleFileImport, pasteCode, clearInput, copyFile.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 487 — `js/98-86.js` (era `86.html`, 1123 linhas)

```text
Crie js/98-86.js. Ele faz: Perito de Metadados — Perito de Metadados.
No app original ele tinha estas funções/partes: EMBUTIDO, esc, latin1, deLatin1, juntar, utf8, decTexto, tamanhoTxt, sha256js, sha256, inflar, inflarZlib, mkData, dataPdf, dataExif, dataIso, difTxt, num.
Ele chamava estes endereços: https://nominatim.openstreetmap.org/search?format=json&limit=1&countrycodes=br&q=. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 488 — `js/98-87.js` (era `87.html`, 1224 linhas)

```text
Crie js/98-87.js. Ele faz: Parser Markdown - Gerador de Projetos — 🚀 Parser Markdown.
No app original ele tinha estas funções/partes: parseMarkdown, generateInteractiveHTML, switchTab, renderFiles, selectFile, renderEditor, saveFile, deleteFile, newFolder, newFile, createFolder, createFile, closeModal, showStats, copyAll, generateScripts, copyScript, openFileSelector.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 489 — `js/98-88.js` (era `88.html`, 3399 linhas)

```text
Crie js/98-88.js. Ele faz: Painel Maikon Caldeira — Advocacia Digital — Maikon Caldeira.
No app original ele tinha estas funções/partes: renderizarApps, renderizarListaApps, abrirModal, fecharModal, limparFormulario, adicionarApp, removerApp, gerarManifest, gerarServiceWorker, gerarIcones, baixarTudo, baixarArquivo, mostrarAlerta, salvarProjetos, carregarProjetos, renderizarSalvos, testarProjeto, limparProjeto.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 490 — `js/98-89.js` (era `89.html`, 558 linhas)

```text
Crie js/98-89.js. Ele faz: Organizador de Documentos — 📑 Organizador de Documentos.
No app original ele tinha estas funções/partes: esc, tipoDe, compDe, numDe, moedaPorData, lerPdf, organizar, deTexto, moldeDe, bate, aplicar, camposUsados, status, tudo, renderLinhas, escolherRegra, renderRegras, fmtComp.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 491 — `js/98-9.js` (era `9.html`, 435 linhas)

```text
Crie js/98-9.js. Ele faz: Leitor de Memória — 📖 Leitor de Memória.
No app original ele tinha estas funções/partes: formatarTexto, escHtml, lerMemoria, copiarMensagem, copiarTudo, limpar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 492 — `js/98-90.js` (era `90.html`, 818 linhas)

```text
Crie js/98-90.js. Ele faz: Extrator Universal BPC/LOAS - Análise Processual — Extrator Universal BPC/LOAS.
No app original ele tinha estas funções/partes: extrairTextoPDF, extrairTextoWord, reprocessar, mostrarTextoBruto, copiarTexto, adicionarVariavel, removerVar, mostrarAjudaRegex, fecharModalAjuda, exportarExcel, exportarPDF, exportarWord, exportarJSON.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 493 — `js/98-91.js` (era `91.html`, 2054 linhas)

```text
Crie js/98-91.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: onChange, updateSelect, current, save, load, setupAutoSave, exportAll, importBackup, handleImport, _download, toggle, render, addManual, closeMemoryModal, saveManual, addMemory, deleteMemory, clearAll.
Ele chamava estes endereços: https://api.openai.com/v1/chat/completions, https://api.anthropic.com/v1/messages, https://generativelanguage.googleapis.com/v1beta/models/${model}:generateContent?key=${apiKey}, https://api.groq.com/openai/v1/chat/completions, https://openrouter.ai/api/v1/chat/completions, ${url}/api/chat, https://google.serper.dev/search. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 494 — `js/98-92.js` (era `92.html`, 4972 linhas)

```text
Crie js/98-92.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: onChange, updateSelect, current, save, load, setupAutoSave, exportAll, importBackup, handleImport, _download, toggle, render, addManual, closeMemoryModal, saveManual, addMemory, deleteMemory, clearAll.
Ele chamava estes endereços: https://api.openai.com/v1/chat/completions, https://api.anthropic.com/v1/messages, https://generativelanguage.googleapis.com/v1beta/models/${model}:generateContent?key=${apiKey}, https://api.groq.com/openai/v1/chat/completions, https://openrouter.ai/api/v1/chat/completions, ${url}/api/chat, https://google.serper.dev/search, /api/code/run. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 495 — `js/98-93.js` (era `93.html`, 2376 linhas)

```text
Crie js/98-93.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: App, updateLineNumbers, saveCurrentTab, loadEditorContent, switchTab, updateTabs, switchMode, buildDocument, run, updatePreview, toggleAuto, autoSave, getSnippets, setSnippets, saveProject, saveAsNew, openSavedModal, closeSavedModal.
Ele chamava estes endereços: https://api.openai.com/v1/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 496 — `js/98-94.js` (era `94.html`, 1896 linhas)

```text
Crie js/98-94.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: App, debouncePreview, updateLineNumbers, saveCurrentTab, loadEditorContent, switchTab, updateTabs, switchMode, buildDocument, main, updatePreview, autoSave, copyCode, importFile, resetCode, getSnippets, setSnippets, saveToLocal.
Ele chamava estes endereços: https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash:generateContent?key=${apiKey}, https://api.openai.com/v1/chat/completions. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 497 — `js/98-95.js` (era `95.html`, 529 linhas)

```text
Crie js/98-95.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: salvarProjetos, carregarProjetos, renderizarSalvos, testarProjeto, limparProjeto, copiarCodigo, importarArquivo, gerarHtmlFinal, trocarProjeto, exportarBackup, importarBackup, escHtml, mostrarToast.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 498 — `js/98-96.js` (era `96.html`, 6896 linhas)

```text
Crie js/98-96.js. Ele faz: Multi-Projetos PWA — Maikon Caldeira.
No app original ele tinha estas funções/partes: App, showStatus, showConfigStatus, updateSupabaseStatus, safeJsonParse, loadState, persistState, nextSequence, getCurrentCode, setCurrentCode, getProjectPayload, getProjectRecord, setMode, setTab, renderModeButtons, renderTabs, updateEditor, renderLayout.
Ele chamava estes endereços: /api/code/run, https://api.openai.com/v1/chat/completions, https://api.anthropic.com/v1/messages, https://generativelanguage.googleapis.com/v1beta/models/${model}:generateContent?key=${apiKey}, https://api.groq.com/openai/v1/chat/completions, https://openrouter.ai/api/v1/chat/completions, ${url}/api/chat, https://google.serper.dev/search. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 499 — `js/98-97.js` (era `97.html`, 746 linhas)

```text
Crie js/98-97.js. Ele faz: Code Merger Pro — Maikon Caldeira.
No app original ele tinha estas funções/partes: generateId, saveState, addProject, deleteProject, selectProject, updateProjectCode, analyzeHTML, renderProjects, setupDragDrop, updateProjectOrder, moveUp, moveDown, duplicateProject, openImportModal, closeImportModal, importCode, importFromFile, analyzeCode.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 500 — `js/98-98.js` (era `98.html`, 768 linhas)

```text
Crie js/98-98.js. Ele faz: Build React - Executável Funcional — ⚛️ Build React - Executável Funcional.
No app original ele tinha estas funções/partes: createWindow, mudarTab, atualizarBundler, gerarPackageJsonReact, copiar, baixarArquivo, verificarConclusao.
O original usava as bibliotecas vite, @vitejs/plugin-react, electron, path, electron-is-dev: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 501 — `js/98-99.js` (era `99.html`, 542 linhas)

```text
Crie js/98-99.js. Ele faz: 🏗️ Montador - Chat IA — 🏗️ Montador - Chat IA Profissional.
No app original ele tinha estas funções/partes: inicializar, renderizarArquivos, abrirModal, fecharModal, copiarConteudo, marcarCompleto, atualizarProgresso, renderizarResumo, gerarTodosCodigos, baixarZip.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 502 — `js/98-hub.js` (era `hub.html`, 81 linhas)

```text
Crie js/98-hub.js. Ele faz: codigos-numerados-2026-10-26 (1) — codigos-numerados-2026-10-26 (1).
No app original ele tinha estas funções/partes: rec, esc, card, show.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 503 — `js/98-inicio.js` (era `index.html`, 148 linhas)

```text
Crie js/98-inicio.js. Ele faz: Maikon Caldeira — Aplicativos — MAIKON CALDEIRA.
No app original ele tinha estas funções/partes: lerInfo, procurar, pintar, abrir, fechar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 504 — `js/99-app.js` e conferir

```text
Crie js/99-app.js: ele olha APP.modulos e monta o menu/abas com um botão para cada módulo. Depois, me mande o index.html atualizado com todos os <script src="js/…"> na ordem certa: js/00-core.js, js/10-abrir.js, js/15-112.js, js/20-122.js, js/25-211.js, js/30-266.js, js/35-278.js, js/40-333.js, js/45-377.js, js/50-392.js, js/55-413.js, js/60-477.js, js/65-76.js, js/70-1.js, js/75-10.js, js/80-100.js, js/85-101.js, js/90-102.js, js/91-103.js, js/92-104.js, js/93-105.js, js/94-106.js, js/95-107.js, js/96-108.js, js/97-109.js, js/98-11.js, js/98-110.js, js/98-111.js, js/98-113.js, js/98-114.js, js/98-115.js, js/98-116.js, js/98-117.js, js/98-118.js, js/98-119.js, js/98-12.js, js/98-120.js, js/98-121.js, js/98-123.js, js/98-124.js, js/98-125.js, js/98-126.js, js/98-127.js, js/98-128.js, js/98-129.js, js/98-13.js, js/98-130.js, js/98-131.js, js/98-132.js, js/98-133.js, js/98-134.js, js/98-135.js, js/98-136.js, js/98-137.js, js/98-138.js, js/98-139.js, js/98-14.js, js/98-140.js, js/98-141.js, js/98-142.js, js/98-143.js, js/98-144.js, js/98-145.js, js/98-146.js, js/98-147.js, js/98-148.js, js/98-149.js, js/98-15.js, js/98-150.js, js/98-151.js, js/98-152.js, js/98-153.js, js/98-154.js, js/98-155.js, js/98-156.js, js/98-157.js, js/98-158.js, js/98-159.js, js/98-16.js, js/98-160.js, js/98-161.js, js/98-162.js, js/98-163.js, js/98-164.js, js/98-165.js, js/98-166.js, js/98-167.js, js/98-168.js, js/98-169.js, js/98-17.js, js/98-170.js, js/98-171.js, js/98-172.js, js/98-173.js, js/98-174.js, js/98-175.js, js/98-176.js, js/98-177.js, js/98-178.js, js/98-179.js, js/98-18.js, js/98-180.js, js/98-181.js, js/98-182.js, js/98-183.js, js/98-184.js, js/98-185.js, js/98-186.js, js/98-187.js, js/98-188.js, js/98-189.js, js/98-19.js, js/98-190.js, js/98-191.js, js/98-192.js, js/98-193.js, js/98-194.js, js/98-195.js, js/98-196.js, js/98-197.js, js/98-198.js, js/98-199.js, js/98-2.js, js/98-20.js, js/98-200.js, js/98-201.js, js/98-202.js, js/98-203.js, js/98-204.js, js/98-205.js, js/98-206.js, js/98-207.js, js/98-208.js, js/98-209.js, js/98-21.js, js/98-210.js, js/98-212.js, js/98-213.js, js/98-214.js, js/98-215.js, js/98-216.js, js/98-217.js, js/98-218.js, js/98-219.js, js/98-22.js, js/98-220.js, js/98-221.js, js/98-222.js, js/98-223.js, js/98-224.js, js/98-225.js, js/98-226.js, js/98-227.js, js/98-228.js, js/98-229.js, js/98-23.js, js/98-230.js, js/98-231.js, js/98-232.js, js/98-233.js, js/98-234.js, js/98-235.js, js/98-236.js, js/98-237.js, js/98-238.js, js/98-239.js, js/98-24.js, js/98-240.js, js/98-241.js, js/98-242.js, js/98-243.js, js/98-244.js, js/98-245.js, js/98-246.js, js/98-247.js, js/98-248.js, js/98-249.js, js/98-25.js, js/98-250.js, js/98-251.js, js/98-252.js, js/98-253.js, js/98-254.js, js/98-255.js, js/98-256.js, js/98-257.js, js/98-258.js, js/98-259.js, js/98-26.js, js/98-260.js, js/98-261.js, js/98-262.js, js/98-263.js, js/98-264.js, js/98-265.js, js/98-267.js, js/98-268.js, js/98-269.js, js/98-27.js, js/98-270.js, js/98-271.js, js/98-272.js, js/98-273.js, js/98-274.js, js/98-275.js, js/98-276.js, js/98-277.js, js/98-279.js, js/98-28.js, js/98-280.js, js/98-281.js, js/98-282.js, js/98-283.js, js/98-284.js, js/98-285.js, js/98-286.js, js/98-287.js, js/98-288.js, js/98-289.js, js/98-29.js, js/98-290.js, js/98-291.js, js/98-292.js, js/98-293.js, js/98-294.js, js/98-295.js, js/98-296.js, js/98-297.js, js/98-298.js, js/98-299.js, js/98-3.js, js/98-30.js, js/98-300.js, js/98-301.js, js/98-302.js, js/98-303.js, js/98-304.js, js/98-305.js, js/98-306.js, js/98-307.js, js/98-308.js, js/98-309.js, js/98-31.js, js/98-310.js, js/98-311.js, js/98-312.js, js/98-313.js, js/98-314.js, js/98-315.js, js/98-316.js, js/98-317.js, js/98-318.js, js/98-319.js, js/98-32.js, js/98-320.js, js/98-321.js, js/98-322.js, js/98-323.js, js/98-324.js, js/98-325.js, js/98-326.js, js/98-327.js, js/98-328.js, js/98-329.js, js/98-33.js, js/98-330.js, js/98-331.js, js/98-332.js, js/98-334.js, js/98-335.js, js/98-336.js, js/98-337.js, js/98-338.js, js/98-339.js, js/98-34.js, js/98-340.js, js/98-341.js, js/98-342.js, js/98-343.js, js/98-344.js, js/98-345.js, js/98-346.js, js/98-347.js, js/98-348.js, js/98-349.js, js/98-35.js, js/98-350.js, js/98-351.js, js/98-352.js, js/98-353.js, js/98-354.js, js/98-355.js, js/98-356.js, js/98-357.js, js/98-358.js, js/98-359.js, js/98-36.js, js/98-360.js, js/98-361.js, js/98-362.js, js/98-363.js, js/98-364.js, js/98-365.js, js/98-366.js, js/98-367.js, js/98-368.js, js/98-369.js, js/98-37.js, js/98-370.js, js/98-371.js, js/98-372.js, js/98-373.js, js/98-374.js, js/98-375.js, js/98-376.js, js/98-378.js, js/98-379.js, js/98-38.js, js/98-380.js, js/98-381.js, js/98-382.js, js/98-383.js, js/98-384.js, js/98-385.js, js/98-386.js, js/98-387.js, js/98-388.js, js/98-389.js, js/98-39.js, js/98-390.js, js/98-391.js, js/98-393.js, js/98-394.js, js/98-395.js, js/98-396.js, js/98-397.js, js/98-398.js, js/98-399.js, js/98-4.js, js/98-40.js, js/98-400.js, js/98-401.js, js/98-402.js, js/98-403.js, js/98-404.js, js/98-405.js, js/98-406.js, js/98-407.js, js/98-408.js, js/98-409.js, js/98-41.js, js/98-410.js, js/98-411.js, js/98-412.js, js/98-414.js, js/98-415.js, js/98-416.js, js/98-417.js, js/98-418.js, js/98-419.js, js/98-42.js, js/98-420.js, js/98-421.js, js/98-422.js, js/98-423.js, js/98-424.js, js/98-425.js, js/98-426.js, js/98-427.js, js/98-428.js, js/98-429.js, js/98-43.js, js/98-430.js, js/98-431.js, js/98-432.js, js/98-433.js, js/98-434.js, js/98-435.js, js/98-436.js, js/98-437.js, js/98-438.js, js/98-439.js, js/98-44.js, js/98-440.js, js/98-441.js, js/98-442.js, js/98-443.js, js/98-444.js, js/98-445.js, js/98-446.js, js/98-447.js, js/98-448.js, js/98-449.js, js/98-45.js, js/98-450.js, js/98-451.js, js/98-452.js, js/98-453.js, js/98-454.js, js/98-455.js, js/98-456.js, js/98-457.js, js/98-458.js, js/98-459.js, js/98-46.js, js/98-460.js, js/98-461.js, js/98-462.js, js/98-463.js, js/98-464.js, js/98-465.js, js/98-466.js, js/98-467.js, js/98-468.js, js/98-469.js, js/98-47.js, js/98-470.js, js/98-471.js, js/98-472.js, js/98-473.js, js/98-474.js, js/98-475.js, js/98-476.js, js/98-478.js, js/98-479.js, js/98-48.js, js/98-480.js, js/98-481.js, js/98-482.js, js/98-483.js, js/98-484.js, js/98-485.js, js/98-486.js, js/98-487.js, js/98-488.js, js/98-489.js, js/98-49.js, js/98-490.js, js/98-491.js, js/98-492.js, js/98-493.js, js/98-494.js, js/98-495.js, js/98-496.js, js/98-497.js, js/98-498.js, js/98-499.js, js/98-5.js, js/98-50.js, js/98-500.js, js/98-51.js, js/98-52.js, js/98-53.js, js/98-54.js, js/98-55.js, js/98-56.js, js/98-57.js, js/98-58.js, js/98-59.js, js/98-6.js, js/98-60.js, js/98-61.js, js/98-62.js, js/98-63.js, js/98-64.js, js/98-65.js, js/98-66.js, js/98-67.js, js/98-68.js, js/98-69.js, js/98-7.js, js/98-70.js, js/98-71.js, js/98-72.js, js/98-73.js, js/98-74.js, js/98-75.js, js/98-77.js, js/98-78.js, js/98-79.js, js/98-8.js, js/98-80.js, js/98-81.js, js/98-82.js, js/98-83.js, js/98-84.js, js/98-85.js, js/98-86.js, js/98-87.js, js/98-88.js, js/98-89.js, js/98-9.js, js/98-90.js, js/98-91.js, js/98-92.js, js/98-93.js, js/98-94.js, js/98-95.js, js/98-96.js, js/98-97.js, js/98-98.js, js/98-99.js, js/98-hub.js, js/98-inicio.js, js/99-app.js.
```

## 5. Conferir no final

- [ ] Abrir o index.html na prévia: aparece a tela sem erro (▤ console vazio)?
- [ ] Cada botão abre a sua parte?
- [ ] Fechar e abrir de novo: os dados continuam?
- [ ] Nada com "replit", "REPL_", "@workspace" no código (🏗️ Preparar confere).
- [ ] 📱 PWA → deixar instalável; 📦 APK ou 🖥️ .exe.
