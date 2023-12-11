# Hello Gitflow

Repositório criado para auxiliar a mim e a você no uso básico do Gitflow.

Viu a oportunidade de melhorar de alguma forma o repositório? Sinta-se à vontade para contribuir 🙂

### Instalação:

- https://github.com/nvie/gitflow/wiki/Installation

### Branches

- `main` é a branch principal do projeto. É considerada a versão de produção estável do código.
- `develops` é a branch de desenvolvimento contínuo, onde as features são integradas.
- `feature` são as branches criadas para desenvolver novas funcionalidades.
- `release` são as branches criadas para preparar o código para um release (correção de bugs, ajustes finos e preparação para a versão de produção).
- `hotfix` são as branches criadas para corrigir bugs na produção.

<br />
<img height="400em" src="https://wac-cdn.atlassian.com/dam/jcr:cc0b526e-adb7-4d45-874e-9bcea9898b4a/04%20Hotfix%20branches.svg?cdnVersion=1351" align="center" />
<br />

### Comandos básicos:

- `git flow init` inicia o git e permite personalizar as branches
- `git flow {branch} start {descrição}` inicia uma nova branch e você pode usar "git add" e "git commit" normalmente.
- `git flow {branch} finish {descrição}` finaliza a branch.

#### Exemplos:

- git flow feature start welcome
- git flow feature finish welcome
