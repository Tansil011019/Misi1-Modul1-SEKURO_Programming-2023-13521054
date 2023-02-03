# Seventh Video : Git Merge Conflict
Git Merge Conflict adalah peristiwa yang terjadi ketika Git tidak dapat secara otomatis menyelesaikan perbedaan kode antara dua komit. Git dapat menggabungkan perubahan secara otomatis hanya jika komit berada di jalur atau cabang yang berbeda.

## Contoh Conflict
```shell
<<<<<<< HEAD (Current Change)
<Code pada branch aktif>
=======
<Code yang ingin di merge>
>>>>>>> (Incoming Change)
```