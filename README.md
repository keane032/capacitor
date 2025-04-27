mkdir meu-pwa-capacitor
cd meu-pwa-capacitor
npm init -y



npm install @capacitor/core @capacitor/cli
npx cap init


 "server": {
    "url": "https://refactoring.guru/pt-br",
    "cleartext": false
  }

Quando cleartext = true: o app permite conexões não criptografadas, ou seja, via http://


Quando cleartext = false: o app restringe para apenas conexões seguras, ou seja, só HTTPS


npm install @capacitor/android

npx cap add android
npx cap add ios


npx cap open android
npx cap open ios


mkdir android\app\src\main\assets


npx cap sync
npx cap copy
