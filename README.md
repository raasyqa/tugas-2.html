<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>tugas 2</title>
</head>
<body>
     <form action="#">
        <fieldset>
            <legend style="font-family: 'Times New Roman', sans-serif; font-size: 36px; color: #2f5db9; text-align: left; margin-bottom: 20px;">Data Diri:
            </legend>
            <table>
                <tr>
                    <td><label for="name">Nama Lengkap:</label></td>
                    <td><input type="text" id="name" name="full name"></td>
                </tr>
                <tr>
                    <td><label for="name">Nomor Handphone:</label></td>
                    <td><input type="text" id="name" name="nomor hp"></td>
                </tr>
                <tr>
                    <td>Alasan Mengikuti Kelas Memasak:</td>
                    <td><textarea name="alasan" id="als"></textarea></td>
                </tr>
                <tr>
                    <td>Usia:</td>
                    <td><input type="radio" name="usia">< 20 tahun<br>
                        <input type="radio" name="usia">21-30 tahun<br>
                        <input type="radio" name="usia">31-40 tahun<br>
                        <input type="radio" name="usia">> 40 tahun</td>
                </tr>
                <tr>
                    <td>Jam Kelas Memasak:</td>
                    <td><input type="checkbox" name="info" id="or"><label for="or">Selasa, 13.30-16.00</label><br>
                        <input type="checkbox" name="info" id="tr"><label for="tr">Kamis, 14.00-16.30</label><br>
                        <input type="checkbox" name="info" id="ks"><label for="ks">Jum'at, 09.00-11.30</label><br>
                        <input type="checkbox" name="info" id="ks"><label for="ks">Sabtu, 07.30-10.00</label><br>
                    </td>
                </tr>
                <tr>
                    <td>Pekerjaan:</td>
                    <td><select name="pekerjaan" id="pekerjaan">
                        <option value="pelajar/mahasiswa">Pelajar / Mahasiswa</option>
                        <option value="IRT">Ibu Rumah Tangga</option>
                        <option value="guru">Guru</option>
                        <option value="karyawan">Karyawan</option>
                        <option value="lainnya">Lainnya</option>
                        </select></td>
                </tr>
                <tr>
                    <td><label for="pass">Buat Password:</label></td>
                    <td><input type="password" id="pass" name="password"></td>
                </tr>
            </table>
        </fieldset>
        <tr></tr>
            <td></td>
            <td><button type="submit" style="color: #2f5db9;">Daftar</button></td>
        </tr>
     </form>
</body>
</html>
