# Optional - Extra Challenges

# Cookies:	
## Description:
Who doesn't love cookies? Try to figure out the best one. http://mercury.picoctf.net:21485/
## Information:
**Point Value**: 40 points
**Category**: Web Explotation
## Hints:
>None
## Tags:
PicoCTF2021 Web Explotation
## Solution:
>1. Enter the url provided in the description.
>2. The website will provide a statement that says "Welcome to my cookie search page. See how much I like different kinds of cookies!" and it will provide a space to place your input. One can start with "snickerdoodle" as shown in the input space and the website will show the following message "I love snickerdoodle cookies!".
>3. When inspecting the website (Windows: Ctrl+I), there will be a "Cookies" storage in the "Application" window. It will show a table with two collumn "Name" and "Value".
>4. Each time you place a name of a cookie, the value will change. To find the value with the flag do a binary search. Refreshing the website each time the value changes. 
>5. The value was 18, I refreshed the website and it provided the flag:picoCTF{3v3ry1_l0v3s_c00k135_94190c8a}
## Flag:
>picoCTF{3v3ry1_l0v3s_c00k135_94190c8a}

# Insp3ct0r	
## Description:
Kishor Balan tipped us off that the following code may need inspection: https://jupiter.challenges.picoctf.org/problem/9670/ (link) or http://jupiter.challenges.picoctf.org:9670
## Information:
**Point Value**: 50 points
**Category**: Web Explotation
## Hints:
>How do you inspect web code on a browser?
>There's 3 parts
## Tags:
- PicoCTF2021 
- Web Explotation
## Solution: 
>1. Open the link provided in the description of the challenge.
>2. Inspect the link.
>3. The first part of the flag will be in the tab `Sources` in the subsection `9670/`.
>4. The second part of the flag will be in the tab `Sources` in the subsection `mycss.css`.
>5. The third part of the flag will be in the tab `Sources` in the subsection `myjs.js`.
>6. Gather all the parts and it will be the flag
## Flag:
>picoCTF{tru3_d3t3ct1ve_0r_ju5t_lucky?2e7b23e3}

# Warmed Up	
## Description:
What is 0x3D (base 16) in decimal (base 10)?
## Information:
**Point Value**: 50 points
**Category**: General Skills
## Hints:
>1. Submit your answer in our flag format. For example, if your answer was '22', you would submit 'picoCTF{22}' as the flag.
## Tags:
- picoCTF 2019
- General Skills
## Solution:
>1. Open: https://www.rapidtables.com/convert/number/hex-to-decimal.html
>2. Input the hex number, in this case: 3D
>3. The flag will be the decimal number, in this case: 61.
## Flag:
>picoCTF{61}

# Bases	
## Description:
What does this `bDNhcm5fdGgzX3IwcDM1` mean? I think it has something to do with bases.

## Information:
**Point Value**: 100 points
**Category**: General Skills
## Hints:
>1. Submit your answer in our flag format. For example, if your answer was 'hello', you would submit 'picoCTF{hello}' as the flag.
## Tags:
- picoCTF 2019
- General Skills
## Solution:
>1. Open CyberChef (https://gchq.github.io/CyberChef/)
>2. Place `bDNhcm5fdGgzX3IwcDM1` in the input and bake from base64.
>3. The flag will be in th output. 
## Flag:
>picoCTF{l3arn_th3_r0p35}

# Codebook	
## Description:
Run the Python script code.py in the same directory as codebook.txt.
- Download code.py
- Download codebook.txt
## Information:
**Point Value**: 100 points
**Category**: General Skills
## Hints:
>1. On the webshell, use `ls` to see if both files are in the directory you are in.
> 2. The `str_xor` function does not need to be reverse engineered for this challenge.
## Tags:
- Beginner picoMini 2022
- General Skills
- shell
- Python
## Solution:
>1. Downloaded files provided in the challenge.
>2. Verified that the files were in the directory with `ls` command.
>3. Followed up with `python code.py` to interpret the file, which led me to my flag.
## Flag:
>picoCTF{c0d3b00k_455157_197a982c}

# dont-use-client-side	

## Description:
Can you break into this super secure portal? https://jupiter.challenges.picoctf.org/problem/17682/ (link) or http://jupiter.challenges.picoctf.org:17682
## Information:
**Point Value**: 100 points
**Category**: Web Exploitation
## Hints:
>1. Never trust the client.
## Tags:
- picoCTF 2019
- Web Exploitation
## Solution:
>1. Open the link to the website and there will be an option to provide credentials.
>2. Inspect the website.
>3. Open the 'Elements' tab and analyze the javascript provided.
>4. The flag will be divided in parts in the javascript. 
## Flag:
>picoCTF{no_clients_plz_b706c5}

# First Grep:
## Description
Can you find the flag in `file`? This would be really tedious to look through manually, something tells me there is a better way.
## Information:
**Point Value**: 100 points
**Category**: General Skills
## Hints:
>1.grep `tutorial`
## Tags:
- picoCTF 2019
- General Skills
## Solution:
>1. Dowloaded the file provided in the description.
>2. Verified it was in the directory with `ls` command.
>3. Displayed the file content with the `cat` command and the flag was in it.

## Flag:
>picoCTF{grep_is_good_to_find_things_5af9d829}

# fixme1.py:

## Description:
>Fix the syntax error in this Python script to print the flag.
Download Python script
## Information
**Point Value**: 100 points 
**Category**: General Skills
## Hints:
>1.Fix the syntax error in this Python script to print the flag.
`Download Python script
>2.To view the file in the webshell, do: `$ nano fixme1.py`
>3.To exit `nano`, press Ctrl and x and follow the on-screen prompts.
>4.The `str_xor` function does not need to be reverse engineered for this challenge.
## Tags:
- Beginner picoMini 2022
- General Skills 
- Python
## Solution:
>1. Downloaded the file and verified it in the directory with `ls` command.
>2. I tried to read it with the `python` command, yet it stated `IndentationError: unexpected indent`.
>3. To fix it, I edited the file with `vim` command.In this case, I deleted the indentetion in the line 15. Exited with command `:wq`.
>4. I executed the file with the `python` command and I had the flag.

## Flag:
>picoCTF{1nd3nt1ty_cr1515_182342f7}

# login:

## Description:
> My dog-sitter's brother made this website but I can't get in; can you help?
login.mars.picoctf.net
## Information:
**Point Value**: 100 points
**Category**: Web Exploitation
## Hints:
None
## Tags: 
- picoMini by redpwn 
- Web Exploitation
## Solution:
>1. Entered the link provided and a website appeared.
>2. Inspected the website and found a javascript in the `Sources` called `index.js`.
>3. After inspecting the script, there was a code in a line that was encoded using the btoa method (a string enconded in Base-64).
>4. Used CyberChef to place my input `cGljb0NURns1M3J2M3JfNTNydjNyXzUzcnYzcl81M3J2M3JfNTNydjNyfQ` and baked it with base64. Which led me to the flag. 
## Flag:
>picoCTF{53rv3r_53rv3r_53rv3r_53rv3r_53rv3r}

# logon:

## Description:
The factory is hiding things from all of its users. Can you login as Joe and find what they've been looking at? https://jupiter.challenges.picoctf.org/problem/44573/ (link) or http://jupiter.challenges.picoctf.org:44573
## Information:
**Point Value**: 100 points
**Category**: Web Exploitation
## Hints:
Hmm it doesn't seem to check anyone's password, except for Joe's?
## Tags:
- picoCTF2019 
- Web Exploitation
## Solution:
>1. Enter the link provided. 
>2. At glance, it will ask for an ursername and a password. If given, there will be a message saying "No flag for you".
>3. Inspect the website 
>4. Inspect the tab `Application` and there is a value named `False`. Change it to `True`.
>5. Refresh the page and the flag will appear. 
## Flag:
>picoCTF{th3_c0nsp1r4cy_l1v3s_0c98aacc}