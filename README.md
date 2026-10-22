# Aula5-de-computacao-em-nuvem


# Aula 5 — Kubernetes

## Objetivo

Aprender na prática a criar, gerenciar e escalar aplicações utilizando Kubernetes.

## Atividades realizadas

* **Verificação do cluster:** conferência da versão do kubectl e do status dos nós.
* **Criação de Deployment:** implantação de uma aplicação Nginx utilizando a imagem `nginx:alpine`.
* **Gerenciamento de Pods:** consulta de informações, status, endereços IP e nós onde os contêineres estão em execução.
* **Escalonamento:** aumento do número de réplicas de 1 para 3, utilizando o comando `kubectl scale`.
* **Recuperação automática:** exclusão de um Pod para observar a criação automática de outro pelo Kubernetes.
* **Criação de Service:** exposição da aplicação por meio de um serviço `ClusterIP`, destinado à comunicação interna do cluster.
* **Teste de conectividade:** tentativa de acesso ao serviço utilizando `curl`, com necessidade de corrigir o comando e validar a resolução do nome do serviço.

## Tecnologias utilizadas

* Kubernetes
* kubectl
* Nginx (Alpine)

## Conclusão

A prática permitiu compreender conceitos fundamentais do Kubernetes, incluindo Deployments, Pods, ReplicaSets, escalonamento, recuperação automática e Services, desenvolvendo habilidades para gerenciar aplicações em contêineres.



