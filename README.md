# pytest_docarat-rler
PYTEST DEKARATÖRLERİ
En sık kullanılanları şunlardır:
1)	@pytest.mark.skip(reason: “testi atlama sebebi yazılır”): şartsız test atlatmak için kullanılır.
2)	@pyest.mark.skipif(koşul,sonuç) : koşula bağlı olarak test atlamak için kullanılır. Koşul sağlanıyorsa testi atlatır.
3)	@paytest.mark.parametrize(): Aynı test fonksiyonunu farklı parametrelerle birden fazla kez çalıştırmak için kullanılır. Testlerinizi daha kapsamlı hale getirmenize ve farklı durumlarda farklı sonuçlar alıp almadığınızı kontrol etmenize olanak tanır.
Örnek:
@paytest.mark.parametrize("username,password",[("standard_user","secret_sauce"),("problem_user","secret_sauce")])
4)	@pytest.mark.xfail: başarısız olacağı bilinen testler için kullanılır

        
