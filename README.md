A simple rating prediction system, based on matrix factorization. To reduce the training time, i have chosen a only 10k users and 10k song_ids, but it is highly recommended to expand it according
to your use cases. Tweak with params like learning_rate, train_test_split. 
IDEA is simple -> for a given matrix W of shape : [N,N], get 2 different smaller matrix i.e A, B such that W ~ A*B^T. We further treat A as user embeddings and B as song embeddings. Learning these
embeddings is the primary goal of any recommendation system. 

Future Work:
By using approximate nearest neighbours one can get set of similar songs for given user/item ids. Hence, can be exploited as basic item/entity/song recommendation system. 
