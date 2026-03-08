# TCC: Análise Comparativa de IAs no Desenvolvimento de Software - Projeto Economizapp

Este repositório contém os arquivos, aplicativos compilados e relatórios de análise de código referentes ao Trabalho de Conclusão de Curso. O objetivo deste projeto é comparar o desenvolvimento de um mesmo aplicativo móvel (**Economizapp**) utilizando três diferentes Modelos de Linguagem de Grande Escala (LLMs).

## Estrutura do Repositório

Abaixo está a descrição detalhada dos arquivos e diretórios disponíveis para análise:

### 📖 Metodologia e Interação
* **`diario_prompts.pdf`**: Documento que registra a evolução e o refinamento dos comandos (prompts) utilizados com cada IA ao longo do tempo. Este arquivo é fundamental para entender a engenharia de prompt aplicada e garantir a reprodutibilidade do estudo.

### 📱 Aplicativos Compilados (Builds Finais)
Os arquivos `.apk` abaixo representam o resultado final executável do projeto Economizapp, gerado a partir do código fornecido por cada respectiva inteligência artificial:
* **`chatgpt_economizapp.apk`**: Aplicativo final criado com o auxílio do ChatGPT.
* **`claude_economizapp.apk`**: Aplicativo final criado com o auxílio do Claude.
* **`gemini_economizapp.apk`**: Aplicativo final criado com o auxílio do Gemini.

### 📊 Relatórios de Qualidade de Código (SonarQube)
Os diretórios a seguir contêm os relatórios completos de análise estática de código extraídos via SonarQube em 06/01/2026. Eles detalham métricas cruciais como *bugs*, vulnerabilidades, *code smells* e débitos técnicos de cada versão:
* **`2026-01-06-Economizapp-ChatGPT-report/`**: Relatório de análise do código gerado pelo ChatGPT.
* **`2026-01-06-Economizapp-Claude-report/`**: Relatório de análise do código gerado pelo Claude.
* **`2026-01-06-Economizapp-Gemini-report/`**: Relatório de análise do código gerado pelo Gemini.

---
