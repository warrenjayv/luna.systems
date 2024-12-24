main : op

op : target.cpp probe.cpp
		date         &>> .err
		echo -e "\n" &>> .err
		g++ -g target.cpp -o target.exe &>> .err
		g++ -g probe.cpp  -o probe.exe  &>> .err

clean :
		rm .err
		rm *.exe

