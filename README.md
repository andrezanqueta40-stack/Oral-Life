# Oral Life Itapira – Site

Site oficial da **Oral Life Odontologia Itapira** (Itapira – SP).
HTML, CSS e JavaScript puros: sem instalação, sem build. Funciona em celular e computador.

## Estrutura

```
index.html                  → o site inteiro
assets/img/                 → fotos
assets/logo/                → logos em PNG (normal, branca e ícone)
favicon.png / apple-touch-icon.png
```

## Publicar no GitHub Pages (grátis)

1. Crie um repositório novo no GitHub (ex.: `oral-life-itapira`).
2. Clique em **Add file → Upload files** e arraste **todo o conteúdo desta pasta** (o `index.html` precisa ficar na raiz).
3. Clique em **Commit changes**.
4. Vá em **Settings → Pages**. Em *Source*, escolha **Deploy from a branch**, branch **main**, pasta **/ (root)** e salve.
5. Em 1 ou 2 minutos o site fica no ar em `https://SEU-USUARIO.github.io/oral-life-itapira/`.

Domínio próprio (ex.: `oralifeitapira.com.br`): em **Settings → Pages → Custom domain**, digite o domínio e configure o DNS conforme a orientação do GitHub.

## Como editar

Tudo que muda com frequência fica no bloco `CONFIGURAÇÃO DA CLÍNICA`, no final do `index.html`:

- `whatsapp` – número com DDI e DDD, só números (ex.: `5519982014048`).
- `linkAvaliar` – link de avaliação do Google (Perfil da Empresa → *Pedir avaliações*).
- `instagram` – link do perfil; vazio esconde o item.
- `horarios` – troque `null` pelos horários reais (há um modelo pronto no comentário). Com isso o site passa a mostrar **Aberto agora / Fechado** automaticamente, no horário de Brasília.

Os tratamentos e as mensagens de WhatsApp de cada um ficam na lista `TRAT`, logo abaixo.

Para trocar uma foto, substitua o arquivo em `assets/img/` mantendo o mesmo nome.

## Responsável técnica

Dra. Elisa Miguel – CRO/SP 129.898
