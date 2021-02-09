+++
weight = 4
outputs = ["Reveal"]
+++

{{% section %}}

# Essentials Crash Course

---

## Git Commands

{{% columns class="two" %}}
{{% column %}}
- init
    - creates a new repo
- clone
    - copies an existing repo from elsewhere
- branch
    - creates a working copy of local repo
- checkout
    - switches to a branch from the local repo
- add
    - adds new files to repo

{{% /column %}}
{{% column %}}

- commit
    - creates a "log entry" of the changes made
- push
    - upload changes to a remote repo
- pull
    - download changes from a remote repo
- merge
    - combine changes from branches, forks, or commits
- remote
    - access repos connected to this one

{{% /column %}}
{{% /columns %}}

---

[chart of how git works, conceptually, with terms]

---

## GUI Tools

{{< fraglist >}}
Github Desktop
VSCode
{{< /fraglist >}}

---

## Authentication Options

<ul>
    <li class="fragment">Password
        <ul>
            <li class="fragment">...uses a password</li>
            <li class="fragment">Uses the `https://` protocol</li>
        </ul>
    </li>
    <li class="fragment">SSH
        <ul>
            <li class="fragment">Passwordless
            <li class="fragment">Uses `ssh://` protocol
        </ul>
    </li>
</ul>

{{% /section %}}
