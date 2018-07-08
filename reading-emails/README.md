Hunt for the  correct ID

An email ID consists of 3 parts:
        <local>@<domain>.<extension or tld>

The local-part of a valid email address can have:
1)  uppercase and lowercase letters (A-Z, a-z)
2)  digits  0-9
3)  valid special characters: !#$%^&*{}|~_+-=/' .Whereas '.' is valid only if it's not first and last character. 
4) It’s length must not exceed 64 characters.

The domain-part of the email address can have:
1)  uppercase and lowercase letters (A-Z,a-z)
2)  '-' is allowed only if it's the first or last character
3)  digits between 0-9 but domain cannot be entirely numeric
4)  special symbols are not allowed in the domain 

The maximum length of the extension allowed here is 3 and must not have any special characters. 
Email address verification are usually used for data validation. Well, there are other techniques better than this one but this is the basic one of them. So, given here is a file 'emails.txt'. So go through all the emails given in the file and implement email validation as explained above.

Sample Input:
//Read from the file “emails.txt”
Testmail..com

raven.claw@#hogs.uk

finnick22@d13.com

Sample Output:

finnick22@d13.com
