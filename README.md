# yoga-exp_5
from pandas import read_csv
from matplotlib import pyplot
series=read_csv("C:\\Users\\Admin\\Downloads\\new-thyroid.csv")

print(series.head())
series.plot()
pyplot.show()
![WhatsApp Image 2024-09-07 at 22 32 39_30707ed0](https://github.com/user-attachments/assets/f4a14064-96b1-44ff-9269-780a85b9d2d8)

series.plot(style='-.')
pyplot.show()
![WhatsApp Image 2024-09-07 at 22 32 39_90508dad](https://github.com/user-attachments/assets/d23e88d7-0e2a-43a1-b0c3-50c9904137a9)


series.hist()
pyplot.show()
![WhatsApp Image 2024-09-07 at 22 32 39_99e86acf](https://github.com/user-attachments/assets/ed739c74-6cde-4245-9da3-99cfc12616b7)

series.plot(kind='kde')
pyplot.show()
![WhatsApp Image 2024-09-07 at 22 32 40_af4aa773](https://github.com/user-attachments/assets/cf261c37-9907-4d40-ac36-d867cc3a5bbc)
