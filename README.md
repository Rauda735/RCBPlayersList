# RCBPlayersList
RCB players List for Upcoming Match

import java.util.*;   
public class RCBPlayersList   
{    
public static void main(String[] args)   
	{    
 int playerCount=player.length(); 
String[] name=new String[playerCount];
String[] country=new String[playerCount];
String[] role=new String[playerCount];

String[] playerList = new String[11];

for(int i=0, int j=0;i<playerList.length-1 && j<playerCount-1;i++,j++){
		//Six Indian Player
		for(String con:country){
			int count=0;
			if(con=="India"){
			playerList[i]=name[j]
			count++;
			}
			if(count<7){
				break;
				}
			}
		// Four Foreign Player
		for(String con:country){
			int count=0;
			if(con!="India"){
			playerList[i]=name[j]
			count++;
			}
			if(count==4){
				break;
				}
			}
	// One Wicket-Keeper
		for(String rol:role){
			if(rol==Wicket-keeper){
			playerList[i]=name[j]
			break;
				}
			}
		}
//Print the 11 Player List
System.out.println(Arrays.toString(playerList ));

	}    
}    
