Title: Visualisation in Machine Learning

Description :
The case study aim is to classify the given audio data. The study focuses on different visualization techniques to explore data.

Here visualization is used for a good feature selection by taking multiple parameters into consideration.

PLatform used : Jupyter Notebook
Tool used : Anaconda Navigator

Visualization techniques and libraries to be installed/import in this case study are :
1) PCA - sklearn.decomposition.pca
2) LLE - sklearn.manifold.LocallyLinearEmbedding
3) ISOMAP - sklearn.manifold.Isomap
4) tSNE - sklearn.manifold.TSNE
5) UMAP - umap

Parameters taken into consideration :
1)Window size
2)Step size
3)Decimate
4)Feature Range
5)Feature
6)Window
		
Window values = ['hamming', 'hann', 'boxcar', 'blackmanharris']
Feature values = ['dct', 'fft', 'fft_phase', 'dct_phase', 'cepstrum', 'raw']

Best score from each visualization is retrieved by sorting the dictionary containing all the score values. 





