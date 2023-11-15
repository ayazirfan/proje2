# proje2
Merge Sort proje ödevi
[16,21,11,8,12,22] -> Merge Sort
önce dizileri tek elemana kadar 2'ye böl
[16,21,11] [8,12,22]
[16,21] [11]  [8,12] [22]
[16][21][11]    [8][12][22]
şimdi sıralı olarak tekrar birleştir.
[11,16][21]   [8,12][22]
[11,16,21]   [8,12,22]
[8,11,12,16,21,22] 

Big-O göterimi;
her defasında 2' ye bölündüğünden 2^x=n
O(n)=logn dir.
