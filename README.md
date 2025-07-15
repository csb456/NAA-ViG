# NAA-ViG
NAA-ViG focus on the speaker recognition task by transforming the audio data into Mel spectrograms, chunking the spectrograms as nodes, constructing the node connection relationships to form a graph, and then training them with the Neighbor Attention Aggregation Vision Graph Neural Network (NAA-ViG) model.


The download link for the dataset: https://www.openslr.org/12/. After downloading the data, first use “data cut.py” to split a segment of audio data into multiple parts, then use “mel transform.py” to convert the cut audio data into Mel spectrograms for training the graph neural network model. (Note: Data processing may take some time. If you need pre-processed data, please contact me at 1056797184@qq.com)

The processed data is saved to a specific path. Changes to the parameters in “NAAViGmodel.py” have no effect. Parameter settings are configured in the “main.ini” file within the ‘confs’ folder. The main function “NAA-ViG” allows for adjustments to training, testing, and patch size parameters.
