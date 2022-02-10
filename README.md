# GoT-PaWnD-
Password Checker Python Script

In recent times there has been a lot of data breaches in big tech companies from hacker's group and most of the accounts got hacked along with their passwords. But unkowingly people are still using the same password for there accounts made in Facebook, Youtube, Twitter etc. We hear a lot of hacking news on a daily basis. This Password checker helps to see whether your password was ever been hacked. Now there is a website named haveibeenpwned which takes your password and check in it's server which has all the leaked accounts to see whether your password is secure or not.

The problem is we can't even trust this website, so with this script you enter your password and the program converts it into hashes and then send the first five character of the hashes. The website gives a response with a list of all the passsword in which the first five hashes are same. So, if the complete hash code is present in any of the password from the list that means the password of the user was hacked before and the user need to change it, Otherwise its all good.
