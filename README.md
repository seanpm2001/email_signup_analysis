# Email signup analysis script
### **Update**: For the sfg_data_analysis_php_only.php script, you don't need to put the files name on the command line next to the command. Now, once you execute the script, the script will ask for the names of the files.
### Usage (sfg_data_analysis scripts):
### Create a directory on your computer, preferably in a place where you can easily access it. Download or copy the contents of the scripts into a text editor and place it in the directory. Make sure you grab both the sfg_data_analysis.php script and hash.pl.
### Open the terminal application located in Applications->Utilities->Terminal.app (MacOS). On Windows, right click on the Windows menu icon and select "Run...", then type "cmd" in the field and press OK.
### In the terminal type in the change directory command to get to the directory you created:
### ```cd [name of directory] (Press enter)```
### You can type in ```pwd``` to be sure you are in the correct directory.
### Once you are in the directory run the following command (make sure you have the SailThru and SFG files in this directory also):
### ```php sfg_data_analysis.php [Sailthru File] [SFG File] [email column number] [dollar amount column] [t (option for testing purposes)]```
### After the script runs, the results should be in a file inside the final_files directory.
## Depends on hash.pl being in the same directory.
### For get_zips.php, there's no need to input the name of the files in the command lines with the command. All you need to do is execute the command.
### Usage:
### ```php get_zips.php (press enter)```
### After you press enter, the script will ask for the name of the files.
