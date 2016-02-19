<h1>Introduction to x86 Assembly Language</h1>

<h3>Welcome to Assembly Language</h3>

<p><i><strong>Assembly Language</strong></i> untuk <i><strong>x86 Processors</strong></i> ini fokus pada pemograman <i><strong>microprocessor</strong></i> yang kompatible dengan Intel dan AMD Processor yang berjalan pada sistem operasi <i><strong>Microsoft Windows</strong></i> versi 32 bit dan 64 bit.</p>

<p>Dari semua bahasa pemograman Bahasa Assembly adalah bahasa pemograman tertua didunia. Bahasa Assembly menyediakan akses secara langsung kedalam <i><strong>Hardware Computer</strong></i>, sehingga sebelum mempelajarinya kita harus benar benar sudah/sambil mempelajari <i><strong>Computer Architecture</strong></i> dan <i><strong>Operating System.</strong></i>Tulisan ini akan mengkaji tentang prinsip dasar sebuah <i><strong>Computer Architecture</strong></i>, <i><strong>Machine Language</strong></i> dan <i><strong>Low Level Language Programming</strong></i>.</p>

<h3>What Background should i have?</h3>
<p>Sebelum mempelajari buku ini, setidaknya sebelumnya anda pernah mempelajari bahasa pemograman terstruktur (High Level Language Programming) seperti C, C++, Python, java. Tau bagaimana cara menggunakan IF Statemant, Array, dan Function untuk menyelesaikan beberapa masalah. </p>

<h3>What Are Assemblers and Linkers?</h3>
<p><i><strong>Assembler</strong></i> adalah sebuah program yang akan mengkonversi sebuah <i><strong>Source Code</strong></i> yang dibuat dengan <i><strong>Assembly Language</strong></i> ke <i><strong>Machine Language</strong></i>. <i><strong>Linker</strong></i> adalah sebuah program yang menggabungkan file yang dibuat oleh <i><strong>Assembler</strong></i> menjadi sebuah program <i><strong>Executable</strong></i>. Selain itu ada pula yang disebut dengan <i><strong>Debugger</strong></i> yang membuat kita bisa menganalisa sebuah program yang sedang berjalan untuk mengkaji <i><strong>Register</strong></i> dan <i><strong>Memory</strong></i>.</p>

<h3>What Hardware and Software Do I Need?</h3>
<p>Komputer yang berjalan menggunakan sistem operasi 32 bit atau 64 bit <i><strong>Microsoft Windows</strong></i> dan <i><strong>Microsoft Visual Studio 2012</strong></i>. Selanjutnya adalah <i><strong>MASM (Microsoft Macro Assembler)</strong></i> biasanya MASM sudah disertakan disetiap paket <i><strong>Microsoft Visual Studio 2012</strong></i> baik itu versi pro, ultimate ataupun express. Selain itu ada lagi <i><strong>Assembler</strong></i> untuk sistem x86 yang berjalan pada <i><strong>Operating System</strong></i> <i><strong>Microsoft Windows</strong></i> seperti <i><strong>TASM (Turbo Assembler)</strong></i>, <i><strong>NASM (Netwide Assembler)</strong></i>, dan <i><strong>MASM32</strong></i> (varian MASM) dan untuk <i><strong>Operating System</strong></i> <i><strong>Linux</strong></i> ada dua <i><strong>Assembler</strong></i> yang popular diantaranya adalah <i><strong>GAS (GNU Assembler)</strong></i> dan <i><strong>NASM (Netwide Assembler)</strong></i>.</p>

<h3>What Types of Programs Can Be Created Using MASM?</h3>
<ul>
<li><i><strong>32 Bit Protected Mode:</strong></i> Program ini berjalan disemua <i><strong>Operating System</strong></i> <i><strong>Microsoft Windows</strong></i> versi 32 bit. </li>
<li><i><strong>64 Bit Mode:</strong></i> Program ini berjalan disemua <i><strong>Operating System</strong></i> <i><strong>Microsoft Windows</strong></i> versi 64 bit.</li>
<li><i><strong>16 Bit Real Address Mode:</strong></i> 16 Bit Program berjalan disemua <i><strong>Operating System</strong></i> <i><strong>Microsoft Windows</strong></i> versi 32 bit dan <i><strong>Embedded System</strong></i> (not supported for 64 bit).</li>
</ul>

<h3>What Will I Learn?</h3>
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

<i><strong></strong></i>

<ul>
Glossary :
<li>Assembly Language</li>
<li>x86 Processor</li>
<li>Microprocessor</li>
<li>Microsoft Windows</li>
<li>Hardware Computer</li>
<li>Computer Architecture</li>
<li>Operating System</li>
<li>Machine Language</li>
<li>Low Level Language Programming</li>
<li>High Level Language Programming</li>
<li>Assembler</li>
<li>Linker</li>
<li>Source Code</li>
<li>Executable</li>
<li>Debugger</li>
<li>Register</li>
<li>Memory</li>
<li>Microsoft Visual Studio 2012</li>
<li>MASM (Microsoft Macro Assembler)</li>
<li>TASM (Turbo Assembler)</li>
<li>NASM (Netwide Assembler)</li>
<li>Linux</li>
<li>GAS (GNU Assembler)</li>
<li>32 Bit Protected Mode</li>
<li>64 Bit Mode</li>
<li>16 Bit Real Address Mode</li>
<li>Embedded System</li>
<li>Boolean Logic</li>
<li>Protected Mode</li>
<li>Virtual Mode</li>
<li>Compiler</li>
<li>Native Machine Code</li>
<li>Arithmetic Expressions</li>
<li>Loops</li>
<li>Logical Structures</li>
<li>Machine Level</li>
<li>Data Representation</li>
<li>Signed & Unsigned Integer</li>
<li>Real Number</li>
<li>Character</li>
<li>Debug</li>
<li>Application Program</li>
<li>Interupt Handlers</li>
<li>System Calls</li>
<li></li>
<li></li>
</ul>
