---
title: Closing an issue
intro: 'You can close an issue when bugs are fixed, feedback is acted on, or to show that work is not planned.'
permissions: 'Anyone can close an issue they opened.<br><br>Repository owners, collaborators on repositories owned by a personal account, and people with triage permissions or greater on repositories owned by an organization can close issues opened by others. {% data reusables.enterprise-accounts.emu-permission-repo %}'
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Issues
  - Project management
shortTitle: Cerrar una propuesta
---

{% note %}

**Note:** You can also close issues automatically with keywords in pull requests and commit messages. Para obtener más información, consulta la sección "[Vincular una solicitud de extracción a un informe de problemas](/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword#linking-a-pull-request-to-an-issue-using-a-keyword)".

{% endnote %}

{% data reusables.repositories.navigate-to-repo %}
{% data reusables.repositories.sidebar-issues %}
1. In the list of issues, click the issue you'd like to close.
{%- if issue-close-reasons %}
1. Optionally, to change the reason for closing the issue, select {% octicon "triangle-down" aria-label="The down triangle octicon" %} next to "Close issue" and click a reason. ![Screenshot showing dropdown menu containing issue close reasons](/assets/images/help/issues/close-issue-select-reason.png)
2. Click **Close issue**. ![Screenshot showing "close issue" button](/assets/images/help/issues/close-issue-with-reason.png)
{%- else %}
1. At the bottom of the page, click **Close issue**. ![Screenshot showing "close issue" button](/assets/images/help/issues/close-issue.png)
{% endif %}
