# Introdução ao Git e ao GitHub (Otávio Reis) - Plataforma DIO

Todas as informações contidas neste arquivo foram baseadas nas aulas da plataforma DIO. 



## Entendendo o Git/GitHub

**Git**

O Git é um sistema de controle de versões distribuído, usado principalmente no desenvolvimento de software. 



**GitHub**

O GitHub é uma plataforma de hospedagem de código-fonte e arquivos de versão usando o Git. Ou seja, no GitHub é onde se armazena os códigos. 



**Principais benefícios do GitHub**

- Controle de Versão; 

- Armazenamento em nuvem;

- Trabalho em equipe;

- Aprimoramento de código;

- Reconhecimento. 

  

### Comandos básicos para um bom desempenho no terminal

 Comandos de operação no Windows: 

* Listar: dir/ls
* Navegar entre pastas: cd 
* Navegar para uma pasta específica: cd /
* Criar diretórios: mkdir
* Deletar diretórios: del/rmdir
* Ir para diretório anterior: cd ..
* Limpar: cls/ ctrl L
* autocomplete: tab
* Mover o arquivo no Git: Mv 



#### SHA-1

A sigla SHA significa Secure Hash Algorithm (Algoritmo de hash seguro), é um conjunto de funções hash criptográficas projetadas pela NSA (Agência de Segurança Nacional dos EUA).

Sha1 é uma forma curta de representar um arquivo. Pois, a encriptação gera um conjunto de caracteres identificador de 40 dígitos. 

**Exemplo:**

Se você pegar um texto enorme e passar ele por esse algoritmo, ele vai gerar um conjunto de caracteres (sha-1). No entanto, se for alterado uma vírgula que seja do texto,  já será gerado outro conjunto de caracteres. 



#### Chave SSH

É uma forma de manter uma conexão segura e criptadas entre duas máquinas.

Comando para chave ssh:

ssh-keygen -t ad25519 -C 



#### Comandos Iniciais do Git

* Git config

* Git config --global user.name "nome"

* Git config --global user.email "email"

  

#### Comandos com Git

* Git init
* Git add
* Git commid



#### File Status Lifecycle

**Untracked:** momento em que o arquivo acaba de ser adicionado no repositório, mas ainda não foi reconhecido pelo Git. 

**Unmodified:**  arquivo não modificado.

**Modified:**  arquivo modificado. 

**Staged:**  onde será criado o arquivo. 



### Resolvendo conflitos

* Git add*
* Git pull origin master/main (é usado quando existem versões diferentes de um arquivo no Github. O Git vai dizer onde está o erro para corrigi-lo)
* Git clone: clona um repositório do GitHub.











