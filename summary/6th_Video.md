# 6th Video : Git Branch & Merge
![Main View](../assets/BranchandMerge.png)

## Table of Content
1. [Git Command for Branch](#git-command-for-branch)
2. [Jenis Merge](#jenis-merge)
3. [Git Command for Merge](#git-command-for-merge)

## Git Command for Branch
```shell
$ git branch <nama_branch> //Membentuk branch baru
```
```shell
$ git branch //Melihat branch yang ada
```
```shell
$ git log //Menampilkan history commit
```
```shell
$ git log --all --decorate --oneline --graph //Menampilkan log dalam grafik
```
```shell
$ alias <name_alias> = "command" //Memberikan alias pada command
```
```shell
$ git checkout <nama_branch> //Berpindah branch
```
```shell
$ git branch -d <nama_branch> //Melakukan delete branch
```

## Jenis Merge
1. Fast Forward
<br>
Terjadi ketika branch yang ingin digabungkan berada dalam direct path.
2. Three-Way Merge
<br>
Menggunakan commit khusus untuk menggabungkan kedua histories.

## Git Command for Merge
```shell
$ git merge <nama_branch> //Melakukan merging branch
```