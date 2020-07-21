# Git and Github Cheat Sheet

> Kurulum

```
  git config —global user.name “Nejdet”
  git config —global user.email “neco@gmail.com”
```

> Dosyaya repository kurar

```
git init 
```
> Dosyaları staging area ya gönderir.

```
git add . 
```
> Staging area dan repository ye aktarır

```
git commit -m “ ”
```
> git dosyasının statüsünü gösterir.

```
git status
```
> Repositorye eklediğimiz çalışmaları gösterir.

```
git log 
git log --oneline
```
> Dosya silmemizi sağlar

```
git rm First.py
```
> Klasörü repositoryden silmemizi sağlar

```
git rm -r klasörünadı
```
> Dosyada yaptığımız değişiklikleri gösterir.

```
git diff
```
>Dosya adı değiştirmemizi sağlar.

```
git mv First.py Second.py
git commit -m “first.py -> second.py”
```
> Dosya konumunu değiştirmeyi sağlar.

```
git mv First.py konum/
git commit -m “First.py -> konum/First.py”
```
> Silinen dosyayı geri getirir.

```
git checkout -- dosyaadı
```
> Staging area dan dosyayı geri getirme.

```
git reset HEAD dosyaadı
git checkout -- dosyaadı
```
> Eski commit e geri götürür.

```
git checkout commitnumarası -- .
git reset 9f61644 --hard
git reset 9f61644 --soft
```
> Commitde değişiklik yapmaya sağlar.

```
git commit --amend
git commit --amend -m 'değiştirmek istediğiniz isim'
```
> Git stash komutları

```
git stash
git stash list
git stash pop
git stash apply stash@{2}
git stash drop stash@{2}
```
> Git Alias komutları

```
git config --global alias.co 'commit -m'
git config --list
```


