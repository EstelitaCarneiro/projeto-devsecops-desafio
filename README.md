# Desafio DevSecOps — Gerenciador de Tarefas

## Sobre o Projeto
Este repositório faz parte do desafio prático do módulo de DevSecOps da ADA Tech.
Você receberá este projeto com vulnerabilidades propositais e uma pipeline incompleta.
Seu objetivo é **implementar a pipeline de segurança** e **corrigir as vulnerabilidades**.

## Estado atual
A pipeline está **incompleta**. Os steps de segurança precisam ser implementados por você.

## Sua missão
1. Implementar os steps de segurança no `pipeline.yml`
2. Fazer a pipeline **quebrar** ao detectar os problemas
3. Corrigir as vulnerabilidades encontradas
4. Fazer a pipeline **passar** com tudo verde ✅
5. Documentar o funcionamento da pipeline neste README

## O que implementar
- [ ] Secrets Scanning com **Gitleaks**
- [ ] SAST com **Semgrep**
- [ ] SCA com **Grype**
- [ ] Deploy com **GitHub Pages**

## Como a pipeline funciona
> A pipeline implementa o DevSecOps com os gates de segurança automatizados que inspecionam tudo antes de publicar/colocar em produção. Ao encontrar riscos de segurança ela trava/pára tudo para proteger os usuários.

> Análise de cada step:

> Step 1 - Secrets Scaninning com Gitleaks: pesquisa o código para identificar senhas, chaves de API ou tokens expostos.

> Step 2 - SAST com Semgrep: pesquisa o código para identificar padrões inseguros comuns e para impedir que hackers testem e explorem essas vulnerabilidades no deploy.

> Step 3 - SCA com Grype: verifica todas as bibliotecas/ferramentas usadas no projeto por vulnerabilidades conhecidas.

> Step 4: Deploy com Github Pages: só permite a publicação do App se todos os steps anteriores estiverem ok.

  Ao final as métricas de segurança foram alcançadas:
  
  Gerenciador de Tarefas - PRODUÇÃO
  Status do Sistema: Conectado ao Banco de Dados

    Tarefas
      Implementar a pipeline de segurança
      Corrigir as vulnerabilidades do projeto
      Fazer o deploy em produção

## URL de Produção
> https://estelitacarneiro.github.io/projeto-devsecops-desafio/
> 
