# MODELTEST
how to use the ML model
#########################
1. import pickel as ...
import pickle
##########################
2.load the model as ....
# load the model
model = pickle.load(open("model.pkl", "rb"))
##########################
3.predict the data by providing 2darray.....
model.predict([encodings])
