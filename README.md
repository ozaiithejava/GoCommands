# GoCommands
go commands list

```bash
# go run komutu, belirtilen Go dosyasını derler ve doğrudan çalıştırır.
go run dosya.go

# go build komutu, belirtilen Go dosyasını derler ve çalıştırılabilir bir dosya oluşturur.
go build dosya.go

# go get komutu, belirtilen GitHub kullanıcısına ait paketi yükler.
go get github.com/kullanici/paket

# go install komutu, belirtilen paketi yükler ve çalıştırılabilir dosyayı $GOPATH/bin dizinine kurar.
go install paket

# go mod init komutu, mevcut bir projeyi modüler hale getirir ve go.mod dosyası oluşturur.
go mod init modul_adi

# go mod tidy komutu, projedeki modül bağımlılıklarını temizler ve go.mod ve go.sum dosyalarını günceller.
go mod tidy

# go test komutu, test dosyalarını çalıştırır.
go test

# go fmt komutu, belirtilen Go dosyasındaki kodu otomatik olarak biçimlendirir.
go fmt dosya.go

# go doc komutu, belirtilen paketin belgelendirme bilgilerini gösterir.
go doc paket

# go version komutu, yüklü Go sürümünü gösterir.
go version
```
