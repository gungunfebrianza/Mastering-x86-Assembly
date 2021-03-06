<h1>1.1 Introduction to x86 Assembly Language</h1>

<h3>1.1.1 Welcome to Assembly Language</h3>

<p><i><strong>Assembly Language</strong></i> untuk <i><strong>x86 Processors</strong></i> ini fokus pada pemograman <i><strong>microprocessor</strong></i> yang kompatible dengan Intel dan AMD Processor yang berjalan pada sistem operasi <i><strong>Microsoft Windows</strong></i> versi 32 bit dan 64 bit.</p>

<p>Dari semua bahasa pemograman Bahasa Assembly adalah bahasa pemograman tertua didunia. Bahasa Assembly menyediakan akses secara langsung kedalam <i><strong>Hardware Computer</strong></i>, sehingga sebelum mempelajarinya kita harus benar benar sudah/sambil mempelajari <i><strong>Computer Architecture</strong></i> dan <i><strong>Operating System.</strong></i>Tulisan ini akan mengkaji tentang prinsip dasar sebuah <i><strong>Computer Architecture</strong></i>, <i><strong>Machine Language</strong></i> dan <i><strong>Low Level Language Programming</strong></i>.</p>

<h3>1.1.2 What Background should i have?</h3>
<p>Sebelum mempelajari buku ini, setidaknya sebelumnya anda pernah mempelajari bahasa pemograman terstruktur (High Level Language Programming) seperti C, C++, Python, java. Tau bagaimana cara menggunakan IF Statemant, Array, dan Function untuk menyelesaikan beberapa masalah. </p>

<h3>1.1.3 What Are Assemblers and Linkers?</h3>
<p><i><strong>Assembler</strong></i> adalah sebuah program yang akan mengkonversi sebuah <i><strong>Source Code</strong></i> yang dibuat dengan <i><strong>Assembly Language</strong></i> ke <i><strong>Machine Language</strong></i>. <i><strong>Linker</strong></i> adalah sebuah program yang menggabungkan file yang dibuat oleh <i><strong>Assembler</strong></i> menjadi sebuah program <i><strong>Executable</strong></i>. Selain itu ada pula yang disebut dengan <i><strong>Debugger</strong></i> yang membuat kita bisa menganalisa sebuah program yang sedang berjalan untuk mengkaji <i><strong>Register</strong></i> dan <i><strong>Memory</strong></i>.</p>

<h3>1.1.4 What Hardware and Software Do I Need?</h3>
<p>Komputer yang berjalan menggunakan sistem operasi 32 bit atau 64 bit <i><strong>Microsoft Windows</strong></i> dan <i><strong>Microsoft Visual Studio 2012</strong></i>. Selanjutnya adalah <i><strong>MASM (Microsoft Macro Assembler)</strong></i> biasanya MASM sudah disertakan disetiap paket <i><strong>Microsoft Visual Studio 2012</strong></i> baik itu versi pro, ultimate ataupun express. Selain itu ada lagi <i><strong>Assembler</strong></i> untuk sistem x86 yang berjalan pada <i><strong>Operating System</strong></i> <i><strong>Microsoft Windows</strong></i> seperti <i><strong>TASM (Turbo Assembler)</strong></i>, <i><strong>NASM (Netwide Assembler)</strong></i>, dan <i><strong>MASM32</strong></i> (varian MASM) dan untuk <i><strong>Operating System</strong></i> <i><strong>Linux</strong></i> ada dua <i><strong>Assembler</strong></i> yang popular diantaranya adalah <i><strong>GAS (GNU Assembler)</strong></i> dan <i><strong>NASM (Netwide Assembler)</strong></i>.</p>

<h3>1.1.5 What Types of Programs Can Be Created Using MASM?</h3>
<ul>
<li><i><strong>32 Bit Protected Mode:</strong></i> Program ini berjalan disemua <i><strong>Operating System</strong></i> <i><strong>Microsoft Windows</strong></i> versi 32 bit. </li>
<li><i><strong>64 Bit Mode:</strong></i> Program ini berjalan disemua <i><strong>Operating System</strong></i> <i><strong>Microsoft Windows</strong></i> versi 64 bit.</li>
<li><i><strong>16 Bit Real Address Mode:</strong></i> 16 Bit Program berjalan disemua <i><strong>Operating System</strong></i> <i><strong>Microsoft Windows</strong></i> versi 32 bit dan <i><strong>Embedded System</strong></i> (not supported for 64 bit).</li>
</ul>

<h3>1.1.6 What Will I Learn?</h3>
<ol>
<li>Prinsip dasar <i><strong>Computer Architecture</strong></i> yang diterapkan pada <i><strong>x86 Processors</strong></i>.</li>
<li>Dasar <i><strong>Boolean Logic</strong></i> dan penerapanya dalam pemograman dan <i><strong>Hardware Computer</strong></i>.</li>
<li>Bagaimana sebuah <i><strong>x86 Processors</strong></i> melakukan manajemen <i><strong>Memory</strong></i> menggunakan <i><strong>Protected Mode</strong></i> dan <i><strong>Virtual Mode</strong></i>.</li>
<li>Bagaimana sebuah <i><strong>Compiler</strong></i> untuk <i><strong>High Level Language Programming</strong></i> seperti C++ diterjemahkan kedalam  <i><strong>Assembly Language</strong></i> dan <i><strong>Native Machine Code</strong></i>.</li>
<li>Bagaimana sebuah <i><strong>High Level Language Programming</strong></i> mengimplementasikan sebuah <i><strong>Arithmetic Expressions</strong></i>, <i><strong>Loops</strong></i> dan <i><strong>Logical Structures</strong></i> pada <i><strong>Machine Level</strong></i>.</li>
<li><i><strong>Data Representation</strong></i> termasuk <i><strong>Signed & Unsigned Integer, Real Number & Character</strong></i>.</li>
<li>Bagaimana cara melakukan <i><strong>Debug</strong></i> pada <i><strong>Machine Level</strong></i>, kemampuan ini sangat dibutuhkan dan sangat vital jika kita menggunakan bahasa pemograman seperti c dan c++.  </li>
<li>Bagaimana Sebuah <i><strong>Application Program</strong></i> berkomunikasi dengan <i><strong>Operating System</strong></i> pada sebuah komputer melalui <i><strong>Interupt Handlers</strong></i> dan <i><strong>System Calls</strong></i>.</li>
<li>Bagaimana cara melakukan <i><strong>Interface</strong></i> dari <i><strong>Assembly Language</strong></i> ke C++ Program.</li>
<li>Bagaimana cara membuat <i><strong>Application Programs</strong></i> menggunakan <i><strong>Assembly Language</strong></i>.</li>
</ol>

<h3>1.1.7 How Does Assembly Language Relate to Machine Language?</h3>
<p><i><strong>Machine Language</strong></i> adalah sebuah <i><strong>Numeric Language</strong></i> yang secara spesifik oleh computer processor (CPU). Seluruh <i><strong>x86 Processor</strong></i> memahami <i><strong>Machine Language</strong></i> secara umum. <i><strong>Assembly Language</strong></i> terdiri dari sekumpulan statement yang ditulis dengan tehnik <i><strong>Mnemonic</strong></i> seperti ADD, MOV, SUB dan CALL. <i><strong>Assembly Language</strong></i> mempunyai relasi satu-ke-satu (one to one) dengan <i><strong>Machine Language</strong></i> yang berarti setiap satu instruksi yang dibuat menggunakan <i><strong>Assembly Language</strong></i> mengacu pada satu <i><strong>Machine-language Instruction</strong></i>. </p>

<h3>1.1.8 How Do C++ and Java Relate to Assembly Language?</h3>
<p><i><strong>High Level Language Programming</strong></i> seperti c, c++, python dan java mempunyai satu-ke-banyak (one to many) relasi dengan <i><strong>Assembly Language</strong></i> dan <i><strong>Machine Language</strong></i>. Sebuah Statement satu baris yang dibuat menggunakan C++ akan mengembang jika diterjemahkan kedalam <i><strong>Assembly Language</strong></i> dan <i><strong>Machine-language Instruction</strong></i>. Dibawah ini adalah dua buah statement dengan C++ code yang didalamnya terdapat <i><strong>Arithmetic Operation</strong></i> dan hasilnya ditetapkan kedalam sebuah <i><strong>Variable</strong></i> dengan asumsi X dan Y adalah <i><strong>Integer</strong></i> :</p>

```C++
int Y;
int X = (Y + 4) * 3;
```
<p>Jika diterjemahkan kedalam <i><strong>Assembly Language</strong></i> maka dibutuhkan banyak statement code seperti dibawah ini :</p>

```Assembly
mov eax,Y ; Pindahkan Y ke EAX register
add eax,4 ; Tambah nilai 4 ke EAX register
mov ebx,3 ; Pindahkan 3 ke EBX register
imul ebx ; Kalikan EAX dengan EBX
mov X,eax ; Pindahkan EAX ke X
```
<p>Selanjutnya dari bahasa assembly akan diterjemahkan kedalam bahasa mesin dengan relasi satu ke satu, artinya dari setiap satu instruksi yang dibuat menggunakan bahasa assembly mengacu pada satu <i><strong>Machine-language Instruction</strong></i> yang selanjutnya menjadi sinyal listrik (<i><strong>Digital Signal</strong></i>). <i><strong>Register</strong></i> adalah nama sebuah lokasi didalam CPU yang menyimpan sebuah hasil sementara.</p>

<h3>1.1.9 Is Assembly Language Portable?</h3>
<p>Sebuah bahasa yang <i><strong>Source Code</strong></i> programnya bisa dikompilasi dan berjalan dihampir semua sistem komputer maka ia dikatakan <i><strong>Portable</strong></i>. <i><strong>Assembly Language</strong></i> adalah bahasa yang tidak <i><strong>Portable</strong></i> karena ini didesain secara khusus untuk <i><strong>Processor Family</strong></i> tertentu. Ada beberapa perbedaan pada <i><strong>Assembly Language</strong></i> yang digunakan saat ini mengacu pada setiap <i><strong>Processor Family</strong></i> itu sendiri. Beberapa <i><strong>Processor Family</strong></i> yang terkenal adalah Motorola 68x00, x86, SUN Sparc, Vax, dan IBM-370, setiap instruksi dari <i><strong>Assembly Language</strong></i> secara langsung akan sama pada <i><strong>Computer Architecture</strong></i> yang dituju atau akan diterjemahkan terlebih dahulu saat proses eksekusi menggunakan sebuah program Pocessor yang disebut dengan <i><strong>Microcode Interpreter</strong></i>.</p>

<h3>1.1.10 Why Learn Assembly Language?</h3>
<ol>
<p>Advantages</p>
<li>Jika kita seorang computer engineer yang sedang menuntut ilmu dengan bidang <i><strong>Computer Engineering</strong></i>. Kita akan sering membuat sebuah <i><strong>Embedded Programs</strong></i>, sebuah program pendek yang disimpan didalam memori dengan ukuran yang sangat kecil dan terbatas untuk membuat sebuah alat tertentu seperti Telephones, Automobile Fuel & Ignition Systems, Air-conditioning Control Systems, Security Systems, Data Acquisition Instruments, Video Cards, Sound Cards, Hard Drives, Modems, dan Printers. <i><strong>Assembly Language</strong></i> sangat ideal jika digunakan untuk membuat sebuah  <i><strong>Embedded Programs</strong></i> dikarenakan hemat dalam penggunaan memory. </li>
<li><i><strong>Real-Time Application</strong></i> yang berinteraksi dengan <i><strong>Simulation and Hardware Monitoring</strong></i> memerlukan <i><strong>Timing and Responses</strong></i> yang tepat. <i><strong>High Level Language Programming</strong></i> tidak memberikan kesempatan pada Programmer untuk melakukan kontrol secara tepat melalui <i><strong>Native Machine Code</strong></i> yang dihasilkan sebuah <i><strong>Compiler</strong></i>. <i><strong>Assembly Language</strong></i>.</li>
<li>Pada Game Komputer secara khusus diperlukan optimasi agar kode yang dibuat ukuranya bisa kecil agar eksekusi bisa dilakukan dengan cepat. Game Programmer yang sudah mahir atau expert akan mengambil manfaat penuh dari kemampuan hardware yang akan menjadi target sistemnya menggunakan <i><strong>Assembly Language</strong></i> karena sanggup untuk mengakses secara langsung kedalam <i><strong>Hardware Computer</strong></i> dan kode bisa dioptimasi agar eksekusi menjadi sangat cepat.</li>
<li><i><strong>Assembly Language</strong></i> membantu kita untuk meningkatkan pemahaman secara menyeluruh tentang interaksi antara <i><strong>Computer Hardwares</strong></i>, <i><strong>Operating Systems</strong></i> dan <i><strong>Application Programs</strong></i>. Dengan <i><strong>Assembly Language</strong></i> kita bisa menerapkan dan menguji informasi secara teoritis yang telah/sedang kita pelajari dalam keilmuan <i><strong>Computer Architecture</strong></i> dan <i><strong>Operating System</strong></i>.</li>
<li>Beberapa bahasa pemograman tingkat tinggi atau <i><strong>High Level Language Programming</strong></i> memiliki abstract dalam representasi datanya sehingga sulit sekali untuk melakukan <i><strong>Bit Manipulation</strong></i>.</li>
<li>Industri perangkat keras atau <i><strong>Hardware Manufacturers</strong></i> membuat sebuah <i><strong>Device Driver</strong></i> sebagai bagian dari peralatan dalam sistem komputer untuk dijual. <i><strong>Device Driver</strong></i> adalah sebuah program yang menterjemahkan <i><strong>General Operating System Command</strong></i> kedalam referensi spesifik sebuah hardware. Sebagai contoh pada Printer Manufacture, mereka membuat sebuah <i><strong>Device Driver</strong></i> yang berbeda-beda pada masing masing versi <i><strong>Microsoft Windows</strong></i>, seringkali setiap <i><strong>Device Driver</strong></i> didalamnya terdapat <i><strong>Assembly Language code</strong></i> dengan jumlah dan konten yang berbeda-beda.</li>
</ol>

<h3>1.1.11 Are There Rules in Assembly Language?</h3>
<p>Aturan dalam penggunaan <i><strong>Assembly Language</strong></i> didasari oleh <i><strong>Physical Limitations</strong></i> dari target processor dan <i><strong>Machine Language</strong></i> itu sendiri. Sebagai contoh pada sebuah CPU dibutuhkan dua instruksi operan dengan ukuran yang sama. <i><strong>Assembly Language</strong></i> mempunyai sedikit aturan, berbeda dengan C++ atau Java karena aturan penggunaan sintaknya mampu mengurangi kesalahan logika yang tidak diinginkan dengan mengorbankan akses data tingkat rendah. <i><strong>Assembly Language Programmer</strong></i> dapat dengan mudah melewati karakteristik pembatasan pada <i><strong>High Level Language Programming</strong></i>, sebagai contoh pada Java yang tidak mengizinkan kita untuk dapat mengakses alamat memori tertentu secara spesifik sedangkan dengan <i><strong>Assembly Language</strong></i> kita bisa secara langsung mengakses alamat memori tertentu.</p>

<h3>1.1.12 Assembly Language Application</h3>
<p>Di awal-awal dunia pemograman, kebanyakan aplikasi ditulis secara sebagian sebagian atau seluruhnya menggunakan <i><strong>Assembly Language</strong></i>, karena kemampuanya yang pas untuk memori yang memiliki kapasitas terbatas sehingga bisa berjalan secara efektif dalam processor yang memiliki kecepatan lamban. Saat <i><strong>Memory</strong></i> menjadi semakin meningkat kapasitasnya begitu juga dengan <i><strong>Processor</strong></i> yang secara dramatis kecepatanya meningkat maka program program yang dibuatpun menjadi semakin kompleks. Banyak programmer berpindah ke bahasa yang lebih tinggi seperti bahasa C, Fotran dan Cobol yang memiliki kemampuan yang lebih baik, kemudian muncul bahasa pemograman berorientasi objek seperti Python, C++, C# dan Java yang memiliki kemampuan untuk membuat sebuah program complex yang mengandung jutaan baris code.</p>

<p>Jadi sangat langka jika ada sebuah aplikasi dlaam bentuk skala besar yang diprogram  menggunakan <i><strong>Assembly Language</strong></i> karena ini akan menyita waktu yang sangat lama saat proses coding dan pemeliharaan kode untuk pengembangan selanjutnya. Sehingga <i><strong>Assembly Language</strong></i> lebih digunakan untuk optimasi bagian tertentu didalam sebuah aplikasi untuk kecepatan dan akses secara langsung kedalam <i><strong>Hardware Computer</strong></i>. Dibawah ini adalah sebuah table yang membandingkan penyesuaian implementasi <i><strong>Assembly Language</strong></i> ke <i><strong>High Level Language Programming</strong></i> dari segi perbedaan tipe dalam pengaplikasianya.</p>


| Type of Application        | High Level Language           | Assembly Language  |
| ------------- |:-------------:| -----:|
| Komersil, Scientific Application, Single Platform, medium to large size      | Lebih Powerful untuk digunakan, sehingga mudah untuk mengatur dan memelihara bagian bagian kodenya meskipun ukuran kode besar| Tidak Cocok |
| Hardware Device Driver      | Tidak Cocok karena bahasa tingkat tinggi tidak menyediakan kemampuan untuk bisa mengakses perangkat keras, jikalaupun bisa akan menggunakan cara yang tidak disarankan yang dapat mempersulit proses pemeliharaan lebih lanjut.      |   Sangat powerful karena mampu mengakses perangkat keras secara langsung dengan mudah. Mudah sekali dikelola jika ukuran program kecil dan didokumentasikan dengan baik. |
| Komersil, Scientific Application, Multiple Platform | Portable, source code bisa dikompilasi ulang untuk setiap sistem operasi dengan perubahan yang minim      |    Tidak Portable, code harus dibuat lagi khusus untuk setiap platform menggunakan assembler yang berbeda beda sehingga sulit sekali untuk dikelola |
| Embedded System dan game komputer | Kemungkinan besar akan menghasilkan kode dalam ukuran yang sangat besar dan tak sanggup untuk ditampung kedalam memory.      |    Ideal sebab executable code ukuranya kecil dan dapat berjalan dengan cepat. |

<i><strong></strong></i>

<ul>
<p><strong>Glossary :</strong></p>
<li><i><strong>Assembly Language</strong></i></li>
<li><i><strong>x86 Processor</strong></i></li>
<li><i><strong>Microprocessor</strong></i></li>
<li><i><strong>Microsoft Windows</strong></i></li>
<li><i><strong>Hardware Computer</strong></i></li>
<li><i><strong>Computer Architecture</strong></i></li>
<li><i><strong>Operating System</strong></i></li>
<li><i><strong>Machine Language</strong></i></li>
<li><i><strong>Low Level Language Programming</strong></i></li>
<li><i><strong>High Level Language Programming</strong></i></li>
<li><i><strong>Assembler</strong></i></li>
<li><i><strong>Linker</strong></i></li>
<li><i><strong>Source Code</strong></i></li>
<li><i><strong>Executable</strong></i></li>
<li><i><strong>Debugger</strong></i></li>
<li><i><strong>Register</strong></i></li>
<li><i><strong>Memory</strong></i></li>
<li><i><strong>Microsoft Visual Studio 2012</li>
<li><i><strong>MASM (Microsoft Macro Assembler)</strong></i></strong></i></li>
<li><i><strong>TASM (Turbo Assembler)</strong></i></li>
<li><i><strong>NASM (Netwide Assembler)</strong></i></li>
<li><i><strong>Linux</strong></i></li>
<li><i><strong>GAS (GNU Assembler)</strong></i></li>
<li><i><strong>32 Bit Protected Mode</strong></i></li>
<li><i><strong>64 Bit Mode</strong></i></li>
<li><i><strong>16 Bit Real Address Mode</strong></i></li>
<li><i><strong>Embedded System</strong></i></li>
<li><i><strong>Boolean Logic</strong></i></li>
<li><i><strong>Protected Mode</strong></i></li>
<li><i><strong>Virtual Mode</strong></i></li>
<li><i><strong>Compiler</strong></i></li>
<li><i><strong>Native Machine Code</strong></i></li>
<li><i><strong>Arithmetic Expressions</strong></i></li>
<li><i><strong>Loops</strong></i></li>
<li><i><strong>Logical Structures</strong></i></li>
<li><i><strong>Machine Level</strong></i></li>
<li><i><strong>Data Representation</strong></i></li>
<li><i><strong>Signed & Unsigned Integer</strong></i></li>
<li><i><strong>Real Number</strong></i></li>
<li><i><strong>Character</strong></i></li>
<li><i><strong>Debug</strong></i></li>
<li><i><strong>Application Program</strong></i></li>
<li><i><strong>Interupt Handlers</strong></i></li>
<li><i><strong>System Calls</strong></i></li>
<li><i><strong>Mnemonic</strong></i></li>
<li><i><strong>Machine-language Instruction</strong></i></li>
<li><i><strong>Arithmetic Operation</strong></i></li>
<li><i><strong>Integer</strong></i></li>
<li><i><strong>Register</strong></i></li>
<li><i><strong>Digital Signal</strong></i></li>
<li><i><strong>Portable</strong></i></li>
<li><i><strong>Processor Family</strong></i></li>
<li><i><strong>Microcode Interpreter</strong></i></li>
<li><i><strong>Computer Engineering</strong></i></li>
<li><i><strong>Simulation and Hardware Monitoring</strong></i></li>
<li><i><strong>Timing and Responses</strong></i></li>
<li><i><strong>Bit Manipulation</strong></i></li>
<li><i><strong>Hardware Manufacturers</strong></i></li>
<li><i><strong>Device Driver</strong></i></li>
<li><i><strong>General Operating System Command</strong></i></li>
<li><i><strong>Physical Limitations</strong></i></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
</ul>

<p>Source : Assembly Language for X86 Processor - Kiv Irvine</p>
