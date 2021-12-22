# ATTENTION

[maaf tapi git saya selalu crash saat ingin melakukan push dan setelah tidak menemukan solusi alhasil saya memasukkan master branch saya yang ter update di link gdrive ini]

https://drive.google.com/file/d/1L4msXlbohhRkTDRlgcw564b4ecReRVNo/view?usp=sharing

[sekali lagi saya minta maaf]

# THE POKE GUIDE

## Ahmad Al Ghiffari/1710817210001

## Tentang

Website yang berisi tentang Guide mengenai game Pokemon.
Dibuat dan dijalankan untuk pembelajaran MK Web Framework menggunakan [Laravel 8][1]

## Instalasi

1. Requirements:
    - [PHP][2] >= 7.3
    - [Composer][5]

2. Clone repository melalui git terminal ke direktori yang diinginkan:
            
        git clone git@github.com:RayClust/PokeGuideWebsite.git

3. Instalasi dependencies PHP dengan [Composer][5]:

        composer install

4. Buat key baru setelah membuat file .env dari .env.example yang tersedia:

        php artisan key:generate

4. Migrate data ke database kosong dengan nama yang sesuai dengan .env

        php artisan migrate
        
6. Jalankan web dan akses ke address yang dijalankan:

        php artisan serve

[1]: https://laravel.com "Laravel"
[2]: https://www.php.net "PHP"
[5]: https://getcomposer.org "Composer"
