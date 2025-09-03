# Termostat z STM32H750 in HTU2X

Projekt termostata, ki temelji na **STM32H750 mikrokontrolerju** in uporablja **HTU2X senzor** za merjenje temperature in vlažnosti.  

## Funkcionalnosti
- Branje temperature in vlažnosti iz HTU2X senzorja  
- Prikaz podatkov preko zaslona  
- Nastavljiva mejna vrednost za termostat preko zaslona na dotik(vklop/izklop ogrevanja/hlajenja)  


## Strojna oprema
- STM32H750 mikrokontroler  
- HTU2X senzor temperature in vlažnosti  
- Napajalni modul (3.3V)  

## Programska oprema
- [STM32CubeIDE](https://www.st.com/en/development-tools/stm32cubeide.html)  
- HAL knjižnice za STM32  
- Gonilnik za HTU2X (I²C komunikacija)  
