Shell, processes and signals     
                                           
Script 1:displays its own PID.     
Script 2:displays a list of currently running processes.Must show all processes, for all users, including those which might not have a TTY. Display in a user-oriented format, show process hierarchy.       
Script 3:displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process. The pgrepcommand cannot be used. The third line of your script must be # shellcheck disable=SC2009.        
Script 4:displays the PID, along with the process name, of processes whose name contain the word bash. The ps command cannot be used.      
Script 5:displays To infinity and beyond indefinitely. In between each iteration of the loop, a sleep 2 is added.     
Script 6:it stops 4-to_infinity_and_beyond process. Here, the kill command must be used.     
Script 7: stops 4-to_infinity_and_beyond process without using kill or killall.      
Script 8:displays:To infinity and beyond indefinitely with a sleep 2 in between each iteration, display "I am invincible!!!" when receiving a SIGTERM signal.       
Script 9:kills the process 7-highlander.         
Script 10:Creates the file /var/run/myscript.pid containing its PID; Displays To infinity and beyond indefinitely; Displays I hate the kill command when receiving a SIGTERM signal; Displays Y U no love me?! when receiving a SIGINT signal; Deletes the file /var/run/myscript.pid and terminates itself when receiving a SIGQUIT or SIGTERM signal.       
Script 11:a manage_my_process Bash script that:Indefinitely writes I am alive! to the file /tmp/my_process, In between every I am alive! message, the program should pause for 2 seconds; then write Bash (init) script 11-manage_my_process that manages manage_my_process.
