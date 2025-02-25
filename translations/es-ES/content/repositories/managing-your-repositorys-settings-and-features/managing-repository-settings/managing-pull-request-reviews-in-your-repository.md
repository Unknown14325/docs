---
title: Administrar las revisiones de las solicitudes de cambios en tu repositorio
intro: Puedes limitar qué usuarios pueden aprobar o solicitar cambios a las solicitudes de cambios en un repositorio público.
versions:
  feature: pull-request-approval-limit
permissions: Repository administrators can limit which users can approve or request changes to a pull request in a public repository.
topics:
  - Repositories
  - Pull requests
shortTitle: Administrar las revisiones de las solicitudes de cambios
---

## Acerca de los límites de revisión de código

Predeterminadamente, en los repositorios públicos, cualquier usuario puede emitir revisiones que aprueben o soliciten cambios a una solicitud de cambios.

Puedes limitar qué usuarios pueden emitir revisiones que aprueben o soliciten cambios a una solicitud de cambios en tu repositorio público. Cuando habilitas los límites de la revisión de código, cualquiera puede comentar en las solicitudes de cambios de tu repositorio público, pero solo las personas con acceso de lectura o superior pueden aprobarlas o solicitar cambios a ellas.

También puedes habilitar los límites de revisión de código para una organización. Si habilitas los límites para una organización, sobrescribirás cualquiera de ellos para los repositorios individuales que le pertenezcan a esta. Para obtener más información, consulta la sección "[Administrar las revisiones de solicitudes de cambio en tu organización](/organizations/managing-organization-settings/managing-pull-request-reviews-in-your-organization)"

## Habilitar los límites de revisión de código

{% data reusables.repositories.navigate-to-repo %}
{% data reusables.repositories.sidebar-settings %}
1. Under **Access**, click **Moderation options**. ![Ajustes de repositorio para opciones de moderación](/assets/images/help/repository/access-settings-repositories.png)
1. Under **Moderation options**, click **Code review limits**. ![Code review limits repositories](/assets/images/help/repository/code-review-limits-repositories.png)
1. Select or deselect **Limit to users explicitly granted read or higher access**. ![Limit review in repository](/assets/images/help/repository/limit-reviews-in-repository.png)
