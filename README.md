# Ekstensi VSCode untuk Go (Golang)

Ekstensi ini menyediakan snippet kode Go (Golang) yang dapat digunakan dalam proyek-proyek Go Anda. Snippet adalah potongan kode yang dapat diambil secara otomatis dengan menggunakan kata kunci tertentu.

## Fitur Utama

- Snippet kode Go (Golang): Ekstensi ini menyediakan berbagai snippet kode yang umum digunakan dalam pengembangan Go, seperti struktur dasar program, fungsi, variabel, perulangan, dan sebagainya. Anda dapat menghemat waktu dan usaha dengan menggunakan snippet ini daripada menulis ulang kode yang sama berulang-ulang.

## Cara Menggunakan Snippet

[Cara Penggunaan](https://www.youtube.com/watch?v=XTACjMu0EwI)

1. Pastikan Anda telah menginstal ekstensi ini di VSCode.
2. Buka file Go yang ingin Anda tambahkan snippet kode.
3. Ketikkan kata kunci snippet yang ingin Anda gunakan.
4. Pilih snippet yang ingin Anda masukkan dengan menggunakan tombol Tab atau kursor.
5. Snippet kode Go akan langsung ditambahkan ke editor.

## Daftar Snippet yang Tersedia

- `!time`: Memunculkan `time.Now()`
- `!timeMonth`: Menunculkan `time.Now().Format("200601")`
- `!timeDay`: Menunculkan `time.Now().Format("20060102")`
- `!convStringToInt`: Menunculkan `int, err := strconv.Atoi(?)`
- `!convStringToUint`: Menunculkan `uint, err := strconv.ParseUint(?, 10, 32)`
- `!convStringToFloat`: Menunculkan `float, err := strconv.ParseFloat(?, 8)`
- `!convFloatToString`: Menunculkan `strconv.FormatFloat(?, 'f', -1, 64)`
- `!convUintToString`: Menunculkan `strconv.FormatUint(uint64(?), 10)`
- `!convFloatToString`: Menunculkan `uint, err := strconv.ParseUint(?, 10, 32)`
- `!fmtSring`: Menunculkan `%s` untuk melengkapi `fmt.Sprintf("%s", "string")`
- `!fmtUint`: Menunculkan `%d` untuk melengkapi `fmt.Sprintf("%d", uint)`
- `!fmtFloat`: Menunculkan `%g` untuk melengkapi `fmt.Sprintf("%g", float)`
- `!switch`: Menunculkan `switch expression {`
  `case condition:`
  `}`
- `!filterMapString`: Menunculkan `data := map[string]string{`
  `"?.eq": "?string"`
  `}`
- `!constraint`: Menunculkan `if !helper.Contains([]string{?}, ?) {`
  `err := &exception.ErrorSendToResponse{Err: "Internal Server Error"}`
  `}`

## Kontribusi

Anda dapat berkontribusi pada pengembangan ekstensi ini dengan menambahkan snippet kode Go baru atau memperbaiki yang ada. Silakan kunjungi [repositori GitHub](https://github.com/takahashiumaru/go-snippets) kami untuk informasi lebih lanjut.

## Lisensi

Ekstensi ini dilisensikan di bawah [MIT License](https://opensource.org/licenses/MIT). Lihat berkas LICENSE untuk informasi selengkapnya.

## Laporan Masalah

Jika Anda menemui masalah saat menggunakan proyek ini atau memiliki saran perbaikan, silakan buat [issue baru](https://github.com/takahashiumaru/go-snippets) di repositori ini. Kami akan berusaha memperbaikinya secepat mungkin.

## Dukungan

Jika Anda mengalami masalah atau memiliki pertanyaan terkait ekstensi ini, silakan buat [issue](https://github.com/takahashiumaru/go-snippets) baru di repositori GitHub kami.

Terima kasih telah menggunakan ekstensi VSCode untuk Go (Golang)!
