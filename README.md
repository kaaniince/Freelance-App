# Freelancer Web Site

## Nasıl Kurulacak?

Uygulama dosyalarını yüklediğinizde veya githup üzerinden fork ettiğinizde bu uygulamayı kullanmaya başlayabilirsiniz. SUnucunuz veya bilgisayarınıza dosyaları indirdiğinizde, hangi klasör üzerinde çalışacak ise tüm dosyaları o klasöre taşıyın.

- Komut satırını açın ve komut satırı üzerinden projenizin olduğu dizine gidin.
- `npm init` komutu ile uygulamayı başlamak için hazırlayın.
- **.env** dosyasında **APP_MONGODB_DB_NAME=veri_tabani_adi**, **APP_MONGODB_FULL_URL=veritabani_tam_url** ve **APP_SESSION_SECRET_KEY=** alanlarını doldurun.
- `node app` komutu ile uygulamanızı çalıştırın.

## Installation

Öncelikle projeyi clonelayın.

```
git clone https://github.com/kaaniince/Freelance-App.git
```

## Usage

Projeyi cloneladıktan sonra Visual Studio Code programında açınız.

Linux için:

```
cd Freelance-App
code .
```

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Kullanılan Teknolojiler

- Express JS
- Bootstrap
- Mongodb
- express-session
- express-fileupload
- express-validator
- randomstring
- mongoose
- bcrypt
- dotenv
- ejs
