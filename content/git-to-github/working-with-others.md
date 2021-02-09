+++
weight = 6
outputs = ["Reveal"]
+++

{{% section %}}
# Working With Others

---

## Forks vs Branches

{{% columns %}}
{{% column %}}
Branches
- Dependent on repo
- Inextricably linked
- Closely related to repo
- Intended to be merged back into main branch (usually)
{{% /column %}}

{{% column %}}
Forks
- Based off a parent repo
- Separate/independent
- Not necessarily related after forking
- Merging back to parent optional

{{% /column %}}
{{% /columns %}}

{{% note %}}
See also: OpenOffice/LibreOffice
{{% /note %}}

---

## Ownership/Source Of Truth Change

{{% columns %}}
[personal; local -> remote]

[fork; local -> remote -> upstream]
{{% /columns %}}

---

## Workflow Change

{{% columns %}}
Branch:
![](/img/git-flow.png)

Fork:
![](/img/git-flow-forks.png)
{{% /columns %}}

<span class="credit">Image source: https://training.github.com</span>

{{% /section %}}
