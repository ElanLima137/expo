# 📱 Access Jobs

Aplicativo de vagas de emprego desenvolvido em **React Native** para facilitar a conexão entre empresas e candidatos.  
O projeto foi pensado para oferecer uma experiência simples, direta e segura no gerenciamento de vagas e currículos.

---

## 🚀 Tecnologias Utilizadas
- [React Native](https://reactnative.dev/)  
- [Expo](https://expo.dev/)  
- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)  
- [HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML)  
- [Supabase](https://supabase.com/)  
- [Node.js](https://nodejs.org/)  
- [Python](https://www.python.org/)  
- [VS Code](https://code.visualstudio.com/)  

---

## ⚙️ Funcionalidades
- 🔐 Login, cadastro e recuperação de senha  
- 👤 Perfil de usuário  
- 📄 Cadastro e gerenciamento de vagas  
- 📝 Visualização de detalhes das vagas  
- 🗂️ Tela de administrador para controle do sistema  
- 📑 Geração e leitura de arquivos PDF  
- 👥 Listagem de pessoas cadastradas  

---

## 📂 Estrutura Principal
/src
/screens
├── SplashScreen.js
├── TelaLogin.js
├── TelaRegistro.js
├── TelaUsuario.js
├── TelaAdmin.js
├── TelaLancarVaga.js
├── TelaPdf.js
├── TelaEsqueceuSenha.js
├── PerfilUsuario.js
├── TelaDetalhesVaga.js
├── GerenciarVagas.js
├── TelaAlterarVaga.js
├── TelaPessoasCadastradas.js
VagaContext.js
App.js

yaml
Copiar código

---

## 🛠️ Como Rodar o Projeto

### Pré-requisitos
- Node.js instalado  
- Expo CLI instalada (`npm install -g expo-cli`)  
- Conta no [Supabase](https://supabase.com/) configurada  

### Passos
```bash
# Clone o repositório
git clone https://github.com/seuusuario/access-jobs.git

# Acesse a pasta
cd access-jobs

# Instale as dependências
npm install

# Inicie o app
npx expo start
Abra no seu emulador Android/iOS ou no app Expo Go no celular.


📌 Roadmap
 Implementar notificações push

 Melhorar UI/UX das telas

 Criar integração com APIs externas de vagas

 Adicionar suporte a multilínguas
