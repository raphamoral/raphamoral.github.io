# raphamoral.github.io — Portfolio

Site estático de portfólio (PT/EN, dark/light). Um arquivo, zero build.

## Publicar no GitHub Pages

1. Criar o repositório **`raphamoral.github.io`** no GitHub (público).
2. Neste diretório:
   ```
   git add index.html README.md
   git commit -m "feat: portfolio site"
   git branch -M main
   git remote add origin git@github.com:raphamoral/raphamoral.github.io.git
   git push -u origin main
   ```
3. O site fica no ar em `https://raphamoral.github.io` em ~1 min (repos com esse
   nome publicam o Pages automaticamente, sem configuração).

> Alternativa com domínio próprio: apontar um CNAME (ex.: `raphael.myratchet.com`
> ou domínio pessoal) nas configurações do Pages.

## Editar

- Todo o conteúdo bilíngue vive em atributos `data-en` / `data-pt` no `index.html`.
- Idioma inicial: detectado do navegador; alternância manual salva em `localStorage`.
- Tema: dark por padrão, toggle salva a preferência.
