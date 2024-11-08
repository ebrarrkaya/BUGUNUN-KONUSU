# Standart Girdi Alma Fonksiyonu Nedir?
Kullanıcılara klavye verisi girmesi için kullanılan fonksiyona denir. input() ismidir. Kullanımı oldukça basittir. Kullanımı, degisken_adi:input() şeklindedir. Kullanıcı veri girene kadar sonlanmaz. Parantez içerisine metin girerek kullanıcıya girilmesi istenen veri hakkında bilgi verilebilir. Ancak bu bilgiler değişkene atanmaz.

Örnek:

matematik,kimya,biyoloji,fizik,ingilizce=96,97,98,99,100
print("matematik:{} kimya:{} biyoloji:{} fizik:{} ingilizce:{}".format(matematik,kimya,biyoloji,fizik,ingilizce))
print("{matematik}{kimya}".format(matematik=96, kimya=97))
print("{0} {1}".format("a","b"))
isim=input("Lutfen isim giriniz:")
print("Kullanicinin girdigi deger:{}".format(isim))

<a href="https://github.com/ebrarrkaya/BUGUNUN-KONUSU/blob/7761a60b9fa0f318abfe0a1b4d2e5413fde1451a/bbb.png">Çıktısını görmek için tıklayınız</a>
