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

# runme.py
## Description:
> Run the `runme.py` script to get the flag. Download the script with your browser or with `wget` in the webshell.
`Download runme.py Python script`
## Information: 
**Point Value** : 100 points
**Category** : General Skills
## Hints:
> 1. If you have Python on your computer, you can download the script normally and run it. Otherwise, use the `wget` command in the webshell.
> 2. To use `wget` in the webshell, first right click on the download link and select 'Copy Link' or 'Copy Link Address'
> 3. Type everything after the dollar sign in the webshell: `$ wget `, then paste the link after the space after `wget` and press enter. This will download the script for you in the webshell so you can run it!
> 4. Finally, to run the script, type everything after the dollar sign and then press enter: `$ python3 runme.py` You should have the flag now!
## Tags:
> - Beginner picoMini 2022
> - General Skills
> - Python
## Solution: 
> 1. Downloaded the script with `wget` command.
> 2. Ran the script with `python` command and got the flag. 
## Flag
> picoCTF{run_s4n1ty_run}

# Serpentine
## Description: 
> Find the flag in the Python script! `Download Python script`
## Information: 
**Point Value** : 100 points
**Category** : General Skills
## Hints:
> 1. Try running the script and see what happens
> 2. In the webshell, try examining the script with a text editor like `nano`
> 3. To exit `nano`, press Ctrl and x and follow the on-screen prompts.
> 4. The `str_xor` function does not need to be reverse engineered for this challenge.
## Tags: 
> - Beginner picoMini 2022
> - General Skills
> - Python
## Solution:
> 1. I downloaded the file with `wget` command.
> 2. Tried running it with `python` command, to which I had to choose a option which appears it will allow you to print the flag. Yet, when doing so it says the flag was misplaced. 
> 3. I opened the file to see the issue, using `cat` command : `cat serpentine.py`
> 4. After further inspection, I noticed that there was the following error : `if __name__ == "__main__": main()`. To solve it, I had to replace th `main()` for `print_flag()`.
> 5. I edited the code with the `vim` command. 
> 6. Once replaced, I ran the code and got the flag.
## Flag:
>picoCTF{7h3_r04d_l355_7r4v3l3d_ae0b80bd}

# First Find
## Description:
> Unzip this archive and find the file named 'uber-secret.txt'
`Download zip file`
## Information: 
**Point Value** : 100 points
**Category** : General Skills
## Hints:
> None
## Tags:
> - picoGym Exclusive
> - General Skills
## Solution:
> 1. I downloaded the file with `wget` command.
> 2. I used the command `cat` command to read it and all the data came out. 
> 3. To find the flag between all those lines, I used `grep` : `strings files.zip | grep pico`.
## Flag:
> picoCTF{f1nd_15_f457_ab443fd1}

# Big Zip
## Description: 
> Unzip this archive and find the flag. `Download zip file`
## Information: 
**Point Value** : 100 points
**Category** : General Skills
## Hints:
> 1. Can grep be instructed to look at every file in a directory and its subdirectories?
## Tags: 
> - picoGym Exclusive
> - General Skills
## Solution:
> 1. Downloaded the file with `wget` command.
> 2. I unziped the file with `unzip`. 
> 3. The file was very long and in order to find the flag, I used `grep`: `grep -nr picoCTF`.
## Flag:
>picoCTF{gr3p_15_m4g1c_ef8790dc}

# chrono
## Description:
> How to automate tasks to run at intervals on linux servers?
Additional details will be available after launching your challenge instance.
## Information:
**Point Value** : 100 points
**Category** : General Skills
## Hints:
> None
## Tags:
- picoCTF 2023
- General Skills
- linux
## Solution:
> 1. I launched the challenge and used the ssh provided to connect to the server.
> 2. `cat/etc/crontab` and I got the flag.
## Flag:
> picoCTF{Sch3DUL7NG_T45K3_L1NUX_1d781160}

# money-ware
## Description:
> Flag format: picoCTF{Malwarename}
The first letter of the malware name should be capitalized and the rest lowercase. Your friend just got hacked and has been asked to pay some bitcoins to `1Mz7153HMuxXTuR2R1t78mGSdzaAtNbBWX`. He doesn’t seem to understand what is going on and asks you for advice. Can you identify what malware he’s being a victim of?
## Information:
**Point Value** : 100 points
**Category** : General Skills
## Hints:
> 1. Some crypto-currencies abuse databases exist; check them out!
> 2. Maybe Google might help.
## Tags:
> - picoCTF 2023
> - General Skills
> - osint
## Solution:
> 1. AFter looking the address: `1Mz7153HMuxXTuR2R1t78mGSdzaAtNbBWX` on my search engine, I found an article (https://www.cnbc.com/2017/06/28/ransomware-cyberattack-petya-bitcoin-payment.html) that mentions that the name of the viru is `Petya`, which was the flag. 
# Flag:
> picoCTF{Petya}'

# Permissions:
## Description:
> Can you read files in the root file?
Additional details will be available after launching your challenge instance.
## Information:
**Point Value** : 100 points
**Category** : General Skills
## Hints:
> 1. What permissions do you have?
## Tags:
> - picoCTF 2023
> - General Skills
> - vim
## Solution:
> 1. I launched the instance and placed my provided shell.
> 2. Once in the port, I entered the directory `/`.
> 3. I used the command `sudo vi`, placed my password and inside I wrote `:! ls -la /root`.
> 4. I got the root directory and with `cat` I was able to get the flag.
## Flag:
> picoCTF{uS1ng_v1m_3dit0r_55878b51}

# Repetitions
## Description:
> Can you make sense of this file? Download the file here.
## Information:
**Point Value** : 100 points
**Category** : General Skills
## Hints:
> 1. Multiple decoding is always good.
## Tags:
> - picoCTF 2023
> - General Skills
> - base64
## Solution: 
> 1. I downloaded the file with `wget` command.
> 2. Verified the file n the directory with `ls` command and opened it with `cat` command
> 3. The file had a code in base 64: `VmpGU1EyRXlUWGxTYmxKVVYwZFNWbGxyV21GV1JteDBUbFpPYWxKdFVsaFpWVlUxWVZaS1ZWWnVhRmRXZWtab1dWWmtSMk5yTlZWWApiVVpUVm10d1VWZFdVa2RpYlZaWFZtNVdVZ3BpU0VKeldWUkNkMlZXVlhoWGJYQk9VbFJXU0ZkcVRuTldaM0JZVWpGS2VWWkdaSGRXCk1sWnpWV3hhVm1KRk5XOVVWVkpEVGxaYVdFMVhSbFpSV0VKWVZGVmtNRTVHV2tWU2JYUlVDbUpXV25sVWJGcHZWbGRHZEdWRlZs aGkKYlRrelZERldUMkpzUWxWTlJYTkxDZz09Cg==`.
> 4. I decoded the code using a website: https://www.base64decode.org/
> 5. Kept decoding the code with the output it would give me, until I got the flag. (Around six more times)
## Flag:
> picoCTF{base64_n3st3d_dic0d!n8_d0wnl04d3d_9b59b35c}

# useless
## Description:
There's an interesting script in the user's home directory
Additional details will be available after launching your challenge instance.
## 

# ASCII Numbers
## Description 
Convert the following string of ASCII numbers into a readable string:
`0x70 0x69 0x63 0x6f 0x43 0x54 0x46 0x7b 0x34 0x35 0x63 0x31 0x31 0x5f 0x6e 0x30 0x5f 0x71 0x75 0x33 0x35 0x37 0x31 0x30 0x6e 0x35 0x5f 0x31 0x6c 0x6c 0x5f 0x74 0x33 0x31 0x31 0x5f 0x79 0x33 0x5f 0x6e 0x30 0x5f 0x6c 0x31 0x33 0x35 0x5f 0x34 0x34 0x35 0x64 0x34 0x31 0x38 0x30 0x7d`
## Information:
**Point Value** : 100 points
**Category** : General Skills
## Hints:
> 1. CyberChef is a great tool for any encoding but especially ASCII.
> 2. Try CyberChef's 'From Hex' function.
## Tags:
> - picoGym Exclusive
> - General Skills
## Solution:
> 1. Placed the string in cyberchef (https://gchq.github.io) input space.
> 2. Selected `From Hex` as my recipe and "baked" it. 
> 3. The flag was the output.
## Flag:
> picoCTF{45c11_n0_qu35710n5_1ll_t311_y3_n0_l135_445d4180}

# Based
## Description:
> To get truly 1337, you must understand different data encodings, such as hexadecimal or binary. Can you get the flag from this program to prove you are on the way to becoming 1337? Connect with nc jupiter.challenges.picoctf.org 29956.
## Information:
**Point Value** : 200 points
**Category** : General Skills
## Hints:
> 1. I hear python can convert things.
> 2. It might help to have multiple windows open.
## Tags:
> - picoCTF 2019
> - General Skills
## Solution:
> 1. I connected to the served provided in the description: `c jupiter.challenges.picoctf.org 29956`
> 2. I received a message where I had to decode `01100011 01101000 01100001 01101001 01110010` as a word and I had 45 seconds. With the help of cyberchef, I used the `Magic` Recipe which gives multiple possible outputs. The first one was a binary code which decoded results in the word `chair`.
> 3. Afer giving my answer, a second code appeared: `157 166 145 156`. I followed the same steps as before. The code was in octal and the word was `oven`.
> 4. Afer giving my answer, a third code appeared `6e75727365`. I followed the same steps as before. The code was in hexadecimal and the word was `nurse`.
> 5. Gave my answer and I got the flag.
## Flag:
> picoCTF{learning_about_converting_values_b375bb16}

# plumbing
## Description:
> Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag? Connect to jupiter.challenges.picoctf.org 4427
## Information:
**Point Value** : 200 points
**Category** : General Skills
## Hints:
> 1. Remember the flag format is picoCTF{XXXX}
> 2. What's a pipe? No not that kind of pipe... This `kind`
## Tags:
- picoCTF 2019
- General Skills
## Solution:
> 1. Read the information provided in the hints to better understand the topic of the challenge: https://www.linfo.org/pipes.html
> 2. Connected to the port provided in the description : `nc jupiter.challenges.picoctf.org 4427`
> 3. Using pipes, I verified how many lines the file had. To do so, I used the command `wc` (word count) with `-l` (lines). The result was `10001`
> 4. In order to look for the flag, I used the `grep` command and the word `pico`: `nc jupiter.challenges.picoctf.org 4427 | grep pico`
## Flag:
> picoCTF{digital_plumb3r_5ea1fbd7}

# mus1c
## Description:
> I wrote you a song. Put it in the picoCTF{} flag format.
## Information:
**Point Value** : 300 points
**Category** : General Skills
## Hints:
> 1. Do you think you can master rockstar?
## Tags:
- picoCTF 2019
- General Skills
## Solution:
> 1. Downloaded the file of the song with `wget` command.
> 2. Used the `cat` command to see the song.
> 3. Copied and pasted the lyrics into a website that translates the language and got the flag as the output. The resource : https://codewithrockstar.com/online
https://gchq.github.io/CyberChef/
rrrocknrn0113r
# Flag:
> picoCTF{rrrocknrn0113r}

# flag_shop
## Description:
> There's a flag shop selling stuff, can you buy a flag? `Source`. Connect with `nc jupiter.challenges.picoctf.org 9745`.
## Information:
**Point Value** : 300 points
**Category** : General Skills
## Hints: 
> 1. Two's compliment can do some weird things when numbers get really big!
## Tags:
- picoCTF 2019
- General Skills
## Solution:
> 1. I connected to the port provided: `nc jupiter.challenges.picoctf.org 9745`.
> 2. A store appeared where I coulc check my balance, buy two types of flags (knockoffs or the real flag) and an exit. 
> 3. The balance was not enough to buy the real flag, but enough to buy the knockoffs. I decided to buy `100000000000000000` of the knockoffs flags, which led me to have a balance of `651691084`.
> 4. I bought the real flag and got it. 
## Flag:
> picoCTF{m0n3y_bag5_65d67a74}

# Special
## Description: 
> Don't power users get tired of making spelling mistakes in the shell? Not anymore! Enter Special, the Spell Checked Interface for Affecting Linux. Now, every word is properly spelled and capitalized... automatically and behind-the-scenes! Be the first to test Special in beta, and feel free to tell us all about how Special streamlines every development process that you face. When your co-workers see your amazing shell interface, just tell them: That's Special (TM)
Start your instance to see connection details.
Additional details will be available after launching your challenge instance.
## Information:
**Point Value** : 300 points
**Category** : General Skills
## Hints:
> None
## Tags:
- picoCTF 2019
- General Skill
- bash
- ssh
## Solution:
> 1. I entered the ssh provided in the dscription once launching the challenge instance. 
> 2. All the command I tried to do, did not work. The shell was restricted, until I noticed that adding single quotes with my commands worked. 
> 3. I was able to find the flag with `'/bin/cat' '/home/ctf-player/blargh/flag.txt'`
## Flag:
> picoCTF{5p311ch3ck_15_7h3_w0r57_3befb794}

# 1_wanna_b3_a_r0ck5tar
## Description: 
> I wrote you another song. Put the flag in the picoCTF{} flag format.
# Information:
**Point Value** : 350 points
**Category** : General Skills
## Hints:
> None
## Tags:
- picoCTF 2019
- General Skills
## Solution
> 1. I downloaded the lyyrics of the song given in th description.
> 2. I had to fix some of the syntax and errors in the lyrics for it to run and give me an output when decoding. 
> 3. A different code appeared, which had a serie of numbers: `66, 79, 78, 74, 79,86, 73`.
> 4. When placing those numbers in Cyberchef(https://gchq.github.io/CyberChef/#recipe=Magic(3,false,false,'')&input=NjYgNzkgNzggNzQgNzkgODYgNzM), under the recipe of from decimal, the flag appeared as `BONJOVI`
## Flag:
>  picoCTF{BONJOVI}

# Specialer
## Description: 
> Reception of Special has been cool to say the least. That's why we made an exclusive version of Special, called Secure Comprehensive Interface for Affecting Linux Empirically Rad, or just 'Specialer'. With Specialer, we really tried to remove the distractions from using a shell. Yes, we took out spell checker because of everybody's complaining. But we think you will be excited about our new, reduced feature set for keeping you focused on what needs it the most. Please start an instance to test your very own copy of Specialer.
Additional details will be available after launching your challenge instance.
## Information:
**Point Value** : 400 points
**Category** : General Skills
## Hints:
> None
## Tags:
- picoCTF 2023
- General Skills
- bash 
- ssh 
## Solution: 
> 1. After setting the ssh, I noticed it was a restricted shell. Only allowing me to use a few of the commands.
> 2. I was able to view the files in the directory with `echo *\*`
> 3. I used the command `echo` to view the contents of the files. To do so, I used `echo "$(<filename)"`.
> 4. After checking each one I found the flag on the `ala/kazam.txt` file. 
## Flag: 
> picoCTF{y0u_d0n7_4ppr3c1473_wh47_w3r3_d01ng_h3r3_a8567b6f}
