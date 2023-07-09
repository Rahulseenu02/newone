#README
public class Input 
{
	
	public static void main(String[] args)
	
	{
		Scanner sca = new Scanner(System.in);
		
		System.out.println("enter your name");
		
		String s1 = sca.next().toUpperCase();
		
		char [] arc = s1.toCharArray();
		
		
		// for(int a2 = 0;a2<=s1.length();a2++) {
		for(char a1 : arc)
		{
		switch (a1)
		{
		
     	case 'A' :
     		
     		for(int i = 1;i<=5;i++)
	    	{
			for(int j = 1;j<=5;j++)
			{
				if(i == 1 || j == 1 ||j==5 || i==3 )
				{
					
					System.out.print("A ");
				}
				else {
					System.out.print("  ");
				}
				
			}
			
			System.out.println();
	    	}
     		break;
     		
     		
			
     		
			case 'B':
				for(int i =1;i<=5;i++)
			{
		
			for(int j = 1;j<=5;j++)
			{
				if((i == 1 && j<=4) || j==1 || (i==5 && j<=4) || i ==3 || (j ==5 && i<5 &&  i!= 1) )
				{
					
					System.out.print("B ");
				}
				else {
					System.out.print("  ");
				}
				
			}
			System.out.println();
		
	}
		break;
		
		case 'C':
			for(int i =1;i<=5;i++)
			{
		
			for(int j = 1;j<=5;j++)
			{
				if(i == 1  || j==1 || i==5 )
				{
					
					System.out.print("C ");
				}
				else {
					System.out.print("  ");
				}
				
			}
			System.out.println();
			
			}
			break;
			
			case 'D' :
				for(int i =1;i<=5;i++)
				{
			
				for(int j = 1;j<=5;j++)
				{
					if((i == 1 && j<=4) || j==1 || (i==5 && j<=4) || (j ==5 && i !=1 && i!=5 ))
					{
						
						System.out.print("D ");
					}
					else {
						System.out.print("  ");
					}
					
				}
				System.out.println();
				
				}
				break;
				
				case 'E': 
					for(int i =1;i<=5;i++)
					{
				
					for(int j = 1;j<=5;j++)
					{
						if( i == 1 || j== 1 || i==3 || i==5)
						{
							
							System.out.print("E ");
						}
						else {
							System.out.print("  ");
						}
						
					}
					System.out.println();
					
					}
					break;
					
					case 'F' : 
						for(int i =1;i<=5;i++)
						{
					
						for(int j = 1;j<=5;j++)
						{
							if( i == 1 || j== 1 || i==3 )
							{
								
								System.out.print("F ");
							}
							else {
								System.out.print("  ");
							}
							
						}
						System.out.println();
						
						}
						break;
						
						case 'G':
							for(int i =1;i<=5;i++)
							{
						
							for(int j = 1;j<=5;j++)
							{
								if( (i == 1) || j==1 || i == 5 || (j ==5 && i>=3)|| i==3 && j>=3 )
								{
									
									System.out.print("G ");
								}
								else {
									System.out.print("  ");
								}
								
							}
							System.out.println();
							
							}
							break;
							
							case 'H' : 
								
								for(int i =1;i<=5;i++)
								{
							
								for(int j = 1;j<=5;j++)
								{
									if( i == 3 || j==5 || j==1 )
									{
										
										System.out.print("H ");
									}
									else {
										System.out.print("  ");
									}
									
								}
								System.out.println();
								
								}
								break;
								
								case 'I':
									for(int i =1;i<=5;i++)
									{
								
									for(int j = 1;j<=5;j++)
									{
										if(j==3 || i==5 || i==1 )
										{
											
											System.out.print("I ");
										}
										else {
											System.out.print("  ");
										}
										
									}
									System.out.println();
									
									}
									break;
									
									case 'J':
										for(int i =1;i<=5;i++)
										{
									
										for(int j = 1;j<=5;j++)
										{
											if(i==1 || j==4 ||( i==5 && j!=5 ) || (i==4 && j==1))
											{
												
												System.out.print("J ");
											}
											else {
												System.out.print("  ");
											}
											
										}
										System.out.println();
										
										}
										break;
										
									case 'K':
											for(int i =1;i<=5;i++)
											{
										
											for(int j = 1;j<=5;j++)
											{
												if(j == 1 || i==2 && j==3 || i ==1 && j==4 || (i==3 && j==2)|| i==4 & j==3 || i==5 & j==4)
												{
													
													System.out.print("k ");
												}
												else {
													System.out.print("  ");
												}
												
											}
											System.out.println();
											
											}
											break;
											case 'L':
												for(int i =1;i<=5;i++)
												{
											
												for(int j = 1;j<=5;j++)
												{
													if(i==5 || j==1 )
													{
														
														System.out.print("L ");
													}
													else {
														System.out.print("  ");
													}
													
												}
												System.out.println();
												
												}
												break;
												case 'M':
													for(int i =1;i<=5;i++)
													{
												
													for(int j = 1;j<=5;j++)
													{
														if(j == 5 || j==1 || i==2 && j==2 || i==2 && j==4 || i== 3 && j==3)
														{
															
															System.out.print("M ");
														}
														else {
															System.out.print("  ");
														}
														
													}
													System.out.println();
													
													}
													break;
					case'N':
						for(int i =1;i<=5;i++)
						{
					
						for(int j = 1;j<=5;j++)
						{
							if(j == 5 || j==1 || i==j)
							{
								
								System.out.print("N ");
							}
							else {
								System.out.print("  ");
							}
							
						}
						System.out.println();
						
						}
						
						break;
				case 'O':
					for(int i =1;i<=5;i++)
					{
				
					for(int j = 1;j<=5;j++)
					{
						if((i ==1 && j!=1 && j!=5) || (j==1 && i!=1 && i!=5)|| (i==5 && j!=1 && j!=5)|| (j==5 && i!=1 &&i!=5))
						{
							
							System.out.print("O ");
						}
						else {
							System.out.print("  ");
						}
						
					}
					System.out.println();
					
					}
					break;
			case'P'	:
				for(int i =1;i<=5;i++)
				{
			
				for(int j = 1;j<=5;j++)
				{
					if(i ==1 || j==1 || i==3 || j==5 && i!=4 && i!=5 )
					{
						
						System.out.print("P ");
					}
					else {
						System.out.print("  ");
					}
					
				}
				System.out.println();
				
				}
				break;
			case'Q'	:
				for(int i =1;i<=5;i++)
				{
			
				for(int j = 1;j<=5;j++)
				{
					if(j==1 && i!=5 || i==4 && j!=5|| i==1 || j==5  ||  i==5 &&j==5 || i==3&&j==3  )
					{
						
						System.out.print("* ");
					}
					else {
						System.out.print("  ");
					}
					
				}
				System.out.println();
				
				}
				break;
				
		case'R':
			for(int i =1;i<=5;i++)
			{
		
			for(int j = 1;j<=5;j++)
			{
				if(i ==1 || j==1 || i==3 || j==5 && i!=4 && i!=5 || i==4 && j==3 || i==5 && j==4 )
				{
					
					System.out.print("R ");
				}
				else {
					System.out.print("  ");
				}
				
			}
			System.out.println();
			}
			
			break;
			case 'S':
				for(int i =1;i<=5;i++)
				{
			
				for(int j = 1;j<=5;j++)
				{
					if(j ==1 && i!=4 && i!=5 || i==1 || i==3 || i==5 || j==5 && i!=2 )
					{
						
						System.out.print("S ");
					}
					else {
						System.out.print("  ");
					}
					
				}
				System.out.println();
				
				}
				break;
				case'T':
					for(int i =1;i<=5;i++)
					{
				
					for(int j = 1;j<=5;j++)
					{
						if(i==1 || j==3 )
						{
							
							System.out.print("* ");
						}
						else {
							System.out.print("  ");
						}
						
					}
					System.out.println();
					
					}
					break;
				case'U'	:
					for(int i =1;i<=5;i++)
					{
				
					for(int j = 1;j<=5;j++)
					{
						if(j==1 && i!=5 || i==5 && j!=1 &&j!=5 || j==5 && i!=5 )
						{
							
							System.out.print("U ");
						}
						else {
							System.out.print("  ");
						}
						
					}
					System.out.println();
					
					}
					break;
				case'W':
					for(int i =1;i<=5;i++)
					{
				
					for(int j = 1;j<=5;j++)
					{
						if(j==1 || j==5 || i==j && j!=1 &j!=2 || i+j==6 && j!=4)
						{
							
							System.out.print("W ");
						}
						else {
							System.out.print("  ");
						}
						
					}
					System.out.println();
					
					}
					break;
				case 'X':
					for(int i =1;i<=5;i++)
					{
				
					for(int j = 1;j<=5;j++)
					{
						if(j==i || i+j ==6)
						{
							
							System.out.print("X ");
						}
						else {
							System.out.print("  ");
						}
						
					}
					System.out.println();
					
					}
					break;
				case 'Y':
					for(int i =1;i<=5;i++)
					{
				
					for(int j = 1;j<=5;j++)
					{
						if(j==i && j!=4 && j!=5|| i+j ==6 && j!=1 &&j!=2 || j==3 && i!=1&&i!=2)
						{
							
							System.out.print("Y ");
						}
						else {
							System.out.print("  ");
						}
						
					}
					System.out.println();
					
					}
					break;
					case'Z':
						for(int i =1;i<=5;i++)
						{
					
						for(int j = 1;j<=5;j++)
						{
							if(i==1|| i+j ==6||i==5)
							{
								
								System.out.print("Z ");
							}
							else {
								System.out.print("  ");
							}
							
						}
						System.out.println();
						
						}
						break;
													
	}
		
	}
	
}
}

