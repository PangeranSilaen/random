Q[n] = Question
n = ke berapa

A[n] = Answer
n = ke berapa.



Q1,
aku ada mau dapet project nih lanjutan dari erp. ini modulnya namanya engineering and tender. aku jujur gatau apa itu tender wkwkwkw. pokoknya ada beberapa hal yg dijelasin ke aku nah aku gatau sumpah makaudnya gimana jadi aku jabarin aja kekamu walaupun agak berantakan gpp ya hehe.
1. PT Bahana Cipta Internusa tempat aku kerja sekarang
2. Tender, rebutan?? lelang?? emang tender dilelang? proyek?? M M an?? miliaran maksudnya. BCI kalah? maksudnya kalah apa njir kalah lelang? score?? phm? (pertamina hulu mahakam)
3. Mba nawang staf tender sering nanya2 apakah dokumen udh sampe mana, jadi sulit tracking nya makanya di erp mau nambah modul ini.

sebelum ke desain sistem aku harus paham dulu sebenarnya apa yg mau kubuat jadi bantu ya hehe maaf kalo agak berantakan informasinya karna jujur aku sistem informasi baru banget dengar2 istilah pas tadi meeting itu


A1,
wkwkw santai pang, ini 100% wajar banget. Anak SI baru masuk dunia industri memang selalu kaget sama istilah tender. Kita rapihin pelan-pelan ya, dari nol, tanpa sok bisnis 😂

⸻

1️⃣ Sebenarnya “Tender” itu apa sih?

Tender = proses rebutan proyek secara resmi.

Biasanya alurnya gini (versi manusia):
	1.	Perusahaan besar (contoh: PHM – Pertamina Hulu Mahakam)
👉 butuh barang/jasa
👉 misalnya: pembangunan, maintenance, engineering, dll
	2.	Mereka buka tender
👉 ngumumin:
	•	lingkup pekerjaan
	•	spesifikasi teknis
	•	nilai proyek (iya, sering M–M an, bahkan puluhan M)
	•	deadline
	3.	Banyak vendor ikut daftar
👉 termasuk PT Bahana Cipta Internusa (BCI)
	4.	Vendor ngumpulin dokumen
	•	dokumen teknis
	•	dokumen administrasi
	•	dokumen harga
	5.	PHM nilai semua peserta
	•	yang paling sesuai + paling kompetitif → MENANG
	•	sisanya → KALAH TENDER

👉 Jadi ya:
	•	Tender = lelang proyek
	•	Kalah = kalah seleksi, bukan kalah berantem wkwk

⸻

2️⃣ “BCI kalah” maksudnya apa?

“BCI kalah? maksudnya kalah apa njir?”

Yes, kalah tender.

Artinya:
	•	BCI ikut tender
	•	Tapi bukan pemenang

Alasannya bisa banyak:
	•	harga terlalu mahal
	•	dokumen kurang lengkap
	•	teknis tidak memenuhi
	•	kalah score dibanding vendor lain

👉 Biasanya ada evaluasi / score, tapi:
	•	vendor jarang dikasih score detail
	•	cuma dikasih status: menang / kalah

⸻

3️⃣ Terus “Engineering and Tender” itu ngapain?

Ini 2 dunia yang nyambung:

🔧 Engineering

Tim engineering:
	•	nyiapin spesifikasi teknis
	•	gambar, metode kerja, perhitungan
	•	jawaban teknis ke owner (PHM)

📑 Tender

Tim tender:
	•	ngumpulin semua dokumen
	•	ngejar deadline
	•	submit ke sistem PHM
	•	komunikasi sama internal (engineering, finance, legal)

👉 Jadi:

Tender = proyek bisnis
Engineering = isi teknisnya

⸻

4️⃣ Kenapa Mba Nawang ribet nanya “dokumen udah sampai mana?”

Nah ini masalah klasik perusahaan 😈

Kondisi sekarang (kemungkinan besar):
	•	Dokumen nyebar:
	•	email
	•	WhatsApp
	•	Excel
	•	folder random
	•	Tidak ada 1 sumber kebenaran

Maka yang terjadi:
	•	Mba Nawang harus nanya manual
	•	“dokumen teknis udah?”
	•	“harga udah final?”
	•	“legal udah approve?”

👉 Tracking = chaos

⸻

5️⃣ Jadi sebenarnya ERP mau bantu apa?

Bukan cuma “nambah modul”, tapi:

Mengontrol proses tender dari awal sampai akhir

Contoh kebutuhan nyatanya:
	•	tahu tender apa saja yang sedang berjalan
	•	tahu status tiap dokumen
	•	tahu siapa PIC
	•	tahu deadline
	•	tahu hasil tender (menang/kalah)

⸻

6️⃣ Versi super sederhana (biar nempel di kepala)

Bayangin tender itu kayak lomba proposal:
	•	PHM = juri
	•	BCI = peserta
	•	Engineering = isi proposal
	•	Tender = panitia internal
	•	ERP = papan skor + checklist + arsip

⸻

7️⃣ Sebelum desain sistem, ini mindset penting buat kamu (anak SI)

❌ Jangan mikir:

“fiturnya apa ya?”

✅ Tapi mikir:

“orang-orang di kantor ini capek di bagian mana?”

Dari ceritamu:
	•	capek tracking dokumen
	•	capek nanya berulang
	•	capek gak tau status tender

👉 itu emas buat desain sistem.

⸻

8️⃣ Next step (kalau kamu mau)

Kalau kamu mau, di step selanjutnya aku bisa bantu:
	1.	Translate kebutuhan bisnis → kebutuhan sistem
	2.	Ngebuatin:
	•	flow tender
	•	entity data (tender, dokumen, status, PIC)
	3.	Nentuin:
	•	modul apa aja
	•	role user (engineering, tender, manajemen)

Tinggal bilang:

“lanjut, jelasin dari sisi sistem”

Santai pang, kamu nggak goblok, kamu cuma baru masuk dunia orang proyek 😄


Q2,
hmm oke mantap aku dot insight baru bro. sekarang biar lebih jelas. kamu gausah bantu aku kek ngerancang. jelasin aja sistemnya ini bakal gimana sih kira2 nantinya? terserah kamu jelasin fitur kah role kah atau gimana


A2,
Oke pang. Ini gambaran “modul Engineering & Tender” di ERP itu biasanya jadi apa, secara bentuk sistem, tanpa kita masuk desain teknis yang ribet.

⸻

Gambaran besarnya: modul ini jadi “kanban + arsip + kontrol deadline” untuk tender

Intinya sistem ngubah proses yang tadinya nanya-nanya jadi:
	•	semua tender tercatat rapi
	•	semua dokumen punya status jelas
	•	semua orang tau siapa ngerjain apa
	•	semua deadline ke-track
	•	hasil tender ke-record buat evaluasi

⸻

1) Objek utama yang bakal ada di sistem (yang dipegang modul)

Biasanya modul ini punya beberapa “data inti”:

A. Tender / Bid (Proyek yang diikutin)

Field yang umum:
	•	Nama tender, nomor tender, owner (contoh PHM)
	•	Jenis pekerjaan (engineering/service/procurement)
	•	Nilai perkiraan (M, puluhan M, dll)
	•	Metode tender (open/limited, dll)
	•	Tanggal penting: open, deadline, clarification, submit, pengumuman
	•	Status tender: draft → on progress → submitted → won/lost → closed

B. Dokumen Tender (Checklist yang bikin orang ribet)

Dokumen biasanya dibagi 3:
	•	Administrasi (legalitas, company profile, pajak, dsb)
	•	Teknis (metode kerja, gambar, spec, QA/QC, HSE plan)
	•	Komersial (BOQ, pricing, penawaran harga)

Di sistem, tiap dokumen punya:
	•	PIC (siapa yang bikin)
	•	reviewer/approver (siapa yang ngecek)
	•	status (belum mulai, dikerjakan, review, revisi, final)
	•	file attachment + versi

C. Aktivitas / Timeline / Log

Biar jelas “tadi udah ngapain”:
	•	siapa upload apa
	•	siapa approve kapan
	•	revisi ke berapa
	•	catatan dan komentar

⸻

2) Alur kerja yang biasanya kejadian di modul ini

Bayangin 1 tender masuk sistem:
	1.	Tender dibuat (oleh tim tender)
	•	input basic info + deadline
	2.	Template dokumen muncul otomatis
	•	checklist admin/teknis/komersial yang wajib
	3.	Assign PIC
	•	Engineering pegang dokumen teknis
	•	Tender/Legal pegang administrasi
	•	Finance/Estimator pegang harga
	4.	Dokumen dikerjakan + upload
	•	ada status dan versi
	5.	Review & approval
	•	misalnya engineering submit → tender review → manager approve
	6.	Submit tender
	•	status tender jadi “Submitted”
	7.	Hasil tender diinput
	•	Won / Lost + alasan (kalau ada)
	8.	Arsip & report
	•	semua file rapi, gampang dicari

⸻

3) Fitur yang “pasti kepake” (yang bikin nggak perlu nanya-nanya)

Dashboard
	•	Tender aktif minggu ini
	•	Tender yang deadline-nya mepet (merah)
	•	Dokumen yang stuck di “review”
	•	Tender per owner (PHM, dll)

Checklist progress (ini core banget)

Semacam progress bar:
	•	Admin: 70% complete
	•	Teknis: 40% complete
	•	Komersial: 0% belum mulai

Assignment + To-do
	•	“Dokumen Metode Kerja: PIC = A, due date = 2 Feb”
	•	orang yang ditugasin punya halaman “tugas saya”

Reminder & notifikasi
	•	H-7, H-3, H-1 sebelum deadline
	•	notif kalau ada dokumen direvisi/ditolak

Versioning & approval trail
	•	file “Penawaran_v3_final.pdf”
	•	siapa approve, kapan, komentar apa

Search & archive
	•	cari tender lama: “PHM 2024 piping”
	•	download paket dokumen tender sekali klik

⸻

4) Role yang biasanya ada (biar kamu kebayang siapa ngapain)

Paling umum:

1) Tender Staff (contoh: Mba Nawang)
	•	bikin tender di sistem
	•	bikin checklist dokumen
	•	assign PIC
	•	mantau progress
	•	compile final submission

2) Engineering
	•	ngerjain dokumen teknis
	•	upload revisi
	•	respon clarification teknis

3) Estimator / Finance / Commercial
	•	bikin BOQ, pricing
	•	upload penawaran harga (kadang aksesnya dibatasi)

4) Legal / Admin
	•	beresin dokumen legal
	•	validasi compliance

5) Manager / Approver
	•	approve final dokumen/tender
	•	lihat report dan performa

⸻

5) Output yang diharapkan perusahaan dari modul ini

Ini “nilai bisnis”-nya yang biasanya dicari:
	•	ngurangin chaos tracking (nanya-nanya hilang)
	•	ngurangin miss deadline
	•	dokumen tender rapi + gampang audit
	•	punya histori tender: menang/kalah + belajar kenapa

⸻

6) Kalau modulnya dikasih label “Engineering and Tender”, biasanya fokusnya apa?

Kalau aku nebak dari nama modulnya:
	•	bukan cuma list tender
	•	tapi juga workflow dokumen teknis engineering yang jadi bagian tender
	•	jadi bridging antara “engineering kerja teknis” dan “tender submit”

⸻

Kalau kamu mau bikin makin kebayang tanpa desain:
Kasih aku 1 contoh tender yang sering BCI ikut (misal: “maintenance piping” atau “pengadaan equipment” gitu), nanti aku ceritain simulasi alur 1 tender dari awal sampai submit pakai sistem ini, biar kerasa real-nya.


Q3,
bebas simulasiin aja 


A3,
Gas. Kita simulasikan 1 tender beneran tapi versi manusia + ERP, bukan versi slide presentasi 😄
Anggap ini 100% fiktif tapi realistis.

⸻

🎯 SIMULASI TENDER DI ERP

Owner: PHM (Pertamina Hulu Mahakam)
Vendor: PT Bahana Cipta Internusa (BCI)
Pekerjaan: Engineering & Maintenance Piping
Nilai: ± Rp 12 M
Deadline submit: 25 Februari

⸻

HARI 0 – PHM BUKA TENDER

PHM ngumumin tender via portal mereka.

➡️ Mba Nawang (Tender Staff) dapet info:
	•	judul tender
	•	nomor tender
	•	deadline
	•	list dokumen wajib

⸻

HARI 1 – TENDER MASUK ERP

Mba Nawang buka ERP → Modul Engineering & Tender

Dia bikin 1 data tender baru:
	•	Nama: PHM – Piping Maintenance 2026
	•	Owner: PHM
	•	Deadline: 25 Feb
	•	Nilai estimasi: 12 M
	•	Status: On Progress

ERP langsung:
	•	generate checklist dokumen standar
	•	bikin timeline H-14, H-7, H-3

⸻

HARI 1–2 – ASSIGN ORANG (INI PENTING)

Di ERP:
	•	Dokumen Teknis → Engineering Team
	•	Metode Kerja → Engineer A
	•	HSE Plan → Engineer B
	•	BOQ & Harga → Estimator
	•	Legal → Admin Legal

Masing-masing orang:
	•	login ERP
	•	lihat tab “Tugas Saya”

❌ Tidak ada WA:

“Mas, dokumen udah sampai mana?”

⸻

HARI 5 – ENGINEERING MULAI KERJA

Engineer A upload:
	•	Metode_Kerja_v1.pdf
Status:
	•	In Review

Engineer B upload:
	•	HSE_Plan_v1.pdf
Status:
	•	In Review

ERP nyatet:
	•	siapa upload
	•	jam berapa
	•	versi ke berapa

⸻

HARI 7 – REVIEW & REVISI

Mba Nawang buka ERP:
	•	lihat checklist
	•	Metode Kerja → ada komentar:
“Tambahin referensi standar PHM”

Engineer A:
	•	upload Metode_Kerja_v2.pdf
	•	status → Final

Semua terekam, gak ada:

“eh ini file terakhir yg mana ya?”

⸻

HARI 10 – HARGA MASUK

Estimator upload:
	•	BOQ_v1.xlsx
	•	Penawaran_Harga_v1.pdf

Akses:
	•	cuma tender + manajemen
	•	engineering tidak bisa lihat harga

(ini penting di dunia tender)

⸻

HARI 15 – DEADLINE MEPEP

Dashboard ERP:
	•	Tender ini warna kuning
	•	Admin dokumen: 100%
	•	Teknis: 100%
	•	Komersial: 90%

ERP kirim reminder:

“H-3 Deadline Tender PHM – Piping Maintenance”

⸻

HARI 18 – SUBMIT

Semua checklist hijau ✅

Mba Nawang klik:

Submit Tender

Status tender:
	•	Submitted
	•	tanggal submit tercatat

ERP:
	•	lock dokumen
	•	simpan paket final

⸻

HARI 30 – HASIL TENDER KELUAR

PHM umumkan hasil:
	•	BCI → Lost

Mba Nawang update:
	•	Status: Lost
	•	Catatan (jika ada): “Harga lebih tinggi dari kompetitor”

⸻

HARI 31 – SETELAH KALAH (INI SERING DILUPAIN)

Manajemen buka ERP:
	•	lihat histori tender PHM
	•	3 tender terakhir → kalah
	•	rata-rata harga BCI > kompetitor

➡️ jadi bahan evaluasi internal

⸻

TANPA ERP VS DENGAN ERP (BEDANYA KERASA)

Tanpa ERP:
	•	nanya via WA
	•	file berantakan
	•	salah kirim versi
	•	deadline deg-degan
	•	evaluasi ngandelin ingatan

Dengan ERP:
	•	semua tender satu tempat
	•	status jelas
	•	dokumen ke-track
	•	histori rapi
	•	knowledge perusahaan naik

⸻

INTI YANG HARUS NANCEP DI KEPALA KAMU

Kalau disederhanakan banget:

Modul Engineering & Tender = sistem buat ngatur lomba proposal mahal biar gak chaos

Bukan soal coding dulu, tapi:
	•	manusia
	•	deadline
	•	dokumen
	•	tanggung jawab

⸻

Kalau kamu mau next level:
	•	aku bisa ceritain kenapa tender sering kalah
	•	atau kenapa engineering & tender sering ribut
	•	atau fitur ERP paling sering disalahpahami orang kantor

Tinggal bilang aja, kita lanjut ngobrol santai 😄


Q4,
hmm aku penasaran tentang manajemen file. jadi setiap versioning akan diupload ya? jadi ini full storage ke server? lalu setiap versioning masa upload lagi? anggapan nya gini bro. misal v1 1000 kata terus v2 1100 nah kan kondisinya ini kalo digabung jadi ada 2100 kata. eh? ah ntah la tapi jadinya setiap versi akan diupload? karna kalau misal direplace dengan revisian maka yg v sebelumnya jadi hilang dong? EHHH OHHH COBA KALO GINI, kalo iya direplace tapi setiap perubahan di note? jadi kek misal di halaman x bagian y diganti dari cc ke dd. gitu? 

aku gatau ya best practice nya gimana tapi ini gimana? aku ngerasa kek overthinking mikirin ini sekarang padahal implementasi aja blm tapi menurutku tetap perlu didiskusikanwkwkkw


A4,
Kamu kepikiran ini justru bagus, karena versioning dokumen tender itu pain point nyata. Jawaban praktisnya:

1) Di sistem dokumen bisnis, “versioning” biasanya memang upload lagi

Karena yang di-versioning itu file (PDF/Word/Excel), bukan “kata-kata di dalamnya”.

Jadi pola umum:
	•	MetodeKerja_v1.pdf (upload)
	•	revisi → MetodeKerja_v2.pdf (upload)
	•	dst

Kenapa? Karena:
	•	proses tender butuh bukti: “yang disubmit versi mana”, “yang di-approve versi mana”
	•	file bisa beda format, layout, tabel, gambar, dll. Susah kalau cuma nyimpen “diff kata”

2) Berarti storage bakal bengkak?

Iya bertambah, tapi biasanya masih aman karena:
	•	file tender umumnya MB-an, bukan GB-an
	•	jumlah revisi per dokumen biasanya tidak ratusan
	•	perusahaan memang “bayar” storage demi auditability

Kalau mau lebih efisien, ada 2 pendekatan:

A) Simpel (paling umum): simpan semua versi full file

Pro:
	•	gampang implement
	•	aman buat audit
	•	restore gampang

Con:
	•	storage lebih besar

B) Advanced: dedup / delta storage (jarang dibuat custom)

Secara teori bisa “nyimpen cuma perubahan”, tapi:
	•	itu ribet
	•	apalagi kalau file-nya PDF/Docx yang struktur internalnya kompleks
	•	best practice perusahaan biasanya: pakai object storage + lifecycle policy, bukan bikin diff engine

Jadi analogi “1000 kata jadi 2100 kata” itu gak kejadian kalau sistemnya nyimpen per versi sebagai snapshot, bukan digabung. Yang ada:
	•	v1 tetap ada (1000 kata)
	•	v2 file baru (1100 kata)
Total storage = v1 + v2 (memang bertambah), tapi nggak digabung secara konsep isi, hanya file terpisah.

3) Kalau file di-replace, versi lama hilang dong?

Makanya jangan replace tanpa histori.

Best practice-nya biasanya salah satu dari ini:

Opsi 1: “Upload versi baru” (recommended)
	•	tombol: Upload New Version
	•	sistem simpan v1, v2, v3…
	•	yang “aktif” ditandai sebagai Latest
	•	versi lama tetap bisa dibuka/download

Opsi 2: “Replace file” tapi sistem auto-archive versi lama

Dari sisi user terasa kayak replace,
tapi belakangnya:
	•	versi lama dipindah jadi archive
	•	tetap ada audit trail

Intinya: di UI bisa keliatan replace, tapi backend tetap versioned.

4) Terus soal “catatan perubahan halaman X bagian Y” gimana?

Ini konsepnya mirip “diff” kayak Git, tapi di dokumen bisnis biasanya:
	•	tidak otomatis
	•	biasanya manual, bentuknya:

A) Change log manual per versi

Saat upload v2, user isi:
	•	“Perubahan: update scope, revisi metode, tambah referensi standar PHM”

B) Comment/annotation workflow

Reviewer bisa kasih:
	•	komentar “tolong ganti CC jadi DD di bab 3”
Lalu di v2 statusnya “addressed”.

C) Redline/track changes (khusus Word)

Kalau format Word dan disiplin:
	•	bisa pakai Track Changes
Tapi untuk tender sering akhirnya dikunci PDF, jadi tracking tetap lewat change log.

Yang paling realistis dipakai di ERP:
✅ upload versi baru + wajib isi ringkasan perubahan + ada review comment thread

5) Jadi jawaban singkatnya buat pertanyaanmu
	•	Ya, versi biasanya diupload lagi (snapshot per versi).
	•	Tidak, versi tidak “digabung” jadi 2100 kata; itu cuma storage nambah karena simpan history.
	•	Tidak ideal kalau cuma replace hilangkan versi lama.
	•	Catatan perubahan biasanya manual (change log + komentar), bukan auto deteksi halaman/kalimat.

⸻

Kalau kamu pengen pegangan “aturan main” paling aman buat modul tender (tanpa ngedesain):
	1.	Dokumen punya Latest version
	2.	Setiap upload baru → auto jadi versi baru
	3.	Versi lama read-only (ga bisa dihapus user biasa)
	4.	Upload versi baru wajib isi change summary
	5.	Ada audit trail: siapa, kapan, ngapain

Kalau kamu mau, aku bisa kasih contoh tampilan UI yang umum (tab Versions, tombol Upload New Version, kolom change summary) biar makin kebayang.
