# Assistente Virtual com PNL em Python (Fase Inicial)

Este repositório documenta a fase inicial de um projeto de Assistente Virtual, com foco na implementação da funcionalidade central de **Conversão de Texto em Fala (Text-to-Speech - TTS)**.

O projeto está configurado para ser executado no **Google Colab**, o que garante facilidade na instalação de dependências e execução em diferentes ambientes.

---

## Funcionalidade Implementada: Conversão de Texto em Fala (TTS)

Esta primeira fase é dedicada à **Saída de Voz** do assistente. A funcionalidade TTS permite que o assistente converta qualquer texto fornecido em fala audível em tempo real.

### Principais Recursos

* **Reprodução no Colab:** O código está especificamente adaptado para reproduzir o áudio diretamente no ambiente do notebook Google Colab.
* **Limpeza Automática:** O sistema garante que os arquivos de áudio temporários sejam excluídos após a reprodução, mantendo um ambiente de execução limpo.

---

## Tecnologias e Bibliotecas Utilizadas

| Tecnologia | Função Principal | Detalhes do Projeto |
| :--- | :--- | :--- |
| **Google Colaboratory** | Ambiente de Desenvolvimento | Usado como a principal plataforma para executar o código Python (Jupyter Notebook hospedado na nuvem). |
| **Python** | Linguagem de Programação | A linguagem base para a funcionalidade TTS. |
| **`gTTS` (Google TTS)** | Conversão de Texto em Fala | Biblioteca primária usada para gerar o áudio a partir do texto (configurada para Português: `lang='pt'`). |
| **`IPython.display.Audio`** | Reprodução de Áudio | Módulo essencial usado para renderizar e reproduzir o áudio MP3 resultante no console do Colab. |
| **`os` e `time`** | Utilitários | Usados para gerenciamento de arquivos e controle da duração/tempo de espera da reprodução. |
