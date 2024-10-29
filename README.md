# APP Cadastro Senha

> Um aplicativo Android simples que funciona como uma calculadora que multiplica, divide, soma e subtrai.

## 📱 Descrição

O **APP Cadastro Senha** permite ao usuário calcular contas simples com multiplicação, divisão, adição e subtração.

## 🔧 Funcionalidades

- [x] 3 Telas
- [x] Garante segurança
- [x] Fácil de usar
- [x] Interface simples e intuitiva
- [ ] Tema claro e escuro (planejado para futuras versões)

## 🚀 Tecnologias Utilizadas

- [x] **Android Studio** (Bumblebee | 2021.1.1)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView**, **Button** e **EditText**

## 🛠️ Como Rodar o Projeto

Siga os passos abaixo para rodar o projeto localmente:


1. Clone este repositório:
    ```bash
    git clone https://github.com/phf2007/Calculadora/primeiroApp.zip
    ```

2. Abra o projeto no Android Studio.

3. Compile e execute o projeto em um emulador ou dispositivo físico.

## 📂 Estrutura do Projeto

pop
├── app
│   ├── main
│   │   ├── java/br.ulbra.pop
│   │   │   ├── MainActivity.java                  # Atividade principal da tela principal
│   │   │   ├── RegistrarActivity.java             # Atividade principal da tela de registro
│   │   │   ├── DBHelper.java                      # Atividade que salva as contas
│   │   │   ├── LoginActivity.java                 # Atividade principal da tela de login
│   │   ├── res
│   │   │   ├── layout
│   │   │   │   ├── activity_main.xml              # Layout da tela principal
│   │   │   │   ├── activity_login.xml             # Layout da tela de login
│   │   │   │   ├── activity_registrar.xml         # Layout da tela de registro
│   │   │   └── values
│   │   │       ├── strings.xml                    # Strings usadas no app
│   │   │       ├── colors.xml                     # Cores definidas no projeto
│   └── build.gradle                               # Configuração do Gradle
└── README.md                                      # Este arquivo



## 🎨 Design e Prototipagem 

A interface do app foi criada usando **ConstraintLayout** para manter a responsividade em diferentes tamanhos de tela. 

O design é minimalista e fácil de usar, com foco na simplicidade.

 ## 🖥️ Telas do Aplicativo

**Tela Principal** 

Na tela principal, teremos dois botões, um para ir para a tela de login e o outro para a tela de registro.

**Tela Secundária** 

Na tela secundária, quatro caixas de texto, duas de senha e duas normais, abaixo delas um botão de salvar que o leva para a tela principal.

**Tela Terciária** 

Na tela terciária, apenas duas caixas de texto, uma de senha e outra normal, abaixo delas um botão e caso insira a senha ou login errado um popup aparece indicando que o login ou senha estão errados.

## 👨‍💻 Desenvolvedores – 
Pedro Henrique Fontes - Desenvolvedor - [GitHub](https://github.com/phf2007)
