# Use-Of-State-Of-Art-Libraries-For-ANN  
CMPE255-SEC48  
Dataset1 : Movie dataset with Labels  


ANN algotithms and specific classes used to build index and perform the query to search data.  

a) LSH - key class used faiss.IndexLSH  
b) Exhaustive search - key class used faiss.IndexFlatL2  
c) Product quantization - key class used faiss.IndexIVFPQ(quantizer)  
d) Trees and graphs - key class used annoy.AnnoyIndex 

Dataset2 : Sift dataset with image formats  
e) hnsw - key class used faiss.IndexHNSWFlat  
