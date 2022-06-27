---
Adı: Microsoft Office 2019 Tool By RavenB
about: Office Deploy Tool aracı, setup.exe dosyasına ihtiyaç duymadan çevrimdışı Office
  2019 yüklemek için kullanılan otomatikleştirilmiş bir komut dosyasıdır.
Başlık: Özellikler

Office Deploy Tool aracı, setup.exe dosyasına ihtiyaç duymadan çevrimdışı Office 2019 yüklemek için kullanılan otomatikleştirilmiş bir komut dosyasıdır. NOT 1: Office Deploy Tool aracı ile sadece Volume kanalı ile yükleme yapılabilir, RETAIL kanalı ile yükleme yapılamaz. NOT 2: OfficeVL.cmd dosyası otomatik yönetici modunda çalışır, çift tıklamanız yeterlidir.


Ürün Paketlerini veya tek uygulamaları ayrı ayrı yükleyebilirsiniz. Birden fazla dilde ayrı ayrı veya birlikte kurulum yapabilirsiniz. (en fazla 9 dil) Kurulum sonrası bazı ayarları (etkinleştirme-güncelleştirme vb.) kurulum öncesinde belirleyebilirsiniz. OfficeVL.cmd dosyasını kaynak klasörün yanında çalıştırdığınızda otomatik algılayacaktır.

Ya da Office 2019 ISO dosyasını bilgisayarınızda sanal sürücüye ekleyip OfficeVL.cmd dosyasını çalıştırdığınızda otomatik olarak ISO dosyasının veya CD/DVD sürücüsünün harf yolunu otomatik algılayacaktır. OfficeVL.cmd dosyasını haricen çalıştırdığınızda sizden kaynak yolu girmeniz istenir. Burada önemli olan nokta Office kurulum klasörünün yolunu değil, Office kurulum klasörünün içinde olduğu dizin ya da klasör yolu girilmelidir. Örneğin: Office kurulum klasörü D:\Office olsun. Kurulum yolu istenildiğinde D:\Office yerine sadece D:\ yolu girilmesi gerekir.

Ya da OfficeVL.cmd dosyasını direkt Office iso dosyasının içine ekleyerek de kullanabilirsiniz. Böylece daha sonraki kurulumlarınızda kurulum/dizin yolu girmenize gerek kalmaz.

Kaynak klasörde birden fazla Office sürümü algılanırsa, sadece birisini seçebilirsiniz. Yani kaynak klasörde Office 365 ve Office 2019 var ise sadece birinin kurulumunu yapabilirsiniz. Kaynak klasörde birden fazla dil algılanırsa, birini veya tümünü seçebilirsiniz(en fazla 9 dil).

Tüm dilleri seçtiyseniz birincil dil seçmeniz istenir.

Office Deploy Tool ile Windows 7 ve 8.1 üzerinde de Office 2019 kurulumu yapabilirsiniz,böyle bir durumda "Program ve Özellikler" deki ürün kimliği Office 2016 gözükecektir ancak Office 2019 lisansları kullanılacaktır.

Otomatik Etkinleştirme seçeneği şu durumlarda çalışır:

Eğer bilgisayarınızda Windows önceden KMS Inject yöntemi ile etkinleştirilmiş ve KMS Görev Zamanla da etkin ise veya orijinal KMS sunucuları ile etkinleştirlmiş ise kurulum sonrasında da Office 2019 otomatik etkinleştirilecektir.
