exScooter v2


	instalujesz arduino w skuterze wraz z czujnikami i kartą sd i mozesz monitorować i zapisywać na kartę SD
	osiągi skuteraz takie jak:
	
	-przyspieszenie (akcelerometr)
	-prędkość max (predkosciomierz)
	i analizowac je wzgledem parametrow takih jak:
	-obroty
	-temperatura oleju
	-otwarcie przepustnicy
	-poziom paliwa
	-kąt pochylania poprzczny
	-kąt pochyalenia wzdłóżny
	-hamulec (bool)
	
	// next version
	PILOT "otwieranie" z pilota czyli zapalanie świateł i dzwięk powitalny jako info asystenta

	
	// next version
	Tempomat - jeden przycisk którym blokujesz prędkość skutera na stałej prędkości. Hamulec zwania blokadę

hardware:
arduinoMain Mega/Uno
arduino RPM - Nano
arduino Speed - Nano
arduinoFuel
czytnik kart sd
//moduł wifi
//moduł gps
//moduł GSM
//moduł remote
//servo przepustnicy
moduł czasu
wyswietlacz oled
wyswietlacz led fuel
button
switch log

czujnik temperatury otoczenia
czyjnik temperatury oleju
czujnik przedkosci

optoizolator RPM
optoizolator STOP

zasilacz 5V
bazpiecznik


inputs:
rpm
speed
tmp1
tmp2
break
fuel
button
button log

Remote Key funkcje:
zapalenie świateł płynne i płynne ich zgaszenie po 20 sec.
odpalenie silnika z pilota
wyłączenie płynne świateł po upływie 20 sek

wifi
transfer logów przez wifi albo bluetooth