# KARU3D — Sua imaginação ganha forma

Site comercial da KARU3D para divulgação de miniaturas, action figures, topos de bolo, colecionáveis e réplicas personalizadas em resina com pintura manual.

## Tecnologias
- React + Vite
- CSS responsivo sem bibliotecas pesadas de UI
- Ícones Lucide React
- GitHub Actions + GitHub Pages

## Rodar localmente

```bash
npm install
npm run dev
npm run build
npm run preview
```

## Atendimento e orçamento
Edite `src/siteConfig.js` para colocar o WhatsApp comercial no formato internacional somente com dígitos (exemplo: 5598999999999), Instagram e email. Nenhum telefone particular foi presumido.

- Com WhatsApp configurado, o formulário abre `wa.me` com os dados da solicitação.
- Sem WhatsApp configurado, o formulário permite **copiar os dados** e deixa claro que o atendimento está em teste.
- O formulário não armazena nem transmite dados a um servidor próprio.
- Prazo, preço e disponibilidade são apresentados apenas após avaliação humana; a plataforma não inventa valores.

## Catálogo
As seis categorias usam ilustrações abstratas e **não se passam por fotos de produtos realizados**. Substituir por fotografias reais autorizadas quando disponíveis.

## Publicar

O workflow `.github/workflows/deploy.yml` realiza build e publica o diretório `dist/` a cada push em `main`.

Em Settings → Pages → Build and deployment, selecione **GitHub Actions** como origem. No GitHub Pages, URL de projeto costuma seguir `https://vixtem.github.io/NOME-DO-REPOSITORIO/`.

O Vite usa `base: './'` para suportar o caminho do projeto e renomeações de repositório.

## Migração do convite antigo
A versão original foi guardada na branch `backup-convite-vitoria-2026-10-22` antes da substituição da branch principal. A branch `main` foi recriada com os arquivos deste projeto; mídias do convite não permanecem no código novo.

Para mudar o nome do repositório, use Settings → General → Repository name, alterando para `karu3d-site`. Essa operação administrativa não está disponível pela integração atual.
