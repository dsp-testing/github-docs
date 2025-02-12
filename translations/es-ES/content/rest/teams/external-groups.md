---
title: Grupos externos
intro: The External groups API allows you to view the external identity provider groups that are available to your organization and manage the connection between external groups and teams in your organization.
versions:
  fpt: '*'
  ghae: '*'
  ghec: '*'
topics:
  - API
miniTocMaxHeadingLevel: 3
---

## About the External groups API

Para utilizar esta API, el usuario autenticado debe ser un mantenedor del equipo o un propietario de la organización asociada con éste.

{% ifversion ghec %}
{% note %}

**Notas:**

- The external groups API is only available for organizations that are part of an enterprise using {% data variables.product.prodname_emus %}. Para obtener más información, consulta la sección "[Acerca de los Usuarios Empresariales Administrados](/admin/authentication/managing-your-enterprise-users-with-your-identity-provider/about-enterprise-managed-users)".
- Si tu organización utiliza la sincronización de equipos, puedes usar la API de Sincronización de Equipos. Para obtener más información, consulta la "[API de sincronización de equipos](#team-synchronization)".

{% endnote %}
{% endif %}
