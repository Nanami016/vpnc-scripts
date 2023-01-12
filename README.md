# vpnc-scripts
personal changed from horar / vpnc-scripts repository

changed file 

original 
	exec("route delete 0.0.0.0 mask 0.0.0.0 ");
	exec("route add  0.0.0.0 mask 0.0.0.0 " + gw);
  
personal updated
  	//exec("route delete 0.0.0.0 mask 0.0.0.0 ");
	  //exec("route add -p 0.0.0.0 mask 0.0.0.0 " + gw);
    
or
	exec("route delete 0.0.0.0 mask 0.0.0.0 ");
	exec("route add -p 0.0.0.0 mask 0.0.0.0 " + gw);
