---
title: Creating a repository security advisory
intro: Você pode criar um projeto de consultoria de segurança para discutir e corrigir de forma privada uma vulnerabilidade de segurança no seu projeto de código aberto.
redirect_from:
  - /articles/creating-a-maintainer-security-advisory
  - /github/managing-security-vulnerabilities/creating-a-maintainer-security-advisory
  - /github/managing-security-vulnerabilities/creating-a-security-advisory
  - /code-security/security-advisories/creating-a-security-advisory
versions:
  fpt: '*'
  ghec: '*'
type: how_to
topics:
  - Security advisories
  - Vulnerabilities
shortTitle: Create repository advisories
---

Qualquer pessoa com permissões de administrador em um repositório pode criar uma consultoria de segurança.

{% data reusables.security-advisory.security-researcher-cannot-create-advisory %}

## Criar uma consultoria de segurança

{% data reusables.repositories.navigate-to-repo %}
{% data reusables.repositories.sidebar-security %}
{% data reusables.repositories.sidebar-advisories %}
4. Clique em **Novo rascunho de consultoria de segurança**. ![Botão Open draft advisory (Abrir consultoria de rascunho)](/assets/images/help/security/security-advisory-new-draft-security-advisory-button.png)
5. Digite um título para sua consultoria de segurança.
{% data reusables.repositories.security-advisory-edit-details %}
{% data reusables.repositories.security-advisory-edit-severity %}
{% data reusables.repositories.security-advisory-edit-cwe-cve %}
{% data reusables.repositories.security-advisory-edit-description %}
11. Clique em **Criar rascunho de consultoria de segurança**. ![Botão para criar consultoria de segurança](/assets/images/help/security/security-advisory-create-security-advisory-button.png)

## Próximas etapas

- Faça um comentário sobre o rascunho da consultoria de segurança para discutir a vulnerabilidade com sua equipe.
- Adicione colaboradores à consultora de segurança. For more information, see "[Adding a collaborator to a repository security advisory](/code-security/repository-security-advisories/adding-a-collaborator-to-a-repository-security-advisory)."
- Colaborar de modo particular com a correção da vulnerabilidade em uma bifurcação privada temporária. For more information, see "[Collaborating in a temporary private fork to resolve a repository security vulnerability](/code-security/repository-security-advisories/collaborating-in-a-temporary-private-fork-to-resolve-a-repository-security-vulnerability)."
- Adicione indivíduos que deveriam receber crédito por contribuírem para a consultoria de segurança. For more information, see "[Editing a repository security advisory](/code-security/repository-security-advisories/editing-a-repository-security-advisory#about-credits-for-security-advisories)."
- Publicar a consultoria de segurança para notificar a sua comunidade sobre a vulnerabilidade de segurança. For more information, see "[Publishing a repository security advisory](/code-security/repository-security-advisories/publishing-a-repository-security-advisory)."
