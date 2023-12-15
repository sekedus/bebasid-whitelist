# bebasid-whitelist

[![Ukuran rilis](https://img.shields.io/github/size/sekedus/bebasid-whitelist/hosts.txt?label=ukuran)](https://github.com/sekedus/bebasid-whitelist/blob/main/hosts.txt) [![Sumber Hosts](https://badgen.net/badge/github/bebasid/212529?icon&label=sumber)](https://github.com/bebasid/bebasid/blob/master/releases/hosts)
 
Buka halaman situs web yang diblokir dengan menggunakan [_hosts file_](<https://en.wikipedia.org/wiki/Hosts_(file)>).

## Daftar Pengecualian:
- [Parked domain](https://icannwiki.org/Domain_Parking)
- Situs down (tidak aktif)
- Situs dewasa/porno
- Situs judi

## Cari alamat IP
### [DNS Lookup](https://sekedus.github.io/bebasid-whitelist/dns-lookup.html)
### Manual
- Cari subdomain dengan [Subdomain Finder](https://subdomainfinder.c99.nl/)
  - klik `Copy to clipboard`
- Dapatkan alamat IP dengan [Bulk DNS Lookup](https://www.onlinednslookup.com/bulk-dns-lookup/)
  - Query: `A`
  - Server: [`Plain DNS IPv4` dari BEBASDNS](https://github.com/bebasid/bebasdns?tab=readme-ov-file#dns-bawaan-default)
    - (untuk memastikan alamat IP yang didapat untuk akses dari Indonesia)
  - klik `Check DNS`
  - Tambahkan ke [hosts](https://en.wikipedia.org/wiki/Hosts_(file)) dengan format `ipaddress url.com`

<!-- ref: https://github.com/curl/curl/wiki/DNS-over-HTTPS#publicly-available-servers -->
