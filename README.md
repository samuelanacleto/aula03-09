# aula03-09
package aula0309;

public class aluno {
 String nome;
 String ra;
 String curso;
 double nota1=0.0;
 double nota2=0.0;
 
 
 
 aluno (String nome,String ra,String curso){
	 this.nome=nome
     this.ra=ra
     this.curso=curso
 }
 
 public void set.nota1(double n){
	 this.nota=n
			 }
 
 public void set.nota2(double n){
	 this.nota=n
			 }
 public double calcMedia(){
	 return (this.nota1+this.nota2)/2;
 }
}

?????????????????????????????????????
#teste




package aula0309;

public class teste01 {
	public static void main (String[]args){
		aluno a1 = new aluno ("maria do  carmo","2018001","gastronomia");
		aluno a2 = new aluno ("joao pedro","20175050","redes");
		
		a1.setnota1(5,0);
		a2.setnota1(7,0);
		
		a1.setnota1(8,0);
		a2.setnota2(7,5);
		
		System.out.println("Media aluno 1:"+a1.calcMedia());
		System.out.println("Media aluno 2:"+a2.calcMedia());
		
	

}
