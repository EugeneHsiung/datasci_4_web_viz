# datasci_4_web_viz


https://uz4xit-eugenehsiung.shinyapps.io/cdcr/ 

## challenges encountered

### Shiny Python: 
One problem I encountered was trying to deploy the app. During my first attempt, I used the command
```pip install shiny``` which had no problems. However, after using  ```shiny run cd --reload```  error messages would pop up. 

Picture: 
<img width="724" alt="Screen_Shot_2023-09-26_at_7 39 00_PM" src="https://github.com/EugeneHsiung/datasci_4_web_viz/assets/141866888/765a9acf-fba9-4249-b35f-5d5469a17465">

After retrying several times, I decided to save all and reload the entire google shell. I reran ```pip install shiny``` and '''shiny run cd --reload``` This time I was able to successfully deploy the app. 

Picture: 
![384443870_244438595217754_7481138554177546565_n](https://github.com/EugeneHsiung/datasci_4_web_viz/assets/141866888/6ce79229-1266-4cb7-8c46-c6c2b60067e7)

### Flask: 
The only problem that I had with Flask was creating a folder named ```Templates``` instead of ```templates```. However, after realizing the case sensitivity, I was able to successfully deploy the app.py

### Shiny R
I ran into a few problems with the Shiny R application on Postit cloud. First I did not realize that I had to install the packages: dplyr, ggplot2, and shiny. After clicking on the packages and running the application, I was able to successfully create an application. 

Picture: 
<img width="904" alt="Screen Shot 2023-09-26 at 11 47 23 PM" src="https://github.com/EugeneHsiung/datasci_4_web_viz/assets/141866888/788bfb89-ac10-4f86-a62d-0ad76c5a625d">



