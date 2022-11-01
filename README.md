# Patikadev Merge Sort Projesi

[patika.dev](https://app.patika.dev/erhnako) kapsaminda almis oldugum egitimin bir parcasi olan bu projeyi paylasiyorum. Patika hesabima ve siteye linkten ulasabilirsiniz.

## Proje 2

---

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

---

### 1. Asamalari;

        [16,21,11] [8,12,22]

        [16] [21,11]   [8,12] [22]

        [16] [21] [11] [8] [12] [22]

        [16] [11,21]   [8,12] [22] 

        [11,16,21] [8,12,22]

        [8,11,12,16,21,22]

### 2. Big-O gosterimi;

```

 O(nlogn)

```