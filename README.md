# Dairenin-Alanini-ve-Cevresini-Hesaplayan-Program
---
Bu bir [patika.dev](www.patika.dev) projesidir.
```
import java.util.Scanner;
public class daire {
    public static void main(String[] args) {
        int r,merkezAci;
        double pi=3.14,alan,cevre,acialan;
        Scanner input = new Scanner (System.in);
        System.out.println("Dairenin Yarıçapını Giriniz:");
        r = input.nextInt();
        alan = r*r*pi;
        System.out.println("Dairenin Alanı:"+alan);
        cevre = 2*pi*r;
        System.out.println("Dairenin Çevresi:"+cevre);
        System.out.println("Merkez Açıyı Giriniz:");
        merkezAci = input.nextInt();
        acialan= pi*r*r*merkezAci/360;
        System.out.println("Merkez Açısı Verilen Dairenin Alanı:"+acialan);
    }
}
```
