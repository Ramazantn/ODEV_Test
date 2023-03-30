#                                                       ODEV_TestPytest Dekoratörler


    Python Programlama dilinde kullanılan fonksiyonlardan maksimum fayda sağlamak amacıyla bu fonksiyonlar/sınıflar üzerinde yapılan işlemlere Dekoratörler denir.            Dekoratörlerin kullanılmasının amacı daha açık, anlaşılır, kendini tekrar etmeyen ve doğru bir programlama dili oluşturmaktır.
    Pytest Dekoratörlere ilişkin olarak aşağıda bazı örnekler verilmiştir; 


@pytest.mark.timeout:  dekoratörü; yapılan test uygulamasının önceden belirlenen bir zaman içerisinde  bitirilmesi gerektiğini ifade eder.

@pytest.mark.skip: dekoratörü; yapılan test çalışmasında testin çalıştırılmadan atlanılmasını sağlar.

@pytest.mark.parametrize; dekoratörü; testin farklı değişkenler ile kullanabileceğini ifade etmektedir. 

@pytest.mark.xfail; dekoratörü; yapılan testin sonucunun başarısız olmasının öngörüldüğü durumlarda kullanılır.

@pytest.mark.dependency: dekoratörü; bir testin başarılı olmasının diğer teste bağlı olması durumunu belirtir.

@pytest.mark.flaky:  dekoratörü, testin öngörülemeyen sebeplerden dolayı bazen başarısız olabileceği durumu ifade eder.


