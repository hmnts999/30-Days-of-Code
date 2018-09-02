package com.example.java;
import java.util.Scanner;

class Main {

    public static void main(String[] args) {
        int a,b,n;
        Scanner sc = new Scanner(System.in);
        int q = sc.nextInt();
            for(int k = 0; k<q; k++) {
                a = sc.nextInt();
                b = sc.nextInt();
                n = sc.nextInt();
                int res = a;
                for(int j = 0; j<n; j++){
                    res += (int)(Math.pow(2,j)*b);
                    System.out.print((res)+ " ");
                }


            }


    }
}