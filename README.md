# OOAD-WEEK09 Homework
##Usecase Diagram

 * รูปที่ 1 ข้อมูลลูกค้า
 
CODE 

Customer --* Adress

Customer : +Firstname()

Customer : +Lastname()

Customer : +Age()

Customer : +IDCard()

Customer : +Sex()

Adress : +Road()

Adress : +City()

Adress : +Country()

Adress : +PostCode()

 [![IMAGE ALT TEXT](http://www.plantuml.com/plantuml/img/SoujBidFJIrIqDNLKd1CAKejBkPoXebPAMYxPHOLb-GbvgPgQAA8-oHY5NPCHnVnT75EB4f14mnEhG2AGAm3yOFo4rDG19mpIofH1V9ByqgAKCK2yejBdFDJW3O20000)
 
 * รูปที่ 2 สายพันธุ์สุนัข
 
code

Dog <|-- Chivava

Dog <|-- Doberman

Dog <|-- Pug

Dog : -name():string

Dog : +brak():void

Dog : +Display():void

Chivava : +brak():void

Chivava : +Display():void

Doberman : +brak():void

Doberman : +Display():void

Pug : +brak():void

Pug : +Display():void

[![IMAGE ALT TEXT](http://www.plantuml.com/plantuml/img/SybFLx2fqTLLSCx8B4iiI-HoWGcuv2Ub5kKcvY540ahJmHmh1TsynDnK3KshufAYp3oOe7PIKM8sKB0iFpC59kIIMLoGarW94uLQWguOIHXD0ymHcCOZnD6q05s9hXegXAOG0000)

 * รูปที่ 3 ประเภทCar
 
code

Car <|-- SuperCar

Car <|-- GameCar

SuperCar <|-- FerarlCar

GameCar <|-- MarioCar

GameCar <|-- BurnoutCar

Car : -Speed:int

Car : -isStarted:Boolean

Car : +void start()

Car : +void drive()

Car : +void()

SuperCar : +void drive()

SuperCar : +void nitrous()

GameCar : +void start()

MarioCar : +void drive()

[![IMAGE ALT TEXT](http://www.plantuml.com/plantuml/img/PSyn3iCW343HlQTWR5HnWQXJaDgf4oUmX0TB2OuCPEhX2qfSAMJaVMIC0p7FhxN6bnN5WToSoXiMRA1brnSAoDpyw3j_G8WlEXM9NBAE7OtrAs8OAMO5IZw3v8eJyumGZ_3Oc899hTs7amMX3SzMJ_yj-skN42aBbrIJxjg_ff_fP_q0)

 * รูปที่ 4 รายการสั่งซื้อของของลูกค้า
 
code

Customer  -- Order

Customer : +Name

Customer : +Adress

Customer : +Creditrating()

Order : +deterecived

Order : +number

Order : +price

Order : +dispatch()

[![IMAGE ALT TEXT](http://www.plantuml.com/plantuml/img/LSsx3O0m40FGdYbIWX0BqA7qC4F8MN158BfSc9-FnA_qaspRd7GD46EQnWn2aCBUr9gwTm4_w4YGqe-iW5Z5AIzJMHNNoEa4XS3p1dfnoM4yFfuSXJq-7KxHgP_BQWS0)

 * รูปที่ 5 ข้อมูลนักเรียน
 
code

Student --o Adress

Student : -FirstName : string

Student : -LastName : string

Student : -HomeAdress : Adress

Student : -Class : string

Student : +Tostring():string

Adress : -streetAdress : string

Adress : -City : string

Adress : -Road : string

Adress : -zip code: string

Adress : +Tostring() : string

[![IMAGE ALT TEXT](http://www.plantuml.com/plantuml/img/2oufJKdDAr7GrSrNS4mfIYqkvWg62bafwBfb5XMN-2NcfW8vnIL5cNdfoB8-YNWaFV9pKo460dcO9Zld989bC3HgX-H3n3GqhQ2IS6DqWGAfgILmFeQySsP99JRneFp456pYLPa52idvAQcOKaZEG6W40000)
