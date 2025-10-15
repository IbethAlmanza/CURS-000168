# Maven
## Settings

1. Instalar plugins maven
     i. Login
    ii. Manage Jenkins
   iii. Manage Plugins
    iv. Clic Avialable
     v. Buscar Plugin: "Maven Integration"
    vi. Buscar Plugin: "Git"
    vi. Buscar Plugin: "JUnit Attachments"
    vi. Clic en Install Without restart
   
1. Instalar maven
    i. Manage Jenkins
   ii. Global Tool Configuration
  iii. Ir a la sección: "Maven"
   iv. Clic en "Add NodeJS"
        * Name: maven-default
        * Install automatically: Check
    v. Clic en Save

## JOBS
1. Crear 06-job-maven
    * Crear proyecto del estilo libre.
        * Nombre: 06-job-maven
        * Description: Node demo
        * Build --> Invoke top-level Maven targets -->
        * Goals: 
        ```shell         
        npm version
        ```        

1. Crear 07-script-nodejs-job
    * Crear proyecto del estilo libre.
        * Nombre: 07-script-nodejs-job
        * Description: Node demo
        * Build --> Execute NodeJS script --> 
        ```shell         
        console.log("ok");
        console.log(process.version);
        ```  


