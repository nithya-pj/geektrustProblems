package trials;

import java.util.Scanner;

public class BattleLengaburuFalconi {

	public static void main(String args[]){
		Scanner input = new Scanner(System.in);
		System.out.println("Falconia has 300 Horses, 200 Elephants, 40 Armoured Tank and 20 Sling Guns");
		int falconiaHorses;
		int falconiaElephants;
		int falconiaArmouredTank;
		int falconiaSlingGun;
		System.out.println("How many Horses to deploy?");
		falconiaHorses=input.nextInt();
		System.out.println("How many Elephants to deploy?");
		falconiaElephants=input.nextInt();
		System.out.println("How many Armoured Tanks to deploy?");
		falconiaArmouredTank=input.nextInt();
		System.out.println("How many Sling Guns to deploy?");
		falconiaSlingGun=input.nextInt();
		Army falconi=new Army(falconiaHorses,falconiaElephants,falconiaArmouredTank,falconiaSlingGun);
		Army lengaburu=new Army();
		
		System.out.println("FALCONI ATTACKS WITH: \n"+falconi.horses+"H "+falconi.elephants+"E "+falconi.armouredTank+"AT "+falconi.slingGun+"SG");
		BattleLengaburu battle=new BattleLengaburu();
		boolean winFlag=battle.battleFuncRound1(falconi, lengaburu);
		battle.finalLengaburuFunc();
		if(winFlag){
			System.out.println("LENGABURU WINS!!");
		}else{
			System.out.println("LENGABURU LOSES. . .");
		}
	}
}
