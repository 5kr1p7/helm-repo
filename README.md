# 5kr1p7's Helm repository

Add repository: `helm3 repo add 5kr1p7 https://5kr1p7.github.io/helm-repo/`

Available packages: `helm3 search repo 5kr1p7`

---

Update packages: `cd repo && helm3 repo index --url https://5kr1p7.github.io/helm-repo/ --merge index.yaml . && git commit -am "Update" && pit push`
