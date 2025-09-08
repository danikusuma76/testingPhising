<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Verifikasi Akun — Perusahaan</title>
  <style>
    /* Simple, neutral styling supaya terlihat "realistis" tapi bersih */
    :root{ --bg:#f4f7fb; --card:#ffffff; --accent:#0b63d6; --danger:#c0392b; --muted:#6b7280; }
    body{ margin:0; font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; background:var(--bg); color:#111;}
    .wrap{min-height:100vh; display:grid; place-items:center; padding:32px;}
    .card{width:100%;max-width:420px;background:var(--card);box-shadow:0 8px 30px rgba(2,6,23,0.08);border-radius:12px;padding:28px;}
    h1{margin:0 0 8px;font-size:18px;color:#0f1724;}
    p.lead{margin:0 0 18px;color:var(--muted);font-size:14px;}
    label{display:block;font-size:13px;margin:10px 0 6px;color:#111;}
    input[type="text"], input[type="password"]{
      width:100%; padding:10px 12px;border:1px solid #e6eef8;border-radius:8px;font-size:14px;
      box-sizing:border-box;
    }
    .row{display:flex; gap:10px; align-items:center;}
    .btn{
      display:inline-block;margin-top:16px;padding:10px 14px;border-radius:10px;background:var(--accent);color:#fff;text-decoration:none;border:0;cursor:pointer;font-weight:600;
      box-shadow:0 6px 18px rgba(11,99,214,0.18);
    }
    .muted{font-size:12px;color:var(--muted);margin-top:10px;}
    .small{font-size:12px;color:#9aa3b2;}
    .footer{margin-top:14px;font-size:12px;color:var(--muted);text-align:center;}
    .notice{border-left:4px solid var(--danger); background:#fff5f5;padding:10px 12px;border-radius:8px;margin-top:14px;color:var(--danger); display:none;}
    .edu{display:none;padding:20px;border-radius:10px;background:#fff;border:1px solid #eef3ff;}
  </style>
</head>
<body>
  <div class="wrap">
    <div class="card" id="mainCard" role="main" aria-labelledby="title">
      <h1 id="title">Verifikasi Akun Perusahaan</h1>
      <p class="lead">Kami mendeteksi aktivitas tidak biasa pada akun Anda. Silakan verifikasi untuk mencegah penangguhan.</p>

      <form id="phishForm" onsubmit="return handleSubmit(event)" autocomplete="off" novalidate>
        <label for="nik">NIK (Nomor Induk Karyawan)</label>
        <input id="nik" name="nik" type="text" inputmode="numeric" placeholder="Masukkan NIK" required>

        <label for="pwd">Sandi</label>
        <input id="pwd" name="pwd" type="password" placeholder="Masukkan sandi" required>

        <div class="row">
          <button type="submit" class="btn" id="submitBtn">Verifikasi Sekarang</button>
        </div>

        <div class="muted small">Jika Anda tidak melakukan permintaan ini, abaikan email ini.</div>

        <div class="notice" id="notice" role="alert">Perhatian: <strong>Link ini terlihat resmi tapi bukan dari IT resmi kami.</strong></div>
      </form>

      <div class="edu" id="eduBox" aria-live="polite">
        <!-- Akan diisi setelah submit -->
      </div>

      <div class="footer">Jika ragu, hubungi <strong>it@perusahaan.com</strong> (bukan alamat yang tercantum di email).</div>
    </div>
  </div>

  <script>
    // Penting: jangan kirim/rekam data ke server. Simulasi ini sepenuhnya client-side.
    function handleSubmit(e) {
      e.preventDefault();

      // Ambil element (TIDAK menyimpan/menampilkan nilai sensitif)
      const nikEl = document.getElementById('nik');
      const pwdEl = document.getElementById('pwd');

      // Minimal validasi client-side
      if (!nikEl.value.trim() || !pwdEl.value.trim()) {
        // Tampilkan peringatan sederhana tanpa mengirim data
        const notice = document.getElementById('notice');
        notice.textContent = 'Mohon isi semua kolom.';
        notice.style.display = 'block';
        notice.style.borderLeftColor = '#f39c12';
        notice.style.color = '#b03a02';
        return false;
      }

      // Simulasi: tampilkan alert lalu ganti isi halaman dengan pesan edukasi
      alert('Selamat — Anda kena phishing (simulasi).');

      // Bersihkan input untuk memastikan tidak ada data tersisa di UI
      nikEl.value = '';
      pwdEl.value = '';

      // Tampilkan panel edukasi
      const eduBox = document.getElementById('eduBox');
      eduBox.innerHTML = `
        <h2 style="margin-top:0">Ini adalah SIMULASI PHISHING</h2>
        <p>Anda baru saja mengklik link dan mencoba memasukkan kredensial pada halaman <strong>palsu</strong>.</p>
        <ul>
          <li>Jangan pernah memasukkan NIK atau kata sandi di link yang terlihat mencurigakan.</li>
          <li>Periksa alamat pengirim email dan tautan (hover link untuk lihat domain).</li>
          <li>Jika ragu, hubungi langsung tim IT lewat kanal resmi.</li>
        </ul>
        <p style="margin-top:8px" class="small">Pelatihan ini aman — tidak ada data yang dikirim atau disimpan.</p>
      `;
      eduBox.style.display = 'block';

      // Sembunyikan form
      document.getElementById('phishForm').style.display = 'none';

      return false;
    }

    // Opsional: jika ingin menampilkan notice awal untuk memberi petunjuk pada admin
    // document.getElementById('notice').style.display = 'block';
  </script>
</body>
</html>
