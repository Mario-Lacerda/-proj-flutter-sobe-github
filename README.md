# DESAFIO Subindo o Seu Projeto Flutter no GitHub



Criar um projeto Flutter passo a passo. Você também aprenderá sobre os arquivos de configuração do Flutter, a estrutura de projetos do Flutter e como importar e exportar projetos Flutter., os seus objetivos neste Desafio são: Instalar o Flutter, configurar o Ambiente, criar um projeto e, por fim, subir o seu projeto do GitHub.  Criar um repositório para seu projeto e a fazer commits e pushs para a sua conta no GitHub.



## Como Subir Seu Projeto Flutter no GitHub

Neste tutorial rápido e prático, você aprenderá o passo a passo para colocar seu projeto Flutter no GitHub. Você também aprenderá a

### **1. Criar um repositório**

Para começar, você precisa criar um repositório no GitHub. Para isso, acesse o site do GitHub e faça login na sua conta. Em seguida, clique no botão **New Repository**.

Na página **New Repository**, você precisará inserir um nome para o seu repositório e uma descrição opcional. Você também pode escolher se o seu repositório será público ou privado. Por fim, clique no botão **Create Repository**.



### **2. Copiar o SSH Key**

Agora que você criou um repositório, você precisa copiar o SSH Key dele. Para isso, clique no ícone de engrenagem na parte superior da página do seu repositório e selecione a opção **Settings**.

Na página **Settings**, role até a seção **SSH Keys** e clique no botão **Add SSH Key**.

Na página **Add SSH Key**, você precisará inserir um nome para a sua chave e colar o SSH Key que você copiou do seu terminal. Por fim, clique no botão **Add Key**.



### **3. Clonar o repositório**

Agora que você copiou o SSH Key do seu repositório, você pode cloná-lo para o seu computador. Para isso, abra o terminal e navegue até a pasta onde você deseja clonar o repositório. Em seguida, digite o seguinte comando:

```plaintext
git clone git@github.com:seu_nome/seu_repositorio.git
```

O comando acima clonará o repositório `seu_repositorio` para a pasta atual.



### **4. Fazer um commit**

Agora que você clonou o repositório, você pode começar a adicionar arquivos ao seu projeto. Cada vez que você fizer uma alteração no seu projeto, você precisará fazer um commit. Para fazer um commit, abra o terminal e navegue até a pasta do seu projeto. Em seguida, digite o seguinte comando:

```plaintext
git add .
```

O comando acima adicionará todos os arquivos alterados no seu projeto ao staging area. Em seguida, digite o seguinte comando para fazer o commit:

```plaintext
git commit -m "Adicionando novas funcionalidades ao projeto"
```

O comando acima criará um novo commit no seu repositório.



### **5. Fazer um push**

Agora que você fez um commit no seu repositório, você precisa fazer um push para a sua conta no GitHub. Para fazer isso, digite o seguinte comando:

```plaintext
git push origin master
```

O comando acima fará um push de todos os commits do seu repositório local para o seu repositório remoto no GitHub.



 Criarum projeto Flutter passo a passo. Você também aprenderá sobre os arquivos de configuração do Flutter, a estrutura de projetos do Flutter e como importar e exportar projetos Flutter.



### **1. Crie um novo projeto Flutter**

Para criar um novo projeto Flutter, você pode usar o comando `flutter create`. Este comando irá criar um novo projeto Flutter na pasta atual.

```plaintext
flutter create meu_projeto
```

Este comando criará um novo diretório chamado `meu_projeto` com os seguintes arquivos e pastas:

- `pubspec.yaml`: Este arquivo contém as informações do seu projeto, como o nome do projeto, a versão da biblioteca Flutter e as dependências do projeto.

- `lib/main.dart`: Este arquivo contém o código do seu aplicativo Flutter.

- `ios/`: Esta pasta contém os arquivos necessários para compilar seu aplicativo para iOS.

- `android/`: Esta pasta contém os arquivos necessários para compilar seu aplicativo para Android.

  

### **2. Entenda a estrutura de projetos do Flutter**

A estrutura de projetos do Flutter é dividida em três partes:

- **O diretório `lib`:** O diretório `lib` contém o código-fonte do seu aplicativo Flutter.
- **O diretório `ios`:** O diretório `ios` contém os arquivos necessários para compilar seu aplicativo para iOS.
- **O diretório `android`:** O diretório `android` contém os arquivos necessários para compilar seu aplicativo para Android.

O diretório `lib` é a parte mais importante da estrutura de projetos do Flutter. É aqui que você irá armazenar todo o código-fonte do seu aplicativo. O diretório `ios` e o diretório `android` são usados para compilar seu aplicativo para iOS e Android, respectivamente.



### **3. Importe e exporte projetos Flutter**

Você pode importar e exportar projetos Flutter usando o comando `flutter pub get`. Este comando irá baixar todas as dependências do projeto do Flutter Hub.

```plaintext
flutter pub get
```

Você também pode exportar seu projeto Flutter usando o comando `flutter build apk` ou `flutter build ios`. Estes comandos irão criar um APK para Android ou um IPA para iOS, respectivamente.



## **Conclusão**

Neste tutorial, você aprendeu a criar um projeto Flutter passo a passo. Você também aprendeu sobre os arquivos de configuração do Flutter, a estrutura de projetos do Flutter e como importar e exportar projetos Flutter.

Mais informações sobre o desenvolvimento de aplicativos Flutter, consultando a documentação oficial do Flutter.



### Links Úteis

Site oficial - Flutter: Flutter - Build apps for any screen  https://flutter.dev/
