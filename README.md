
# AuthLoginApp

AuthLoginApp é um aplicativo de autenticação de usuários desenvolvido em Kotlin utilizando Firebase Authentication. Ele permite que usuários realizem o registro, login e recuperação de senha. O projeto é uma demonstração de boas práticas no desenvolvimento de aplicativos Android.

## Funcionalidades

- Registro de usuários com e-mail e senha.
- Login de usuários autenticados.
- Recuperação de senha por e-mail.
- Tela inicial de boas-vindas após o login.
- Validações de campos (e-mail e senha).
- Design moderno utilizando Material Components.

---

## Pré-requisitos

Antes de iniciar, certifique-se de ter as seguintes ferramentas instaladas:

- [Android Studio](https://developer.android.com/studio) (versão mais recente).
- [Firebase Console](https://console.firebase.google.com/) para configuração do Firebase Authentication.
- Conta no Firebase para obter o arquivo `google-services.json`.

---

## Configuração do Projeto

### 1. Clonar o Repositório

```bash
git clone https://github.com/phillipe17macedo/AuthLoginApp.git
cd AuthLoginApp
```

### 2. Configurar o Firebase

- No [Firebase Console](https://console.firebase.google.com/), crie um novo projeto.
- Habilite **Firebase Authentication** no menu de autenticação.
- Adicione o SHA-1 do seu aplicativo ao projeto Firebase.
- Baixe o arquivo `google-services.json` e coloque-o na pasta `app` do projeto.

### 3. Abrir no Android Studio

- Abra o Android Studio e importe o projeto.
- Sincronize o Gradle para baixar todas as dependências.

---

## Estrutura do Projeto

- `MainActivity.kt`: Gerencia o login e registro do usuário.
- `WelcomeActivity.kt`: Tela de boas-vindas exibida após o login.
- `activity_main.xml`: Layout principal para login e registro.
- `styles.xml`: Configurações de estilos para botões, textos e layout.
- `colors.xml`: Paleta de cores usada no design do aplicativo.

---

## Tecnologias Utilizadas

- **Kotlin**: Linguagem principal do projeto.
- **Firebase Authentication**: Gerenciamento de autenticação de usuários.
- **Material Components**: Para design moderno e responsivo.
- **ConstraintLayout**: Gerenciamento de layouts flexíveis e adaptáveis.

---

## Como Executar

1. Certifique-se de que o `compileSdk` e o `targetSdk` estão configurados corretamente no arquivo `build.gradle`:
   ```gradle
   android {
       compileSdk = 34
       targetSdk = 34
   }
   ```

2. Conecte um dispositivo ou inicie um emulador no Android Studio.

3. Clique em **Run** ou pressione `Shift + F10`.

---

## Melhorias Futuras

- Suporte a autenticação com Google e Facebook.
- Adicionar tela para gerenciamento de perfis de usuários.
- Implementação de testes unitários para validação de funcionalidades.

---

## Contribuições

Contribuições são sempre bem-vindas! Siga os passos abaixo para contribuir:

1. Faça um fork do projeto.
2. Crie um branch para sua funcionalidade:
   ```bash
   git checkout -b minha-nova-funcionalidade
   ```
3. Faça o commit das suas alterações:
   ```bash
   git commit -m 'Adicionando nova funcionalidade'
   ```
4. Envie para o branch principal:
   ```bash
   git push origin minha-nova-funcionalidade
   ```
5. Abra um Pull Request.

---

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## Capturas de Tela

<p align="center">
  <img src="https://via.placeholder.com/200x400.png?text=Sign+In+Screen" alt="Tela de Login" width="200">
  <img src="https://via.placeholder.com/200x400.png?text=Welcome+Screen" alt="Tela de Boas-vindas" width="200">
</p>
