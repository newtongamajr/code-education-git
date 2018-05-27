# Repositório Teste

Este repositório será utilizado para os projetos da Code Education.

## Começando com o GIT
Para a criação deste repositório foram seguidos os seguintes passos:

* Criação do repositório no GITHub através da interface da plataforma, com as opções de criação dos arquivos de .gitignore e README.md ativadas.
* Criação do clone do repositório criado no GITHub.

        git clone https://github.com/newtongamajr/code-education-git.git
        
* Como estou utilizando o PHPStorm como plataforma de IDE e ambientte foi preparado para uma aplicação Laravel, foram adicionadas as seguintes linhas ao arquivo

        vendor/
        node_modules/
        npm-debug.log
        .idea
        # Laravel 4 specific
        bootstrap/compiled.php
        app/storage/
        
        # Laravel 5 & Lumen specific
        public/storage
        public/hot
        storage/*.key
        .env.*.php
        .env.php
        .env
        Homestead.yaml
        Homestead.json
        
        # Rocketeer PHP task runner and deployment package. https://github.com/rocketeers/rocketeer
        .rocketeer/
 
* Modificação das informações no conteúdo do arquivo README.md para espelhar as instruções necessárias.
* Com o uso do comando abaixo podemos verificar o que foi modificado e depois marcar estes arquivos como 'staged'

        git status
        git add .
        
* Após, executamos o commit para que as alterações 'staged' estejam preparadas para serem devolvidas ao repositório:        

        git commit -m "Modificações realizadas no README.md para apresentar os passos seguidos para criação e modificação do respositório."

* Agora estamos prontos para devolver as informações ao repositório no branch master:

        git push origin master
        
        