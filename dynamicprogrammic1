package com.company;

import java.util.*;

public class Main {
    public static int sum=8;
    public static void main(String[] args) {
	// write your code here
        Scanner sc = new Scanner(System.in);
        ArrayList<ArrayList> answer = new ArrayList<ArrayList>();
        int[] n = {1,2,3,4,5,6,7,8};
        int num = n.length;
        for (int i = 0; i < n.length; i++) {
            System.out.print(n[i]+" ");
        }
        int ai=0;
        System.out.println();
        for (int l = 2; l < num; l++) {
            for (int i = 0; i < num; i++) {
                for (int j = i+1; j < num; j++) {
                    answer.add(new ArrayList<Integer>());
                    int mej = (n[i]+n[j]);
                    answer.get(ai).add(n[i]);
                    answer.get(ai).add(n[j]);
                    for (int p = 2; p < l; p++) {
                        if(p==j || p==i){continue;}
                        mej+=n[p];
                        answer.get(ai).add(n[p]);
                    }
                    if(mej==sum){
                        System.out.print(answer.get(ai)+" ");
                        System.out.println("= sum");
                    }
                    ai++;
                }
            }
        }
    }
}
