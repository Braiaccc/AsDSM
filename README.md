# Pokédex Flutter App

O **Pokédex Flutter App** é um aplicativo desenvolvido em Flutter que consome a API de Pokémon para exibir uma lista de Pokémons, permitindo a filtragem por nome e a visualização de detalhes individuais. O projeto também integra autenticação com Firebase.

## 📝 Funcionalidades

- Listagem de Pokémons com imagens.
- Pesquisa por nome de Pokémon.
- Tela de detalhes de cada Pokémon com imagem e informações básicas.
- Tela de login integrada ao Firebase Authentication.

---

## 🛠️ Tecnologias Utilizadas

- **Dart**: Linguagem principal do Flutter.
- **Flutter**: Framework para construção da interface.
- **Firebase Authentication**: Para login e autenticação.
- **PokéAPI**: Para consumo dos dados dos Pokémons.
- **HTTP**: Para realizar requisições à API.

---

## 🚀 Como Executar o Projeto

Siga as etapas abaixo para clonar e executar o projeto localmente.

### 1. Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas:

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (versão mínima recomendada: 3.0.0).
- [Dart](https://dart.dev/get-dart) (já incluído no Flutter SDK).
- Um emulador ou dispositivo físico configurado para desenvolvimento.
- [Firebase CLI](https://firebase.google.com/docs/cli) (se necessário para configuração adicional).

### 2. Clonar o Repositório

Abra o terminal e execute o comando:

```bash
git clone (https://github.com/Braiaccc/AsDSM) 
```

### 3. Instalar Dependências
Execute o comando abaixo para instalar as dependências do projeto:

``` flutter pub get ```

### 4. Configuração do Firebase
Certifique-se de configurar o Firebase para o projeto:

Adicione o arquivo google-services.json (Android) nas pastas correspondentes.
Configure os métodos de autenticação no console do Firebase.

### 5. Executar o Projeto
Conecte um dispositivo físico ou inicie um emulador, e execute o seguinte comando:

```bash
flutter run
```

O aplicativo será iniciado no dispositivo/emulador conectado.

---

## 📂Estrutura do Projeto
