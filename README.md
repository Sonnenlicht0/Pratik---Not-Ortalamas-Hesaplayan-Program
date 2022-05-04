https://app.patika.dev/courses/java101/pratik-not-ortalamasi


import java.util.Scanner;

public class java {
    public static void main(String[] args) {
        int mat, fizik, kimya, türkçe, tarih, müzik;

        Scanner inp = new Scanner(System.in);

        System.out.print("Matematik Notunuz:");
        mat = inp.nextInt();

        System.out.print("Fizik Notunuz:");
        fizik = inp.nextInt();

        System.out.print("Kimya Notunuz:");
        kimya = inp.nextInt();

        System.out.print("Türkçe Notunuz:");
        türkçe = inp.nextInt();

        System.out.print("Tarih Notunuz:");
        tarih = inp.nextInt();

        System.out.print("Müzik Notunuz:");
        müzik = inp.nextInt();

        int toplam = (mat + fizik + kimya + türkçe + tarih + müzik);
        double sonuc = (toplam / 6);
        System.out.println(" Ortalamanız : " + sonuc);

        String str = sonuc >= 60 ? "Geçtiniz" : "Kaldınız";
        System.out.println(str);



    }
}
