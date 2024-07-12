# Documentação de Criação

Documentação de como o projeto foi criado passo a passo atraves das aulas do NLW Journey na trilha de React Native.

## Iniciando o projeto

* Inicie criando o tamplate da aplicação.

~~~bash
 npx create-expo-app --template
~~~

* Selecione a opção `Navigation (TypeScript).`
* Após projeto criado, podera apagar algumas paginas.
  * Pasta `App`
  * Pasta `Components`
  * Pasta `Constants`
  * Pasta `Fonts` em `Assets`

## Rodando a aplicação

* Para rodar a aplicação usamos o Expo Go onde pode ser acessado por todos dispositivos web, Android e IOS.
* Para iniciar o Expo rode o seguinte comando.

~~~bash
 npx expo start
~~~

## Estilização

* Para usar o TailwindCSS para otimizar o tempo de estilização rode o seguinte comando.

~~~bash
  npx expo install nativewind@^4.0.1 react-native-reanimated tailwindcss
~~~