# Modificadores de Acesso

Os modificadores de acesso em Java são recursos que controlam a visibilidade dos membros de uma classe, como métodos e atributos. Eles determinam quais partes do código podem acessar esses membros. Em Java, existem quatro tipos de modificadores de acesso: public, private, protected e default. Cada um desses modificadores oferece diferentes níveis de acesso, permitindo maior controle e segurança no desenvolvimento de programas orientados a objetos.

## Public
- permite que os membros sejam acessados de qualquer lugar, ou seja, por qualquer classe ou pacote.

## Default
- não é uma palavra-chave explícita, é quando nenhum modificador de acesso é especificado.
- visível dentro da própria classe e também em classes do mesmo pacote

## Protected
- visível dentro da própria classe e também em classes do mesmo pacote
- visível em subclasses, mesmo que estejam em pacotes diferentes

## Private
- restringe o acesso aos membros apenas à própria classe.
