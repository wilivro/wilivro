# Processo de desenvolvimento de sofware

## Processo

- **Task Builder**

São identificadas novas funcionalidades, melhorias e bugs.

Por: Qualquer pessoa envolvida no projeto (Stakeholders).


- **Task Manager**

As tarefas são distribuidas aos times/desenvolvedores responsáveis.

Por: Responsável principal pelo projeto (Product Owner)


- **Development**

Desenvolver a funcionalidade conforme as regras estabelecidas no [documento]().

Por: Desenvolvedores


- **Self Test**

Teste completo da funcionalidade garantindo que está tudo ok e nada mais precisa ser desenvolvido.

Por: Mesmo desenvolvedor que fez a tarefa.


- **Test**

Teste completo da funcionalidade garantindo que está tudo ok e já pode ir para a branch **Develop** .

Por: Outro desenvolvedor que não participou do desenvolvimento da tarefa.


- **Pull Request**

Enviar o código que foi testado para a branch **develop**, deverá ser usado um pull request pelo github para que o código a ser submetido passe pelo **Build Test**, ou seja, não será permitido fazer merge diretamente entre as branchs sem pull request

Por: Desenvolvedor que realizou o **Test**


- **Build Test**

Teste automatizado que é executado quando uma funcionalidade é enviada para a branch **Develop**

Por: [CircleCI](https://circleci.com/)


- **Doc Generator**

Geração automatizada da documentação completa do sistema.

Por: [PHPDoc](http://www.phpdoc.org/)
