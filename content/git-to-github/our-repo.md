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

{{% columns %}}
{{% fragment %}}![](/img/master.jpg){{% /fragment %}}

{{% fragment %}}![](/img/main.jpg){{% /fragment %}}
{{% /columns %}}

{{% typed %}}
git config --global init.defaultBranch main
{{% /typed %}}

---

## Step 3: Making Our First Commit

{{% typed %}}
git add .
{{% /typed %}}

{{% typed %}}
^250 git commit -m "First commit"
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
git push
{{% /typed %}}

---

## Step 6: Pulling Changes

{{% typed %}}
git pull
{{% /typed %}}

{{% /section %}}
