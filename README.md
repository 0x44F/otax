# Otax
This is a popularized Discord exploit that abuses the analytics sector of Discord.
If any of you had half a brain, you would know how this works. Since you don't, let me explain

### Explaination

First, we connect to the discord gateway so we have to keep sending heartbeats and discord will respond
with an opcode or "operation code". We can send a specially crafted packet which prompts the server to
send us an analytical opcode, to which we respond with the users ID. 

The server will then send back their authentication token encrypted with a key. Since it can be locally
decrypted and the key is only 4 - 7 letters long in every case (depending on when their account was made)
we can easily bruteforce it.

--------------------------------------------------------------------------------------------------------------

### Dispelling rumors

##### Who made Otax?
> I did
##### Was HellSec involved?
> No? Hes just some stupid liar
##### Won't he dox you for this?!?!?!
> No lmfao, hes just some fake internet tough guy.
