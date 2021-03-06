# Oevelse-Smarthome-controller

### **1.** Identify the problem domain <Br />
"Klienten" ønsker at få installeret et IOT-smarthome styresystem, til at opgradere sit hjem.  <Br />
Følgende skal inkluderes: <Br />
**1-** Lys  <Br />
**2-** Varme (Radiator styring)  <Br />
**3-** Kaffemaskine  <Br />
**4-** Vækkeur  <Br />
**5-** Robot støvsuger   <Br /> <Br />

### **2.** Use case <Br />

Hjemmet skal kunne styres via en smartphone, både manuelt og automatisk ved detection af telefonen. <Br />


Så snart huset opfanger telefonen, skal det automatisk vide at du er kommet hjem, og skal derfor: <Br />
**-** Tænde lyset i entreen og foran hoveddøren, alt efter tidspunktet på dagen.<Br />
**-** Justere på varmen. <Br />

Så snart huset opfanger at telefonen forlader huset, skal det automatisk vide at du er taget hjemmefra , og skal derfor: <Br />
**-** Slukke alt lyset i huset.<Br />
**-** Justere på varmen. <Br />
**-** Støvsuge hele huset. <Br />

Når telefonen sættes til opladning i stikket ved sengen: <Br />
**-** Justere på varmen. <Br />

Når vækkeuret ringer: <Br />
**-** Justere på varmen. <Br />
**-** Skrue stille og roligt op for lyset. <Br />
**-** Kaffen skal være klar. <Br />

Når du enter/leave et rum: <Br />
**-** Skal lyset tænde/slukke <Br />


### **3.** Design your classes <Br />
**-** SystemMain.java <Br />
**-** Hus.java <Br />
**-** Lys.java  <Br />
**-** Varme.java <Br />
**-** Kaffe.java <Br />
**-** Støvsuge.java <Br />
**-** Vækkeur.java <Br />









### **4.** Abstraction  and interfaces <Br />
