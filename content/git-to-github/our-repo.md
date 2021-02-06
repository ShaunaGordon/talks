+++
weight = 5
outputs = ["Reveal"]
+++

{{% section %}}
# Creating & Managing Our Own Repository

---

## Step 1: Create In Github

{{% note %}}
Switch to Github tab.
{{% /note %}}

---

## Step 2: Initialize Local Repo

{{% typed %}}
git init
{{% /typed %}}

---

### 2a: Tweaking Git's Default Branch Name

![](/img/master.jpg)

![](/img/main.jpg)

---

{{% typed %}}
git config --global init.defaultBranch main
{{% /typed %}}

---

## Step 3: Making Our First Commit

{{% typed %}}
^1000 git add .
{{% /typed %}}

{{% typed %}}
^2500 git commit -m "First commit"
{{% /typed %}}

---

## Step 4: Connecting Local & Remote

{{% typed %}}
git remote add origin [Github repo url]
{{% /typed %}}

---

## Step 5: Push To Remote

{{% typed %}}
git push -u origin main
{{% /typed %}}

{{% typed %}}
^2500 git push
{{% /typed %}}

---

## Step 6: Pulling Changes

{{% typed %}}
git pull
{{% /typed %}}

{{% /section %}}
