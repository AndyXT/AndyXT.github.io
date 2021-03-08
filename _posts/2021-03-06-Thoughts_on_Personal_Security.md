# Should You Be Worried About Your Online Security? [**In Progress**]

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
to make your password as complicated as possible (*Length, and a combination of numbers, symbols, and mixed cases*), **while still being able to remember it**.
Secondly, you do not want to reuse your password on other accounts. This will give the would-be attacker access to multiple accounts if he gets ahold
of it. But this leads to the issue of being able to remember the password each time you change it. And Thirdly, you want to change your password over time. 
a password is always only a temporary protection. If someone wants to crack your password, they can brute force,
or if you use a common password, use a dictionary attack. These tactics are simply guessing based on randomness or using a list
of leaked passwords hoping you don't think too differently from others online (this tactic is very effective).

#### So how does one meet the aforementioned criteria, while keeping track of our passwords?

The solution is a password manager. A password manager is a program that saves all of your passwords for various accounts and can tie into your
mobile device, desktop, and web browser. With the click of a button, it will fill in your passwords for you. Many of us already use one built into our browsers or phones. But sometimes this ties us to a specific ecosystem like google or apple. A good password manager can be independent and multi-platform. The power of a password manager is that it leaves you with only **1** password to remember, which allows you to make it as complicated as possible
since it is only 1 password [^1]. 

#### Are Password Managers Reliable? And How Does One Get A Password Manager?

Password managers are very reliable. They have End-to-end Encryption (*at least the PM's I will be suggesting do*), which means only the sender and receiver with the proper encryption keys can read what is being communicated (the information containing your passwords). So, in theory, even the people running the servers cannot see your messages. That means, that if one of the companies hosting your passwords gets hacked, the hacker will still need your master password to look into your vault and get your passwords.

A few of the more popular and reputable passwords managers are [LastPass](https://www.lastpass.com/), [BitWarden](https://bitwarden.com/), and [1Password](https://1password.com/).

#### Is A Password Manager Enough?

No. Passwords are still not enough these days. with key loggers, phishing attacks, and various other methods, there are ways to get around having to guess your password. They can get it directly from you without your knowledge, and often times this is much easier and more effective.

So now you're probably thinking, then what's the point of a password manager? Well, its still your last defense, but there is many more walls you can put up. The best way to prevent most of these attacks is to enable multi-factor authentication (MFA) for all of your accounts. This makes it so you have to use a 2nd form of authentication along with your password. Most services offer the ability to verify by sending a text to your phone. But there is a better way. This most often takes the form of an authenticator app on your phone that generates a new passcode on a set interval (15-30 seconds). When you input your password it will ask for the passcode, or alternatively some will send notifications that ask you verify it with the push of a button on your phone. LastPass offers an authentication app you can download for iPhone or android, and its compatible with most, if not all services that allow MFA. Alternatively, Microsoft, Google, and the other large tech companies offer their own authentication apps that are just as good. Its mostly up to your preference. However, many people find giving the large tech companies even more of their information quite distasteful..

If the authentication app is still not secure enough for you, you can use a yubikey which is a physical USB key that contains the necessary encryption keys to authenticate you. There are even USB keys with finger print readers on them for further security. In most cases this is overkill.

### Second, you want to obscure your internet traffic.

One of the most risky things you can do is connect to public wifi. This opens you up for a plethora of attacks. Someone can easily intercept your traffic, and see every key you enter on your keyboard. However, it's difficult not to use public wifi in many cases. Especially for a student looking for a quiet place to study, if one is traveling for work, or if one is in a foreign country. In each cases using data can be prohibitively expensive. 

However, the dangers are not limited to public wifi. If one is not careful with their router settings, their home wifi can fairly easily be hacked, and the would-be attacker can get all the information they want from your traffic or keystrokes.

Finally, ISPs (Internet Service Providers) often take advantage of having logs of everyone's internet traffic by selling the information to the large tech companies looking to make money off of targeted advertising. And for many people, this predatory behavior alone is enough to make them look for a way to obscure their internet traffic. 

The solution is to use a VPN (Virtual Private Network). 

#### So what is a VPN?

A VPN basically allows you to surf the web by going through a remote server that encrypts all of your traffic, and hides your location. This means anyone who manages to get into your wifi network, will be unable to make heads or tails of your traffic. They will see the encrypted communications being sent back and forth between you and the VPN server, while being unable to make heads or tails of what is being communicated. 

#### Are there any downsides to a VPN?

Yes, there is some give and take with a VPN. For instance, you will lose some speed while using a VPN, as it is constantly encrypting and decrypting your communications. Also, the distance between you and the remote server can be a factor in your speed reduction.

Also, you will have to pay a fee to use the VPN. Usually its an annual fee, and I personally feel like it is worth it for the sense of security it provides. 

#### How do I get a VPN?

There are many options available for setting up a VPN. You can host your own VPN on separate server (locally or remotely in the cloud) and maintain the software and handle the networking (*This can be a lot of work. And if you can do this, then you won't be getting much out of this blog*). Or you can use one of the myriad VPN services out there.

### Third, you want a reliable browser.

### Bonus: Encrypted Messenger/Email & Non-Tracking Search Engines.
[^1]: You will want to change this password regularly as well. the more often, the better.
