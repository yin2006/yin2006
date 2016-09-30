# yin2006
hoi
 lol
 ;) # appel

![appel](appel.jpg)

hier wat leuke websaits

www.StaggeringBeauty.com

http://cat-bounce.com/

http://www.sadforjapan.com/

www.corgiorgy.com

www.theuselessweb.com

http://ducksarethebest.com/

en hier een super erge websait

http://thatsthefinger.com/

ik hoop dat je dit leuk vind 

 30-9-2016
vandaag hebben we allemaal een websait gemaakt die er nog geen hadden,
bijvoorbeeld ik.












int ledPin = 9;



void setup() {
  
}

void loop() {
  
for (int fadeWaarde = 0; fadeWaarde <= 255; fadeWaarde +=5){

  analogWrite(ledPin, fadeWaarde);
  
  delay(30);
  
}

for (int fadeWaarde = 255; fadeWaarde >= 0; fadeWaarde -=5){

  analogWrite(ledPin, fadeWaarde);
  
  delay(30);
  }

}



