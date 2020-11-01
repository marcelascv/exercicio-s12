# exercicio-s12

Resumo aula da semana

Desenvolvedores backend se comunicam com o banco de dados através das permissões de acesso às informações;
Armazenamos dados com alguma finalidade para resolver problemas;
Temos entidades que são grupos que armazenam dados, ou seja, armazena os atributos que têm as características que compõe a entidade;
E os sistemas de gerenciamento de dados servem para gerir essas estruturas, permitindo manipular e controlar as permissões de uso do banco de dados;

Existem dois tipos de sistemas, o SQL (relacional) e o NoSQL (não relacional). O primeiro tem uma estrutura de dados pré-definida, em formato de tabela, próximo da ideia do Excel de linha e coluna. Já o último, os registros são diferentes uns dos outros, os banco de dados são mais dinâmicos, tem estrutura independente de armazenamento e não precisa ter a estrutura pré-definida.

Para práticas com JavaScritpt o MongoDB é um dos sistemas NoSQL que mais está sendo utilizado pelos desenvolvedores backend, por ser um open source e ter a comunidade bem ativa nas melhorias e constribuições;

MongoDB é um banco de dados voltado para documentos e funciona na base de BSON, estrutura de dados semelhandte ao JSON, porém tem mais tipos de dados para ser trabalhado;

O documento é o registro 
{
    name: "Marcela"
    id: 12
}

E ele é salvo em uma collection, ou seja, array de documentos

-Passo a passo de instalação do Mongodb