# Penjelasan General Audit

Informasi pada *General Audit* dibagi menjadi beberapa bagian, yaitu:

* [Header](#bagian-header)
* [Tab Links](#tab-links)
* [Tab Reviews](#tab-reviews)
* [Tab Policies](#tab-policies)
* [Tab Logs](#tab-logs)

### <a name="bagian-header">HEADER</a>

![](../../img/general-audit/bagian-header.png)

#### <a name="field-no-document"># Document</a>

Nomor dokumen.

#### <a name="field-partner">Partner</a>

Nama partner.

#### <a name="field-sector">Sector</a>

Nama sektor usaha partner.

#### <a name="field-account-type-set">Account Type Set</a>

Set tipe akun.

#### <a name="field-financial-accounting-standard">Financial Accounting Standard</a>

Standar akuntansi keuangan.

#### <a name="field-currency">Currency</a>

Mata uang.

#### <a name="field-responsible">Responsible</a>

Nama penanggung jawab general audit.

#### <a name="field-accountant">Accountant</a>

Nama akuntan.

#### <a name="field-num-audit-firm">Num. of Consecutive Audit (Firm)</a>

Jumlah audit berturut-turut (firma).

#### <a name="field-field-num-audit-accountant">Num. of Consecutive Audit (Accountant)</a>

Jumlah audit berturut-turut (akuntan).

#### <a name="field-start-date">Start Date</a>

Tanggal mulai audit.

#### <a name="field-end-date">End Date</a>

Tanggal akhir audit.

#### <a name="field-previous-start-date">Previous Start Date</a>

Tanggal mulai audit sebelumnya.

#### <a name="field-previous-end-date">Previous End Date</a>

Tanggal akhir audit sebelumnya.

#### <a name="field-interim-start-date">Interim Start Date</a>

Tanggal sementara mulai audit.

#### <a name="field-interim-end-date">Interim End Date</a>

Tanggal sementara akhir audit.

#### <a name="tab-links">TAB LINKS</a>

![](../../img/general-audit/tab-links.png)

#### <a name="field-risk-assesment">Risk Assesment</a>

Indeks penilaian resiko.

#### <a name="field-risk-reporting">Reporting</a>

to do.

#### <a name="field-risk-response">Risk Response</a>

Respon terhadap indeks penilaian resiko.

#### <a name="field-other">Other</a>

Tautan lainnya.

#### <a name="tab-reviews">TAB REVIEWS</a>

![](../../img/general-audit/tab-reviews.png)

#### <a name="field-review-partners-validations">Review Partners Validations</a>

Nama-nama user yang dapat menyetujui/menolak *general audit*

#### <a name="tabel-validations">TABEL Validations</a>

Tahapan-tahapan persetujuan *general audit*

#### <a name="field-validations-tier">Tier</a>

Urutan persetujuan

#### <a name="field-validations-validated-by">Validated By</a>

Metode pemilihan user-user yang dapat menyetujui/menolak *general audit*. Metode pemilihan terdiri dari 3 (tiga) yaitu:

1. *Specific user*. User-user yang dapat menyetujui/menolak *general audit* ditentukan langsung.
2. *Any user in specific group*. User-user yang dapat menyetujui/menolak *general audit* adalah user-user yang tergabung dalam kelompok-kelompok user yang ditentukan.
3. *Both specific user and group*. User-user yang dapat menyetujui/menolak *general audit* ditentukan langsung ditambah dengan user-user yang tergabung dalam kelompok-kelompok user yang ditentukan.
4. *Python code*. User-user yang dapat menyetujui/menolak *general audit* ditentukan oleh algoritma kode python tertentu

#### <a name="field-validations-reviewers">Reviewers</a>

Nama-nama user yang dapat menyetujui/menolak *general audit* pada *tier* yang dimaksud.

#### <a name="field-validations-validated-rejected">Validated/Rejected By</a>

User yang menyetujui/menolak *general audit*.

#### <a name="field-validations-date">Date</a>

Tanggal dan waktu **Validated/Rejected By** menyetujui/menolak *general audit*

#### <a name="field-validations-date">Status</a>

Status persetujuan, terdiri dari 2 (dua) kemungkinan:

1. **Approved**. Tier disetujui.
2. **Rejected**. Tier ditolak.

#### <a name="tab-policies">TAB POLICIES</a>

![](../../img/general-audit/tab-policies.png)

#### <a name="field-confirm">Can Confirm</a>

Berhak/tidaknya user aktif untuk dapat mengkonfirmasi general audit.

#### <a name="field-restart-validation">Can Restart Validation</a>

Berhak/tidaknya user aktif untuk dapat merestart persetujuan general audit.

#### <a name="field-cancel">Can Cancel</a>

Berhak/tidaknya user aktif untuk dapat membatalkan general audit.

#### <a name="field-restart">Can Restart</a>

Berhak/tidaknya user aktif untuk dapat merestart general audit.

#### <a name="tab-logs">TAB LOGS</a>

![](../../img/general-audit/tab-logs.png)

#### <a name="field-confirmation">Confirmation</a>

Waktu konfirmasi dan user yang mengkonfirmasi general audit.

#### <a name="field-cancellation">Cancellation</a>

Waktu batal dan user yang membatalkan general audit.
