# Penjelasan Index A.210

Informasi pada *Index A.130* dibagi menjadi beberapa bagian, yaitu:

* [Header](#bagian-header)
* [Tab Materiality](#tab-materiality)
* [Tab Reviews](#tab-reviews)
* [Tab Policies](#tab-policies)
* [Tab Logs](#tab-logs)

### <a name="bagian-header">HEADER</a>

![](../../../img/index-a210/bagian-header.png)

#### <a name="field-no-document"># Document</a>

Nomor dokumen.

#### <a name="field-no-general-audit"># General Audit</a>

Nomor general audit.

#### <a name="field-partner">Partner</a>

Nama partner.

#### <a name="field-account-type-set">Account Type Set</a>

Set tipe akun yang digunakan.

#### <a name="field-responsible">Responsible</a>

Nama penanggungjawab.

#### <a name="field-start-date">Start Date</a>

Tanggal awal.

#### <a name="field-end-date">End Date</a>

Tanggal akhir.

#### <a name="field-previous-start-date">Previous Start Date</a>

Tanggal awal sebelumnya.

#### <a name="field-previous-end-date">Previous End Date</a>

Tanggal akhir sebelumnya.

#### <a name="field-interim-start-date">Interim Start Date</a>

Tanggal awal sementara.

#### <a name="field-interim-end-date">Interim End Date</a>

Tanggal akhir sementara.

#### <a name="tab-materiality">TAB MATERIALITY</a>

![](../../../img/index-a210/tab-materiality-1.png)
![](../../../img/index-a210/tab-materiality-2.png)

#### <a name="field-computation-item">Computation Item To Use</a>

Item perhitungan yang akan digunakan.

#### <a name="field-use-other-amount">Use Other Amount</a>

Penggunaan jumlah lainnya.

#### <a name="field-other-base-amount">Other Base Amount</a>

Jumlah dasar lainnya.

#### <a name="field-base-amount-computation">Base Amount for Materiality Computation</a>

Jumlah dasar yang diunakan untuk perhitungan materialitas.

#### <a name="field-base-extrapolation">Base Extrapolation Amount for Materiality Computation</a>

Jumlah ekstrapolasi dasar untuk perhitungan materialitas.

***Overall Materiality***

#### <a name="field-overall-percentage">Percentage</a>

Persentase.

#### <a name="field-overall-year-end">Year End</a>

Jumlah di akhir tahun.

#### <a name="field-overall-extrapolation">Extrapolation</a>

Jumlah ekstrapolasi.

#### <a name="field-overall-consideration">Consideration</a>

Pertimbangan.

***Performance Materiality***

#### <a name="field-performance-percentage">Percentage</a>

Persentase.

#### <a name="field-performance-year-end">Year End</a>

Jumlah di akhir tahun.

#### <a name="field-performance-extrapolation">Extrapolation</a>

Jumlah ekstrapolasi.

#### <a name="field-performance-consideration">Consideration</a>

Pertimbangan.

***Tolerable Misstatement***

#### <a name="field-tolerable-percentage">Percentage</a>

Persentase.

#### <a name="field-tolerable-year-end">Year End</a>

Jumlah di akhir tahun.

#### <a name="field-tolerable-extrapolation">Extrapolation</a>

Jumlah ekstrapolasi.

#### <a name="field-tolerable-consideration">Consideration</a>

Pertimbangan.

***Conclusion***

#### <a name="field-status">Status</a>

Status.

#### <a name="field-conclusion">Conclusion</a>

Kesimpulan.

#### <a name="tab-reviews">TAB REVIEWS</a>

![](../../../img/index-a210/tab-reviews.png)

#### <a name="field-review-partners-validations">Review Partners Validations</a>

Nama-nama user yang dapat menyetujui/menolak *Index A.210*

#### <a name="tabel-validations">TABEL Validations</a>

Tahapan-tahapan persetujuan *Index A.210*

#### <a name="field-validations-tier">Tier</a>

Urutan persetujuan

#### <a name="field-validations-validated-by">Validated By</a>

Metode pemilihan user-user yang dapat menyetujui/menolak *Index A.210*. Metode pemilihan terdiri dari 3 (tiga) yaitu:

1. *Specific user*. User-user yang dapat menyetujui/menolak *Index A.210* ditentukan langsung.
2. *Any user in specific group*. User-user yang dapat menyetujui/menolak *Index A.210* adalah user-user yang tergabung dalam kelompok-kelompok user yang ditentukan.
3. *Both specific user and group*. User-user yang dapat menyetujui/menolak *Index A.210* ditentukan langsung ditambah dengan user-user yang tergabung dalam kelompok-kelompok user yang ditentukan.
4. *Python code*. User-user yang dapat menyetujui/menolak *Index A.210* ditentukan oleh algoritma kode python tertentu

#### <a name="field-validations-reviewers">Reviewers</a>

Nama-nama user yang dapat menyetujui/menolak *Index A.210* pada *tier* yang dimaksud.

#### <a name="field-validations-validated-rejected">Validated/Rejected By</a>

User yang menyetujui/menolak *Index A.210*.

#### <a name="field-validations-date">Date</a>

Tanggal dan waktu **Validated/Rejected By** menyetujui/menolak *Index A.210*

#### <a name="field-validations-date">Status</a>

Status persetujuan, terdiri dari 2 (dua) kemungkinan:

1. **Approved**. Tier disetujui.
2. **Rejected**. Tier ditolak.

#### <a name="tab-policies">TAB POLICIES</a>

![](../../../img/index-a210/tab-policies.png)

#### <a name="field-confirm">Can Confirm</a>

Berhak/tidaknya user aktif untuk dapat mengkonfirmasi Index A.210.

#### <a name="field-valid">Can Valid</a>

Berhak/tidaknya user aktif untuk dapat menyetujui Index A.210.

#### <a name="field-restart-validation">Can Restart Validation</a>

Berhak/tidaknya user aktif untuk dapat merestart persetujuan Index A.210.

#### <a name="field-cancel">Can Cancel</a>

Berhak/tidaknya user aktif untuk dapat membatalkan Index A.210.

#### <a name="field-restart">Can Restart</a>

Berhak/tidaknya user aktif untuk dapat merestart Index A.210.

#### <a name="tab-logs">TAB LOGS</a>

![](../../../img/index-a210/tab-logs.png)

#### <a name="field-confirmation">Confirmation</a>

Waktu konfirmasi dan user yang mengkonfirmasi Index A.210.

#### <a name="field-validation">Validation</a>

Waktu persetujuan dan user yang menyetujui Index A.210.

#### <a name="field-cancellation">Cancellation</a>

Waktu batal dan user yang membatalkan Index A.210.
