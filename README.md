# Portfólio — Pedro Paiva

Site estático (HTML, CSS e JS puros). Não precisa de build nem de dependências.

## Estrutura

```
index.html      a página inteira
assets/         prints dos projetos (WebP)
```

## Publicar no GitHub Pages (pelo navegador, sem Git)

1. Em github.com, clique em **New repository**.
   - Nome `SEU-USUARIO.github.io` → o site fica em `https://SEU-USUARIO.github.io/`.
   - Qualquer outro nome → fica em `https://SEU-USUARIO.github.io/NOME/`.
   - Deixe o repositório **Public** (no plano grátis, o Pages só funciona em repositórios públicos).
2. Na página do repositório, clique em **uploading an existing file**.
3. Arraste o **conteúdo** desta pasta (`index.html` e a pasta `assets`), não a pasta em si.
4. Clique em **Commit changes**.
5. Vá em **Settings → Pages**. Em **Source**, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`. Salve.
6. Espere cerca de um a dois minutos. O endereço do site aparece no topo da mesma tela.

## Trocar uma imagem

Substitua o arquivo em `assets/` mantendo o nome, ou mude o caminho no objeto `SHOTS`, perto do fim do `index.html`.

## Pendências de conteúdo

- Os anos dos artigos em Writings estão como 2022; confira se está certo.
- Hoje em Dia e JM Online abrem direto o site; se quiser modal com prints, adicione as imagens em `assets/`.
