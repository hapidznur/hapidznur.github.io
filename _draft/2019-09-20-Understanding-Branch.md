---
layout: post
title:  "Understanding Branch"
author: "hapidznur"
categories: journal
tags: [documentation,git]
image: spools.jpg
---


Tulisan ini lanjutan dari kelas git dari @dloreno pertengahn agustus lalu.

Untuk memahami tulisan ini dibutuhkan:
- Git [Branch](https://git-scm.com/book/en/v1/Git-Branching-What-a-Branch-Is)


Misal nya terdapat master seperti pada gambar dibawah.
![Master Branch](/assets/img/master_branch.png)

Kemudian buat branch baru bernama `feature` dari commit terakhir. 
```
git branch feature
```
![Feature Branch](/assets/img/featue_branch.png)

Nah sekarang HEAD pointer ada branch master.
![HEAD Branch](/assets/img/HEAD.png)

Kemudian checkout untuk berganti branch `feature` yang otomatis mengganti HEAD dari master ke feature.
![HEAD Feature Branch](/assets/img/HEAD_feature.png)

Nah misalkan nambah sebuah file yang sedang dikerjakan.

```
vim nitip.md
git add nitip.md
git commit -m "daftar pesanan makanan anak kantor"
```


Pustaka:
1. [Dloreno Presentation](https://docs.google.com/presentation/d/1d_ZoCUZdABJJCH6wLeIeyw0ND2CEmRLQmc-XdzwM-KQ/edit#slide=id.g34d24d4cfd_0_51)
