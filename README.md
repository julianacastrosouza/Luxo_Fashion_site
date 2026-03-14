# Luxo Fashion - Site Oficial

Landing page moderna e responsiva para a Luxo Fashion - Moda Feminina de Qualidade.

## 🚀 Como Hospedar no GitHub Pages

### Passo 1: Criar Repositório no GitHub
1. Acesse [GitHub](https://github.com) e faça login
2. Clique em **"New"** (Novo) para criar um novo repositório
3. Nome do repositório: `luxo-fashion` (ou o nome que preferir)
4. Marque como **Public** (Público)
5. **NÃO** marque "Add a README file"
6. Clique em **"Create repository"**

### Passo 2: Fazer Upload dos Arquivos
Você tem duas opções:

#### Opção A: Upload Direto pelo GitHub (Mais Fácil)
1. No seu novo repositório, clique em **"uploading an existing file"**
2. Arraste o arquivo `index.html` ou clique para selecioná-lo
3. Adicione uma mensagem como "Adicionar site Luxo Fashion"
4. Clique em **"Commit changes"**

#### Opção B: Usando Git (Linha de Comando)
```bash
# No terminal, navegue até a pasta luxo-fashion-site
cd luxo-fashion-site

# Inicialize o repositório Git
git init

# Adicione os arquivos
git add .

# Faça o primeiro commit
git commit -m "Adicionar site Luxo Fashion"

# Conecte ao repositório remoto (substitua SEU-USUARIO pelo seu nome de usuário)
git remote add origin https://github.com/SEU-USUARIO/luxo-fashion.git

# Renomeie a branch para main
git branch -M main

# Envie os arquivos
git push -u origin main
```

### Passo 3: Ativar GitHub Pages
1. No seu repositório, vá em **Settings** (Configurações)
2. No menu lateral, clique em **Pages**
3. Em "Source", selecione **"Deploy from a branch"**
4. Em "Branch", selecione **main** e pasta **/ (root)**
5. Clique em **Save** (Salvar)
6. Aguarde alguns minutos e seu site estará online!

### 🌐 URL do Site
Seu site ficará disponível em:
```
https://SEU-USUARIO.github.io/luxo-fashion/
```

## 📱 Sobre o Site

- **Design Responsivo**: Funciona perfeitamente em desktop, tablet e mobile
- **Cores**: Roxo claro e azul claro conforme solicitado
- **Seções**: 
  - Hero com chamada principal
  - Diferenciais (Qualidade, Entrega Veloz, Variedade)
  - Catálogo de Produtos (Vestidos, Camisas, Shorts, Sapatos)
  - Call-to-Action
  - Footer completo

## 🎨 Customização

Para personalizar o site, edite o arquivo `index.html`:

- **Cores**: Edite as variáveis CSS no `:root`
- **Textos**: Altere diretamente no HTML
- **Imagens**: Substitua os emojis por imagens reais
- **Contatos**: Atualize email, telefone e redes sociais no footer

## 📞 Contato

Luxo Fashion - Moda Feminina de Qualidade
- Email: contato@luxofashion.com
- WhatsApp: (11) 99999-9999
- Instagram: @luxofashion

---

💜 Desenvolvido com carinho para Luxo Fashion
