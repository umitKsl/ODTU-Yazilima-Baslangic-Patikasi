# Binary Search Tree Projesi
[Patika.dev](https://www.patika.dev/)  <br>
<br>
Root 5'tir. <br>
Rootun sağında 0,1,2,3,4; solunda 6,7,8,9 bulunur. <br>
Solda oluşan ilk subtree'de parent 1'dir. Çocuklar, solda 0 ve sağda 3'tür. <br>
3'ün parent olduğu subtree'de çocuklar, solda 2 ve sağda 4'tür. <br>
Root'un solunda oluşan ilk subtree'de parent 7'dir. Çocuklar, solda 6 ve sağda 8'dir. <br>
8'in tek çocuğu 9 ise solunda yer alır. <br>
```mermaid
flowchart
    id1((5))-->id2((1));
    id1((5))-->id3((7));
    id2((1))-->id4((0));
    id2((1))-->id5((3));
    id3((7))-->id6((6));
    id3((7))-->id7((8));
    id5((3))-->id8((2));
    id5((3))-->id9((4));
    id7((8))-->id10((9));
```
