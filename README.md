# Restaurant-Order-App-techinical-test-

package testegft;

import java.util.Scanner;

//Mathias Bezerra Silva

    public class TesteGFT {

    public static void main(String[] args) {
       
		String opcao = "";
		
		System.out.println("Digite o período do dia como manha ou noite:");
                System.out.println("*Obs.:Digite sem acentuação");
		System.out.println("1 - Manhã");
		System.out.println("2 - Noite");
		
		Scanner input = new Scanner(System.in);
		opcao = input.nextLine();
		
                        // manhã
			if(opcao.equals("manha") || opcao.equals("Manha")) {
                                int ovos = 0;
                                int torrada = 0;
                                int cafe = 0;
                                int sobremesa = 0;
                            
				System.out.println("Refeição da Manhã.");
				System.out.println("1 = Entrada, 2 = Acompanhamento, 3 = bebida e 4 = Sobremesa.");
				System.out.println("1 - Ovos");
				System.out.println("2 - Torrada");
				System.out.println("3 - Café.");
				System.out.println("4 - Invalido");
				System.out.println("*Obs.: Apenas a bebida pode ser repetida.");
				System.out.println("Digite a quantidade que deseja de Entrada:");
				ovos = input.nextInt();
				System.out.println("Digite a quantidade que deseja de Acompanhamento:");
				torrada = input.nextInt();
				System.out.println("Digite a quantidade que deseja de Bebida:");
				cafe = input.nextInt();
				System.out.println("Digite a quantidade que deseja de Sobremesa:");
				sobremesa = input.nextInt();
				
				System.out.println("|| Refeição da Manhã ||\n");
				if(ovos > 0 && ovos < 2){
                                    System.out.println(ovos + " - Ovo");
				}
                                else if(ovos == 0){
                                
                                }
                                else{
                                    System.out.println("erro");
                                }
				
                                if(torrada > 0 && torrada < 2){
                                    System.out.println(torrada + " - Torrada");
				}
                                else if(torrada == 0){
                                
                                }
                                else{
                                    System.out.println("erro");
                                }
                                
                                if(cafe > 0){
                                    System.out.println(cafe + " - Café");
				}
                                
                                if(sobremesa > 0){
                                    System.out.println("erro");
				}
				
				
		}
			if(opcao.equals("noite") || opcao.equals("Noite")) {
				int bife = 0;
                                int batata = 0;
                                int vinho = 0;
                                int bolo = 0;
                            
				System.out.println("Refeição da Noite.");
				System.out.println("1 = Entrada, 2 = Acompanhamento, 3 = bebida e 4 = Sobremesa.");
				System.out.println("1 - Bife");
				System.out.println("2 - Batata");
				System.out.println("3 - Vinho.");
				System.out.println("4 - Bolo");
				System.out.println("*Obs.: Apenas o acompanhamento pode ser repetida.");
				System.out.println("Digite a quantidade que deseja de Entrada:");
				bife = input.nextInt();
				System.out.println("Digite a quantidade que deseja de Acompanhamento:");
				batata = input.nextInt();
				System.out.println("Digite a quantidade que deseja de Bebida:");
				vinho = input.nextInt();
				System.out.println("Digite a quantidade que deseja de Sobremesa:");
				bolo = input.nextInt();
				
				System.out.println("|| Refeição da Noite ||\n");
				if(bife > 0 && bife < 2){
                                    System.out.println(bife + " - Bife");
				}
                                else if(bife == 0){
                                
                                }
                                else{
                                    System.out.println("erro");
                                }
                                if(batata > 0){
                                    System.out.println(batata + " - Batata");
				}
                                if(vinho > 0 && vinho < 2){
                                    System.out.println(vinho + " - Vinho");
				}
                                else if(vinho == 0){
                                
                                }
                                else{
                                    System.out.println("erro");
                                }
                                 if(bolo > 0 && bolo < 2){
                                    System.out.println(bolo + " - Bolo");
				}
                                else if(bolo == 0){
                                
                                }
                                else{
                                    System.out.println("erro");
                                }
          }
        }

    }
