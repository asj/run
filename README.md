run [options] command
   A tool for displaying the executed command along with its optional
   output. It shows the command output status return code at the end
   of the command line. Typically used in shell scripting when writing
   test cases.

   When no options are specified, run the command, and display return
   status code at the end the command.

   Options:
     	-qq Run the command quietly; no command information is shown
     	-q  Run the command quietly; show err only when the command fails
     	-s  Skip calling exit when the command fails
     	-o  Show the output the command created
