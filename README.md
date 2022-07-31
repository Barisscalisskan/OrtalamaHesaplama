# Not Ortalaması Hesaplayan Program

/* **Java Kütüphanemizi Sisteme Dahil Ediyoruz Öncelikle** */

import java.util.Scanner;
Scanner alinp = new Scanner(System.in);

/* **Kullanıcıdan İnput Almak İçin Değişken Oluşturuyoruz** */

int mat, kimya, turkce, tarih,muzik;

/* **Ekrana Notları Girmesini Söylüyoruz Sonra** */


Systems.out.print("Matematik Notunu Girin :");
mat = alinp.next.int();

Systems.out.print("Kimya Notunu Girin :");
kimya = alinp.next.int();

Systems.out.print("Turkçe Notunu Girin :");
turkce = alinp.next.int();

Systems.out.print("Tarih Notunu Girin :");
tarih = alinp.next.int();

Systems.out.print("Muzik Notunu Girin :");
muzik = alinp.next.int();

/* **Kullanıcının Giriği Notların hepsini Toplayıp Sınıfı Geçip Geçmediğini Ekrana Yazdırıyoruz** */

int toplam = mat + kimya + turkce + tarih + muzik;

double böl = toplam / 5.0;
Systems.out.print("Ortalamanız:" + böl)

boolean kontrol = böl >= 60;

String analiz = kontrol ? "Sınıfı Geçti" : "Sınıfta Kaldı";

Systems.out.print(analiz);

/* **Aldığımız Notları ortalamaya Bölüp 60 ile Kıyasladık Ve Sınıfı Geçip Geçemeyeceğini Tespit Etmiş Olduk.Not Ortalaması Testimiz Burda Sonlanmış Oldu Patika.İyi Günler** */

    Barış ÇAlışkan

[PatikaBeniOku](https://www.patika.dev)
