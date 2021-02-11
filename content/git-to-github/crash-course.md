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

<dl>
    <dt class="fragment">init</dt>
        <dd class="fragment">creates a new repo</dd>
    <dt class="fragment">clone</dt>
        <dd class="fragment">copies an existing repo from elsewhere</dd>
    <dt class="fragment">branch</dt>
        <dd class="fragment">creates a working copy of local repo</dd>
    <dt class="fragment">checkout</dt>
        <dd class="fragment">switches to a branch from the local repo</dd>
    <dt class="fragment">add</dt>
        <dd class="fragment">adds changes to "staging area" for commit review</dd>
</dl>

{{% /column %}}
{{% column %}}
<dl>
    <dt class="fragment">commit</dt>
        <dd class="fragment">creates a "log entry" of the changes made</dd>
    <dt class="fragment">push</dt>
        <dd class="fragment">upload changes to a remote repo</dd>
    <dt class="fragment">pull</dt>
        <dd class="fragment">download changes from a remote repo</dd>
    <dt class="fragment">merge</dt>
        <dd class="fragment">combine changes from branches, forks, or commits</dd>
    <dt class="fragment">remote</dt>
        <dd class="fragment">access repos connected to the local one</dd>
</dl>
{{% /column %}}
{{% /columns %}}

---

<div class="mermaid fragment">
graph LR
    files[Make changes to project]-->|add|add[Add changes to staging area]
    add-->|commit|commit[Save changes to repo]
    commit-->|edit|files
</div>

{{< columns >}}
<div class="mermaid fragment">
graph
    branch[Branch project to work]-->|edit|files[Make changes to project]
    files-->|add|add[Add changes to staging area]
    add-->|commit|commit[Save changes to repo]
    commit-->|merge|merge[Combine changes with original branch]
    merge-->|branch|branch
</div>

<div class="mermaid fragment" style="padding-top: 5rem;">
graph
    remote[Remote copy]-->|pull|local[Local copy]
    local-->|push|remote
    local-->|edit|files[Do work]
    files-->|commit|local
</div>
{{< /columns >}}

---

## GUI Tools

{{< fraglist >}}
Github Desktop
VSCode
Meld
Sublime Merge
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