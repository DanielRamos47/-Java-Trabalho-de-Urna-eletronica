# -Java-Trabalho-de-Urna-eletronica


package xD;

package com.mycompany.mavenproject1;

import java.util.Scanner;

public class UrnaDaniel {

    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);

        int turma[] = new int[8];
        int eleitor = 0, eleitor_valido = 0, branco = 0;
        int voto1 = 777, voto2 = 777, voto3 = 777;
        double nulo = 0.0;
        //VOTO TURMA 1:
        double turma1 = 0, ana_turma1 = 0.0, pedro_turma1 = 0, rita_turma1 = 0, alfredo_turma1 = 0, regina_turma1 = 0, ricardo_turma1 = 0;
        //VOTO TURMA 2:
        double turma2 = 0, ana_turma2 = 0.0, pedro_turma2 = 0, rita_turma2 = 0, alfredo_turma2 = 0, regina_turma2 = 0, ricardo_turma2 = 0;
        //VOTO TURMA 3:
        double turma3 = 0, ana_turma3 = 0, pedro_turma3 = 0, rita_turma3 = 0, alfredo_turma3 = 0, regina_turma3 = 0, ricardo_turma3 = 0;
        //Contas

        
        for (int i = 0; i < 8; i++) {
            System.out.println("Qual sua turma? (1,2,3)");
            turma[i] = ler.nextInt();

            while (turma[i] != 1 && turma[i] != 2 && turma[i] != 3) {
                System.out.println("Informe uma turma válida (1, 2, 3)");
                turma[i] = ler.nextInt();
            }

            switch (turma[i]) {
                case 1 -> {
                    System.out.println("(Turma 1) Informe seu seu voto");
                    voto1 = ler.nextInt();
                    while (voto1 != 1 && voto1 != 2 && voto1 != 3 && voto1 != 4 && voto1 != 5 && voto1 != 6 && voto1 != 10 && voto1 != 0) {
                        System.out.println("Informe um Voto correto (1,2,3,4,5,6,10,0) ");
                        voto1 = ler.nextInt();
                    }
                }
                case 2 -> {
                    System.out.println("(Turma 2) Informe seu voto");
                    voto2 = ler.nextInt();
                    
                    while (voto2 != 1 && voto2 != 2 && voto2 != 3 && voto2 != 4 && voto2 != 5 && voto2 != 6 && voto2 != 10 && voto2 != 0) {
                        System.out.println("Informe um Voto correto (1,2,3,4,5,6,10,0) ");
                        voto2 = ler.nextInt();
                    }
                }
                case 3 -> {
                    System.out.println("(Turma 3) Informe seu voto");
                    voto3 = ler.nextInt();
                    while (voto3 != 1 && voto3 != 2 && voto3 != 3 && voto3 != 4 && voto3 != 5 && voto3 != 6 && voto3 != 10 && voto3 != 0) {
                        System.out.println("Informe um Voto correto (1,2,3,4,5,6,10,0) ");
                        voto3 = ler.nextInt();
                    }
                }

            }

            switch (voto1) {
                case 1 -> {
                    ana_turma1++;
                    voto1 = 777;
                    eleitor++;
                    eleitor_valido++;
                    turma1++;
                }
                case 2 -> {
                    pedro_turma1++;
                    voto1 = 777;
                    eleitor++;
                    eleitor_valido++;
                    turma1++;
                }
                case 3 -> {
                    rita_turma1++;
                    voto1 = 777;
                    eleitor++;
                    eleitor_valido++;
                    turma1++;
                }
                case 4 -> {
                    alfredo_turma1++;
                    voto1 = 777;
                    eleitor++;
                    eleitor_valido++;
                    turma1++;
                }
                case 5 -> {
                    regina_turma1++;
                    voto1 = 777;
                    eleitor++;
                    eleitor_valido++;
                    turma1++;
                }
                case 6 -> {
                    ricardo_turma1++;
                    voto1 = 777;
                    eleitor++;
                    eleitor_valido++;
                    turma1++;
                }

                case 10 -> {
                    branco++;
                    voto1 = 777;
                    eleitor++;
                }

                case 0 -> {
                    nulo++;
                    voto1 = 777;
                    eleitor++;
                }

            }
            switch (voto2) {
                case 1 -> {
                    ana_turma2++;
                    voto2 = 777;
                    eleitor++;
                    eleitor_valido++;
                    turma2++;
                }
                case 2 -> {
                    pedro_turma2++;
                    voto2 = 777;
                    eleitor++;
                    eleitor_valido++;
                    turma2++;
                }
                case 3 -> {
                    rita_turma2++;
                    voto2 = 777;
                    eleitor++;
                    eleitor_valido++;
                    turma2++;
                }
                case 4 -> {
                    alfredo_turma2++;
                    voto2 = 777;
                    eleitor++;
                    eleitor_valido++;
                    turma2++;
                }
                case 5 -> {
                    regina_turma2++;
                    voto2 = 777;
                    eleitor++;
                    eleitor_valido++;
                    turma2++;
                }
                case 6 -> {
                    ricardo_turma2++;
                    voto2 = 777;
                    eleitor++;
                    eleitor_valido++;
                    turma2++;
                }

                case 10 -> {
                    branco++;
                    voto2 = 777;
                    eleitor++;
                }

                case 0 -> {
                    nulo++;
                    voto2 = 777;
                    eleitor++;
                }
            }
            switch (voto3) {
                case 1 -> {
                    ana_turma3++;
                    voto3 = 777;
                    eleitor++;
                    eleitor_valido++;
                    turma3++;
                }
                case 2 -> {
                    pedro_turma3++;
                    voto3 = 777;
                    eleitor++;
                    eleitor_valido++;
                    turma3++;
                }
                case 3 -> {
                    rita_turma3++;
                    voto3 = 777;
                    eleitor++;
                    eleitor_valido++;
                    turma3++;
                }
                case 4 -> {
                    alfredo_turma3++;
                    voto3 = 777;
                    eleitor++;
                    eleitor_valido++;
                    turma3++;
                }
                case 5 -> {
                    regina_turma3++;
                    voto3 = 777;
                    eleitor++;
                    eleitor_valido++;
                    turma3++;
                }
                case 6 -> {
                    ricardo_turma3++;
                    voto3 = 777;
                    eleitor++;
                    eleitor_valido++;
                    turma3++;
                }
                case 10 -> {
                    branco++;
                    voto3 = 777;
                    eleitor++;
                }
                case 0 -> {
                    nulo++;
                    voto3 = 777;
                    eleitor++;
                }

            }
        }
        double perc_valido = ((double) eleitor_valido / eleitor) * 100;
        double perc_nulo = ((double) nulo / eleitor) * 100;
        double perc_branco = ((double) branco / eleitor) * 100;

        double perc_ana = (((double) ana_turma1 + ana_turma2 + ana_turma3) / eleitor) * 100;
        double perc_pedro = (((double) pedro_turma1 + pedro_turma2 + pedro_turma3) / eleitor) * 100;
        double perc_rita = (((double) rita_turma1 + rita_turma2 + rita_turma3) / eleitor) * 100;
        double perc_alfredo = (((double) alfredo_turma1 + alfredo_turma2 + alfredo_turma3) / eleitor) * 100;
        double perc_regina = (((double) regina_turma1 + regina_turma2 + regina_turma3) / eleitor) * 100;
        double perc_ricardo = (((double) ricardo_turma1 + ricardo_turma2 + ricardo_turma3) / eleitor) * 100;
        
double perc_ana1=((double)ana_turma1/turma1)*100;
double perc_ana2=((double)ana_turma2/turma2)*100;
double perc_ana3=((double)ana_turma3/turma3)*100;

double perc_pedro1=((double)pedro_turma1/turma1)*100;
double perc_pedro2=((double)pedro_turma2/turma2)*100;
double perc_pedro3=((double)pedro_turma3/turma3)*100;

double perc_rita1=((double)rita_turma1/turma1)*100;
double perc_rita2=((double)rita_turma2/turma2)*100;
double perc_rita3=((double)rita_turma3/turma3)*100;

double perc_alfredo1=((double)alfredo_turma1/turma1)*100;
double perc_alfredo2=((double)alfredo_turma2/turma2)*100;
double perc_alfredo3=((double)alfredo_turma3/turma3)*100;

double perc_regina1=((double)regina_turma1/turma1)*100;
double perc_regina2=((double)regina_turma2/turma2)*100;
double perc_regina3=((double)regina_turma3/turma3)*100;

double perc_ricardo1=((double)ricardo_turma1/turma1)*100;
double perc_ricardo2=((double)ricardo_turma2/turma2)*100;
double perc_ricardo3=((double)ricardo_turma3/turma3)*100;
int i=0;
System.out.println("Numero total de eleitores: " +eleitor+ "\n Numero total de eleitores Validos: " + eleitor_valido + "\n Numero total de votos Nulos: " + nulo + "\n Numero total de votos Brancos: " + branco + "\n \n % de votos Validos: " + perc_valido + "%\n % de votos Nulos: " + perc_nulo + "%\n % de votos Brancos: " + perc_branco + "%\n \n % de votos na Ana: " + perc_ana + "%\n % de votos na Pedro: " + perc_pedro + "%\n % de votos na Rita: " + perc_rita + "%\n % de votos na Alfredo: " + perc_alfredo + "%\n % de votos na Regina: " + perc_regina + "%\n % de votos na Ricardo: " + perc_ricardo + "%\n");

System.out.println("\n");

System.out.println(" % de votos Turma 1 (Ana): "+perc_ana1+"%\n"); System.out.println(" % de votos Turma 2 (Ana): "+perc_ana2+"%\n") ;System.out.println(" % de votos Turma 3 (Ana): "+perc_ana3+"%\n");

System.out.println("\n");

System.out.println(" % de votos Turma 1 (Pedro): "+perc_pedro1+"%\n"); System.out.println(" % de votos Turma 2 (Pedro): "+perc_pedro2+"%\n"); System.out.println(" % de votos Turma 3 (Pedro): "+perc_pedro3+"%\n");

System.out.println("\n");

System.out.println(" % de votos Turma 1 (Rita): "+perc_rita1+"%\n") ;System.out.println(" % de votos Turma 2 (Rita): "+perc_rita2+"%\n"); System.out.println(" % de votos Turma 3 (Rita): "+perc_rita3+"%\n");

System.out.println("\n");

System.out.println(" % de votos Turma 1 (Alfredo): "+perc_alfredo1+"%\n") ;System.out.println(" % de votos Turma 2 (Alfredo): "+perc_alfredo2+"%\n") ;System.out.println(" % de votos Turma 3 (Alfredo): "+perc_alfredo3+"%\n");

System.out.println("\n");

System.out.println(" % de votos Turma 1 (Regina): "+perc_regina1+"%\n"); System.out.println(" % de votos Turma 2 (Regina): "+perc_regina2+"%\n") ;System.out.println(" % de votos Turma 3 (Regina): "+perc_regina3+"%\n");

System.out.println("\n");

System.out.println(" % de votos Turma 1 (Ricardo): "+perc_ricardo1+"%\n") ;System.out.println(" % de votos Turma 2 (Ricardo): "+perc_ricardo2+"%\n") ;System.out.println(" % de votos Turma 3 (Ricardo): "+perc_ricardo3+"%\n") ;
        
    }
}
