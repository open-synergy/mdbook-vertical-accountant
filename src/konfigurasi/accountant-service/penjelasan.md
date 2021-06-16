# Penjelasan Accountant Service

Informasi pada *Accountant Service* dibagi menjadi beberapa bagian, yaitu:

* [Header](#bagian-header)
* [Tab Python Code](#tab-python-code)
* [Tab Signing Partner](#tab-signing-partner)
* [Tab Opinions](#tab-opinions)
* [Tab Quality Control](#tab-quality-control)
* [Tab Methods](#tab-methods)
* [Tab Policy](#tab-policy)
* [Tab Description](#tab-description)

### <a name="bagian-header">HEADER</a>

![](../../img/accountant-service/bagian-header.png)

#### <a name="field-name">Name</a>

Nama jasa yang diberikan oleh akuntan.

#### <a name="field-internal-ref">Internal Reference</a>

Nomor referensi Internal.

#### <a name="field-active">Active</a>

Penanda status accountant service aktif.

#### <a name="field-assurance-service">Assurance Service</a>

Jasa assurance apabila aktif. Jasa non-assurance apabila tidak aktif.

#### <a name="field-code">Code</a>

Kode accountant service.

#### <a name="field-sequence-creation">Sequence Creation Method</a>

Metode nomor urut pembuatan accountant service. Metode terdiri dari 2 (dua) pilihan, yaitu:

1. *Standard*. Nomor urut ditentukan secara standar.
2. *Python Code*. Nomor urut ditentukan secara kustom berdasarkan kode Python.

#### <a name="tab-python-code">TAB PYTHON CODE</a>

![](../../img/accountant-service/tab-python-code.png)

#### <a name="field-python-code">Python Code for Custom Sequence Generation</a>

Kode Python untuk membuat nomor urut yang diinginkan.

#### <a name="tab-signing-partner">TAB SIGNING PARTNER</a>

![](../../img/accountant-service/tab-signing-partner.png)

#### <a name="field-signing-partner-table">Tabel Signing Partner</a>

Daftar akuntan publik yang diperbolehkan untuk bertanggung jawab terhadap jasa

*Pop Up Signing Partner* saat *add an item* diklik.

![](../../img/accountant-service/tab-signing-partner-detail.png)

#### <a name="field-signing-partner">Signing Partner</a>

Nama akuntan publik.

#### <a name="field-sequence">Sequence</a>

Nomor urut.

#### <a name="field-allowed-to-confirm">Allowed To Confirm</a>

Daftar kelompok pengguna yang diperbolehkan untuk mengkonfimasi accountant report dengan signing partner yang sesuai dengan isian Signing Partner dan jasa terkait.

#### <a name="field-allowed-to-finalization">Allowed To Finalization</a>

Daftar kelompok pengguna yang diperbolehkan untuk memfinalisasi accountant report dengan signing partner yang sesuai dengan isian Signing Partner dan jasa terkait.

#### <a name="field-allowed-to-validate">Allowed To Validate</a>

Daftar kelompok pengguna yang diperbolehkan untuk memvalidasi accountant report dengan signing partner yang sesuai dengan isian Signing Partner dan jasa terkait.

#### <a name="field-allowed-to-cancel">Allowed To Cancel</a>

Daftar kelompok pengguna yang diperbolehkan untuk membatalkan accountant report dengan signing partner yang sesuai dengan isian Signing Partner dan jasa terkait.

#### <a name="field-allowed-to-restart">Allowed To Restart</a>

Daftar kelompok pengguna yang diperbolehkan untuk merestart accountant report dengan signing partner yang sesuai dengan isian Signing Partner dan jasa terkait.

#### <a name="tab-opinions">TAB OPINIONS</a>

![](../../img/accountant-service/tab-opinions.png)

#### <a name="field-opinion-required">Opinion Required</a>

Laporan akhir jasa membutuhkan opini apabila aktif. Laporan akhir jasa tidak membutuhkan opini apabila tidak aktif.

#### <a name="field-opinion-table">Tabel Opinion</a>

Daftar opini yang boleh diberikan terkait jasa.

#### <a name="tab-quality-control">TAB QUALITY CONTROL</a>

![](../../img/accountant-service/tab-quality-control.png)

#### <a name="field-quality-control-table">Tabel Quality Control</a>

Daftar item-item yang harus diuji terhadap laporan akhir jasa.

*Pop Up Questions* saat *add an item* diklik.

![](../../img/accountant-service/tab-quality-control-detail-quantitative.png)
![](../../img/accountant-service/tab-quality-control-detail-qualitative.png)

#### <a name="field-question">Question</a>

Item pertanyaan untuk kontrol kualitas.

#### <a name="field-question-sequence">Sequence</a>

Urutan pertanyaan.

#### <a name="field-question-type">Type</a>

Tipe jawaban untuk kontrol kualitas (kuantitatif atau kualitatif).

***Type Quantitative***

#### <a name="field-min-value">Min. Value</a>

Nilai minimum jawaban.

#### <a name="field-max-value">Max. Value</a>

Nilai maksimum jawaban.

***Type Qualitative***

#### <a name="field-value">Value</a>

Jawaban.

#### <a name="field-correct-answer">Correct Answer</a>

Penanda jawaban yang benar.

#### <a name="tab-methods">TAB METHODS</a>

![](../../img/accountant-service/tab-methods.png)

#### <a name="field-method-required">Method Required</a>

Penyelesaian jasa membutuhkan penggunaan metode tertentu apabila aktif. Penyelesaian jasa tidak membutuhkan penggunaan metode tertentu apabila tidak aktif.

#### <a name="field-method-table">Tabel Method</a>

Daftar metode yang dapat dipergunakan untuk menyelesaikan jasa.

#### <a name="tab-policy">TAB POLICY</a>

![](../../img/accountant-service/tab-policy.png)

#### <a name="field-allowed-confirm">Allowed To Confirm</a>

Daftar kelompok pengguna yang diperbolehkan untuk mengkonfimasi accountant report dengan jasa terkait.

#### <a name="field-allowed-finalization">Allowed To Finalization</a>

Daftar kelompok pengguna yang diperbolehkan untuk memfinalisasi accountant report dengan jasa terkait.

#### <a name="field-allowed-validate">Allowed To Validate</a>

Daftar kelompok pengguna yang diperbolehkan untuk memvalidasi accountant report dengan jasa terkait.

#### <a name="field-allowed-cancel">Allowed To Cancel</a>

Daftar kelompok pengguna yang diperbolehkan untuk membatalkan accountant report dengan jasa terkait.

#### <a name="field-allowed-restart">Allowed To Restart</a>

Daftar kelompok pengguna yang diperbolehkan untuk merestart accountant report dengan jasa terkait.

#### <a name="tab-description">TAB DESCRIPTION</a>

![](../../img/accountant-service/tab-description.png)

#### <a name="field-description">Description</a>

Deskripsi accountant service.
