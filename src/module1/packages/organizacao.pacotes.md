# Organizando as classes em pacotes

Este é um projeto de exemplo que demonstra as boas práticas de organização de classes e pacotes em um projeto.

## Estrutura do Projeto

O projeto é estruturado da seguinte forma:

```
projeto-exemplo/
├── src/
│ ├── dev/
│ │ ├── emanoel/
│ │ │ ├── pacote1/
│ │ │ │ ├── Classe1.java
│ │ │ │ ├── Classe2.java
│ │ │ ├── pacote2/
│ │ │ │ ├── Classe3.java
│ │ │ │ ├── Classe4.java
│ │ │ ├── pacote3/
│ │ │ │ ├── Classe5.java
│ │ │ │ ├── Classe6.java
├── test/
│ ├── dev/
│ │ ├── emanoel/
│ │ │ ├── pacote1/
│ │ │ │ ├── Classe1Test.java
│ │ │ │ ├── Classe2Test.java
│ │ │ ├── pacote2/
│ │ │ │ ├── Classe3Test.java
│ │ │ │ ├── Classe4Test.java
├── README.md
├── LICENSE
├── .gitignore
```



### Pacotes

Os pacotes são usados para organizar e agrupar as classes relacionadas. No exemplo acima, adicionamos o domínio "dev.emanoel" antes de cada pacote para diferenciá-los. Isso evita conflitos de nomes caso existam outros projetos com pacotes semelhantes.

As classes dentro de cada pacote estão organizadas de forma lógica e coesa, facilitando a navegação e compreensão do código. Por exemplo, as classes relacionadas a uma determinada funcionalidade podem ser agrupadas em um único pacote.

### Arquivos de Código-fonte

Os arquivos de código-fonte estão localizados na pasta `src/`. Seguindo a nova estrutura, os pacotes estão localizados dentro de `src/dev/emanoel/`. Por exemplo, a classe `Classe1.java` está localizada em `src/dev/emanoel/pacote1/`.

Os arquivos de teste estão localizados na pasta `test/`. A estrutura de pastas dentro de `test/` segue a mesma estrutura de pacotes em `src/`. Por exemplo, a classe de teste `Classe1Test.java` está localizada em `test/dev/emanoel/pacote1/`.

### Outros Arquivos

Além dos arquivos de código-fonte, o projeto também possui outros arquivos importantes:

- `README.md`: Este arquivo contém informações sobre o projeto, sua estrutura e como utilizá-lo.
- `LICENSE`: O arquivo de licença do projeto.
- `.gitignore`: Arquivo que especifica quais arquivos e pastas devem ser ignorados pelo controle de versão Git.


