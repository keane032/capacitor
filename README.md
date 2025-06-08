# Criar e configurar projeto PWA com Capacitor

1. **Crie a pasta do projeto e acesse-a:**  
   Digite no terminal:
   ```
   mkdir meu-pwa-capacitor  
   cd meu-pwa-capacitor
   ```

2. **Inicie o projeto Node.js:**  
   Execute o comando:  
   ```json
   npm init -y

3. **Instale e inicialize o Capacitor:**  
   Use os comandos:  
   ```json
   npm install @capacitor/core @capacitor/cli  
   npx cap init

4. **Configure o servidor no arquivo `capacitor.config.js`:**  
   Adicione este trecho dentro da configuração do arquivo:

   ```json
   "server": {
     "url": "https://refactoring.guru/pt-br",
     "cleartext": false
   }

5. **Instale a plataforma android:**
   Use os comandos:
   
   ```json
    npm install @capacitor/android
    npx cap add android

6. **Execute esse comando**

   ```json
   mkdir android\app\src\main\assets

7. **Use os comando abaixo para atualizar auteracoes no projeto:** 

   ```json
    npx cap sync
    npx cap copy

8. **Agora abra a pasta android no android studio e execute o projeto** 

