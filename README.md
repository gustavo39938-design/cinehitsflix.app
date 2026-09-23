# FilmeFlix - Plataforma de Streaming

Site de streaming de filmes e séries grátis em HD.

## 📋 Estrutura

```
├── index.html          # Página principal
├── css/               # Estilos compilados
├── js/                # Scripts React compilados
├── images/            # Imagens e assets
├── vercel.json        # Configuração Vercel
└── README.md          # Este arquivo
```

## 🚀 Deploy via Vercel + GitHub

### Passo 1: Criar repositório no GitHub

1. Vá em https://github.com/new
2. Nome do repositório: `filmeflix-site`
3. Descrição: "FilmeFlix - Plataforma de streaming"
4. Escolha "Public" ou "Private"
5. Clique em "Create repository"

### Passo 2: Fazer commit e push

```bash
# Dentro da pasta do projeto
git init
git add .
git commit -m "Initial commit - FilmeFlix site"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/filmeflix-site.git
git push -u origin main
```

### Passo 3: Conectar com Vercel

1. Vá em https://vercel.com
2. Clique em "New Project"
3. Selecione "Import Git Repository"
4. Cole a URL do seu repositório GitHub
5. Clique em "Import"
6. Configure o projeto:
   - **Framework Preset**: Other
   - **Build Command**: (deixe em branco)
   - **Output Directory**: (deixe em branco)
7. Clique em "Deploy"

**Pronto!** 🎉 Seu site estará live em `https://filmeflix-site.vercel.app`

## 📝 Personalizações

Para editar conteúdo:
- **HTML**: Edite `index.html`
- **Estilos**: Modifique `css/index-*.css`
- **Scripts**: Customize `js/index-*.js`

Depois faça push pro GitHub e Vercel fará deploy automático.

## 💡 Próximos passos

- Conectar domínio customizado (Vercel oferece essa opção)
- Configurar analytics
- Otimizar SEO

---
Created with ❤️ por Gusta
