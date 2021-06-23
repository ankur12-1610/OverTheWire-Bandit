
             OverTheWire-Bandits 




Level 0 :
Command:  ankur12@ankur-12:~$ ssh bandit0@bandit.labs.overthewire.org -p 2220

                                                                                                                                                                                                                                                                                                                                

Level 0 - 1 :
commands:   
●	bandit0@bandit:~$ ls
●	bandit0@bandit:~$ cat readme       (Password-boJ9jbbUNNfktd78OOpsqOltutMc3MY1)
●	bandit0@bandit:~$ exit
●	ankur12@ankur-12:~$ ssh bandit1@bandit.labs.overthewire.org -p 2220
●	bandit1@bandit.labs.overthewire.org's password: (Entered the above password)




Level 1 - 2 :
commands:   
●	bandit1@bandit:~$ ls
●	bandit1@bandit:~$ cat ./-       (Password-boJ9jbbUNNfktd78OOpsqOltutMc3MY1)
●	bandit1@bandit:~$ exit
●	ankur12@ankur-12:~$ ssh bandit2@bandit.labs.overthewire.org -p 2220
●	bandit2@bandit.labs.overthewire.org's password: (Entered the above password)


Level 2 - 3 :
commands:   
●	bandit2@bandit:~$ ls

●	bandit2@bandit:~$ cat spaces\ in\  this\ filename     
(Password-UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK)

●	bandit2@bandit:~$ exit
●	ankur12@ankur-12:~$ ssh bandit3@bandit.labs.overthewire.org -p 2220
●	bandit3@bandit.labs.overthewire.org's password: (Entered the above password)



Level 3 - 4 :
commands:   
●	bandit3@bandit:~$ ls
●	bandit3@bandit:~$ cd inhere
●	bandit3@bandit:~$ ls -alps
●	bandit3@bandit:~$ cat .hidden   (Password-pIwrPrtPN36QITSp3EQaw936yaFoFgAB)
●	bandit3@bandit:~$ exit
●	ankur12@ankur-12:~$ ssh bandit4@bandit.labs.overthewire.org -p 2220
●	bandit4@bandit.labs.overthewire.org's password: (Entered the above password)








                                                                                                                                                                                                                                                                                                                                      
Level 4 - 5 :
commands:   
●	bandit4@bandit:~$ ls
●	bandit4@bandit:~$ cd inhere
●	bandit4@bandit:~$ ls -alps
●	bandit4@bandit:~/inhere$ find . -type f | xargs file   (we get the ASCII text file)
●	bandit4@bandit:~$ cat . /-file07 (Password-koReBOKuIDDepwhWk7jZC0RTdopnAYKh)
●	bandit4@bandit:~$ exit
●	ankur12@ankur-12:~$ ssh bandit5@bandit.labs.overthewire.org -p 2220
●	bandit5@bandit.labs.overthewire.org's password: (Entered the above password)
















Level 5 - 6 :
commands:   
●	bandit5@bandit:~$ ls
●	bandit5@bandit:~$ cd inhere
●	bandit5@bandit:~$ ls -alps
●	bandit5@bandit:~/inhere$ find . -type f -size 1033c ! -executable 
●	
●	bandit5@bandit:~$ cat ./maybehere07/.file2  
(Password-DxjZPULLxYr17uwoI01bNLQbtFemEgo7)
●	
●	bandit5@bandit:~$ exit
●	ankur12@ankur-12:~$ ssh bandit6@bandit.labs.overthewire.org -p 2220
●	bandit6@bandit.labs.overthewire.org's password: (Entered the above password)



Level 6 - 7 :
commands:   
●	bandit6@bandit:~$ ls
●	bandit6@bandit:~$ ls -alps
●	bandit6@bandit:~$ find / -type f -user bandit7 -group bandit6 -size 33c
●	
●	bandit6@bandit:~$ cat /var/lib/dpkg/info/bandit7.password
(Password-HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs)
●	
●	bandit6@bandit:~$ exit
●	ankur12@ankur-12:~$ ssh bandit7@bandit.labs.overthewire.org -p 2220
●	bandit7@bandit.labs.overthewire.org's password: (Entered the above password)


                                                                                                                                                                                                         

Level 7 - 8 :
commands:   
●	bandit7@bandit:~$ ls
●	bandit7@bandit:~$ cat data.txt
●	
●	bandit7@bandit:~$ strings data.txt | grep “millionth”
(Password-cvX2JJa4CFALtqS87jk27qwqGhBM9plV)

●	bandit7@bandit:~$ exit
●	ankur12@ankur-12:~$ ssh bandit8@bandit.labs.overthewire.org -p 2220
●	bandit8@bandit.labs.overthewire.org's password: (Entered the above password)


Level 8 - 9 :
commands:   
●	bandit8@bandit:~$ ls
●	bandit8@bandit:~$ strings data.txt
●	
●	bandit8@bandit:~$ sort data.txt

●	bandit8@bandit:~$ stort data.txt | uniq -c     
(Password: UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR)


●	bandit8@bandit:~$ exit
●	ankur12@ankur-12:~$ ssh bandit9@bandit.labs.overthewire.org -p 2220
●	bandit9@bandit.labs.overthewire.org's password: (Entered the above password)


Level 9 - 10 :
commands:   
●	bandit9@bandit:~$ ls
●	
●	bandit9@bandit:~$ strings data.txt     
(Password: truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk)


●	bandit9@bandit:~$ exit
●	ankur12@ankur-12:~$ ssh bandit10@bandit.labs.overthewire.org -p 2220
●	bandit10@bandit.labs.overthewire.org's password: (Entered the above password)


Level 10 - 11 :
commands:   
●	bandit10@bandit:~$ ls
●	
●	bandit10@bandit:~$ cat data.txt    
 
●	bandit10@bandit:~$  base64 -d data.txt   
(Password: IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR)


●	bandit10@bandit:~$ exit
●	ankur12@ankur-12:~$ ssh bandit11@bandit.labs.overthewire.org -p 2220
●	bandit11@bandit.labs.overthewire.org's password: (Entered the above password)

Level 11 - 12 :
commands:   
●	bandit11@bandit:~$ ls

●	bandit11@bandit:~$ cat data.txt    
 
●	used cyrber chef to use ROT13 ( ‘Gur cnffjbeq vf 5Gr8L4qetPEsPk8htqjhRK8XSP6x2RHh’ trhansformed to ‘The password is 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu’)

(Password: 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu)


●	bandit11@bandit:~$ exit
●	ankur12@ankur-12:~$ ssh bandit12@bandit.labs.overthewire.org -p 2220
●	bandit12@bandit.labs.overthewire.org's password: (Entered the above password)


Level 12 - 13 :
commands:   
Commands over here are too long so I have inserted the screenshots


                                                                              

                                                                             





     
                                

password: ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL



Level 13 - 14 :
commands:   
●	bandit13@bandit:~$ ls

●	bandit13@bandit:~$   ssh -i sshkey.private bandit14@localhost

●	bandit14@bandit:~$ cat /etc/bandit_pass/bandit14 
 (Password: 4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e)


Level 14 - 15 :
commands:   
●	bandit14@bandit:~$ nc localhost 30000
4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e
            (Password: BfMYroe26WYalil77FoDi9qh59eK5xNr)

●	bandit14@bandit:~$ exit
●	ankur12@ankur-12:~$ ssh bandit15@bandit.labs.overthewire.org -p 2220
●	bandit15@bandit.labs.overthewire.org's password: (Entered the above password)

 
 
Level 15 - 16 :
commands:   
●	bandit15@bandit:~$ ncat –ssl  localhost 30001
BfMYroe26WYalil77FoDi9qh59eK5xNr
            (Password: cluFn7wTiGryunymYOu4RcffSxQluehd)

●	bandit15@bandit:~$ exit
●	ankur12@ankur-12:~$ ssh bandit16@bandit.labs.overthewire.org -p 2220
●	bandit16@bandit.labs.overthewire.org's password: (Entered the above password)

 
