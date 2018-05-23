# MWebScraper

Web Scraper para o site do Matricula Web! Retorna informações de campus, departamentos, cursos, currículos, fluxos, matérias e ofertas em arquivos de formato JSON para fácil implementação em seu programa.

## Execução

Para executar este programa basta executar os seguintes comandos no terminal:

```
  $ bash install.sh
```

Este comando acima instala as dependências do código. No entanto, é necessario já possuir instalado o pip3 e o Homebrew. Após a instalação destes módulos, execute o arquivo python da seguinte forma:

```
  $ python3 scrap.py
```

## Pré-requisitos do sistema

Este programa foi testado no sistema operacional ``macOS High Sierra``, versão ``10.13.3``. A linguagem de programação utilizada para implementar todo o projeto foi ``Python 3.6.5``.

## Detalhes sobre o projeto

Este programa utiliza o arquivo ``scrap.py`` para buscar dados da graduação no site do Matricula Web da Universidade de Brasília.

### Funcionalidades Atuais:

Atualmente o programa minera as seguinte informações do MW

* **Campus**
* **Curso**
* **Departamento**
* **Matéria**
* **Currículo**
* **Fluxo**
* **Oferta**
