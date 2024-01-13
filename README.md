# Projeto Cluster Swarm com Vagrant

## Descrição

Este projeto tem como objetivo criar um Cluster Swarm local utilizando máquinas virtuais e o gerenciador de configuração Vagrant. A proposta é aplicar conhecimentos em Docker Swarm, Vagrant e Git, buscando otimizar o processo de implementação para melhorar a eficiência dos desenvolvedores.

## Passo a Passo

### 1. Configuração do Vagrantfile
   - Crie um arquivo Vagrantfile com as definições das máquinas virtuais.
   - As máquinas virtuais devem ter os seguintes nomes: master, node01, node02 e node03.

### 2. Atribuição de IPs Fixos
   - Configure cada máquina virtual com um IP fixo para facilitar a comunicação.

### 3. Instalação do Docker
   - Todas as máquinas virtuais devem ter o Docker pré-instalado.

### 4. Configuração do Cluster Swarm
   - A máquina com o nome 'master' será designada como nó manager do cluster.
   - As demais máquinas (node01, node02) devem ser incluídas no cluster Swarm como Workers.

## Pré-requisitos

- Conhecimento Básico em Docker (Cluster Swarm)
- Conhecimento Básico em Git e GitHub
- Computador com Sistema Operacional de sua preferência (Windows, Linux, Mac OS)

## Instruções de Execução

1. Clone este repositório: `git clone https://github.com/Alexandregs10/Docker-Cluster-Swarm--with-Vagrant`
2. Navegue até o diretório do projeto: `cd Docker-Cluster-Swarm--with-Vagrant`
3. Execute as máquinas virtuais com o Vagrant: `vagrant up`
4. Aguarde o término do processo de provisionamento.
5. Acesse a máquina 'master' para gerenciar o cluster Swarm.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.
