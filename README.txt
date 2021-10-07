'''
hostname R1
ip domain-name wsr.lol 
crypto key generate rsa
ip add 10.0.10.1 255.255.255.0
no sh
username admin privilege 15 secret cisco
line vty 0 15 
login local
transport input ssh
'''
