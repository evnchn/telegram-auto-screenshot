# Telegram Auto Screenshot
Automatically take screenshot of the URL when Telegram message received

## Backstory

![Scam message](markdown_media/scam_message.jpg)

There's a scam going on in WhatsApp about someone claiming to have "looked at your CV" and "would like to offer you a job". 

In reality, it consists of:
- Pressing like on particular products (even this is mostly fake)
- Pay them money, and then they will pay you back an amount greater than you paid (**very sketchy, do not participate!! You will not get your money back!!**)

The reason the "pressing like" is likely a scam is because, my auto screenshot tool **does not create a screenshot with the like button pressed**, 
though, I very much could with some extra CSS trickery. 

They claim that if you do the "pay them money, and then they will pay you back" thing, you'll earn more on each pressing like. In reality, they can make a profit out of you by holding onto your money. 

In fact, with this bot, just as I made enough money as the minimum "pay them money" amount (~$HKD80), they kicked me out of the Telegram group :(

## Expected message format

Message input: 

![Expected input](markdown_media/input.png)

Message output: 

![Expected output](markdown_media/output.png)

## Note

The code is made to run as a Pyrobud module. It is a modified version of the `example.py`. 

It was made in a hurry and as a proof-of-concept. 

It is also a screw-you as a programmer towards scammers. I did got ~$HKD80 from them using this tool. 
