# biodatakaryawan.html
biodata karyawan
</div>


<footer>Terakhir disunting: 24 Oktober 2025</footer>
</aside>


<main class="right">
<section>
<div class="section-title"><h2>Ringkasan</h2></div>
<p>Saya seorang profesional di bidang [posisi] dengan pengalaman N tahun dalam [keahlian utama]. Memiliki minat pada pengembangan produk yang berguna dan desain yang berfokus pada pengguna.</p>
</section>


<section>
<div class="section-title"><h2>Pendidikan</h2></div>
<div class="timeline">
<div class="timeline-item">
<div class="role">S1 — Universitas Contoh</div>
<div class="subtitle">2010 — 2014 · Teknik Informatika</div>
<p>IPK: 3.60 — Kegiatan: UKM, proyek penelitian, dsb.</p>
</div>
</div>
</section>


<section>
<div class="section-title"><h2>Pengalaman Kerja</h2></div>
<div class="timeline">
<div class="timeline-item">
<div class="role">Front-end Developer — PT. Contoh</div>
<div class="subtitle">2020 — Sekarang</div>
<p>Membangun antarmuka web, meningkatkan performa, memimpin tim kecil, dan mengimplementasikan best practices.</p>
</div>
<div class="timeline-item">
<div class="role">Intern UI/UX — Startup XYZ</div>
<div class="subtitle">2018 — 2019</div>
<p>Mendesain prototype, melakukan usability testing, dan kolaborasi antar-tim.</p>
</div>
</div>
</section>


<section>
<div class="section-title"><h2>Keahlian</h2></div>
<div class="skills">
<span class="skill">HTML</span>
<span class="skill">CSS</span>
<span class="skill">JavaScript</span>
<span class="skill">React</span>
<span class="skill">Figma</span>
<span class="skill">Komunikasi</span>
</div>
</section>


<section id="contact">
<div class="section-title"><h2>Referensi & Kontak</h2></div>
<p>Referensi tersedia atas permintaan. Silakan hubungi saya melalui telepon atau email di samping.</p>
<div style="margin-top:12px" class="contact-row">
<a class="btn" href="mailto:nama@email.com">Kirim Email</a>
<a class="mutebtn" href="tel:+6281234567890">Telepon</a>
</div>
</section>


</main>
</div>
</div>


<script>
function downloadCV(){
const cvContent = `Surya\n\nRingkasan:\nSaya seorang profesional...\n`;
const blob = new Blob([content], { type: 'text/plain' });
const url = URL.createObjectURL(blob);
const a = document.createElement('a');
a.href = url; a.download = 'CV-Nama-Anda.txt';
document.body.appendChild(a); a.click(); a.remove();
URL.revokeObjectURL(url);
}
</script>
</body>
</html>
