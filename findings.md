# How secure is your password?

Do you know that any password can be cracked by brute force and other techniques? The once brute-forced password can be used in several ways to get to sensitive information. So here the strength of the password plays an important role. As we discussed, every password can be cracked, but the main point is TIME. Let's say I have set my password to my name or numbers; this can be easily guessed or brute-forced with freely available tools. 

In order to avoid such casualties, we have to set  our password strongly such that it takes months to bruteforce it. SO CANT I JUST KEEP THE STRONGEST PASSWORD SO NO ONE CAN CRACK IT? AND THE ANSWER IS NO AS I SAID, ANY PASSWORD CAN BE CRACKED BUT WE CAN PUSH THE LIMIT SO IT TAKES MONTHS TO CRACK IT!! 

There are many available applications and tools to test the strength of our passwords. 

Go to -> https://bitwarden.com/password-strength/

![example](https://github.com/WEAREJAM/Kickstart_at_ElevateLabs-WiresharkAnalysis/blob/main/assets/sa1.png?raw=true)

This application is showing how strong your password is and how many hours/days/years will take for any tool to crack it.

# Trail 1: Just name 

![example](https://github.com/WEAREJAM/Kickstart_at_ElevateLabs-WiresharkAnalysis/blob/main/assets/sa2.png?raw=true)

__The password is very weak and it will take less than a second to crack it.__ 

# Trail 2: Adding special characters

![example](https://github.com/WEAREJAM/Kickstart_at_ElevateLabs-WiresharkAnalysis/blob/main/assets/sa3.png?raw=true)

__The password is very weak and it takes 2 seconds to crack it__

# Trail 3: First character uppercase and more characters

![example](https://github.com/WEAREJAM/Kickstart_at_ElevateLabs-WiresharkAnalysis/blob/main/assets/sa4.png?raw=true)

__The password strength is good and it takes 3 hours to crack__ Not good enough

# Trail 4: special character and numeric 

![example](https://github.com/WEAREJAM/Kickstart_at_ElevateLabs-WiresharkAnalysis/blob/main/assets/sa5.png?raw=true) 

__The password is strong and the time estimated to crack is 5 months__ Pretty good.

This is just an example of how well and secure can your password be with adding numerics and special characters. 

Note: Every brute forcing tool is just designed to try the already available characters stored. When your password is common it can be crackedd with the already available combinations. 

Previous the websites do accept  any password but now we see the application signup is not possible when your password is not strong enough 

![example](https://github.com/WEAREJAM/Kickstart_at_ElevateLabs-WiresharkAnalysis/blob/main/assets/sa6.png?raw=true) 

In the above image, we see the password requirements there, the account can be created only  when the password is strong enough. PERIOD!!

Till now we saw how can we set our password and now let's see what tools used for brute forcing. 

Hydra 

John the Ripper 

So can i just use the tool randomly with the any wordlist?? NO




