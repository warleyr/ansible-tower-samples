# ansible-tower-samples
Ansible Tower Playbook Samples

# Ansible Galaxy
https://www.concrete.com.br/2017/04/26/automacao-e-provisionamento-agil-com-ansible/

https://blog.mandic.com.br/artigos/ansible-dicas-para-quem-esta-comecando-a-usar-a-ferramenta-de-automacao/

https://blog.4linux.com.br/conhecendo-um-pouco-do-ansible-galaxy/

https://www.owlbearconsulting.com/doku.php?id=linux_wiki:ansible_awx

Tasks: uma tarefa é a menor unidade de trabalho. Pode ser uma ação como “Instalar um banco de dados”, “Instalar um servidor web”, “Criar uma regra de firewall” ou “Copiar este arquivo de configuração para esse servidor”.

Plays: um play é composto de tarefas. Por exemplo, o play: “Preparar um banco de dados para ser usado por um servidor web” é composto das tarefas: 1) Instalar o pacote de banco de dados; 2) Definir uma senha para o administrador do banco de dados; 3) Criar um banco de dados; e 4) Definir o acesso ao banco de dados.

Playbook: Um playbook é composto por um conjunto de plays. Um playbook poderia ser: “Prepare meu site com um backend de banco de dados”, e os plays seriam 1) Configurar o servidor de banco de dados; e 2) Configurar o servidor web.

Roles: as funções são usadas para salvar e organizar manuais e permitir compartilhar e reutilizar playbooks. Seguindo os exemplos anteriores, se você precisa configurar completamente um servidor web, pode usar uma função que outros escreveram e compartilharam para fazer exatamente isso. Uma vez que as funções são altamente configuráveis (se escritas corretamente), elas podem ser facilmente reutilizadas para atender a quaisquer requisitos de deploy.

Ansible Galaxy: O Ansible Galaxy é um repositório online onde as funções são carregadas para que possam ser compartilhadas com outras pessoas. Está integrado com o GitHub, de modo que os roles podem ser organizados em repositórios Git e, em seguida, compartilhados via Ansible Galaxy.




o site seria um repositotio de roles, e o comando ansible-galaxy.
E um site aonde voce pode compatilhar roles para qualquer tipo de atividade: em nosso exemplo um servidor jenkins.

ansible-galaxy init jenkins

Dentro do gitcorporativo criar um novo repositorio, com o nome ansible-role-warley

Depois de criado execute o git clone do endereco do seu repositorio para sua estacao

ansible-galaxy init jenkins

conferir a estrutura da nossa role

tree

git add .

git commit "projeto inicial"

git push origin master
