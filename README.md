# On-Accelerating-Multi-Layered-Heterogeneous-Network-Embedding-Learning
Commands

for politics:
deepwalk --format edgelist --input Politics-UK/lists-to-community.txt --number-walks 10 --representation-size 128 --walk-length 3 --window-size 2 --output Politics-UK/lists-to-community.embeddings

for Olympics:
deepwalk --format edgelist --input Olympics/lists-to-community.txt --number-walks 10 --representation-size 128 --walk-length 3 --window-size 2 --output Olympics/lists-to-community.embeddings