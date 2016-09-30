# entmob2016_6
Ons project zal eruit bestaan dat onze applicatie een basic interface gaat hebben die bepaalde data van de Sensortag gaat weergeven. 
Wij leggen niet echt de focus op een origineel idee, maar willen zeker zijn dat de datastructuur en al de achterliggende code zo perfomant mogelijk zijn.


-Onze architectuur zal er als volgt uit zien:
(Een mooie weergave van dit diagram staat ook in de repository.)

            Bluetooth              HTTP                JSON
TI Sensortag -----> Mobile Phone  -----> Api / Server <----> Database 
                                             ˄
                                             |   HTTP
                                             ˅
                                     Desktop Application
                                     

