# Should You Be Worried About Your Security Online?

1. TOC
{:toc}

As of late, I have been going down the rabbit hole of personal security in the context of one's online presence.
And its really amazing how little technical knowledge one needs nowadays to keep one's accounts and identity safe.

## What Options Does the Regular Person Have?

There are Quite a few options available now. I have narrowed it down to **3** categories.

### First, you want to protect your passwords.

The password is your last defense against a cyberattack. It can be what stands between you and identity theft,
the loss of thousands of dollars (*really you could lose it all. even more than what you have.*), ruined credit (*debt out of nowhere*),
or embarrassing social media posts (*If you're unlucky, this could cost you your job*).

#### So what exactly makes a strong password? 

There are three criteria you must consider when creating a password. First of all, there is the obvious (although not so obvious that everyone practices it), you want 
to make your password as complicated as possible (*Length, and a combiniation of numbers, symbols, and mixed cases*), **while still being able to remember it**.
Secondly, you do not want to reuse your password on other accounts. This will give the would-be attacker access to multiple accounts if he gets ahold
of it. But this leads to the issue of being able to remember the password each time you change it. And Thirdly, you want to change your password over time. 
a password is always only a temporary protection. If someone wants to crack your password, they can brute force,
or if you use a common password, use a dictionary attack. These tactics are simply guessing based on randomness or using a list
of leaked passwords hoping you dont think too differently from others online (this tactic is very effective).

#### So how does one meet the aforementioned criteria, while keeping track of our passwords?

The solution is a password manager. A password manager is a program that saves all of your passwords for various accounts and can tie into your
mobile device, desktop, and web browser. So this only leaves you with **1** password to remember and allows you to make it as complicated as possible
since it is only 1 password [^1]. 

#### Are Password Managers Reliable? And How Does One Get A Password Manager?

Password managers are very reliable. They will have End-to_end Encryption, which means only the sender and receiver with the proper encryption keys can read the communication. So, in theory, even the people running the servers cannot see your messages. So, if one of the companies hosting your passwords gets hacked, the hacker will still need your master password to look into your vault and get your other passwords.

A few of the more popular and reputable passwords managers are [LastPass](https://www.lastpass.com/), [BitWarden](https://bitwarden.com/), and [1Password](https://1password.com/).

#### Is A Password Manager Enough?

No. Passwords are still not enough these days. with key loggers, phishing attacks, and various other methods, there are ways to get around having to guess your password. They can get it directly from you without your knowledge, and often times this is much easier and more effective.

So now you're probably thinking, then whats the point of a password manager now? Well, its still your last defense, but there is many more walls you can put up. The best way to prevent some of these attack is to enable multi-factor authentication for all of your accounts. This makes it so you have to use a 2nd form of authentication along with your password. This most often takes the form of an authenitcator app on your phone that generates a new passcode on a set interval (15-30 seconds). When you input your password it will ask for the passcode, or alternatively you can verify it with the push of a button on your phone. LastPass offers an authentication app you can download for iphone or android. Microsoft, Google, and other large tech companies offer their own authenitcation apps as well.

If the authentication app is still not secure enough for you, you can use a yubikey which is a physical USB key that contains the necessary encryption keys to authenticate you. There are even USB keys with finger print readers on them for further security. In most cases this is overkill.

### Second, you want to obscure your traffic.

### Third, you want a reliable browser.

### Bonus: Encrypted Messenger/Email
[^1]: You will want to change this password regularly as well. the more often, the better.
