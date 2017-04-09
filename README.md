# Tugas_2- Achmad_Fatahillah_1154004_D4.TI.2A
Klik File => New => Project => Plug-in Project 
Buat baru beri nama sesuai keperluan saya,saya menamakan Tugas_2, lalu klik Next => Finish
Project Explorer, fold: src/Tugas_2.Klik kanan
Pilih New => Other => XML file => Klik Next saya menamakan Pendidikan.xml
Isikan file Pendidikan.xml
Setelah selesai, klik kanan pada file Pendidikan.xml dan pilih Create XML definition. sebelum itu jika tidak ada plugin Rinzo xml editor Link Download : https://sourceforge.net/projects/editorxml/files/Rinzo%20XML%20Editor/ ) 
Beri nama Pendidikan1.xsd (jangan lupa pakai .xsd) dan klik Finish
Setelah itu akan terlihat design schema dari Pendidikan.xml 
Setelah itu membuat patterns pada atribut email dengan ketentuan @gmail.com email => klik kanan => show properties => pada constraint klik pattern di sebelah kanan => add
Beri nama “.+@gmail.com”
schema ini mempunyai sebuah aturan saat mengisi data email tidak mengikuti aturan dari file schema ini seperti tidak ada “@” dan “.”  , maka akan terjadi error
klik kanan => validate, jika tidak muncul error berarti anda berhasil
