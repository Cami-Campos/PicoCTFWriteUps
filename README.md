# PicoCTFWriteUps
Solutions for PicoCTF Beginner Challenges

# Obedient Cat 

## Description
This file has a flag in plain sight (aka "in-the-clear"). [Download flag](./flag).

## Information

**Point Value**: 5 points

**Category**: General Skills

## Hints:

>1. Any hints about entering a command into the Terminal (such as the next one), will start with a '$'... everything after the dollar sign will be typed (or copy and pasted) into your Terminal.
>2. To get the file accessible in your shell, enter the following in the Terminal prompt: $ wget wget https://mercury.picoctf.net/static/2d24d50b4ebed90c704575627f1f57b2/flag
>3. $ man cat

## Tags:
PicoCTF2021 
General SKills

## Solution

>1. Copy and paste the terminal prompt : $ wget https://mercury.picoctf.net/static/2d24d50b4ebed90c704575627f1f57b2/flag
>2. Place the command `ls` to view the files
>3. View the contents on the file "flag" with the command: "`cat` flag"
>4. Retrieve the flag and paste it.

## Flag:

>picoCTF{s4n1ty_v3r1f13d_f28ac910}


# Python Wrangling

## Description
Python scripts are invoked kind of like programs in the Terminal... Can you run this `Python script` using `this password` to get `the flag`?

## Information

**Point Value**: 10 points

**Category**: General Skills

## Hints: 
>1. Get the Python script accessible in your shell by entering the following command in the Terminal prompt: $ wget https://mercury.picoctf.net/static/0bf545252b5120845e3b568b9ad0277e/ende.py
>2. $ man python

## Tags:
PicoCTF2021 
General SKills

## Solution:
>1. Dowload all the three url files using the `wget` command with each url. 
>2. Use the command `ls` to view the files.
>3. Run the command `python` to excecute the python script. In this case: `python ende.py`.
>4. The terminal will answer with:"Usage: ende.py. (-e/-d) [file]". Therefore, the command `-d` will be needed to debug the python script: `python ende.py -d flag.txt.en.1`.
>5. It will ask for a password which to find the password use the command `cat`: `cat pw.txt`.
>6. Copy and paste the password provided to retrieve the flag. In this case it was: `6008014f6008014f6008014f6008014f`.
>7. Copy and paste the flag obtained. 


## Flag:
>picoCTF{4p0110_1n_7h3_h0us3_6008014f}

# Wave a flag	

## Description:
Can you invoke help flags for a tool or binary? This program has extraordinarily helpful information...


## Information:

**Point Value**: 10 points

**Category**: General Skills

## Hints:
>1. This program will only work in the webshell or another Linux computer.
>2. To get the file accessible in your shell, enter the following in the Terminal prompt: $ wget https://mercury.picoctf.net/static/b28b6021d6040b086c2226ebeb913bc2/warm
>3. Run this program by entering the following in the Terminal prompt: ./warm, but you'll first have to make it executable with $ chmod +x warm
>4. -h and --help are the most common arguments to give to programs to get more information from them!
>5. Not every program implements help features like -h and --help.

## Tags
PicoCTF2021 
General SKills

## Solution:
>1. Copy and paste: $ wget https://mercury.picoctf.net/static/b28b6021d6040b086c2226ebeb913bc2/warm
>2. Run the file given with the command: `./warm`
>3. Follow with the command: `./warm -h`
>4. Copy and paste the flag.

## Flag:
>picoCTF{b1scu1ts_4nd_gr4vy_d6969390}

# Nice netcat...

## Description:
There is a nice program that you can talk to by using this command in a shell: $ nc mercury.picoctf.net 22342, but it doesn't speak English...


## Information:

**Point Value**: 15 points

**Category**: General SKills

## Hints:
>1. You can practice using netcat with this picoGym problem: what's a netcat?
>2. You can practice reading and writing ASCII with this picoGym problem: Let's Warm Up

## Tags:
PicoCTF2021 
General SKills

## Solution:
>1. Copy and paste: $ nc mercury.picoctf.net 22342
>2. It will provide a list of numbers which you would need to copy and paste it in a ASCII translator to retrieve the flag 
>3. Copy and paste the flag.

## Flag:
>picoCTF{g00d_k1tty!_n1c3_k1tty!_5fb5e51d}

# Static ain't always noise	

## Description:
Can you look at the data in this binary: static? This BASH script might help!


## Information:

**Point Value**: 20 points

**Category**: General Skills

## Hints:
> None

## Tags:
PicoCTF2021 
General SKills

## Solution:
>1. Copy and paste the file url given in the description with the `wget` command to dowload it. In this case: `wget https://mercury.picoctf.net/static/ec4dbd8898ade34e1d60d5b70c1b8c8c/static`
>2. It will open the file and use command `cat` to open the file static: `cat static`. 
>3. The flag will be somewhere in the file.  
>4. Copy and paste the flag.

## Flag:
>picoCTF{d15a5m_t34s3r_98d35619}

# Tab, Tab, Attack	

## Description
Using tabcomplete in the Terminal will add years to your life, esp. when dealing with long rambling directory structures and filenames: Addadshashanammu.zip

## Information

**Point Value**: 20 points

**Category**: General Skills

## Hints:
>1. After `unzip`ing, this problem can be solved with 11 button-presses...(mostly Tab)...

## Tags:
PicoCTF2021 
General SKills

## Solution:
>1. Dowload file provided into the Webshell. To do so copy the file url and paste it into the Webshell with `wget` command.  wget https://mercury.picoctf.net/static/e38f6a5b69b45d21e33cf7281d8c2531/Addadshashanammu.zip
>2. A zip file file will appear and it needs to be unzip with: `unzip` Addadshashanammu.zip
>3. A list of files will appear: "Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurnabitashpi/Maelkashishi/Onnissiralis/Ularradallaku/fang-of-haynekhtnamet" and to reach the last file the commands `cd` and `ls` will be needed for each file. 
>4. After reaching the last file, place the command `./` and it will provide the flag. "`./`fang-of-haynekhtnamet"
>5. Copy and paste the flag.

## Flag:
>picoCTF{l3v3l_up!_t4k3_4_r35t!_f3553887}

# Magikarp Ground Mission	

## Description:
Do you know how to move between directories and read files in the shell? Start the container, `ssh` to it, and then `ls` once connected to begin. Login via `ssh` as `ctf-player` with the password, `481e7b14`
Additional details will be available after launching your challenge instance.


## Information:

**Point Value**: 30 points

**Category**: General Skills

## Hints:
>1. Finding a cheatsheet for bash would be really helpful!

## Tags:
PicoCTF2021 
General SKills

## Solution:
>1. Start Challenge by clicking: Lauch Instance. This will start and hour timer to complete the challenge.
>2. After starting the challenge it will provide an ssh code which it will placed on the terminal: `ssh ctf-player@venus.picoctf.net -p 54015`
>3. The terminal will ask for a password which it will be the one provided in the description. In my case it was `481e7b14`. 
>4. Place the command `ls` to view the files.
>5. Once the files appear, use the command `cat` to view the file that has the word flag in it. This will provide a part of the flag. 
>6. Continue usig `ls` and `cat` commands, until you gather all the parts of the flag. 
>7. Copy and paste all the parts of the flag to retrieve it. 


## Flag: 
>picoCTF{xxsh_0ut_0f_\/\/4t3r_1118a9a4}

# 2Warm

## Description:
Can you convert the number 42 (base 10) to binary (base 2)?


## Information:

**Point Value**: 50 points

**Category**: General Skills

## Hints:
>1. Submit your answer in our competition's flag format. For example, if your answer was '11111', you would submit 'picoCTF{11111}' as the flag.

## Tags:
PicoCTF2021 
General SKills

## Solution:
>1. Use the website: https://www.rapidtables.com/convert/number/decimal-to-binary.html to place the number provided in the description. In this case: 42.
>2. Copy the convertion and submit it in the competition's flag format.
>3. Submit flag.


## Flag:
>picoCTF{101010}

# Lets Warm Up	

## Description:
If I told you a word started with 0x70 in hexadecimal, what would it start with in ASCII?


## Information

**Point Value**: 50 points

**Category**: General Skills

## Hints:
>1. Submit your answer in our flag format. For example, if your answer was 'hello', you would submit 'picoCTF{hello}' as the flag.
## Tags:
PicoCTF2021 
General SKills

## Solution:
>1. Use the website:https://codebeautify.org/ascii-to-text#google_vignette to place the word given in the description. In this case "0x70"
>2. Copy and paste the decoded text. In this case, the decoded text was "p".
>3. Submit it in the competition's flag format.


## Flag:
>picoCTF{p}

# Warmed Up

## Description:
What is 0x3D (base 16) in decimal (base 10)?

## Information

**Point Value**: 50 points

**Category**: General Skills

## Hints:
>1. Submit your answer in our flag format. For example, if your answer was '22', you would submit 'picoCTF{22}' as the flag.

## Tags:
PicoCTF2021 
General SKills

## Solution:
>1. Use the website: https://decimal.info/hex-to-decimal/0/how-to-convert-0X0E-to-decimal.html to place the number given by the description. In this case: 0x3D.
>2. Copy and paste the converted numebr. In this case, the result was "61".
>3. Submit it in the competition's flag format.

## Flag:
>picoCTF{61}
