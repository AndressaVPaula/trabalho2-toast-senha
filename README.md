# Trabalho 2 - Toast e Campo Senha

Aplicativo Android (Kotlin + XML) com um campo de e-mail, um campo de senha e um botão **Entrar**.
Ao clicar no botão, o e-mail e a senha digitados são exibidos em um `Toast`:

```
Email: exemplo@teste.com
Senha: 123456
```

## O que foi alterado
- `activity_main.xml`: novo `EditText` (`editTextSenha`) com `inputType="textPassword"`.
- `MainActivity.kt`: ao clicar no botão, lê os dois campos e mostra em um `Toast`.

## Como executar
1. Instale o [Android Studio](https://developer.android.com/studio) (ou JDK 17+ e Android SDK para usar VS Code).
2. Clone o repositório: `git clone <link-do-repositorio>`
3. Abra a pasta do projeto e aguarde o Gradle sincronizar.
4. Inicie um emulador (AVD) ou conecte um celular com depuração USB.
5. Execute o app (botão **Run** no Android Studio, ou `./gradlew installDebug` no terminal).
