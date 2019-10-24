2.b)
PINA0, PINC9.

3.d)
HAL_GPIO_TogglePin(GPIOC, GPIO_PIN_9);

3.e)
10ms.

3.f)+g)
HAL_GPIO_TogglePin(GPIOC, GPIO_PIN_8);
HAL_Delay(500);

4.b)
Modra LED se ne spremeni ob pritisku na modro tipko. Prižge, oz. ugasne se le zelena LED.

4.c)
Na modro LED ni vpljiva modrega gumba, le na zeleno, saj je tako zapisan program.

//Modra LED samostojno utripa in nikoli neha. Ob pritisku na modro se prižge oz. ugasne zelena LED.
//Modra LED je neodvisna pristikov modrega gumba.
