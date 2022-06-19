import base64
words = "5YaN57K+5b2p55qE5peF6YCU5Lmf5pyJ57uI54K577yM6ICM5paw55qE5b6B56iL5bCx5Zyo55y85YmN44CC"
data = base64.b64decode(words.encode()).decode()
print(data)
