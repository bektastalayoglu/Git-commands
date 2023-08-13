# GIT COMMANDS

-----------------------

git diff  /   git difftool   : staging area ile working directory arasındki farkları görebiliriz.

--------------------

git diff HEAD  : working directory ile son commit arasındaki farkları görebiliriz.

--------------------

git diff --staged HEAD : staging area ile remote arasındaki değişikler
git diff --cached

--------------------

git diff -- <file_name>  : Birden fazla working directory de değiştirdiğin file var ve bunlarında birinde yapılan değişiklikleri görmek için

--------------------

git diff <commitid_1> <commitid_2> : 2 commiti karşılaştırmak için kullanılır.

---------------------

git diff HEAD^ HEAD : son committen bir önceki commit ile son commiti karşılaştırır.

---------------------

git diff master origin/master : Local branch ile remote branch karşılaştırır.

----------------------

mv <old_file_name> <new_file_name>  : Bir file ismini değiştirmek için

---------------------

ls -al  : gizli dosyaları gösterir.

---------------------

git commit -am "message"  : add ve commit işlemini aynı anda yapmak için

----------------------

git ls-files  : tracked edilen fileları görebiliriz

----------------------

git reset HEAD <file_name>  : Bir değişiklik yaptık ve onuda add ile staging area'ya ekledik. Ama sonra düşündük ki o değişikliği istemiyoruz. Geri almak için.

----------------------

git checkout -- <file_name> : Sonra bu değişikleri silip önceki commite dönmek için

----------------------

git mv <current_file_name> <new_file_name> : rename yapmak

-----------------------

git mv <file_name> <folder_name> : Bir file'ı başka bir foldera taşımak için. İçi içe ise önceki foldera taşımak için .. yeterli.

-----------------------

git rm <file_name>  : Track olan bir file silmek için.

-----------------

git reset HEAD <file_name>
git checkout -- file_name    : sildik ama geri almak için

------------------

git log --abbrev-commit : Logları verir ve commitleri numaralarını kısaltır.

-------------------

git log --oneline   : Bir lineda commitleri gösteriri.

-------------------

git log -- <file_name> : spesifik bir filedaki loglara bakmak için

------------------

git show <commit_id> : committe yapılan değişiklikleri gösterir.

-------------

cp <kopyalanacak_file_adi> <yeni_file_adi>  : Bir fileı copy etmek

-------------
END






