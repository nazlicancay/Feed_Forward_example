# Feed_Forward_example
• Forward propagation için, input olarak  su X matrisini verelim:
X =
[1 2 3
4 5 6]
Satırlar veriler (sample’lar), kolonlar  öznitelikler (feature’lar).

• Bir adet hidden layer olsun ve içinde tanh aktivasyon fonksiyonu olsun

• Hidden layer’da 50 nöron olsun

• Bir adet output layer olsun, tek nöronu olsun ve içinde sigmoid aktivasyon fonksiyonu olsun

Tanh fonksiyonu:
f (x) = exp(x)−exp(−x)/ (exp(x)+exp(−x))

Sigmoid fonksiyonu:
f (x) = 1/(1+exp(−x))

bu fonkisyon için Seed değerini
1 olarak set edelim (FeedForward example1'da) 


daha sonra custom bir değeri (okul numaramızı) seed değerine atayalım (FeedForward Example2)
