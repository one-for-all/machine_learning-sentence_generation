## Language Generation Model
Trains a RNN with Microsoft COCO annotations dataset. http://cocodataset.org/#download  
Generates sentences from this model.  
After 12 epochs, achieve a validation accuracy of 0.7697. (Take this number with a grain of salt, as it does not accurately represent the performance of this model)  
Trained on Google Compute Engine: 8 CPU, 1 NVIDIA Tesla K80 GPU.  

#### Sample Sentences:
Good:
* two cows standing next to each other in a grass field.
* a woman sits on a bench with some people that are flying a kite.
* there is a sign near the display of a pool.
* one elephant is laying in a giraffe area by rocks .

Kinda good:
* the two pizzas on a table with wine glass sitting on top of a table.
* a group of people, riding on a brown wave, is riding on a wave.
* giraffe eating from a bag with other people standing for field.
* a dessert with a flower in it's.

Bad:
* cooking in a room with mountains , standing side the ground.
* it is a white in outdoor near objects.
* enjoying next to kitchen area with pen, brown and white phone. a glass small baby and a signs.
* beside a basket of water sitting down on the sand at the top of a boat.