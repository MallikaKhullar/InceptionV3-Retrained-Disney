# retrained-inceptionv3-disney
Retrained Tensorflow's Inception V3 on disney characters: Jasmine, Meg, Genie, Ariel

To test an image, store it in the tf_files folder and run this command 
```
python -m scripts.label_image     --graph=tf_files/retrained_graph.pb      --image=tf_files/test3.jpg
```
