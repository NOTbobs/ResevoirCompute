# ResevoirCompute
Practice with dynamically growing compute resevoirs

Personal Notes: 
Resevoir Computing networks are networks with a set of neurons with randomized connections. Connections are recurrent or directed. During training the parameters of the resevoir are frozen. Data is inputted into the resevoir and undergoes various trainsformations that are deterministic. After the transformation by the resevoir a single 'read-out' network is trained to interpret the transformation and to map the output into a desired output. 

Observation 1: 

"Pushing" trained layers with frozen weights into the resevoir using toy datasets can speed up convergence of new read-out networks, and can slightly improve accuracy. Pushing additional layers results in slight improvement of accuracy. 

