# Ecommerce-Stream
package app;



import java.util.ArrayList;
import java.util.Comparator;
import java.util.HashMap;
import java.util.List;

/* 
ArrayList vs HashMap
*/


	public class Solution {

	    public static void main(String[] args) {
	      
	    	List <String> arr = new ArrayList<>();
	    	
	    	arr.add("Stas");
	    	arr.add("Vitea");
	    	arr.add("Masha");
	    	arr.add("Vova");
	    	arr.add("Vladimir");
	    	arr.add("Sasha");
	    	arr.add("Marina");
	    	arr.add("Alex");
	    	arr.add("Boris");
	    	arr.add("Anton");

	    	arr
	    		.stream()
	    		.sorted(Comparator.reverseOrder())
	    		.forEach(n -> System.out.println(n));
	    }
	}
