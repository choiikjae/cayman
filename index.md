---
layout: default
---

# My OSSW PROJECT.

**PLUG N GENIE**

new product **< _CH-22_ >**




#### INDEX

*   SetTop Box MVP Making Teaser.
*   Interim Presentation 1, 2
*   Final Product Making Snapshot
* 	 3D Printing
*   Final Presentation
*   CODE
*   Review


## [](#header-2) SetTop Box MVP Making Teaser.

> This is first Prototype(Most Valuable Player) Making Teaser
> <iframe width="854" height="480" src="https://www.youtube.com/embed/cm97yw0XA68" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>
> 



## [](#header-2) Interim Presentation 1

> This is our interim presentation in class
> <iframe width="854" height="480" src="https://www.youtube.com/embed/WPMjf_oOeDo" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>



## [](#header-2) Interim Presentation 2

> This is our interim presentation in studio
> <iframe width="854" height="480" src="https://www.youtube.com/embed/WGzCB_HqLOc" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>



* * *

## [](#header-2) Final Product Making Snapshot

>![abc](https://postfiles.pstatic.net/MjAxNzEyMjZfMTc4/MDAxNTE0Mjc5ODYxMjY3.xMyprycuFYWn1KfHJzM2yQGZcO1YtH5nKkrX_lwX49Qg.se1tXtFFb0_mJH6zm81y-IH2PPHiFZZ-aDplJ7pExOkg.PNG.ssumoa/image_6476745941514279829506.png?type=w966)
>![abc](https://postfiles.pstatic.net/MjAxNzEyMjZfOTUg/MDAxNTE0Mjc5OTQ3NDYw.mve0hOPYptadDbUIlP0v0klmJkfhuLAckHP1FTWQQmIg.OBQvS9Zm9c39PrqxvPNhmysbaZkI-mEkHPCNoaBbrhMg.PNG.ssumoa/image_3517951681514279829508.png?type=w966)
>![abc](https://postfiles.pstatic.net/MjAxNzEyMjZfODAg/MDAxNTE0Mjc5OTQ4MzMx.eQlDJh0FDpnH34B9wDyjJUneX4akCCRLtpHPP54UR_Ig.A8A5T5oFa25M4-mb7_kIYKdvFNNjpS13En8q9-Yr0MYg.PNG.ssumoa/image_8601754001514279829508.png?type=w966)
>![abc](https://postfiles.pstatic.net/MjAxNzEyMjZfMTEz/MDAxNTE0Mjc5OTQ2MDYz.G6zCOAQEHYRc1mwT-mMfspfHP7sFJC_8su5-RXUwX50g.77w_7DSFejgeZ5WjSsgUSbiZ7GcmbHM3_B9j8Qz3S24g.PNG.ssumoa/image_7780098221514279829508.png?type=w966)
>![abc](https://postfiles.pstatic.net/MjAxNzEyMjZfMjUy/MDAxNTE0Mjc5OTYzNDgx.LPyqXjs2kfLSz7oBkDDPOm4XesLhpT9VEMTuNkZT10kg.LPNmlrAvWFZPP68I2nV0lCoi96coUm6rb-Xb5Cz526wg.PNG.ssumoa/image_9678767961514279829509.png?type=w966)
> 

## [](#header-2) 3D Printing

>![abc](https://postfiles.pstatic.net/MjAxNzEyMjZfMTM2/MDAxNTE0Mjc5OTgyOTg1.QstwCGsw5iyNjs0LYEuq4_5V6qB1Z8uvmP-0yly9gM8g.0n1w0wHtYJV-IBZk_TrqYKi43ATTsPmYJSa7wGVdbJYg.PNG.ssumoa/image_6163899441514279829509.png?type=w966)
>![abc](https://postfiles.pstatic.net/MjAxNzEyMjZfMTgg/MDAxNTE0Mjc5OTc5ODIw.aV5gkiDstMqIUnJK2qqQZ8d-Fomgu6VBL_41doctT0Ug.ysLsGq3b-Td-0-6onHYZ1Ejh2Imr2X2UKOE2AB34pXUg.PNG.ssumoa/image_2935936921514279829510.png?type=w966)
>![abc](https://postfiles.pstatic.net/MjAxNzEyMjZfMjA2/MDAxNTE0Mjc5ODI5MTky._w_Qm_PfkqzjhLuQBYnX9bxE6V9sCSvFnB8a4vPPOvQg.bQyw6CyYM9uMJNppl0uOh9jQ3cGbJmUMuuYwcdNBWzIg.PNG.ssumoa/9.png?type=w966)
>![abc](https://postfiles.pstatic.net/MjAxNzEyMjZfMTYw/MDAxNTE0Mjc5OTgwODAw.Wr_ewnPT-Z8CZum4bdGkj90l8qMASsmQP85vvM-FrUEg.TcvteJXdLVuC2oOcFxXa-HmqH405RTNJT78dNUhgIAEg.PNG.ssumoa/image_3211879601514279829509.png?type=w966)
> 
> 


## [](#header-2) Final Presentation

> <iframe width="854" height="480" src="https://www.youtube.com/embed/FhJa0tm1bTM" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>
> <iframe width="854" height="480" src="https://www.youtube.com/embed/T3NYgEYmuMk" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>


### [](#header-3) CODE

```js
// python CODE with raspberry pi
import time
import smbus
import RPi.GPIO as GPIO
import os
import vlc

 
GPIO.setmode(GPIO.BCM)
 
GPIO.setup(14, GPIO.IN)
 
GPIO.setup(15, GPIO.IN)
 
GPIO.setup(18, GPIO.IN)
 
GPIO.setup(23, GPIO.IN)

GPIO.setup(27, GPIO.IN)
 
GPIO.setup(22, GPIO.IN)

GPIO.setup(26, GPIO.IN)



I2C_ADDR = 0x27  # I2C device address
LCD_WIDTH = 16  # Maximum characters per line

# Define some device constants
LCD_CHR = 1  # Mode - Sending data
LCD_CMD = 0  # Mode - Sending command

LCD_LINE_1 = 0x80  # LCD RAM address for the 1st line
LCD_LINE_2 = 0xC0  # LCD RAM address for the 2nd line
LCD_LINE_3 = 0x94  # LCD RAM address for the 3rd line
LCD_LINE_4 = 0xD4  # LCD RAM address for the 4th line


LCD_BACKLIGHT = 0x08  # On
# LCD_BACKLIGHT = 0x00  # Off

ENABLE = 0b00000100  # Enable bit

# Timing constants
E_PULSE = 0.0005
E_DELAY = 0.0005

# Open I2C interface
# bus = smbus.SMBus(0)  # Rev 1 Pi uses 0
bus = smbus.SMBus(1)  # Rev 2 Pi uses 1


def lcd_init():
    # Initialise display
    lcd_byte(0x33, LCD_CMD)  # 110011 Initialise
    lcd_byte(0x32, LCD_CMD)  # 110010 Initialise
    lcd_byte(0x06, LCD_CMD)  # 000110 Cursor move direction
    lcd_byte(0x0C, LCD_CMD)  # 001100 Display On,Cursor Off, Blink Off
    lcd_byte(0x28, LCD_CMD)  # 101000 Data length, number of lines, font size
    lcd_byte(0x01, LCD_CMD)  # 000001 Clear display
    time.sleep(E_DELAY)


def lcd_byte(bits, mode):
    # Send byte to data pins
    # bits = the data
    # mode = 1 for data
    #        0 for command

    bits_high = mode | (bits & 0xF0) | LCD_BACKLIGHT
    bits_low = mode | ((bits << 4) & 0xF0) | LCD_BACKLIGHT

    # High bits
    bus.write_byte(I2C_ADDR, bits_high)
    lcd_toggle_enable(bits_high)

    # Low bits
    bus.write_byte(I2C_ADDR, bits_low)
    lcd_toggle_enable(bits_low)


def lcd_toggle_enable(bits):
    # Toggle enable
    time.sleep(E_DELAY)
    bus.write_byte(I2C_ADDR, (bits | ENABLE))
    time.sleep(E_PULSE)
    bus.write_byte(I2C_ADDR, (bits & ~ENABLE))
    time.sleep(E_DELAY)


def lcd_string(message, line):
    # Send string to display

    message = message.ljust(LCD_WIDTH, " ")

    lcd_byte(line, LCD_CMD)

    for x in range(LCD_WIDTH):
        lcd_byte(ord(message[x]), LCD_CHR)


def main():
    # Main program block
    # Initialise display
    lcd_init()


if __name__ == '__main__':

    try:
        main()
    except KeyboardInterrupt:
        pass
    finally:
        lcd_byte(0x01, LCD_CMD)

        i = 0


instance = vlc.Instance()
 
player = instance.media_player_new()
 
path = "/home/pi/Downloads/"
 
a = os.listdir(path)
 
file = ("/home/pi/Downloads/" + a[i])

print(a[i])
 
media = instance.media_new(file)
 
player.set_media(media)
 
time.sleep(1)
  
n = 0
 
num = player.get_state()

b = ['3:44 -IU','3:38 - IU','3:43 - IU','5:37 - IU','3:53 - IU','4:26 - IU']

v=0

vol = 50

player.audio_set_volume(100)
    

while True:
    num = player.get_state()

    if (num == 3 or num == 4):

        lcd_string(    str(a[i]) + str("")    , LCD_LINE_1)
        lcd_string(    str(b[v]) + str("")    , LCD_LINE_2)
     
    if GPIO.input(14) == 0:
        #num = player.get_state()
     
        n = n + 1
     
        if n == 1: # first click music play

            
     
            player.play()  # play a[0] possible??

            print(i)

            print('music start')
     
            time.sleep(0.5)
     
        else:#after, play and pause
     
            player.pause()
     
            time.sleep(0.5)
     
    if GPIO.input(15) == 0: #next music play #time sleep problem?
            #num = player.get_state()

        i = i + 1

        v = v + 1
     
        if (i==len(a)): #if now play last > back to a[0]
     
            player.stop()
     
            i = 0

            v = 0
                
            print(i)

            print('fisrt music')
     
            file = ("/home/pi/Downloads/" + a[i])
            media = instance.media_new(file)
            player.set_media(media)
     
            player.play()
     
            time.sleep(0.5)
     


        else:

            print(i)
      
            player.stop()

                #new i value receive?
            file = ("/home/pi/Downloads/" + a[i])
            media = instance.media_new(file)
            player.set_media(media)
     
     
            player.play()

            lcd_string(    str(a[i])     , LCD_LINE_1)


            print('next music')
     
            time.sleep(0.5)
     
     
    if GPIO.input(18) == 0: #previous music
        #num = player.get_state()

        i = i - 1

        v = v - 1
     
        if (i <= -1): #if now play a[0] > go to last music
                
            player.stop()

            i = len(a)

            v = 6

            print(i)

            print('last music')
     
            file = ("/home/pi/Downloads/" + a[i])
            media = instance.media_new(file)
            player.set_media(media)
            player.play()

            time.sleep(0.5)

        else:
            player.stop()

            print(i)

            print('previous music')
     
            file = ("/home/pi/Downloads/" + a[i])
            media = instance.media_new(file)
            player.set_media(media)
            player.play()

            time.sleep(0.5)
    
    if GPIO.input(27) == 0:   #volume down

        vol = vol - 10

        player.audio_set_volume(vol)

        print("down")
        
    if GPIO.input(22) == 0:    #volume up
        vol = vol + 10

        player.audio_set_volume(vol)        

        print("up")

    if GPIO.input(23) == 0: #program stop
        num = player.get_state()
     
        if(num==3 or num ==4):
     
            player.stop()

            lcd_string(     str("")    , LCD_LINE_1)
            lcd_string(     str("")    , LCD_LINE_2)
            
            time.sleep(0.5)

            break

    if GPIO.input(26) == 0:
        player.stop()
        i = 0
        instance = vlc.Instance()
        player = instance.media_player_new()
        path = "/home/pi/Music/"
        a = os.listdir(path)
        file = ("/home/pi/Music/" + a[i])
        media = instance.media_new(file)
        player.set_media(media)
        time.sleep(1)
        
        n = 0
    
        num = player.get_state()
        c = ['5.:12 - Piano', '5:00 - Piano', '3:52 - Piano']

        v = 0
        

        lcd_string(    str("List change")   , LCD_LINE_1)
        lcd_string(    str("")    , LCD_LINE_2)
        

        while True:
            num = player.get_state()

            if (num == 3 or num == 4):
 
                lcd_string(    str(a[i]) + str("")    , LCD_LINE_1)
                lcd_string(    str(c[v]) + str("")    , LCD_LINE_2)
            if GPIO.input(14) == 0:
                if n == 0:# first click music play
                    n = n + 1
                         

                    print(i)
     
                    print('music start')

                    player.play()
                    time.sleep(0.5)
                        
                else:#after, play and pause
                    player.pause()
                    time.sleep(0.5)
     
     
            if GPIO.input(15) == 0: #next music play #time sleep problem?
                #num = player.get_state()
                i = i + 1
     
                v = v + 1
                if (i==len(a)): #if now play last > back to a[0]
         
                    player.stop()
         
                    i = 0
     
                    v = 0
                    
                    print(i)
     
                    print('fisrt music')
         
                    file = ("/home/pi/Music/" + a[i])
                    media = instance.media_new(file)
                    player.set_media(media)         
                    player.play()
         
                    time.sleep(0.5)
     
                else:
     
                    print(i)
          
                    player.stop()#new i value receive?
                    
                    file = ("/home/pi/Music/" + a[i])
                    media = instance.media_new(file)
                    player.set_media(media)
         
         
                    player.play()
    
                    lcd_string(    str(a[i])     , LCD_LINE_1)     
     
                    print('next music')
         
                    time.sleep(0.5)
         
         
            if GPIO.input(18) == 0: #previous music
                    
                    #num = player.get_state()
                i = i - 1
     
                v = v - 1
     
                if (i <= -1): #if now play a[0] > go to last music
                    
                    player.stop()
     
                    i = 5
     
                    v = 5
     
                    print(i)
     
                    print('last music')
         
                    file = ("/home/pi/Music/" + a[i])
                    media = instance.media_new(file)
                    player.set_media(media)
                    player.play()
     
                    time.sleep(0.5)

                else:
                    player.stop()
                             
                    print(i)
                    print('previous music')
         
                    file = ("/home/pi/Music/" + a[i])
                    media = instance.media_new(file)
                    player.set_media(media)
                    player.play()
     
                    time.sleep(0.5)
                    
            if GPIO.input(27) == 0:   #volume down

                vol = vol - 10

                player.audio_set_volume(vol)

                print("down")
                        
            if GPIO.input(22) == 0:    #volume up
                vol = vol + 10

                player.audio_set_volume(vol)        

                print("up")

         
            if GPIO.input(23) == 0: #program stop
                num = player.get_state()

                if(num==3 or num ==4):
                    player.stop()
     
                    lcd_string(     str("")    , LCD_LINE_1)
                    lcd_string(     str("")    , LCD_LINE_2)
                
                    time.sleep(0.5)     
                    break
```





### Review
 이번 오픈소스 수업을 통해 많은 것을 배웠습니다. 하나의 결과물을 만들어 내기 위해서는 절대로 가벼운 마음가짐을 가져서는 안되고 끝까지 자신이 해내겠다는 열정으로 임해야 한다는 것을 배웠습니다. 또한 이것저것 지식을 쌓은 것 같고 앞으로 살아가면서 자신의 능력으로 해쳐나갈 일이 대부분이라는 것을 느꼈습니다. 결론적으로 주어진 일에 최선을 다하며 자립심을 기르도록 노력해야겠다고 생각했습니다.
