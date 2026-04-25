# Nuvitai - Páginas Legais (Política de Privacidade e Termos de Uso)

Este repositório contém as páginas estáticas necessárias para a publicação do aplicativo Nuvitai na Google Play Store. O Google exige que a Política de Privacidade (e preferencialmente os Termos de Serviço) estejam hospedados publicamente na web.

## Como publicar usando o GitHub Pages

Siga o passo a passo abaixo para colocar este site no ar de forma gratuita:

### Passo 1: Preparar o Repositório no GitHub
1. Acesse sua conta no [GitHub](https://github.com/).
2. Clique no sinal de **+** no canto superior direito e selecione **New repository**.
3. Dê um nome ao repositório (ex: `nuvitai-legal` ou `nuvitai-pages`).
4. Certifique-se de que o repositório seja **Public** (Público).
5. **Não** marque a opção de criar com um arquivo README (pois já estamos criando este agora).
6. Clique em **Create repository**.

### Passo 2: Enviar os arquivos da sua máquina para o GitHub
Abra um terminal (Pode ser o Git Bash, Prompt de Comando ou PowerShell) na pasta onde estão estes arquivos (`c:\dev\nuvitai-pages`) e rode os seguintes comandos:

```bash
# 1. Inicia o repositório Git localmente
git init

# 2. Adiciona todos os arquivos
git add .

# 3. Cria o primeiro commit
git commit -m "Initial commit - Páginas Legais"

# 4. Define o nome da branch principal como 'main'
git branch -M main

# 5. Vincula a sua pasta local ao repositório criado no GitHub
# ATENÇÃO: Substitua a URL abaixo pela URL que o GitHub forneceu no Passo 1
git remote add origin https://github.com/SEU_USUARIO/NOME_DO_REPO.git

# 6. Envia os arquivos para o GitHub
git push -u origin main
```

### Passo 3: Ativar o GitHub Pages
1. No seu repositório lá no GitHub, clique na aba **Settings** (Configurações) no topo da página.
2. No menu lateral esquerdo, desça um pouco e clique em **Pages**.
3. Na seção **Build and deployment**:
   - Em "Source", deixe "Deploy from a branch".
   - No dropdown da "Branch", selecione **main** e mantenha a pasta como `/(root)`.
   - Clique em **Save**.
4. Aguarde de 1 a 2 minutos. Atualize a página e o GitHub mostrará uma mensagem verde com a URL do seu novo site (geralmente será `https://seuusario.github.io/nome-do-repo/`).

### Passo 4: Atualizar o Google Play Console
Com o site no ar, pegue a sua URL e adicione na listagem da loja e na seção "Conteúdo do app" -> "Política de Privacidade" no Google Play Console.
- URL Política de Privacidade: `https://seuusario.github.io/nome-do-repo/politica-de-privacidade.html`
- URL Termos de Uso (se houver campo): `https://seuusario.github.io/nome-do-repo/termos-de-uso.html`
