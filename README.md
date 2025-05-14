# FineTuningAI

Andamento del training del modello DS_Finetuned:
100 	2.409300
200 	0.342900
300 	0.311500
400 	0.316500
500 	0.318600
600 	0.305900
700 	0.306500
800 	0.311700
900 	0.296400
1000 	0.302700
1100 	0.305800
1200 	0.287200
1300 	0.298100
1400 	0.291200
1500 	0.291200

TrainOutput(global_step=1500, training_loss=0.4463768793741862, metrics={'train_runtime': 10262.9326, 'train_samples_per_second': 1.169, 'train_steps_per_second': 0.146, 'total_flos': 1.14457602686976e+17, 'train_loss': 0.4463768793741862})


Andamento del training del modello DS_Finetuned_3, che nasconde l'instruction nel preprocessing:
100 	1.945700
200 	0.333200
300 	0.308200
400 	0.314100
500 	0.316400
600 	0.303900
700 	0.304400
800 	0.309900
900 	0.294400
1000 	0.300900
1100 	0.303900
1200 	0.285500
1300 	0.296300
1400 	0.289400
1500 	0.289400

TrainOutput(global_step=1500, training_loss=0.41304088465372724, metrics={'train_runtime': 10447.7841, 'train_samples_per_second': 1.149, 'train_steps_per_second': 0.144, 'total_flos': 1.14457602686976e+17, 'train_loss': 0.41304088465372724})


Andamento del training del modello DS_Finetuned_5, allenato usando response al posto di seed:
100 	1.675900
200 	0.229700
300 	0.224200
400 	0.216100
500 	0.217400
600 	0.208700
700 	0.206000
800 	0.209900
900 	0.201400
1000 	0.209800
1100 	0.202700
1200 	0.195400
1300 	0.199100
1400 	0.196400
1500 	0.195600

TrainOutput(global_step=1500, training_loss=0.30588720703125, metrics={'train_runtime': 10386.4181, 'train_samples_per_second': 1.155, 'train_steps_per_second': 0.144, 'total_flos': 1.14457602686976e+17, 'train_loss': 0.30588720703125})