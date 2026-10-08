# Site Lidia Souza Odontologia

Site institucional de uma página só (HTML, CSS e JavaScript em um único arquivo), responsivo e com botão de WhatsApp.

## Estrutura

```
lidia-souza-odontologia/
├── index.html          <- o site inteiro (fotos já embutidas)
├── README.md
└── assets/
    ├── originais/      <- fotos originais, para guardar e usar em futuras edições
    └── video/          <- coloque aqui o vídeo da clínica (MP4)
```

## Como publicar no GitHub Pages (grátis)

1. Crie um repositório no GitHub (ex.: `lidia-souza-odontologia`).
2. Envie todo o conteúdo desta pasta para o repositório (arraste os arquivos em "Add file" > "Upload files").
3. Vá em **Settings** > **Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`. Salve.
5. Em alguns minutos o site fica em `https://SEU-USUARIO.github.io/lidia-souza-odontologia/`.

Alternativa: ligar o repositório à Vercel (vercel.com) e publicar com um clique.

## Como colocar o vídeo da clínica

1. Salve o vídeo como `assets/video/clinica.mp4` (ideal: até 10 MB e 30 a 40 segundos).
2. No `index.html`, procure `<video id="v"` e acrescente `src="assets/video/clinica.mp4"` dentro da tag.
3. Os botões "Reproduzir" e "Ativar áudio" passam a funcionar sozinhos.

## O que conferir antes de divulgar

- Autorização por escrito das pacientes para as fotos de antes e depois.
- Regras de publicidade do conselho (CFO) para imagens de antes e depois.
- Textos das perguntas frequentes e dos serviços, aprovados pela Dra. Lidia.
- Número do WhatsApp, endereço e horários (estão no `index.html`; use Ctrl+F para localizar).
- Direitos de uso da música, se o vídeo tiver trilha.

## Dados usados

- WhatsApp: (31) 98223-3370
- Endereço: Av. Álvares Cabral, 374, Lourdes, Belo Horizonte, MG
- Instagram: @dralidia.souza
- Horário: seg. a sex., 9h às 20h; sáb., 10h às 13h
