# 🤖 auto-wpp-node  🤖
------------

Bot whatsapp para automação de processos relacionados a ITIL com foco no suporte da aplicação GLPI.

## 🚀 Começando
------------

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

Consulte Implantação ou contato para saber como implantar o projeto.

### 📋 Pré-requisitos
Para a implantação desse projeto será necessário a instalação do [Node.js](https://nodejs.org/en/ "Node.js") para servidor. Também é necessário a ferramenta [git](https://git-scm.com "GIT") em sua máquina para a clonagem do repositório. 

Além da instalação node o projeto depende de alguns pacotes essenciais, entre eles a API [@open-wa/wa-automate](https://docs.openwa.dev "@open-wa/wa-automate"), além do DB [SQLite](https://www.npmjs.com/package/sqlite "sqlite").

Se estiver em ambiente Linux é possível instalar o Node.js utilizando o curl:

```bash
sudo apt-get install curl
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
sudo apt-get install -y nodejs
```
Em ambiente Windows é possível fazer o download e instalação através do link  [Node.js](https://nodejs.org/en/ "Node.js"). 

### 🔧 Instalação
Primeiramente realize o clone do repositório:
` git clone https://github.com/williamciva/auto-wpp-node.git`

Após o clone realize a instalação das dependências, elas podem ser instaladas através do comando:
`npm install`

### 🎁 Agradecimentos
- Obrigado ao usuário do GitHub @lohhans pelo modelo do README.md disponibilizado. Link para:
`https://gist.github.com/lohhans/f8da0b147550df3f96914d3797e9fb89`
