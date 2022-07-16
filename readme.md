# Visual Studio Code Editörü Kullanım Rehberi

Yazılım geliştirmede bu artan talep ve büyüme karşısında geliştiricilerin hızlı bir şekilde verimli uygulamalar oluşturmasına yardımcı olmak için doğru geliştirme araçlarına ve ortamlarına ihtiyaç var. Tıpkı Visual Studio Code Editor gibi…
belli basli IDE ler sunlardir
<a>cd  

Visual Studio Code Nedir?

## image

Visual Studio Code, Windows, Linux ve macOS için bir kaynak kodu düzenleyicisidir. Microsoft tarafından geliştirilen bu araç hem kişisel hem de ticari kullanım için yüzde 100 ücretsizdir. Tek yapmanız gereken aracı indirmek, yüklemek ve kodunuzu yazmaya başlamaktır.

Çoğu donanım ve yazılım yapılandırmasında çalışan Visual Studio Code için Microsoft’un önerdiği tek şey 1,6 GHz veya daha hızlı bir işlemci ve 1 GB RAM’dir. Windows 7 kullanıyorsanız, Microsoft .NET Framework 4.5.2’ye de ihtiyacınız olacaktır.

Diğer bir önemli husus ise, Visual Studio Code’nin her ay daha fazla özellik ve hata düzeltme içeren yeni bir sürüm yayınlamasıdır. Çoğu platform otomatik güncellemeleri desteklediğinden, en son sürümler kullanıma sunulur sunulmaz yüklenir. İstediğiniz zaman güncellemeyi tercih ederseniz, bu otomatik güncellemeleri devre dışı bırakmayı seçebilirsiniz.

Visual Studio Code’un Özellikleri Nelerdir?
Visual Studio Code, kullanımı kolaylaştıran ve aynı zamanda kısa sürede birinci sınıf uygulamalar oluşturmanıza yardımcı olacak kadar güçlü bir dizi özellikle birlikte gelir. 

# İşte Visual Studio Code’nin bazı önemli özellikleri:

Windows, Linux ve macOS gibi birçok işletim sisteminde iyi çalışır.
Desteklenen tüm diller için sözdizimi vurgulama, parantez eşleştirme ve daha fazlasını sağlayarak yüzlerce programlama dilini destekler.
Sezgisel klavye kısayollarına sahiptir.
Kod tamamlama için yerleşik destek içerir.
Kolay özelleştirme, kodunuzda kolayca gezinmenize yardımcı olur.
Kod yeniden düzenlemeyi destekler.
Etkileşimli hata ayıklayıcısı, kodunuzu hızla gözden geçirmenize, değişkenleri kontrol etmenize ve daha pek çok şeye olanak tanır.
Açık kaynak kodlu olduğu için siz de gelişimine katkıda bulunabilirsiniz.
Node.js, JavaScript, TypeScript, JSX/React, HTML, CSS, JSON ve daha fazlası için yerleşik desteğe sahiptir.
Web teknolojilerini yerel uygulamalarla birleştirmek için Electron API’lerini kullanır.
Bir sürü üçüncü taraf uygulama yükleyebilirsiniz. Kutudan çıktığı gibi çalışma eğilimindedir, bu nedenle yapılandırmalar hakkında endişelenmenize gerek yoktur.
Düzenleyiciyi kişisel tercihinize göre özelleştirmenize veya optimize etmenize olanak tanır. 
Taşınabilir bir sürümü vardır, böylece nerede sakladığınızdan bağımsız olarak verilerinizi ve ayarlarınızı bozulmadan tutabilirsiniz. 
Dosyalarda yapılan kaydedilmemiş değişiklikleri hatırlar ve bunları yedekte saklar. 
Dilerseniz otomatik kaydetmeyi açabilirsiniz. 
Açılan klasörde bulunan dosyalar arasında arama yapmayı destekler. 
Hızlı düzenlemeler için çoklu imleçleri destekler. Ayrıca Ctrl + Alt + Aşağı, Ctrl + Alt + Yukarı veya başka herhangi bir özel kısayolu da kullanabilirsiniz.
Ortak görevleri otomatikleştirmek için komut satırında derleme ve komut dosyası oluşturma araçlarıyla iyi bir şekilde bütünleşir.
Geliştiricilerin uzantılar oluşturmasına ve özelleştirmesine izin vermek için genel bir genişletilebilirlik modeline dayanır.
Gördüğünüz gibi, Visual Studio Code, geliştiricilerin hızlı bir şekilde uygulamalar oluşturmasına yardımcı olacak bir çok özellik ile birlikte gelir.

Peki bu aracı nasıl kullanacaksınız?

## image

# Visual Studio Code Nasıl Kullanılır?

Visual Studio Code’u kullanmaya başlamak oldukça kolaydır. Öncelikle, indirmek için Windows, macOS ve Linux bağlantılarına tıklayın. Bu araç oldukça küçük olduğundan, hızlı bir şekilde indirilir ve bant genişliğinizi tıkamaz.

Ardından, indirilen dosyaya çift tıklayın, Çalıştır’ı (Run) seçin ve sihirbazı (wizard) takip edin.

Yükleme sırasında ek bileşenler, uzantılar ve araçlar yüklemeyi seçebilirsiniz. Yaygın olarak kullanılan bazı bileşenler, GitHub ile entegrasyon için Git, JavaScript uygulamalarını çalıştırmak için Node.js ve TypeScript’i JavaScript’e dönüştürmek için TypeScript’tir.

Kod uzantılarına gelince… Pazardaki yüzlerce taneden birini seçebilirsiniz. Visual Studio Code ile iyi entegre olan araç zincirlerinden bazıları; Yeoman, generator-aspnet, Express, Gulp, Mocha, Yarn’dır.

1. Ayarları özelleştirin
Size kolaylık sağlaması için Visual Studio Code ile her bir yönü özelleştirebilirsiniz (kullanıcı ayarları ve çalışma alanı ayarları).

Kullanıcı ayarları, herhangi bir yerden açtığınız her Visual Studio Code örneğine uygulanan özelleştirmelerdir. Buna karşılık, çalışma ayarları belirli bir çalışma alanının özelleştirmeleridir ve bunlar yalnızca çalışma alanının bulunduğu belirli cihaz için geçerlidir.

Ayrıca, bu çalışma alanı ayarları bir projeye özeldir ve aynı proje üzerinde çalışan diğer kişilerle paylaşılabilir. Bu çalışma alanı ayarlarının her zaman kullanıcı ayarlarını geçersiz kılacağını, unutmamanızda fayda vardır.

Bu ayarları görüntülemek ve özelleştirmek için Windows ve Linux’ta File > Preferences > Settings (Dosya > Tercihler > Ayarlar) ve macOS’ta Code >Preferences > Settings’e (Kod >Tercihler > Ayarlar) gidin. Sol bölmede, yaygın olarak kullanılan tercihlerin bir listesini göreceksiniz, daha fazla özelleştirme için her birine tıklayın.

Belirli ayarlar için, istediğiniz ayarı aramak ve keşfetmek için Setting Editor’ü açın ve bunları tercihlerinize göre özelleştirin. Dile özgü ayarları da değiştirebilirsiniz.

2. Klavye kısayollarını ayarlayın

Kullanıcı ve çalışma ayarlarını yaptıktan sonra klavye kısayollarını ayarlamak isteyebilirsiniz. Bu değişiklikleri istediğiniz zaman yapabilecek olmanıza rağmen, daha sonra üretkenliğinizi artırmak için tam kurulum sırasında yapmanız önerilir.

Visual Studio Code, tüm komutları ve ilişkili klavye kısayollarını listeleyen bir klavye kısayolları düzenleyicisiyle birlikte gelir. Tercihlerinize göre bunları her zaman değiştirebilir veya kaldırabilirsiniz.

Bu klavye düzenleyiciye Windows ve Linux’ta File > Preferences > Keyboard Shortcuts (Dosya > Tercihler > Klavye Kısayolları) ve macOS’ta Code > Preferences > Keyboard Shortcuts (Kod > Tercihler > Klavye Kısayolları) aracılığıyla erişebilirsiniz.

3.  Telemetri
Son olarak, telemetri hakkında biraz konuşmakta fayda var.

Microsoft varsayılan olarak ürününü geliştirmek için kullanımınızla ilgili verileri toplar. Güncelleştirmeleri Microsoft’a göndermemeyi seçerseniz, devre dışı bırakabilirsiniz.

Bunu yapmak için  (File > Preferences > Settings) Dosya > Tercihler > Ayarlar’a gidin ve “telemetri”yi arayın. “Telemetry: Enable Telemetry (Telemetri: Telemetriyi Etkinleştir)” seçeneğinin işaretini kaldırın. Bu, Visual Studio Code’un Microsoft’a daha fazla veri göndermesini durduracak, ancak zaten gönderilmiş olan verileri silmeyecektir.

JSON düzenleyicisi aracılığıyla da değiştirebilirsiniz. Bunun için kod:

"telemetry.enableTelemetry": false

## image