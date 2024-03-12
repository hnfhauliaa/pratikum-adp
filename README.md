# pratikum-adp
repository untuk mengelola pratikum ADP 2024

Nama : Hanifa Aulia Kamal
NIM  : 2310433024

uses crt;
var
kalkulus, andat, pengmat, fisdas, kimdas, bing, bindo, agama, sks, ip:real;
begin 
clrscr;

writeln('Tugas Modul 1 Shift 2 No. 1');
writeln('Nama : Hanifa Aulia Kamal'); 
writeln('NIM : 2310433024');
writeln(' ');
writeln('Kalkulus = ');
readln(kalkulus);
writeln('Analisis Data = ');
readln(andat);
writeln('Pengantar Matematika = ');
readln(pengmat);
writeln('Fisika Dasar = '); 
readln(fisdas);
writeln('Kimia Dasar = ');
readln(kimdas);
writeln('Bahasa Inggris = ');
readln(bing);
writeln('Bahasa Indonesia = ');
readln(bindo);
writeln('Agama readln(agama);
readln(agama);
writeln('Banyak sks = ');
readln(sks);
writeln('');
ip:=((3*kalkulus)+(3*andat)+(3*pengmat)+(2*fisdas)+(2*kimdas)+(3*bing)+(3*bindo)+(2*agama))/sks;
writeln('IP Semester 1 =', ip);
readln;
end.


uses crt;
var
volume, luas, sisi, tinggi, miring, datar, tegak:real;
begin clrscr;
writeln('Tugas Modul 1 Shift 2 No. 2');
writeln('Nama : Hanifa Aulia Kamal');
writeln('NIM : 2310433024');
writeln('');
writeln('Diketahui :');
write('Sisi Alas = ');
readln(sisi);
write('Tinggi Limas = ');
readln(tinggi);
write('Sisi Datar Segitiga = ');
readln(datar);
miring:=SQRT((tinggi*tinggi)+(datar*datar));
volume:=(1/3)*sisi sisi tinggi;
writeln('');
writeln('Volume Limas Segi Empat, volume); luas: (sisi sisi)+(4*(1/2)*sisi*miring);
writeln('Luas Permukaan Limas Segi Emppat = ',luas);
readln;
end.
