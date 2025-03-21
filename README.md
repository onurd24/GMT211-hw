# README.md - Git/GitHub Kullanımı

## Proje Açıklaması
Bu proje, Git ve GitHub kullanımını öğrenmek ve uygulamak amacıyla oluşturulmuştur. README.md dosyası, projenin genel yapısını, kullanılan Git komutlarını ve sürecin nasıl ilerlediğini açıklar.

---

## README.md Dosyasını Nasıl Oluşturduk?

### 1. Yerel Depo (Local Repository) Oluşturma
Aşağıdaki komut ile mevcut dizinde bir Git deposu başlattık:
```bash
git init
```
Bu komut, proje klasörümüzü bir Git deposuna dönüştürdü.

### 2. README.md Dosyasını Ekledik
Dosyayı oluşturmak için şu komutu kullandık:
```bash
touch README.md
```
Alternatif olarak manuel olarak dosya oluşturulabilir.

### 3. Dosyayı Git'e Ekledik ve Commit Yaptık
Öncelikle dosyayı takip edilmesi için ekledik:
```bash
git add README.md
```
Daha sonra değişiklikleri commit ettik:
```bash
git commit -m "README dosyası eklendi"
```

### 4. GitHub’a Yükleme (Push İşlemi)
GitHub üzerinde bir repository oluşturduktan sonra aşağıdaki komutlarla değişiklikleri GitHub’a gönderdik:
```bash
git remote add origin https://github.com/kullanici-adi/proje-adi.git
git branch -M main
git push -u origin main
```

---

## Git ve GitHub İş Akışı Arasındaki Farklar

| **Yerel Git (Local Repository)** | **GitHub (Remote Repository)** |
|-------------------------|--------------------------|
| Değişiklikler bilgisayarda saklanır. | Değişiklikler çevrimiçi olarak GitHub’da saklanır. |
| Commit ve branch işlemleri yerel olarak yapılır. | Takım çalışması için paylaşım yapılır. |
| İnternet bağlantısı gerekmez. | İnternet bağlantısı gereklidir. |

---

## Karşılaşılan Zorluklar ve Çözümleri

- **Hata:** `fatal: pathspec 'README.md' did not match any files`
  - **Çözüm:** Dosyanın var olup olmadığını kontrol ettik ve `git add README.md` komutunu çalıştırdık.

- **Hata:** `nothing to commit, working tree clean`
  - **Çözüm:** Tüm değişikliklerin commit edildiğini gördük ve yeni değişiklikler ekleyerek sürece devam ettik.

![foto](https://github.com/onurd24/GMT211-hw/blob/master/img/IMG_2889.jpg)
