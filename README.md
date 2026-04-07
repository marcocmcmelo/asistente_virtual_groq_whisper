# Assistente Virtual com Voz (Python + IA)

Este projeto é um **Assistente Virtual com suporte a voz**, capaz de:

* Receber áudio como entrada
* Processar com Inteligência Artificial
* Gerar resposta em texto
* Converter a resposta em áudio (português brasileiro)

---

## Funcionalidades

✔ Transcrição de áudio (Speech-to-Text)

✔ Geração de respostas com IA

✔ Conversão de texto para voz (Text-to-Speech)

✔ Áudio final unificado e natural

✔ Divisão inteligente de texto para melhor leitura

✔ Tratamento de pausas para fala mais humana

---

## Tecnologias utilizadas

* Python 3
* Biblioteca `gTTS` (Google Text-to-Speech)
* `pydub` para manipulação de áudio
* `IPython.display` para reprodução
* (Opcional) Integração com APIs de IA (ex: Groq)

---

## Instalação

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

Instale as dependências:

```bash
pip install gtts pydub
```

> Para uso do `pydub`, pode ser necessário instalar o ffmpeg:

**Linux:**

```bash
sudo apt install ffmpeg
```

**Windows:**

* Baixe em: https://ffmpeg.org/download.html
* Adicione ao PATH

---

## Como usar

1. Defina o texto ou utilize saída de uma IA:

```python
chatgpt_response = "Olá, este é um exemplo de resposta do assistente virtual."
```

2. Execute o script

3. O sistema irá:

* Limpar o texto
* Dividir em partes
* Gerar áudio com gTTS
* Unificar em um único arquivo
* Reproduzir automaticamente

---

## Exemplo de saída

* Arquivo final: `resposta_final.mp3`
* Áudio em português brasileiro
* Com pausas naturais e melhor entonação

---

## Melhorias implementadas

* Remoção de caracteres especiais (Markdown)
* Ajuste de pontuação para fala natural
* Inserção de pausas (`...`)
*  Divisão inteligente por frases
* Junção dos áudios em um único arquivo

---

## Possíveis aplicações

* Atendimento automático via voz
* Bots para WhatsApp
* Assistente para sistemas empresariais
* Leitura de relatórios e boletos
* Acessibilidade (leitura de textos)

---

## Próximos passos

* Integração com WhatsApp (Twilio / API)
*  Integração com banco de dados (ex: Firebird)
* Memória de conversação
* Voz mais natural (TTS avançado)
* Interface web (Flask / Streamlit)

---

## Observações

* O gTTS utiliza vozes padrão do Google
* Para voz mais natural, pode-se integrar com serviços premium

---

## Autor

Desenvolvido por **Marcos Melo**
Focado em automação, IA e soluções empresariais

---

## Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar e modificar.

---

## Contribuição

Contribuições são bem-vindas!
Sinta-se à vontade para abrir issues ou pull requests.

---
