İlk olarak github dosyalarimizi cekecegimiz dosyayi olusturuyoruz 
Dosyanin icindeyken vscode aciyoruz
Kullanmak istedigimiz uzak repodaki kodu kopyaliyoruz 
Git clone (repodan kopyalanan code) bu komut ilk defa uzak repoyu kendi lokalimize indiriyor 
Lokalinizdeki dosyayi kontrol edin uzak repodaki tum dosyalar gelmis olacak
Dosyanizin icinde gizli dosya halinde git dosyasi gormuyorsaniz Bir dosyayi git reposu haline getirmek icin kullanilan git init komutunu girin (git clone komutunu kullandiginiz icin buna gerek olmayacaktir)
Git pull komutuyla uzak repodaki yapilan tum degisiklikleri kendi local repoma cekebilirim
Git branch burcu yeni bir branch olusturmak icin kullaniyoruz 
Takim calismasi yapacagimiz icin ve takim arkadaslarimizin yaptigi tum degisikliklerin master branchda görünmemesi icin kendimize yeni bir branch olusturmamiz sart .Fakat takim arkadaslarimiz uzak repodan bizim branchimize girerek yaptigimiz degisiklik ve katkilarimizi gorebilecekler
Git checkout burcu komutuyla kendi branchimize geciyoruz
Deneme icin kendi branchimin icindeyken  adima olusturulan dosyanin icine birseyler atiyorum yada icinden birseyler siliyorum.Bu yaptigimiz bir degisiklik oldugu icin versiyonlamamiz gerekecek 
Git add . 
Git commit -m “ bla bla ”
Degisikliklerimi bu sayede work spaceden stage area sonrasinda commit store atmis oluyorum
Git push --set --upstream origin burcu local repomdan uzak repoya ilk defa itme islemi yaptigimda kullanacagim komut 
Bu ismemi yaptiktan sonra uzak repoma baktigimda pull request ekrani gormus olacagim(Yani uzaktaki repomdan local repoda yaptigim degisiklikleri cekmis olacagim) yönlendirmeleri takip ediyorum ve merge islemi tamamlanmis oluyor
Uzak repoda pull request islemini yapmak benim kendi branchimde yaptigim degisikligi master branche merge etmek demek oluyor.(Bu istedigimiz bir islem degil takim halinde calisacagimiz icin deneme amacli yapabilirsiniz.Kaydettigini kaldirmak yada silmek islemide bir degisiklik oldugundan kendi brachiniza gectikten sonra uyguladigimiz tum adimlari tekrar ederek masterdaki degisikligi kaldirabilirsiniz)Ama takim halinde oldugumuz icin kendi branchimde calismalarimi yapiyorum
Master a degil sadece kendi branchinize degisiklikleri kaydetmek istiyorsaniz; kendi branchinizdeyken degisikligi yapip versiyonlayip itmeniz yeterli olacaktir
Degisiklik yap
Git add .
Git commit -m “ bla bla ”
Git push

Git push bundan sonraki tüm uzak repoya itme islemlerini bu komutla yapabilirim
Git pull master branchinde iken git pull ile takim arkadaslarimizin yaptigi tum degisiklikleri localime cekebilirim
Git merge master kendi branchimde iken masterda yapilan tum degisiklikleri lokalimdeki kendi branchime cekmis olurum
 
