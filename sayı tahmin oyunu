package soru3;
import java.util.Random;
import javax.swing.JOptionPane;
public class oyun {
public static void main(String[]args) {
	int i=10;
	Random r=new Random();
	int sayi=r.nextInt(100);

	do{
		
	String tahmin=JOptionPane.showInputDialog("tahmin gir:");
	int t=Integer.parseInt(tahmin);
	if(t==sayi)
	{
	String mesaj="tahmin doğru-"+i+". tahminde bildiniz";
	JOptionPane.showMessageDialog(null,mesaj);
	break;
	}
	else
		--i;
	
	}	while(i>0);
	String mesaj="bilemediniz oyun bitti";
	JOptionPane.showMessageDialog(null,mesaj);
}
}
	
	
