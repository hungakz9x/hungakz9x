//LAB1
package Lab1;
import java.util.Scanner;

public class bai1 {
    public static void main(String[] args) {
        String hoVaTen;
        Float diemTB;
        Scanner sc = new Scanner(System.in);
        System.out.print("Nhap ho va ten: ");
        hoVaTen = sc.nextLine();
        System.out.print("Nhap diem trung binh: ");
        diemTB = sc.nextFloat();
        System.out.printf("Ho va ten sinh vien :%s    |   Diem trung binh:%.1f ",hoVaTen,diemTB);
    }
}

//bai 2
package Lab1;

import java.util.Scanner;

public class bai2 {
    public static void main(String[] args) {
        Float dai, rong, chuVi, dienTich, canhNN;
        Scanner sc = new Scanner(System.in);
        System.out.print("Nhap vao chieu dai: ");
        dai = sc.nextFloat();
        System.out.print("Nhap vao chieu rong: ");
        rong = sc.nextFloat();
        chuVi = (dai + rong) * 2;
        dienTich = dai*rong;
        canhNN =Math.min(dai, rong);
        System.out.printf("Chieu dai cua hinh chu nhat la:%.1f|Chieu rong cua hinh chu nhat la:%.1f",dai,rong);
        System.out.println();
        System.out.printf("Chu Vi hinh Chu nhat la:%.1f|Dien tich hinh chu nhat la:%.1f|Canh nho nhat cua hinh chu nhat la:%.1f",chuVi,dienTich,canhNN);
    }
}

//bai3
package Lab1;

import java.util.Scanner;

public class bai3 {
    public static void main(String[] args) {
        float a, V;
        Scanner sc = new Scanner(System.in);
        System.out.print("Nhap canh cua khoi lap phuong:");
        a = sc.nextFloat();
        V = a * a * a;
        V=(float)Math.pow(a, 3);
        System.out.printf("The tich khoi lap phuong la:%.1f",V);
    }

}

//bai4
package Lab1;

import java.util.Scanner;

public class bai4 {
    public static void main(String[] args) {
        Float a, b, c, delta, candelta;
        Scanner sc = new Scanner(System.in);
        System.out.print("Nhap a: ");
        a = sc.nextFloat();
        System.out.print("Nhap b: ");
        b = sc.nextFloat();
        System.out.print("Nhap c: ");
        c = sc.nextFloat();
        delta = (float) (Math.pow(2, b) - 4 * a * c);
        candelta = (float) Math.sqrt(delta);
        System.out.printf("delta la:%.1f | Can bac hai cua delta la:%.1f", delta, candelta);
    }

}
