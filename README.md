### Stacked-Bar-Chart
1.	Stacked Bar Chart
II.	Jenis Chart : Bar
II.	Option: 
####**Title**####
5.	title : text (string) : untuk membuat judul pada echart.
6.	title: subtext (string) : untuk membuat subtext pada baris baru.
7.	title: sublink (string) : text yang support untuk hyperlink.
8.	title : link (string) : untuk berpindahan halaman dengan menggunakan text.
9.	title : padding (number) : membuat ruang di sekitar text.
10.	title : backgroundColor (color) : mengubah warna belakang sebuah objek.
11.	title : borderColor (color) : mengubah warna area pinggir pada objek.
12.	title : shadowBlur (number) : membuat bayangan objek menjadi blur.
13.	title : shadowColor (color) : mengubah warna bayangan objek.
14.	title : shadowOffsetX (number) : jarak bayangan horizontal.
15.	title : shadowOffsetY (number) : jarak bayangan vertikal.
16.	title : textAlign (string) : menentukan posisi huruf (left,center,right).
17.	title : textBaseLine (string) : mengatur posisi text dalam vertical (middle,top,bottom).
18.	title : textStyle : color(string) : untuk mengubah warna pada text.
19.	title : textStyle : fontSize(number) : untuk mengubah ukuran text (default=18).
20.	title : textStyle : fontStyle(string) : italic : mengubah huruf menjadi miring.
21.	title : textStyle : fontWeight (string) : bold : membuat text menjadi tebal.
22.	title : textStyle : fontWeight (string) : lighter : membuat text menjadi tipis.
23.	title : textStyle : fontFamily (string) : mengubah jenis font.

####**Legend**####
1.	legend : left (string,number) : jarak objek dari sebelah kiri.
2.	legend : right (string,number) : jarak objek dari sebelah kanan.
3.	legend : top (string,number) : jarak objek dari sebelah atas.
4.	legend : bottom (string,number) : jarak objek dari sebelah bawah.
5.	legend : width (string,number) : menentukan lebar komponen legend.
6.	legend : height (string,number) : menentukan panjang komponen legend.
7.	legend : orient (string) : mengatur letak orientasi legend (horizontal,vertical).
8.	legend : align (string) : menentukan posisi text (auto,left,right).
9.	legend : padding (number) : membuat ruang di sekitar text.
10.	legend : itemGap (number) : jarak antara masing-masing legend, jarak horizontal dalam tata letak horizontal, dan jarak vertical dalam tata letak vertical.
11.	legend : itemWidth (number) : lebar gambar simbol legend.
12.	legend : itemHeight (number) : panjang gambar simbol legend.
13.	legend : formatter (string,function) : formatter digunakan untuk memformat label legend, yang mendukung template string dan function callback.
14.	legend : selectedMode (string,boolean) : mode legend yang dipilih, yang mengontrol apakah sama dapat ditampilkan secara bergantian dengan mengklik salah satu legend (single,multiple).
15.	legend : inactiveColor (color) : warna legend pada saat tidak aktif.
16.	legend : textStyle : color(string) : untuk mengubah warna pada text.
17.	legend : textStyle : fontSize(number) : untuk mengubah ukuran text (default=18).
18.	legend : textStyle : fontStyle(string) : italic : mengubah huruf menjadi miring.
19.	legend : textStyle : fontWeight (string) : bold : membuat text menjadi tebal.
20.	legend : textStyle : fontWeight (string) : lighter : membuat text menjadi tipis.
21.	legend : textStyle : fontFamily (string) : mengubah jenis font.
22.	legend : backgroundColor (color) : mengubah warna belakang sebuah objek.
23.	legend : borderColor (color) : mengubah warna area pinggir pada objek.
24.	legend : shadowBlur (number) : membuat bayangan objek menjadi blur.
25.	legend : shadowColor (color) : mengubah warna bayangan objek.
26.	legend : shadowOffsetX (number) : jarak bayangan horizontal.
27.	legend : shadowOffsetY (number) : jarak bayangan vertikal.
28.	legend : data(object/array) : item array biasanya merupakan nama yang mewakili string.

####**Grid**####
1.	grid : left(string/number) : jarak antara komponen grid dan sisi kiri.
2.	grid : right(string/number) : jarak antara komponen grid dan sisi kanan.
3.	grid : bottom(string/number) : jarak antara komponen grid dan sisi bawah.
4.	grid : top(string/number) : jarak antara komponen grid dan sisi atas.
5.	grid : tooltip: trigger (string)none : untuk tidak menampilkan kategori.
6.	grid : tooltip : axisPointer (object) : type (string)  : item konfigurasi untuk indikator axis (line,shadow,cross).
7.	grid : tooltip : formatter (string,function) : formatter dari layer floating tooltip yang mendukung template string dan fungsi callback.
8.	grid : containLabel(boolean) : daerah grid mengandung label sumbu.
9.	grid  : borderColor (color) : mengubah warna area pinggir pada objek.
10.	grid : shadowBlur (number) : membuat bayangan objek menjadi blur.
11.	grid : shadowColor (color) : mengubah warna bayangan objek.
12.	grid : shadowOffsetX (number) : jarak bayangan horizontal.
13.	grid : shadowOffsetY (number) : jarak bayangan vertikal.
14.	grid : tooltip : padding (number) : membuat ruang di sekitar text.
15.	grid : tooltip : textStyle : color(string) : untuk mengubah warna pada text.
16.	grid : tooltip : textStyle : fontSize(number) : untuk mengubah ukuran text (default=18).
17.	grid : tooltip : textStyle : fontStyle(string) : italic : mengubah huruf menjadi miring.
18.	grid : tooltip : textStyle : fontWeight (string) : bold : membuat text menjadi tebal.
19.	grid : tooltip : textStyle : fontWeight (string) : lighter : membuat text menjadi tipis.
20.	grid : tooltip : textStyle : fontFamily (string) : mengubah jenis font.
####**Toolbox**####
1.	toolbox : feature(object) : saveImage(object) : untuk save gambar.
####**xAXis**####
1.	xAxis : type(string) : type dari axis(value,category,time,log).
2.	xAxis : boundaryGap(boolean,array) : batas pada kedua sisi sumbu koordinat. Pengaturan sumbu kategori dan sumbu non-kategori berbeda.
3.	xAxis : position (string) : posisi sumbu xAxis.
4.	xAxis : offset (number) : sumbu x relatif terhadap posisi default. Bisa berguna juga bila multiple xAxis memiliki nilai posisi yang sama.
5.	xAxis : name (string) : membuat text pada sumbu xAxis.
6.	xAxis : nameLocation (string) : menentukan posisi text pada sumbu xAxis (start,middle,end).
7.	xAxis : nameTextStyle : color(string) : untuk mengubah warna pada text.
8.	xAxis : nameTextStyle : fontSize(number) : untuk mengubah ukuran text (default=18).
9.	xAxis : nameTextStyle : fontStyle(string) : italic : mengubah huruf menjadi miring.
10.	xAxis : nameTextStyle : fontWeight (string) : bold : membuat text menjadi tebal.
11.	xAxis : nameTextStyle : fontWeight (string) : lighter : membuat text menjadi tipis.
12.	xAxis : nameTextStyle : fontFamily (string) : mengubah jenis font.
13.	xAxis : nameGap (number) : celah antara nama sumbu dan garis sumbu.
14.	xAxis : nameRotate (number) : rotasi nama sumbu.
15.	xAxis : inverse (boolean) : sumbu yang terbalik.
16.	xAxis : min (number,string) : minimum value sumbu.
17.	xAxis : max (number,string) : maxsimum value sumbu.
18.	xAxis : scale (boolean) : ini hanya tersedia dalam axis numerik, yaitu, type: 'value.
konfigurasi ini tidak tersedia saat min dan max ditetapkan.
19.	xAxis : data(object) : data kategori, tersedia dalam type 'category' axis.
20.	xAxis : axisLine (object) : show (boolean) : memunculkan garis sumbu (true) atau tidak memunculkan garis sumbu (false).
21.	xAxis : axisLine (object) : onZero (boolean) : menentukan sumbu X atau Y terletak pada posisi asal yang lain, dimana value 0 pada sumbu. Berlaku hanya jika sumbu yang lain adalah value type, dan mempunyai value 0 (default=true).
22.	xAxis : axisLine (object) : lineStyle (color) : warna pada garis.
23.	xAxis : axisLine (object) : type (string) : type garis yang digunakan (solid,dashed,dotted).
24.	xAxis : axisLine (object) : shadowBlur (number) : membuat bayangan objek menjadi blur.
25.	xAxis : axisLine (object) : shadowColor (color) : mengubah warna bayangan objek.
26.	xAxis : axisLine (object) : shadowOffsetX (number) : jarak bayangan horizontal.
27.	xAxis : axisLine (object) : shadowOffsetY (number) : jarak bayangan vertikal.
28.	xAxis : axisTick (object) : show (boolean) : untuk menunjukkan tanda sumbu.
29.	xAxis : axisTick (object) : alignWithLabel (boolean) : sejajarkan sumbu dengan label, yang tersedia hanya jika boundaryGap diset menjadi true dalam sumbu kategori.
30.	xAxis : axisLabel (object) : rotate (number) : untuk merotasikan label pada axis.
31.	xAxis : axisLabel (object) : margin (number) : margin antara axis label dan garis sumbu.
32.	xAxis : axisLabel (object) : formatter (string,function) : Formatter dari label sumbu, yang mendukung template string dan fungsi callback. 
33.	xAxis : axisLabel (object) : textStyle (object) : color(string) : untuk mengubah warna pada text.
34.	xAxis : axisLabel (object) : textStyle (object) : fontSize(number) : untuk mengubah ukuran text (default=18).
35.	xAxis : axisLabel (object) : textStyle (object) : fontStyle(string) : italic : mengubah huruf menjadi miring.
36.	xAxis : axisLabel (object) : textStyle (object) : fontWeight (string) : bold : membuat text menjadi tebal.
37.	xAxis : axisLabel (object) : textStyle (object) : fontWeight (string) : lighter : membuat text menjadi tipis.
38.	xAxis : axisLabel (object) : textStyle (object) : fontFamily (string) : mengubah jenis font.
39.	xAxis : align (string) : menentukan posisi huruf (left,center,right).
40.	xAxis : axisLabel (object) : textStyle (object) : baseLine (string) : textStyle (object) : mengatur posisi text dalam vertical (middle,top,bottom).
41.	xAxis : splitLine (object) : show (boolean)  :  nilai sumbu ditampilkan secara default, sedangkan sumbu kategori tidak.
42.	xAxis : splitLine (object) : lineStyle (object) : interval (number,function) : garis pada chart.
43.	xAxis : splitLine (object) : lineStyle (object) : shadowBlur (number) : membuat bayangan objek menjadi blur.
44.	xAxis : splitLine (object) : lineStyle (object) : shadowColor (color) : mengubah warna bayangan objek.
45.	xAxis : splitLine (object) : lineStyle (object) : shadowOffsetX (number) : jarak bayangan horizontal.
46.	xAxis : splitLine (object) : lineStyle (object) : shadowOffsetY (number) : jarak bayangan vertikal.
47.	xAxis : splitLine (object) : lineStyle (object) : color(string) : untuk mengubah warna pada text.
48.	xAxis : splitLine (object) : lineStyle (object) : width (number) : lebar splitLine.
49.	xAxis : splitLine (object) : lineStyle (object) : type (string) : type garis yang digunakan (solid,dashed,dotted).

#####**yAxis**####
1.	yAxis : type(string) : type dari axis(value,category,time,log).
2.	yAxis : boundaryGap(boolean,array) : batas pada kedua sisi sumbu koordinat. Pengaturan sumbu kategori dan sumbu non-kategori berbeda.
3.	yAxis : position (string) : posisi sumbu yAxis.
4.	yAxis : offset (number) : sumbu y relatif terhadap posisi default. Bisa berguna juga bila multiple yAxis memiliki nilai posisi yang sama.
5.	yAxis : name (string) : membuat text pada sumbu xAxis.
6.	yAxis : nameLocation (string) : menentukan posisi text pada sumbu xAxis (start,middle,end).
7.	yAxis : nameTextStyle : color(string) : untuk mengubah warna pada text.
8.	yAxis : nameTextStyle : fontSize(number) : untuk mengubah ukuran text (default=18).
9.	yAxis : nameTextStyle : fontStyle(string) : italic : mengubah huruf menjadi miring.
10.	yAxis : nameTextStyle : fontWeight (string) : bold : membuat text menjadi tebal.
11.	yAxis : nameTextStyle : fontWeight (string) : lighter : membuat text menjadi tipis.
12.	yAxis : nameTextStyle : fontFamily (string) : mengubah jenis font.
13.	yAxis : nameGap (number) : celah antara nama sumbu dan garis sumbu.
14.	yAxis : nameRotate (number) : rotasi nama sumbu.
15.	yAxis : inverse (boolean) : sumbu yang terbalik.
16.	yAxis : min (number,string) : minimum value sumbu.
17.	yAxis : max (number,string) : maxsimum value sumbu.
18.	yAxis : scale (boolean) : ini hanya tersedia dalam axis numerik, yaitu, type: 'value.
19.	konfigurasi ini tidak tersedia saat min dan max ditetapkan.
20.	yAxis : data(object) : data kategori, tersedia dalam type 'category' axis.
21.	yAxis : axisLine (object) : show (boolean) : memunculkan garis sumbu (true) atau tidak memunculkan garis sumbu (false).
22.	yAxis : axisLine (object) : onZero (boolean) : menentukan sumbu X atau Y terletak pada posisi asal yang lain, dimana value 0 pada sumbu. Berlaku hanya jika sumbu yang lain adalah value type, dan mempunyai value 0 (default=true).
23.	yAxis : axisLine (object) : lineStyle (color) : warna pada garis.
24.	yAxis : axisLine (object) : type (string) : type garis yang digunakan (solid,dashed,dotted).
25.	yAxis : axisLine (object) : shadowBlur (number) : membuat bayangan objek menjadi blur.
26.	yAxis : axisLine (object) : shadowColor (color) : mengubah warna bayangan objek.
27.	yAxis : axisLine (object) : shadowOffsetX (number) : jarak bayangan horizontal.
28.	yAxis : axisLine (object) : shadowOffsetY (number) : jarak bayangan vertikal.
29.	yAxis : axisTick (object) : show (boolean) : untuk menunjukkan tanda sumbu.
30.	yAxis : axisTick (object) : alignWithLabel (boolean) : sejajarkan sumbu dengan label, yang tersedia hanya jika boundaryGap diset menjadi true dalam sumbu kategori.
31.	yAxis : axisLabel (object) : rotate (number) : untuk merotasikan label pada axis.
32.	yAxis : axisLabel (object) : margin (number) : margin antara axis label dan garis sumbu.
33.	yAxis : axisLabel (object) : formatter (string,function) : Formatter dari label sumbu, yang mendukung template string dan fungsi callback.
34.	yAxis : axisLabel (object) : 
35.	yAxis : axisLabel (object) : textStyle (object) : color(string) : untuk mengubah warna pada text.
36.	yAxis : axisLabel (object) : textStyle (object) : fontSize(number) : untuk mengubah ukuran text (default=18).
37.	yAxis : axisLabel (object) : textStyle (object) : fontStyle(string) : italic : mengubah huruf menjadi miring.
38.	yAxis : axisLabel (object) : textStyle (object) : fontWeight (string) : bold : membuat text menjadi tebal.
39.	yAxis : axisLabel (object) : textStyle (object) : fontWeight (string) : lighter : membuat text menjadi tipis.
40.	yAxis : axisLabel (object) : textStyle (object) : fontFamily (string) : mengubah jenis font.
41.	yAxis : align (string) : menentukan posisi huruf (left,center,right).
42.	yAxis : axisLabel (object) : textStyle (object) : baseLine (string) : textStyle (object) : mengatur posisi text dalam vertical (middle,top,bottom).
43.	yAxis : splitLine (object) : show (boolean)  :  nilai sumbu ditampilkan secara default, sedangkan sumbu kategori tidak.
44.	yAxis : splitLine (object) : lineStyle (object) : interval (number,function) : garis pada chart.
45.	yAxis : splitLine (object) : lineStyle (object) : shadowBlur (number) : membuat bayangan objek menjadi blur.
46.	yAxis : splitLine (object) : lineStyle (object) : shadowColor (color) : mengubah warna bayangan objek.
47.	yAxis : splitLine (object) : lineStyle (object) : shadowOffsetX (number) : jarak bayangan horizontal.
48.	yAxis : splitLine (object) : lineStyle (object) : shadowOffsetY (number) : jarak bayangan vertikal.
49.	yAxis : splitLine (object) : lineStyle (object) : color(string) : untuk mengubah warna pada text.
50.	yAxis : splitLine (object) : lineStyle (object) : width (number) : lebar splitLine.
51.	yAxis : splitLine (object) : lineStyle (object) : type (string) : type garis yang digunakan (solid,dashed,dotted).
52.	series (object) : name(string) : penamaan pada array. 
####**textStyle**####
1.	textStyle : color(string) : untuk mengubah warna pada text.
2.	textStyle : fontSize(number) : untuk mengubah ukuran text (default=18).
3.	textStyle : fontStyle(string) : italic : mengubah huruf menjadi miring.
4.	textStyle : fontWeight (string) : bold : membuat text menjadi tebal.
5.	textStyle : fontWeight (string) : lighter : membuat text menjadi tipis.
6.	textStyle : fontFamily (string) : mengubah jenis font.
