# What's a net cat?
## Description:
Using netcat (nc) is going to be pretty important. Can you connect to `jupiter.challenges.picoctf.org` at port `41120` to get the flag?
## Information:
**Point Value:** 100 points
**Category:** General Skills
## Hints:
> nc `tutorial`
## Tags:
- picoCTF2019
- General Skills
## Solution:
>1. Entered the terminal and with the command `netcat` I connected to the host `jupiter.challenges.picoctf.org` and the port `41120`. The flag was provided. 
## Flag:
>picoCTF{nEtCat_Mast3ry_3214be47}

# String it
## Description:
Can you find the flag in `file` without running it?
## Information:
**Point Value:** 100 points
**Category:** General Skills 
## Hints:
> `strings`
## Tags:
- picoCTF2019
- General Skills
## Solution:
>1. Dowloaded the file and verified it was in the directory. 
## Flag:
>picoCTF{5tRIng5_1T_7f766a23}

# Convertme.py
## Description:
Run the Python script and convert the given number from decimal to binary to get the flag.
## Information:
**Point Value:** 100 points
**Category:** General Skills
## Hints:
>1. Look up a decimal to binary number conversion app on the web or use your computer's calculator!
>2. The `str_xor` function does not need to be reverse engineered for this challenge.
>3. If you have Python on your computer, you can download the script normally and run it. Otherwise, use the `wget` command in the webshell.
>4. To use `wget` in the webshell, first right click on the download link and select 'Copy Link' or 'Copy Link Address'
>5.Type everything after the dollar sign in the webshell: `$ wget` , then paste the link after the space after `wget` and press enter. This will download the script for you in the webshell so you can run it! 
>6. Finally, to run the script, type everything after the dollar sign and then press enter: `$ python3 convertme.py`
## Tags:
- Beginner picoMini 2022
- General Skills
- Base
- Python
## Solution:
>1. Dowloaded the file and made sure it was in the directory by using command `ls`.
>2. Ran the file with `python` command.
>3. The following question appear : If 22 is in decimal base, what is it in binary base?
>4. Used RapidTables to convert it, which gave the answer `10110`.
>5. After answering the question, the flag appeared. 
## Flag:
>picoCTF{4ll_y0ur_b4535_762f748e}

# fixme2.py
## Description: Fix the syntax error in the Python script to print the flag.
`Download Python script`
## Information: 
**Point Value:** 100 points
**Category:** General Skills
## Hints: 
>1. Are equality and assignment the same symbol?
>2. To view the file in the webshell, do: `$ nano fixme2.py`
>3. To exit `nano`, press Ctrl and x and follow the on-screen prompts.
>4. The `str_xor` function does not need to be reverse engineered for this challenge.
## Tags:
- Beginner picoMini 2022
- General Skills
- Python
## Solution:
>1. Downloaded the python script with `wget` command.
>2. Tried to run it, but it had a syntaxerror in the line 22.
>3. Used `vim` command to edit it and added `=`.
>4. Ran the code again using `python` command and got the flag.
## Flag:
>picoCTF{3qu4l1ty_n0t_4551gnm3nt_e8814d03}

# Glitchcat
## Description:
Our flag printing service has started glitching!
`$ nc saturn.picoctf.net 52682`
## Information:
**Point Value:** 100 points
**Category:** General Skills
## Hints:
>1. ASCII is one of the most common encodings used in programming
>2. We know that the glitch output is valid Python, somehow!
>3. Press Ctrl and c on your keyboard to close your connection and return to the command prompt.
## Tags:

## Solution:
>1. Ran the command provided `nc saturn.picoctf.net 52682`
>2. Noticed that the result was in python syntax.It also provided part of the flag.
>3. I copied the code and pasted it with `print`, which gave me the last part of the flag.
## Flag: 
> picoCTF{gl17ch_m3_n07_bda68f75}

# HashingJobApp
## Description:
If you want to hash with the best, beat this test!
`nc saturn.picoctf.net 53638`
## Information:
**Point Value:** 100 points
**Category:** General Skills
## Hints:
>1. You can use a commandline tool or web app to hash text
>2. Press Ctrl and c on your keyboard to close your connection and return to the command prompt.
## Tags:
- Beginner picoMini 2022
- General Skills
- hashing
- nc
- shell
- Python
## Solution:
> 1. I ran the command provided in the description: `nc saturn.picoctf.net 53638`
> 2. I received an output that said: `lease md5 hash the text between quotes, excluding the quotes: 'apple pie'`, to provide the right answer I used the following site:
https://www.md5hashgenerator.com/.
> 3. Had to repeat two more times and finally, I got the flag. 
## Flag:
> picoCTF{4ppl1c4710n_r3c31v3d_bf2ceb02}

# PW Crack 1
## Description:
Can you crack the password to get the flag?
Download the password checker `here` and you'll need the encrypted `flag` in the same directory too.
## Information:
**Point Value:** 100 points
**Category:** General Skills
## Hints:
> 1. To view the file in the webshell, do: `$ nano level1.py`
>2. To exit `nano`, press Ctrl and x and follow the on-screen prompts.
>3. The `str_xor` function does not need to be reverse engineered for this challenge.
## Tags:
- Beginner picoMini 2022
- General Skills
- password_cracking 
## Solution:
> 1. I entered the file in the webshell by following the command in the description: `$ nano level1.py`
> 2. Verified it in the directory with `ls` command and tried to run it with `python` command.
> 3. It was requesting a password, which to get I opened the file with `cat` command.
> 4. After analyzing the file, I noticed a specific user name, which ended up being the password.
> 5. Ran the `python` command again and entered the password: `691d`. I got the flag.
## Flag:
> picoCTF{545h_r1ng1ng_56891419}

# PW Crack 2
## Description:
Can you crack the password to get the flag?
Download the password checker `here` and you'll need the encrypted `flag` in the same directory too.
## Information:
**Point Value:** 100 points
**Category:** General Skills
## Hints:
> 1. Does that encoding look familiar?
> 2. The `str_xor` function does not need to be reverse engineered for this challenge
## Tags:
- Beginner picoMini 2022
- General Skills
- password_cracking
## Solution:
> 1. Downloaded both files in the description. 
> 2. I tried to run the file `level2.py` with `python` command, but it was requesting a password.
> 3. Opened the file with `cat` command to analyze it.
> 4. Noticed that there was an hexadecimal code, which said: `if( user_pw == chr(0x33) + chr(0x39) + chr(0x63) + chr(0x65)`. 
> 5. Translated the code to ASCII characters using the following link:
https://ss64.com/ascii.html
> 6. Gathered the password and got the flag. 
## Flag:
> picoCTF{tr45h_51ng1ng_502ec42e}

# PW Crack 3
## Description:
Can you crack the password to get the flag?
Download the password checker `here` and you'll need the encrypted `flag` and the `hash` in the same directory too.
There are 7 potential passwords with 1 being correct. You can find these by examining the password checker script.
## Information:
**Point Value:** 100 points
**Category:** General Skills
## Hints:
> 1. To view the level3.hash.bin file in the webshell, do: `$ bvi level3.hash.bin`
> 2. To exit `bvi` type `:q` and press enter. 
> 3. The `str_xor` function does not need to be reverse engineered for this challenge.
## Tags:
- Beginner picoMini 2022
- General Skills
- password_cracking
- hashing
## Solution:
> 1. After downloading each file needed I tried to open the file with `python` command: `python level3.py`, yet it requested a password. 
> 2. I opened the main file with the `cat` command: `cat level3.py`and noticed a list: 
`pos_pw_list = ["6997", "3ac8", "f0ac", "4b17", "ec27", "4e66", "865e"]`.
> 3. I could had entered each of the password until I reached the flag, but instead I created a file to find the password: `vim pwhash.py`. 
![File](file:///c%253A/Users/Camila%2520De%2520La%2520Rosa/Pictures/Screenshots/Captura%2520de%2520pantalla%2520%25285%2529.png)
> 4. The result after running the file created was: `865e`, which led me to the flag. 
## Flag:
>picoCTF{m45h_fl1ng1ng_2b072a90}

# PW Crack 4

## Description:
Can you crack the password to get the flag?
Download the password checker `here` and you'll need the encrypted `flag` and the `hash` in the same directory too.
There are 100 potential passwords with only 1 being correct. You can find these by examining the password checker script.
## Information:
**Point Value:** 100 points
**Category:** General Skills
## Hints:
> 1. A for loop can help you do many things very quickly.
> 2. The `str_xor` function does not need to be reverse engineered for this challenge.
## Tags:
- Beginner picoMini 2022
- General Skills
- password_cracking
- hashing
## Solution:
> 1. After downloading each file needed I tried to open the file with `python` command: `python level4.py`, yet it requested a password.
> 2. I opened the main file with the `cat` command: `cat level4.py`and noticed an hundred value list. 
> 3. I could had entered each of the password until I reached the flag,but trying each one of them would not be practical. Therefore I created  file `vim pwhash.py2` to find the right password: 
![Code](file:///c%253A/Users/Camila%2520De%2520La%2520Rosa/Pictures/Screenshots/Captura%2520de%2520pantalla%2520%25286%2529.png)
> 4. After running the file I created, the result was: `973a`, which ended up being the password for the flag.
## Flag:
> picoCTF{fl45h_5pr1ng1ng_ae0fb77c}

# PW Crack 5 
## Description:
Can you crack the password to get the flag?
Download the password checker `here` and you'll need the encrypted `flag` and the `hash` in the same directory too. Here's a `dictionary` with all possible passwords based on the password conventions we've seen so far.
## Information:
**Point Value:** 100 points
**Category:** General Skills
## Hints:
> 1. Opening a file in Python is crucial to using the provided dictionary.
> 2. You may need to trim the whitespace from the dictionary word before hashing. Look up the Python string function, `strip`.
> 3.The `str_xor` function does not need to be reverse engineered for this challenge. 
## Tags:
- Beginner picoMini 2022
- General Skills
- password_cracking
- hashing
## Solution:
> 1. After downloading each file needed I tried to open the file with `python` command: `python level5.py`, yet it requested a password.
> 2.  I opened the main file with the `cat` command: `cat level5.py`and noticed another list.
> 3. I created  file `vim pwhash.py3` to find the right password:
 ![code](file:///c%253A/Users/Camila%2520De%2520La%2520Rosa/Pictures/Screenshots/Captura%2520de%2520pantalla%2520%25289%2529.png)
> 4. After running the file I created, the result was: `9581`, which ended up being the password for the flag.
## Flag:
> picoCTF{h45h_sl1ng1ng_36e992a6}