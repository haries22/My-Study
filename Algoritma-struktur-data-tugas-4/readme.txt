flowchart matriks 3x3 
https://drive.google.com/file/d/1qIV_6u-aLsu1dYmRno_2KZjJAOyQeUjW/view?usp=drivesdk
psudocode=
BEGIN

    // Inisialisasi matriks a dan b
    a = [[1, -5, 2],
     [1, 4, 1],
     [5, 0, 1]]
    b = [[-1, 2, 4],
     [3, 5, 2],
     [4, 3, 0]]
    
    // Inisialisasi matriks c sebagai matriks kosong
    c = []

    // Hitung jumlah baris dan kolom dari matriks a
    baris_a = LENGTH(a)
    kolom_a = LENGTH(a[0])

    // Hitung jumlah baris dan kolom dari matriks b
    baris_b = LENGTH(b)
    kolom_b = LENGTH(b[0])

    // Tampilkan matriks a dan b serta dimensi mereka
    PRINT a
    PRINT "Baris matriks a adalah: ", baris_a
    PRINT "Kolom matriks a adalah: ", kolom_a
    PRINT NEWLINE
    PRINT b
    PRINT "Baris matriks b adalah: ", baris_b
    PRINT "Kolom matriks b adalah: ", kolom_b

    // Periksa apakah kolom a sama dengan baris b
    IF (kolom_a != baris_b) THEN
        PRINT "Matriks a dengan b tidak dapat dikalikan"
    ELSE
        PRINT "Matriks a dengan b dapat dikalikan"
        PRINT NEWLINE
   
    END IF

END
