# 🚀 Como Criar o Repositório GitHub para Quest4Couple

## 📋 Passos para Criar o Repositório no GitHub:

### 1. **Acessar o GitHub**
- Acesse [github.com](https://github.com)
- Faça login na sua conta (ou crie uma se não tiver)

### 2. **Criar Novo Repositório**
- Clique no botão **"New"** ou **"+"** no canto superior direito
- Selecione **"New repository"**

### 3. **Configurar o Repositório**
```
Repository name: quest4couple
Description: 💕 Sistema de Compatibilidade Íntima para Casais - Questionários temáticos com encriptação e relatórios de compatibilidade
```

**Configurações importantes:**
- ✅ **Public** (para que outros possam ver) OU **Private** (apenas para você)
- ❌ **NÃO** marcar "Add a README file" (já temos um)
- ❌ **NÃO** marcar "Add .gitignore" (já temos um)
- ❌ **NÃO** escolher licença por agora

### 4. **Conectar Repositório Local ao GitHub**

Após criar o repositório no GitHub, copie a URL que aparece e execute:

```bash
# Adicionar o repositório remoto
git remote add origin https://github.com/SEU_USUARIO/quest4couple.git

# Renomear branch principal para main (padrão GitHub)
git branch -M main

# Fazer push do código para GitHub
git push -u origin main
```

### 5. **Verificar Upload**
- Volte ao GitHub e atualize a página
- Você deve ver todos os arquivos do projeto
- O README.md será exibido automaticamente

## 🎯 Comandos Resumidos:

```bash
# Se ainda não fez:
cd "g:\O meu disco\Formação JAVA - Projetos\Projeto Quest4Couple"

# Conectar ao GitHub (substitua SEU_USUARIO pelo seu username)
git remote add origin https://github.com/SEU_USUARIO/quest4couple.git
git branch -M main
git push -u origin main
```

## 📱 Resultado Final:

Após o upload, seu repositório terá:
- ✅ **README.md** com documentação completa
- ✅ **Quest4couple1.2.html** - Sistema principal
- ✅ **QuizzIndividualv1.0.html** - Sistema individual  
- ✅ **Logo e assets** organizados
- ✅ **Documentação** das perguntas
- ✅ **.gitignore** configurado
- ✅ **Histórico Git** preservado

## 🌐 URL do Projeto:

Após criar, o projeto estará disponível em:
`https://github.com/SEU_USUARIO/quest4couple`

E pode ser acessado via GitHub Pages em:
`https://SEU_USUARIO.github.io/quest4couple/Quest4couple1.2.html`

## 🎊 Pronto!

Seu projeto Quest4Couple agora está no GitHub e pode ser:
- ✅ **Compartilhado** com outros
- ✅ **Versionado** com Git  
- ✅ **Colaborativo** se quiser
- ✅ **Hospedado** gratuitamente via GitHub Pages
- ✅ **Documentado** profissionalmente

---

💡 **Dica**: Para ativar GitHub Pages, vá em Settings > Pages e selecione "Deploy from a branch" usando a branch "main".
