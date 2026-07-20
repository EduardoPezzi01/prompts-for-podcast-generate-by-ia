<p align="center">
<img 
    src="./assets/cover.png"
    width="300"
/>
</p>

<p align="center">
<a href="https://dio.me/">
    <img 
        src="https://img.shields.io/badge/DIO-Code_The_Future-28DA77?logo=youtube" 
        alt="DIO - Code The Future">
</a>
<a href="https://dio.me/">
<img 
    src="https://img.shields.io/badge/🔴_LIVE_CODE-FF5E72" 
    alt="🔴 LIVE CODE">
</a>
</p>

<p align="center">
    preview do podcast
</p>

<div align="center">
    <audio src="output/podcast_editado.MP3" controls title="Podcast editado"></audio>
</div>

# Projeto Podcast Gerado por I.A.s


 > ℹ️ **NOTE:** Este é o repositório desenvolvido durante uma live no Youtube em parceria com a [DIO](https://dio.me)

Projeto com o objetivo de gerar um podcast utilizando ferramentas de IA através de prompts mais trabalhado.

Utilizer uma esteira de prompts para gerar cada etapa do processo criativo.

## 💻 Tecnologias utilizadas no projeto

- [ChatGPT](https://chat.openai.com/) 
- [MidJourney](https://www.midjourney.com/app/)
- [ElevenLabs](https://beta.elevenlabs.io/)
- [Capcut](https://www.capcut.com/pt-br/)

## ✨ Como foi feito ?

- Roteiro gerado via chatgpt
- Audio gerado pela elevenLabs
- Midjourney Para gerar capas
- Capcut para tratar aúdio e adicionar sons de fundo

## 📚 Materiais

- [Link da live no Youtube](https://www.youtube.com)
- [Notion Template](https://helpful-jump-17b.notion.site/PAS-Podcast-AI-Studio-210489e15d7a4a73b743bb159e45d06f?pvs=4)
- [Editor de aúdio](https://www.capcut.com/editor?from_page=landing_page&__action_from=picture_V%C3%ADdeos%20profissionais%20em%20minutos,%20n%C3%A3o%20em%20horas.)


## 🛠️ Instruções de execução

Utilize os prompts dentro do link do `Notion` fornecido na parte de `Materiais` para criar um podcast de maneira automatizada, para isso siga o passo a passo abaixo.

- 🤖 1. Use os prompts de roteiro no `chagpt`
- 🤖 2. Use os prompts de roteiro gerados pelo chatgpt no  `ElevenLabs`
- 🤖 3. Use os prompts de artes no `midjourney`

🎧 Roteiro e Conteúdo
Você pode conferir o roteiro completo detalhado na pasta ou arquivo roteiro_podcast.md.

Resumo do Episódio:
Título: Episódio 1: IA Generativa: O Novo Copiloto da Criatividade e do Trabalho

Duração Estimada: 5 a 8 minutos

Formatos / Participantes:

Host 1 (Alex): Perfil mais técnico, focado em insights e dados.

Host 2 (Elena): Perfil didático, focado em exemplos práticos e mercado.

🚀 Como Replicar este Projeto
Criação do Roteiro:

Utilize os prompts descritos em prompts_utilizados.md para gerar ou adaptar o texto no ChatGPT/Claude.

Geração das Vozes:

Copie as falas marcadas para o ElevenLabs, selecionando vozes com boa cadência em português (ex: Adam, Rachel ou Fin).

Geração da Capa:

Insira o prompt de imagem presente na documentação no DALL-E 3 ou Midjourney.

Montagem do Áudio:

Exporte as trilhas em MP3/WAV, adicione uma trilha de fundo suave (lo-fi ou tech ambient) no Audacity/CapCut e ajuste o volume.

👨‍💻 Autor / Desenvolvedor
Desenvolvido como projeto prático no Bootcamp Universia - Fundamentos de IA Generativa.

GitHub: EduardoPezzi01

LinkedIn: https://www.linkedin.com/in/eduardo-pezzi-gil-de-souza/

Gerado com suporte de IAs Generativas - 2026
"""

with open("README.md", "w", encoding="utf-8") as f:
f.write(readme_content)

Create roteiro_podcast.md
roteiro_content = """# 📜 Roteiro do Podcast: PodIA

Episódio: 01

Título: IA Generativa: O Novo Copiloto da Criatividade e do Trabalho

Duração: ~5-7 minutos

Participantes:

ALEX: Especialista em Tecnologia e IA (Voz firme, empolgada, técnica)

ELENA: Entusiasta de Inovação e Carreira (Voz acolhedora, dinâmica, didática)

🎵 Vinheta de Abertura (00:00 - 00:15)
(Trilha sonora estilo Tech Synth / Lo-Fi em ritmo ascendente. Diminui gradativamente para fundo)

[ALEX]

(Voz motivada e clara)

Olá, pessoal! Sejam muito bem-vindos ao PodIA, o seu podcast quinzenal sobre inovação, tecnologia e Inteligência Artificial Generativa! Eu sou o Alex.

[ELENA]

(Voz calorosa e animada)

E eu sou a Elena! É um prazer gigante estar aqui com vocês. Hoje, no nosso episódio de estreia, vamos conversar sobre algo que está redefinindo o mercado de trabalho e a criação de conteúdo: como a IA Generativa deixou de ser uma promessa futurista para se tornar o nosso copiloto do dia a dia.

💡 Bloco 1: O Que é a IA Generativa no Mundo Real? (00:15 - 02:00)
[ALEX]

Exatamente, Elena. Quando falamos de IA Generativa, muita gente ainda pensa em algoritmos complexos de laboratório. Mas a verdade é que ferramentas como o ChatGPT, Claude, Midjourney e ElevenLabs trouxeram o poder da geração de linguagem e mídia diretamente para as nossas mãos.

[ELENA]

E a chave aqui, Alex, é a palavra 'Copiloto'. A IA não veio para substituir a mente humana, mas para potencializar nossa produtividade. Pense nisso: tarefas analíticas, rascunhos de e-mails, estruturação de códigos e até brainstorms criativos agora acontecem em minutos, e não em dias.

[ALEX]

Perfeito! Um estudo recente da McKinsey mostra que a automação impulsionada por LLMs pode aumentar o valor da economia global em trilhões de dólares. Mas a pergunta que fica é: como o profissional de hoje deve se adaptar a essa transformação?

🛠️ Bloco 2: Engenharia de Prompt e Novas Habilidades (02:00 - 04:00)
[ELENA]

A resposta tá numa habilidade fundamental: Engenharia de Prompt e Pensamento Crítico! Não basta apenas perguntar para a IA; é preciso saber contextualizar, definir papéis, restrições e objetivos claros.

[ALEX]

Com certeza! Um bom prompt funciona como um briefing detalhado para um assistente brilhante. Se você pede: "Escreva um e-mail sobre vendas", o resultado é genérico. Mas se você instrui: "Atue como um especialista em Copywriting B2B, crie uma abordagem persuasiva de 3 parágrafos para executivos de TI com foco em eficiência de custos", o resultado é transformador.

[ELENA]

(Risos)

É a famosa regra: entrada de qualidade gera saída de qualidade! E isso vale para imagens, códigos e até na produção deste podcast, que teve seu roteiro, imagem de capa e síntese de voz desenvolvidos com auxílio de IAs.

🚀 Bloco 3: Casos Práticos e Dicas Práticas (04:00 - 05:30)
[ALEX]

E para quem quer começar hoje mesmo a usar IA no fluxo de trabalho, qual é a dica de ouro, Elena?

[ELENA]

Primeiro: perca o medo e comece a testar pequenos projetos. Monte um resumo de um relatório longo, crie uma estrutura de apresentação, ou use para aprender um assunto novo com analogias simples. Segundo: valide sempre as fontes. A IA traz velocidade, mas a curadoria final é sempre sua.

[ALEX]

Excelente! A responsabilidade e a ética no uso das ferramentas são pilares inegociáveis.

🏁 Encerramento e Chamada para Ação (05:30 - 06:15)
(Entra trilha sonora suave de fundo crescendo aos poucos)

[ELENA]

E assim chegamos ao fim do nosso primeiro episódio do PodIA! Esperamos que esse papo tenha inspirado você a explorar o universo generativo.

[ALEX]

Se você curtiu este episódio, não se esqueça de conferir a documentação completa e os prompts utilizados no nosso repositório no GitHub. Deixe sua estrela no projeto e compartilhe com os amigos!

[ELENA]

Um grande abraço e até o próximo episódio!

[ALEX]

Até mais, pessoal!

(Trilha sonora sobe por 5 segundos e finaliza com efeito fade out)
"""

with open("roteiro_podcast.md", "w", encoding="utf-8") as f:
f.write(roteiro_content)

Create prompts_utilizados.md
prompts_content = """# 🎯 Engenharia de Prompts Utilizada no Projeto

Este documento contém todos os prompts desenvolvidos para a geração dos materiais do podcast PodIA.

📝 1. Prompts para Roteiro e Texto (LLM - ChatGPT / Claude)
Prompt 1: Definição de Persona e Formato
Plaintext
Atue como um Roteirista Profissional de Podcasts focado em Tecnologia e Inteligência Artificial.
Preciso que você crie o roteiro de um podcast dinâmico com 2 apresentadores (Alex: técnico/analítico e Elena: didática/entusiasta).

Tema: Como a IA Generativa está transformando carreiras e a criação de conteúdo.
Duração: ~5 minutos.
Idioma: Português do Brasil.

O roteiro deve conter:
- Vinheta de abertura e encerramento com indicações de efeitos sonoros (SFX) e música de fundo (BGM).
- Introdução cativante com saudação dos hosts.
- 3 blocos de conteúdo (Conceito, Engenharia de Prompt/Habilidades, Dicas Práticas).
- Chamada para ação (CTA) para o repositório GitHub.
- Marcações claras de fala no formato [HOST]: Texto.
🎙️ 2. Prompts e Configurações para Síntese de Voz (TTS - ElevenLabs)
Configuração do Narrador 1 (Alex)
Voice Model: Eleven Multilingual v2

Voice Name: Adam ou Fin (Voz masculina, madura, tom profissional)

Settings:

Stability: 55%

Clarity + Similarity Boost: 75%

Style Exaggeration: 10%

Configuração da Narradora 2 (Elena)
Voice Model: Eleven Multilingual v2

Voice Name: Rachel ou Bella (Voz feminina, fluida, engajada)

Settings:

Stability: 50%

Clarity + Similarity Boost: 80%

Style Exaggeration: 15%

🎨 3. Prompts para Arte de Capa (Midjourney / DALL-E 3)
Prompt Principal para Arte Visual
Plaintext
A modern and stylish podcast cover art for a tech podcast named 'PodIA'.
Features a sleek futuristic microphone floating in a neon-lit studio setting with subtle holographic AI wave nodes, cyan and purple accent lighting, clean dark background, 8k resolution, minimalist digital art style, professional typography space. --ar 1:1 --v 6.0
Prompt Alternativo (DALL-E 3 em Português)
Plaintext
Uma capa de podcast moderna e minimalista para um show sobre Inteligência Artificial chamado 'PodIA'. Mostrar um microfone estilizado envolto por ondas sonoras luminosas em tons de azul ciano e roxo profundo, fundo escuro elegante, estilo arte digital HD, proporção quadrada 1:1.
"""

with open("prompts_utilizados.md", "w", encoding="utf-8") as f:
f.write(prompts_content)

print("Arquivos criados com sucesso: README.md, roteiro_podcast.md, prompts_utilizados.md")


```text?code_stdout&code_event_index=1
Arquivos criados com sucesso: README.md, roteiro_podcast.md, prompts_utilizados.md

Os materiais para o seu repositório no GitHub do projeto "Criando um Podcast com IAs" (Desafio DIO & Universia) foram gerados com sucesso!

Você pode baixar os arquivos criados ou copiar a estrutura abaixo diretamente para o seu repositório:

README.md — Documentação principal do repositório no padrão DIO. 

README
 MD 
Aberto

roteiro_podcast.md — Roteiro completo do episódio piloto com falas, tempo e indicações de áudio/SFX. 

roteiro_podcast
 MD 
Aberto

prompts_utilizados.md — Engenharia de prompts para geração do roteiro (ChatGPT/Claude), voz (ElevenLabs) e arte de capa (Midjourney/DALL-E 3). 

prompts_utilizados
 MD 
Aberto

📂 Estrutura do Repositório Sugerida
Para organizar seu GitHub exatamente como exigido no projeto da DIO:

Plaintext
meu-podcast-ia/
├── README.md                 # Apresentação do projeto e tecnologias
├── roteiro_podcast.md        # Script detalhado do episódio
└── prompts_utilizados.md     # Prompts de texto, áudio e imagem

## 👨‍💻 Expert

<p>
    <img 
      align=left 
      margin=10 
      width=80 
      src="https://avatars.githubusercontent.com/u/37452836?v=4"
    />
    <p>&nbsp&nbsp&nbspFelipe Aguiar<br>
    &nbsp&nbsp&nbsp
    <a 
        href="https://github.com/felipeAguiarCode">
        GitHub
    </a>
    &nbsp;|&nbsp;
    <a 
        href="www.linkedin.com/in/felipe-exe">
        LinkedIn
    </a>
    &nbsp;|&nbsp;
    <a 
        href="https://www.instagram.com/felipeaguiar.exe/">
        Instagram
    </a>
    &nbsp;|&nbsp;</p>
</p>
<br/><br/>
<p>

---

⌨️ com 💜 por [Felipe Aguiar](https://github.com/felipeAguiarCode)
