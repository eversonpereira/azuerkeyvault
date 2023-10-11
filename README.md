# Exercício Prático: Implementação de Política de Segurança com Azure Key Vault

## Objetivo
Familiarizar os alunos com a gestão e implementação de políticas de segurança na nuvem, utilizando o Azure Key Vault para armazenar e gerenciar segredos de aplicativos de maneira segura.

## Contexto
Uma pequena empresa de desenvolvimento de software utiliza diversas APIs e bancos de dados em suas aplicações. A empresa deseja aprimorar suas práticas de segurança, assegurando que todas as credenciais, como strings de conexão e chaves API, sejam armazenadas de maneira segura.

## Duração
1 a 2 horas.

## Tarefas

### Tarefa 1: Configuração do Azure Key Vault
#### Objetivo
Criar um cofre no Azure Key Vault e configurá-lo seguindo as melhores práticas de segurança.

#### Passos
1. Criar um Key Vault no portal Azure.
2. Configurar a política de acesso, garantindo que apenas entidades autorizadas tenham acesso aos segredos armazenados.
3. Adicionar um segredo (ex.: uma string de conexão fictícia) no Key Vault.

### Tarefa 2: Integração de Aplicativo com Key Vault
#### Objetivo
Desenvolver um pequeno aplicativo ou script que recupere um segredo do Azure Key Vault sem expor a credencial diretamente no código.

#### Passos
1. Utilizar qualquer linguagem de programação suportada pelo Azure SDK para desenvolver o aplicativo/script.
2. Autenticar o aplicativo com o Azure Key Vault usando Managed Identity (evitando o uso de credenciais no código, se possível).
3. Recuperar o segredo armazenado no Key Vault e exibi-lo de forma segura ou usá-lo para autenticar com algum serviço fictício.
4. (Opcional) Implementar um mecanismo de logging seguro para registrar o acesso aos segredos.

## Avaliação
A avaliação pode ser baseada em:
- Correta configuração e uso do Azure Key Vault.
- Implementação segura e eficaz da recuperação de segredos no aplicativo/script.

## Nota
Este exercício prático visa proporcionar uma experiência introdutória sobre como gerenciar segredos de forma segura em ambientes de nuvem usando o Azure. O mesmo oferece uma oportunidade de aprender, discutir e aplicar conceitos básicos de segurança, sendo uma atividade produtiva que pode ser concluída em uma sessão de 1 a 2 horas.
