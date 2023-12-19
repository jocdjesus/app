# app

## Instalación
1. Clona este repositorio: `git clone https://github.com/jocdjesus/app.git`
2. Debes tener instalado node.js y npm, android studio 
3. Ingresa a la carpeta donde guardaste el git
4. npm install -g expo-cli #linea de comandos 
5. expo init rate-repository-app
5.1 si aparece un error como expo : File C:\Users\Jocd\AppData\Roaming\npm\expo.ps1 cannot be loaded. The file C:\Users\Jocd\AppData\Roaming\npm\expo.ps1 is not digitally signed. You cannot run this script on the current 
system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170.
At line:1 char:1
+ expo init rate-repository-app
+ ~~~~
    + CategoryInfo          : SecurityError: (:) [], PSSecurityException
    + FullyQualifiedErrorId : UnauthorizedAccess

entonces deberas ingresar al cmd como administrador y posteriormente copiar el siguiente comando
powershell -ExecutionPolicy Bypass -File C:\Users\Jocd\AppData\Roaming\npm\expo.ps1 init rate-repository-app

selecciona el blank

6. entrar a repository app
7. npm start //abrira el proyecto 
