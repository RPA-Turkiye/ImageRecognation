# ImageRecognation 

RPA Türkiye Image Recognation Workshop
<br>
<a href="https://www.kaggle.com/grassknoted/asl-alphabet">ASL --> American Sign Language Dataset From Kaggle<a>
  
Training
<br>
<code>python scripts/retrain.py --image_dir image_dir/ --architecture  inception_v3 --model_dir inputs/inception_v3 / --bottleneck_dir bottleneck/inception_v3/ --output_graph output/inception_v3/output_graph.pb --output_labels output/inception_v3/inception_v3_labels.txt --saved_model_dir output/inception_v3/1/ -summaries_dir logdir/inception_v3/ --how_many_training_steps 5000 --learning_rate 0.00</code>
