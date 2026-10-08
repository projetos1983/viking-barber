# Viking Barber — GitHub Pages

Este projeto está preparado para publicação gratuita no GitHub Pages.

## Publicação pelo celular

1. Crie um repositório **público** no GitHub, por exemplo `viking-barber`.
2. Envie todos os arquivos deste projeto para a raiz do repositório.
3. Vá em **Settings → Pages**.
4. Em **Build and deployment → Source**, selecione **GitHub Actions**.
5. Volte para **Actions** e aguarde o workflow `Deploy Viking Barber to GitHub Pages` terminar.
6. O endereço será parecido com:
   `https://SEU-USUARIO.github.io/viking-barber/`

## Atualizações

Sempre que você enviar alterações para a branch `main`, o GitHub Actions instalará as dependências, executará `npm run build` e publicará novamente a pasta `dist`.

## Importante

O projeto usa React + Vite. Por isso, **não publique a pasta `src` diretamente como se fosse um site HTML simples**. O workflow faz o build automaticamente.

As animações React/Motion/GSAP continuam no site depois do build porque são executadas no navegador.

## Firebase / Google Drive

O projeto contém integração com Firebase e Google Drive. O site visual pode ser publicado no GitHub Pages, mas recursos de autenticação/Drive podem exigir configuração adicional no Firebase/Google Cloud, especialmente para autorizar o domínio `SEU-USUARIO.github.io`.
