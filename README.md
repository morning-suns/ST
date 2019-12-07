# Semantic Transformation

> This is the code for paper **Transformation of Dense and Sparse Text Representations**. 

REQUIRMENTS:

python2.7.13

pytorch0.4.1

INSTRUCTIONS:

python2 runner.py 

--save [save path] 

--dictionary [dictionary file] 

--train-data [train file] 

--val-data [valid file] 

--test-data [test file] 

--class-number [class number] 

--cuda


We attach the SST1 data here and you can run the following instruction directly to get the results on this dataset.

python2 runner.py --save ./save/ve --dictionary ./SST1/dict.json --train-data ./SST1/train.json --val-data ./SST1/dev.json --test-data ./SST1/test.json --class-number 5 --cuda
