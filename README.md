# CNN (Convolutional Neural Network) Nedir?
CNN (Convolutional Neural Network), derin öğrenme alanında sıkça kullanılan bir yapay sinir ağı türüdür. Görüntü işleme, görüntü sınıflandırma, nesne tespiti ve diğer görsel veri analizi görevlerinde başarılı sonuçlar elde etmek için kullanılır. CNN'ler, verilerin özelliklerini hiyerarşik olarak öğrenmek için farklı katmanlardan oluşur.

Bu Jupyter defteri, en temel haliyle CNN'in temel yapı taşlarını açıklamak ve PyTorch ile nasıl kodlandığını göstermek için tasarlanmıştır.

### Bölüm 1: Convolutional Layer
Bu bölümde, Convolutional Layer'ın ne olduğunu ve nasıl çalıştığını anlatacağız. Bu katman, görüntüler üzerinde özellikleri vurgulamak ve öğrenmek için bir dizi filtre veya kerneli kullanır.

### Bölüm 2: Pooling (Downsampling) Layer
Pooling katmanı, ağırlıklı bir şekilde boyut azaltma işlevi görür. Bu bölümde, Pooling katmanının ne olduğunu ve nasıl çalıştığını öğreneceğiz.

### Bölüm 3: Non-Linearity Layer - ReLU
ReLU (Rectified Linear Unit), CNN'lerde yaygın olarak kullanılan bir aktivasyon fonksiyonudur. Bu bölümde, ReLU'nun ne olduğunu ve neden kullanıldığını inceleyeceğiz.

### Bölüm 4: Output Layer
Output Layer, CNN'in son katmanıdır ve genellikle sınıflandırma veya regresyon gibi görevler için kullanılır. Bu bölümde, bu katmanın işlevini açıklayacağız.

### CNN ile Kodlama Örneği (PyTorch)
Son olarak, PyTorch kütüphanesi kullanılarak basit bir CNN modelini nasıl kodlayacağımızı göstereceğiz. Bu örnek, cifar10 veri kümesi üzerinde sınıflandırmayı hedefleyecektir.
