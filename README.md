# Ignite Lab Rockethelp
Projeto em React Native feito em um evento fornecido pela Rocketseat para a construção de um aplicativo, que tem como objetivo levantar solicitações (pedidos) e atendê-los.

## Principais bibliotecas utilizadas
- [Native Base](https://github.com/GeekyAnts/nativebase) para a construção de componentes;
- [Firebase](https://firebase.google.com) para o armazenamento dos dados;

## Observações
- Com a biblioteca [React Native Firebase](https://github.com/GeekyAnts/nativebase) instalada no projeto, será necessário o uso de emuladores, por que não será possível fazer a depuração do aplicativo utilizando "Expo Go" app, pois a biblioteca requer código nativo;
- Configurações para utilizar Firebase, são realizadas no [Console do firebase](console.firebase.google.com);

## Passo-a-Passo Firebase
- São necessários os arquivos ` google-services.json ` (Android) e ` GoogleService-Info.plist ` (IOS) na raíz do projeto para o funcionamento do [Native Base](https://github.com/GeekyAnts/nativebase);
- Os arquivos comentados acima, são gerados no [Console do firebase](console.firebase.google.com), siga a documentação para mais detalhes: [Documentação Firebase](https://rnfirebase.io);
- Após os arquivos ` google-services.json ` e ` GoogleService-Info.plist ` serem inseridos no projeto, insira essas informações em seu ` app.json `:

    ![Expo Config](https://i.imgur.com/VIUNude.png)

- Depois de inserir as informações no ` app.json `, faça o seguinte comando no seu projeto: `$ expo prebuild --clean` para adicionar os plugins necessários para o código nativo, sendo necessário para a utilização do [Firebase](https://firebase.google.com);
- Após realizar os passos acima, é só gerar um emulador no [Android Studio](https://developer.android.com/studio?hl=pt&gclid=Cj0KCQjw_viWBhD8ARIsAH1mCd6KyCgMTTo-Zv3ZdoL-P2xEW1JWCGbN6UI2SMYyN4XPMUqGC4fbdroaAhwuEALw_wcB&gclsrc=aw.ds) (Android) ou no [Xcode](https://developer.apple.com/xcode/) (IOS) para a realização da depuração do projeto 😎👍.
 
