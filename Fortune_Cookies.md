# Fortune Cookies

## About Challenge
Challenge ini menuntut kita untuk mempelajari terkait cara kerja cookie di sebuah website

![Foresty Hacker Class - Google Chrome 15_06_2023 15_00_22](https://github.com/mirandadewi/CTF-Write-Up/assets/136687271/d82ebd2f-596e-4037-b8e5-e3cc419f8725)

## Solutions
Challenge ini memberikan sebuah website :

![Foresty Hacker Class - Google Chrome 15_06_2023 15_02_34](https://github.com/mirandadewi/CTF-Write-Up/assets/136687271/17f3b157-d962-4b6c-8076-9375bc7ee227)

Jika kita menekan tombol 'Get Your Fortune Cookies' maka tampilan akan berubah menjadi :

![Foresty Hacker Class - Google Chrome 15_06_2023 15_02_56](https://github.com/mirandadewi/CTF-Write-Up/assets/136687271/6c8d988c-36d8-4341-9aca-d445156b28b1)

Mari lihat cookiesnya menggunakan cookie editor :

![Foresty Hacker Class - Google Chrome 15_06_2023 15_03_06](https://github.com/mirandadewi/CTF-Write-Up/assets/136687271/7793f1c2-fb87-4415-a419-8ebe6b89b814)

Terdapat satu cookie yang mencurigakan yaitu cookie 'flag' mari ubah valuenya dari 0 ke 1

![Foresty Hacker Class - Google Chrome 15_06_2023 15_03_12](https://github.com/mirandadewi/CTF-Write-Up/assets/136687271/c493397b-7154-4f7a-87ee-5c18ea391040)

lalu refresh situsnya dan boom kita dapatkan flagnya :

![Foresty Hacker Class - Google Chrome 15_06_2023 15_03_55](https://github.com/mirandadewi/CTF-Write-Up/assets/136687271/9906570b-49ab-43aa-9bc6-85adef406f21)

## Flag

**ForestyHC{here_is_your_fortun3_cookie_4a0a47}**

