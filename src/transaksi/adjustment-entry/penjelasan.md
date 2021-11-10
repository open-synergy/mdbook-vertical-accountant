# Penjelasan Adjustment Entry

Informasi pada *Adjustment Entry* dibagi menjadi beberapa bagian, yaitu:

* [Header](#bagian-header)
* [Tab Details](#tab-details)
* [Tab Reviews](#tab-reviews)
* [Tab Policies](#tab-policies)
* [Tab Logs](#tab-logs)

### <a name="bagian-header">HEADER</a>

![](../../img/adjustment-entry/bagian-header.png)

#### <a name="field-no-document"># Document</a>

Nomor dokumen.

#### <a name="field-no-general-audit"># General Audit</a>

Nomor dokumen General Audit.

#### <a name="field-partner">Partner</a>

Nama partner.

#### <a name="field-account-type-set">Account Type Set</a>

Set tipe akun.

#### <a name="field-currency">Currency</a>

Mata uang.

#### <a name="field-adjustment-type">Adjustment Type</a>

Tipe adjustment.

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

#### <a name="tab-details">TAB DETAILS</a>

![](../../img/adjustment-entry/tab-details.png)

#### <a name="field-account">Account</a>

Nama Akun.

#### <a name="field-description">Description</a>

Deskripsi.

#### <a name="field-debit">Debit</a>

Jumlah debit.

#### <a name="field-credit">Credit</a>

Jumlah credit.

#### <a name="field-tb-detail">TB Detail</a>

to do.

#### <a name="tab-reviews">TAB REVIEWS</a>

![](../../img/adjustment-entry/tab-reviews.png)

#### <a name="field-review-partners-validations">Review Partners Validations</a>

Nama-nama user yang dapat menyetujui/menolak *adjustment entry*

#### <a name="tabel-validations">TABEL Validations</a>

Tahapan-tahapan persetujuan *adjustment entry*

#### <a name="field-validations-tier">Tier</a>

Urutan persetujuan

#### <a name="field-validations-validated-by">Validated By</a>

Metode pemilihan user-user yang dapat menyetujui/menolak *adjustment entry*. Metode pemilihan terdiri dari 3 (tiga) yaitu:

1. *Specific user*. User-user yang dapat menyetujui/menolak *adjustment entry* ditentukan langsung.
2. *Any user in specific group*. User-user yang dapat menyetujui/menolak *adjustment entry* adalah user-user yang tergabung dalam kelompok-kelompok user yang ditentukan.
3. *Both specific user and group*. User-user yang dapat menyetujui/menolak *adjustment entry* ditentukan langsung ditambah dengan user-user yang tergabung dalam kelompok-kelompok user yang ditentukan.
4. *Python code*. User-user yang dapat menyetujui/menolak *adjustment entry* ditentukan oleh algoritma kode python tertentu

#### <a name="field-validations-reviewers">Reviewers</a>

Nama-nama user yang dapat menyetujui/menolak *adjustment entry* pada *tier* yang dimaksud.

#### <a name="field-validations-validated-rejected">Validated/Rejected By</a>

User yang menyetujui/menolak *adjustment entry*.

#### <a name="field-validations-date">Date</a>

Tanggal dan waktu **Validated/Rejected By** menyetujui/menolak *adjustment entry*

#### <a name="field-validations-date">Status</a>

Status persetujuan, terdiri dari 2 (dua) kemungkinan:

1. **Approved**. Tier disetujui.
2. **Rejected**. Tier ditolak.

#### <a name="tab-policies">TAB POLICIES</a>

![](../../img/adjustment-entry/tab-policies.png)

#### <a name="field-confirm">Can Confirm</a>

Berhak/tidaknya user aktif untuk dapat mengkonfirmasi adjustment entry.

#### <a name="field-reject">Can Reject</a>

Berhak/tidaknya user aktif untuk dapat menolak adjustment entry.

#### <a name="field-restart-approval">Can Restart Approval</a>

Berhak/tidaknya user aktif untuk dapat merestart persetujuan adjustment entry.

#### <a name="field-cancel">Can Cancel</a>

Berhak/tidaknya user aktif untuk dapat membatalkan adjustment entry.

#### <a name="field-restart">Can Restart</a>

Berhak/tidaknya user aktif untuk dapat merestart adjustment entry.

#### <a name="tab-logs">TAB LOGS</a>

![](../../img/adjustment-entry/tab-logs.png)

#### <a name="field-confirmation">Confirmation</a>

Waktu konfirmasi dan user yang mengkonfirmasi adjustment entry.

#### <a name="field-rejection">Rejection</a>

Waktu konfirmasi dan user yang menolak adjustment entry.

#### <a name="field-cancellation">Cancellation</a>

Waktu batal dan user yang membatalkan adjustment entry.
