# Write-a-Java-Program-To-add-Two-binary-Numbers

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package unit1;

import java.util.Scanner;

/**
 *
 * @author aruns
 */
public class addBin {
    
    public static void main(String[] args) {
        
        Scanner obj = new Scanner(System.in);
        System.out.println("Enter first binary no");
        String a = obj.next();
        System.out.println("Enter second binary no");
        String b = obj.next();
        
        int var = Integer.parseInt(a,2);
        int var1 = Integer.parseInt(b,2);
        int var2 = var+var1;
        
        System.out.print("Addition of above binary no is:");
        System.out.print(Integer.toBinaryString(var2));
     
    }
}
