# Detect-Tab

Project ini mencontohkan bagaimana mendeteksi apakah tab aktif atau tidak dengan menggunakan requestAnimationFrame. Pendeteksian dilakukan dengan cara menghitung interval requestAnimationFrame. requestAnimationFrame akan dipanggil secara normal saat tab aktif. Pada saat tab tidak aktif, fungsi requestAnimationFrame hanya akan dipanggil dengan frame rate yang sangat rendah. Jika requestAnimationFrame dipanggil dengan interval kurang dari 100 mili detik, ini mengindikasikan bahwa tab sedang tidak aktif.
