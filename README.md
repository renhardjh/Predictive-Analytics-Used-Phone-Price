# Predictive Analytics Used Phone Price

## Latar Belakang

Dalam era digital dan teknologi yang terus berkembang, handphone (ponsel) telah menjadi salah satu perangkat elektronik yang sangat penting dalam kehidupan sehari-hari. Banyak orang yang tertarik untuk membeli handphone bekas, baik untuk alasan finansial, keinginan untuk mencoba model atau merek baru, atau sebagai alternatif jika handphone mereka rusak atau hilang. Namun, menentukan harga yang tepat untuk handphone bekas bisa menjadi tugas yang rumit. Harga handphone bekas dapat bervariasi secara signifikan tergantung pada faktor-faktor seperti merek, model, kondisi fisik, usia, spesifikasi teknis, dan permintaan pasar. Para pembeli dan penjual handphone bekas seringkali kesulitan dalam menetapkan harga yang adil dan kompetitif.

Dalam hal ini, Machine Learning dan Predictive Analytics dapat memberikan solusi yang berguna. Dengan memanfaatkan teknik Machine Learning dan menganalisis data historis penjualan handphone bekas, data spesifikasi teknis, data kondisi fisik, dan faktor-faktor lainnya, kita dapat mengembangkan model yang dapat memprediksi harga handphone bekas secara akurat. Model ini akan mempertimbangkan berbagai fitur handphone bekas, seperti merek, model, spesifikasi teknis (RAM, penyimpanan, kamera, dll.), usia handphone, kondisi fisik (goresan, kerusakan, dll.), serta faktor eksternal seperti tren pasar, harga terkini, dan keadaan ekonomi.

Dengan menggunakan model prediksi harga handphone bekas, para penjual dapat memperoleh wawasan yang lebih baik tentang harga yang adil untuk menawarkan handphone mereka, sementara para pembeli dapat menggunakan informasi tersebut untuk menilai apakah harga yang diminta oleh penjual wajar atau tidak.

Keuntungan dari proyek ini adalah:
1. Kemudahan dalam menentukan harga: Dengan model prediksi harga handphone bekas, para penjual dapat dengan lebih mudah menentukan harga yang adil dan kompetitif berdasarkan faktor-faktor yang signifikan.
2. Efisiensi dalam pembelian: Para pembeli dapat menggunakan model untuk memperkirakan harga yang diharapkan untuk suatu handphone bekas sebelum melakukan pembelian. Hal ini membantu mereka dalam membuat keputusan yang lebih baik dan memperoleh nilai terbaik dari pembelian mereka.
3. Transparansi pasar: Dengan model prediksi harga yang akurat, transparansi pasar handphone bekas dapat ditingkatkan, membantu penjual dan pembeli dalam melakukan negosiasi yang lebih adil dan efisien.

Dalam pengembangan proyek ini, langkah-langkah yang perlu diambil meliputi pengumpulan data penjualan handphone bekas, persiapan dan pembersihan data, pemilihan dan pelatihan model Machine Learning, serta evaluasi dan pengujian model untuk memastikan keakuratan prediksi harga. Dengan demikian, proyek ini dapat memberikan nilai tambah bagi penjual dan pembeli handphone bekas, membantu mereka dalam mengoptimalkan pengalaman jual beli dan menemukan harga yang adil dalam pasar yang dinamis.

## Business Understanding

Dalam industri jual beli handphone bekas, ada kebutuhan yang signifikan untuk menentukan harga yang tepat untuk handphone bekas. Para penjual ingin menawarkan harga yang adil dan kompetitif, sementara para pembeli ingin memperoleh handphone bekas dengan harga yang wajar. Namun, menentukan harga yang tepat bisa menjadi tantangan karena faktor-faktor yang beragam dan kompleks yang mempengaruhi harga handphone bekas. Dalam hal ini, proyek prediksi harga handphone bekas menggunakan Machine Learning akan memberikan solusi yang berguna untuk para penjual dan pembeli. Dengan memanfaatkan teknologi Machine Learning, proyek ini bertujuan untuk mengembangkan model yang dapat memprediksi harga handphone bekas berdasarkan berbagai faktor seperti merek, model, spesifikasi teknis, usia, kondisi fisik, dan faktor-faktor lainnya.

Pemahaman bisnis ini akan membantu penjual handphone bekas dalam menentukan harga yang adil berdasarkan karakteristik dan kondisi handphone yang mereka jual. Dengan menggunakan model prediksi, mereka dapat mengoptimalkan penawaran mereka dan meningkatkan kesempatan untuk menjual handphone bekas dengan harga yang menguntungkan. Di sisi pembeli, pemahaman bisnis ini akan memberikan wawasan yang lebih baik dalam mengevaluasi harga handphone bekas yang mereka minati. Dengan memiliki perkiraan harga yang diharapkan, mereka dapat membuat keputusan yang lebih baik dan memastikan bahwa mereka tidak membayar terlalu mahal atau kurang dari nilai sebenarnya.

Selain itu, dengan adanya model prediksi harga handphone bekas, akan tercipta transparansi pasar yang lebih baik. Penjual dan pembeli akan memiliki panduan yang lebih jelas dalam menentukan harga yang adil, dan hal ini dapat mengurangi negosiasi yang tidak produktif serta meningkatkan efisiensi dalam transaksi jual beli handphone bekas. Dalam rangka pengembangan proyek ini, penting untuk bekerja sama dengan para penjual handphone bekas, pedagang, dan platform jual beli handphone untuk memahami kebutuhan dan perspektif mereka. Dengan memahami dinamika pasar handphone bekas dan tantangan yang dihadapi oleh para pemangku kepentingan, kita dapat mengarahkan proyek ini untuk memberikan solusi yang paling relevan dan bermanfaat.

Dengan demikian, proyek prediksi harga handphone bekas menggunakan Machine Learning memiliki potensi untuk meningkatkan efisiensi dan transparansi dalam pasar handphone bekas, memberikan manfaat bagi penjual, pembeli, dan pemangku kepentingan terkait lainnya.

### Problem Statement and Goals

Berdasarkan kondisi yang telah diuraikan sebelumnya, kami akan mengembangkan sebuah sistem prediksi harga handphone bekas untuk menjawab permasalahan berikut:
1. Sulitnya menentukan harga yang tepat untuk handphone bekas: Para penjual handphone bekas seringkali kesulitan dalam menetapkan harga yang adil dan kompetitif berdasarkan berbagai faktor seperti merek, model, spesifikasi teknis, usia, kondisi fisik, dan faktor-faktor lainnya. Ini dapat mengakibatkan harga yang terlalu tinggi atau terlalu rendah, yang berdampak negatif pada proses jual beli.

2. Ketidakpastian dalam mengevaluasi harga yang wajar: Para pembeli handphone bekas menghadapi kesulitan dalam mengevaluasi apakah harga yang diminta oleh penjual handphone bekas itu wajar atau tidak. Kurangnya informasi dan wawasan yang akurat tentang harga handphone bekas dapat menyebabkan pembeli membayar terlalu mahal atau melewatkan kesempatan untuk memperoleh handphone dengan harga yang lebih baik.

Serta untuk menjawab pertanyaan tersebut, Anda akan membuat predictive modelling dengan tujuan atau goals sebagai berikut:
1. Membantu penjual menentukan harga yang adil: Tujuan utama proyek ini adalah memberikan panduan kepada penjual handphone bekas dalam menetapkan harga yang adil dan kompetitif berdasarkan karakteristik dan kondisi handphone yang mereka jual. Dengan demikian, para penjual dapat meningkatkan peluang mereka untuk menjual handphone bekas dengan harga yang menguntungkan.

2. Memungkinkan pembeli untuk mengevaluasi harga yang wajar: Proyek ini bertujuan memberikan wawasan yang lebih baik kepada pembeli handphone bekas dalam mengevaluasi harga yang wajar untuk handphone yang mereka minati. Dengan memiliki perkiraan harga yang diharapkan, pembeli dapat membuat keputusan yang lebih baik dan memastikan bahwa mereka tidak membayar terlalu mahal atau kurang dari nilai sebenarnya.

### Solution Statement

Dalam rangka meraih tujuan tersebut, solusi yang diajukan adalah membangun model Machine Learning yang dapat memprediksi harga handphone bekas berdasarkan berbagai faktor seperti merek, model, spesifikasi teknis, usia, kondisi fisik, dan faktor-faktor lainnya. Model ini akan menggunakan teknik Machine Learning untuk menganalisis data historis penjualan handphone bekas dan faktor-faktor yang mempengaruhi harga.

Data yang diperoleh akan meliputi informasi tentang penjualan handphone bekas, kondisi fisik, spesifikasi teknis, merek, dan model. Model akan dilatih dengan menggunakan algoritma Machine Learning KNN, Boosting, LinearRegression dan Support Vector Regression dengan membandingkan hasil dari keempat algoritma tersebut untuk mendapatkan hasil prediksi yang terbaik. Setelah dilatih, model akan dapat memprediksi harga yang diharapkan untuk handphone bekas berdasarkan input faktor-faktor yang diberikan.

Alasan menggunakan algoritma tersebut karena ke empat algoritma tersebut merupakan yang paling cocok untuk penyelesaian masalah dengan cara regresi.

Algoritma KNN (K-Nearest Neighbors):
1. KNN adalah algoritma yang sederhana dan mudah dipahami. Karena proyek ini melibatkan prediksi harga berdasarkan fitur-fitur yang relevan, KNN dapat digunakan untuk mencari tetangga terdekat berdasarkan atribut-atribut yang serupa. Hal ini memungkinkan KNN untuk memprediksi harga handphone bekas berdasarkan harga handphone bekas yang memiliki atribut serupa.

2. KNN memiliki kemampuan untuk menangani data dengan variasi yang tinggi. Dalam kasus ini, handphone bekas memiliki berbagai atribut seperti merek, model, spesifikasi teknis, usia, dan kondisi fisik yang sangat bervariasi. KNN mampu mengatasi variasi ini dengan mengambil kategori tetangga terdekat yang memiliki atribut yang serupa.

Algoritma Boosting:
1. Boosting adalah algoritma yang mampu meningkatkan performa model dengan menggabungkan beberapa model yang lemah menjadi model yang lebih kuat. Dalam kasus prediksi harga handphone bekas, faktor-faktor yang mempengaruhi harga dapat sangat kompleks dan saling terkait. Dengan menggunakan algoritma Boosting, kita dapat menghasilkan model yang lebih akurat dan dapat menangani hubungan yang kompleks antara fitur-fitur yang ada.

2. Boosting memiliki kemampuan untuk mengatasi overfitting. Dalam proyek ini, kita ingin menghasilkan model yang dapat menggeneralisasi dengan baik pada data baru. Dengan menggunakan teknik Boosting, kita dapat menghindari overfitting dan menghasilkan model yang dapat memberikan prediksi yang lebih konsisten dan akurat pada data baru.

Algoritma Linear Regression:
1. Linear Regression adalah algoritma yang sesuai untuk memodelkan hubungan linier antara variabel dependen dan variabel independen. Dalam proyek ini, kita ingin memprediksi harga handphone bekas berdasarkan beberapa fitur seperti spesifikasi teknis, usia, dan kondisi fisik. Linear Regression dapat membantu dalam memodelkan hubungan linier antara fitur-fitur tersebut dengan harga handphone bekas.

2. Linear Regression dapat memberikan interpretasi yang mudah. Dalam kasus prediksi harga handphone bekas, interpretasi dari koefisien regresi dapat memberikan wawasan tentang sejauh mana setiap fitur berkontribusi terhadap harga handphone bekas. Ini dapat membantu penjual dan pembeli dalam memahami faktor-faktor yang mempengaruhi harga dan membuat keputusan yang lebih baik.

Algoritma SVR (Support Vector Regression):
1. SVR adalah metode regresi yang memanfaatkan konsep-konsep dari Support Vector Machines (SVM). Dalam proyek ini, SVR dapat digunakan untuk memodelkan hubungan kompleks antara fitur-fitur yang ada dengan harga handphone bekas.

2. SVR memiliki kemampuan untuk menangani data yang tidak linear. Dalam banyak kasus, hubungan antara fitur-fitur dan harga handphone bekas mungkin tidak linier. Dengan menggunakan kernel yang sesuai, SVR dapat memetakan data ke ruang fitur yang lebih tinggi dan menemukan hubungan non-linear yang ada antara fitur-fitur dan harga.

## Data Understanding

Data yang kami gunakan merupakan data kumpulan harga handphone bekas yang bersumber dari Kaggle, yang berisi features sebagai berikut:

- **device_brand:** Nama merek pabrikan
- **os:** OS tempat perangkat berjalan
- **screen_size:** Ukuran layar dalam cm
- **4g:** Apakah 4G tersedia atau tidak
- **5g:** Apakah 5G tersedia atau tidak
- **front_camera_mp:** Resolusi kamera belakang dalam megapiksel
- **back_camera_mp:** Resolusi kamera depan dalam megapiksel
- **internal_memory:** Jumlah memori internal (ROM) dalam GB
- **ram:** Jumlah RAM dalam GB
- **baterai:** Kapasitas energi baterai perangkat dalam mAh
- **berat:** Berat perangkat dalam gram
- **release_year:** Tahun model perangkat dirilis
- **days_used:** Jumlah hari perangkat bekas/refurbished telah digunakan
- **normalized_new_price:** Harga normal perangkat baru dengan model yang sama
- **normalized_used_price (TARGET):** Harga normal untuk peralatan bekas/rekondisi

### Membaca Data

    usedPhones = pd.read_csv('datasets/used_device_data.csv')
    usedPhones
    
![alt text](https://github.com/renhardjh/Predictive-Analytics-Used-Phone-Price/blob/main/Images/dataframe.png?raw=true)

    usedPhones.describe()

    usedPhones.info()

### Data Cleansing

    usedPhones.isnull().sum()
    
![alt text](https://github.com/renhardjh/Predictive-Analytics-Used-Phone-Price/blob/main/Images/null_info.png?raw=true)

Seperti yang terlihat bahwa datasets berisi beberapa value NaN yang harus kita atur sebelum memulai analisis dan membuat model

    for i in features:
        a=usedPhones[i].median()
        print(i,'new value : ', a)
        usedPhones[i]= usedPhones[i].fillna(a)
        
Dapat kita lihat ada beberapa nilai nol dalam fitur, menghapusnya bukanlah opsi yang tepat, karena datasets kita tidak terlalu banyak, sehingga lebih baik dengan cara menggganti nilai dengan nilai median dimana nilai median tidak akan terpengaruh oleh outlier

Kemudian gunakan IQR untuk mengeliminasi outliers

    features=['screen_size','front_camera_mp','ram','battery','weight','normalized_used_price','normalized_new_price']
    for i in features:
        lower = usedPhones[i].quantile(0.10)
        upper = usedPhones[i].quantile(0.90)
        usedPhones[i] = np.where(usedPhones[i] <lower, lower,usedPhones[i])
        usedPhones[i] = np.where(usedPhones[i] >upper, upper,usedPhones[i])

    usedPhones.shape
    
Perlakukan fitur internal_memory, battery dan rear_camera_mp dengan perhitungan yang berbeda, karena mereka memiliki outlier skewness yang berbeda

    upper= usedPhones.rear_camera_mp.quantile(0.95)
    usedPhones.rear_camera_mp= np.where(usedPhones.rear_camera_mp>upper,upper,usedPhones.rear_camera_mp)

    upper= usedPhones.internal_memory.quantile(0.9)
    usedPhones.internal_memory= np.where(usedPhones.internal_memory>upper,upper,usedPhones.internal_memory)

    upper= usedPhones.weight.quantile(0.8)
    usedPhones.weight= np.where(usedPhones.weight>upper,upper,usedPhones.weight)
    
### Analisis Univariate

Hitung persentase data device_brand dan visualisasikan diagram batang

    numerical_features = ['normalized_used_price', 'normalized_new_price', 'screen_size', 'rear_camera_mp', 'front_camera_mp', 'internal_memory', 'battery', 'weight', 'release_year', 'days_used']
    categorical_features = ['device_brand', 'os', '4g', '5g', 'ram']

    feature = categorical_features[0]
    count = usedPhones[feature].value_counts()
    percent = 100*usedPhones[feature].value_counts(normalize=True)
    df = pd.DataFrame({'Total sample':count, 'percentage':percent.round(1)})
    print(df)
    count.plot(kind='bar', title=feature);

Visualisasikan diagram batang semua fitur numerik sehingga kita bisa analisis dan bandingkan

    usedPhones.hist(bins=40, figsize=(18,12))
    plt.show()

![all text](https://github.com/renhardjh/Predictive-Analytics-Used-Phone-Price/blob/main/Images/Visuallize%20bar%20chart%20numerical_features.png?raw=true)

Berikut kesimpulan informasi dari data yang bisa didapat

- Rentang mp kamera depan sebagian besar antara 0-10 mega piksel
- Memori internal sebagian besar antara 0-100
- Penyimpanan ram ponsel sebagian besar antara 3-5 GB
- Masa pakai baterai sebagian besar sekitar 3000 mah
- Berat sekitar 150-210
- Samsung adalah ponsel yang paling banyak digunakan kembali di samping merek ponsel yang dikategorikan sebagai Lainnya.
- Rata-rata orang yang menggunakan OS Android
- Ukuran layar kebanyakan antara 10-15
- Pengguna 4g dan 5g lebih banyak
- Orang-orang telah menggunakan telepon rata-rata antara 600-800 hari yang kira-kira 2-2,5 tahun
- Rata-rata harga bekas yang dinormalisasi antara 4,2-5rb
- Rata-rata harga baru normal antara 5-6rb
- Kisaran mp kamera belakang sebagian besar antara 5-15 mega piksel
- Sebagian besar ponsel dirilis antara 2013-2015

### Analisis Multivariate

Kita bisa melakukan visualisasi sekaligus untuk membandingkan rata-rata **normalized_us_price** dengan setiap fitur untuk mengerti relasi hubungan setiap data, baik itu menggunakan **catplot**, **pairplot**, dan juga matriks korelasi dengan heatmap.

Berikut visualisasi matriks korelasinya

    correlation_matrix = usedPhones.corr().round(2)

    sns.heatmap(data=correlation_matrix, annot=True, cmap='coolwarm', linewidths=0.5, )
    plt.title("Correlation matrix for numerical features ", size=20)

![alt text](https://github.com/renhardjh/Predictive-Analytics-Used-Phone-Price/blob/main/Images/matrix_correlation_value.png?raw=true)

Dari matriks korelasi tersebut kita dapat simpulkan 5 fitur teratas yang mempunyai relasi tertinggi, sebagai berikut:

- normalized_new_price: 0.79
- battery: 0.69
- front_camera_mp: 0.68
- screen_size: 0.64
- weight: 0.61

Dapat dilihat juga ram tidak memiliki garis karena memiliki nilai dominan atau terbanyak yaitu 4, lebih baik di drop dari datasets

    usedPhones.drop(['ram'], axis=1, inplace=True)
    usedPhones
    
## Data Preparation

Mengubah data kategory yes/no pada fitur 4g dan 5g dengan 1 dan 0 agar model lebih mudah diolah

    dict_cat_symbol = {'yes':1,'no':0}
    usedPhones['4g'] = usedPhones['4g'].map(dict_cat_symbol)
    usedPhones['5g'] = usedPhones['5g'].map(dict_cat_symbol)

Melakukan one hot encoding pada setiap fitur categorical

    from sklearn.preprocessing import  OneHotEncoder

    usedPhones = pd.concat([usedPhones, pd.get_dummies(usedPhones['device_brand'], prefix='device_brand')],axis=1)
    usedPhones = pd.concat([usedPhones, pd.get_dummies(usedPhones['os'], prefix='os')],axis=1)
    usedPhones.drop(['device_brand','os'], axis=1, inplace=True)
    usedPhones.head()
    
Melakukan pengurangan dimensi dengan PCA untuk mengurangi jumlah fitur sambil mempertahankan informasi dalam data. PCA merupakan teknik untuk mereduksi dimensi, mengekstraksi fitur, dan mentransformasi data dari “n-dimensional space” ke dalam sistem berkoordinat baru dengan dimensi m, di mana m lebih kecil dari n.

    from sklearn.decomposition import PCA

    pca = PCA(n_components=len(dimension_features), random_state=12345)
    pca.fit(usedPhones[dimension_features])
    princ_comp = pca.transform(usedPhones[dimension_features])

Menggabungkan fitur dengan korelasi tertinggi kedalam fitur baru dimensi

    from sklearn.decomposition import PCA
    pca = PCA(n_components=1, random_state=12345)
    pca.fit(usedPhones[dimension_features])
    usedPhones['dimension'] = pca.transform(usedPhones.loc[:, (dimension_features)]).flatten()
    usedPhones.drop(dimension_features, axis=1, inplace=True)

### Memisahkan Data training dan test

Pisahkan data latih dan uji, karena data tidak terlalu banyak maka bagi dengan proporsi 95:5

    from sklearn.model_selection import train_test_split

    X = usedPhones.drop(["normalized_used_price"],axis =1)
    y = usedPhones["normalized_used_price"]
    X_train, X_test, y_train, y_test = train_test_split(X, y, test_size = 0.05, random_state = 12345)
    
Setelah dibagi dataset akan terpecah menjadi:
- Total sampel keseluruhan dataset: 3454
- Total sampel dataset latih: 3281
- Total sample dataset tes: 173

### Scaling and Normalisasi

Pada umumnya disarankan untuk menskalakan dan menormalkan data sebelum melakukan pemodelan untuk memastikan bahwa semua fitur memiliki bobot yang sama dan distribusi yang serupa. Hal ini dapat mencegah fitur yang mendominasi model tertentu, yang dapat menyebabkan overfitting atau hasil yang salah.

    from sklearn.preprocessing import MinMaxScaler

    numerical_features = ['weight','release_year','internal_memory','days_used','dimension']
    scaler = MinMaxScaler()
    scaler.fit(X_train[numerical_features])
    X_train[numerical_features] = scaler.transform(X_train.loc[:, numerical_features])
    X_train[numerical_features].head()

## Pengembangan Model

Seperti yang sudah dijelaskan sebelumnya bahwa dalam kasus prediksi harga handphone bekas ini akan menggunakan algoritma KNN, Boosting, LinearRegression dan SVR, karena dinilai lebih cocok dalam kasus kasus prediksi harga, Kemudian kita akan mengukurnya dengan mean squared error untuk membandingkan model dengan algoritma mana yang terbaik

    models = pd.DataFrame(index=['train_mse', 'test_mse'], 
                          columns=['KNN', 'Boosting', 'LinearRegression', 'SVR'])
                          
Model dengan algoritma K-Nearest Neighbor

    from sklearn.neighbors import KNeighborsRegressor
    from sklearn.metrics import mean_squared_error

    knn = KNeighborsRegressor(n_neighbors=10)
    knn.fit(X_train, y_train)

    models.loc['train_mse','knn'] = mean_squared_error(y_pred = knn.predict(X_train), y_true=y_train)

Model dengan algoritma AdaBoostingRegressor

    from sklearn.ensemble import AdaBoostRegressor

    boosting = AdaBoostRegressor(learning_rate=0.05, random_state=55)                             
    boosting.fit(X_train, y_train)
    models.loc['train_mse','Boosting'] = mean_squared_error(y_pred=boosting.predict(X_train), y_true=y_train)

Model dengan algoritma LinearRegression

    from sklearn.linear_model import LinearRegression

    LG = LinearRegression()                             
    LG.fit(X_train, y_train)
    models.loc['train_mse','LinearRegression'] = mean_squared_error(y_pred=LG.predict(X_train), y_true=y_train)

Model dengan algoritma Support Vector Regression

    from sklearn.svm import SVR

    SVR = SVR()                             
    SVR.fit(X_train, y_train)
    models.loc['train_mse','SVR'] = mean_squared_error(y_pred=SVR.predict(X_train), y_true=y_train)

## Evaluasi Model

Evaluasi model dengan membandingkan mean squared error setiap model kemudian coba lakukan prediksi dan bandingkan hasilnya

    mse = pd.DataFrame(columns=['train', 'test'], index=['KNN','Boosting','LinearRegression','SVR'])
 
    # Create a dictionary for each algorithm used
    model_dict = {'KNN': knn, 'Boosting': boosting, 'LinearRegression': LG, 'SVR': SVR}

    # Calculate the Mean Squared Error of each algorithm on the train and test data
    for name, model in model_dict.items():
        mse.loc[name, 'train'] = mean_squared_error(y_true=y_train, y_pred=model.predict(X_train))
        mse.loc[name, 'test'] = mean_squared_error(y_true=y_test, y_pred=model.predict(X_test))

    # Call mse
    mse
    
![alt text](<img width="297" alt="Screenshot 2023-06-05 at 01 40 56" src="https://github.com/renhardjh/Predictive-Analytics-Used-Phone-Price/assets/24643123/45931324-e80d-44fd-8661-ab0fc34d2144">
)

subplot hasil mse setiap model untuk membandingkannya

    fig, ax = plt.subplots()
    mse.sort_values(by='test', ascending=False).plot(kind='barh', ax=ax, zorder=3)
    ax.grid(zorder=0)

![alt text](![mse_models](https://github.com/renhardjh/Predictive-Analytics-Used-Phone-Price/assets/24643123/4df217fc-471d-4ae9-99da-833fb5b107b8)
)

### Predict menggunakan Model

    prediction = X_test.iloc[:3].copy()
    pred_dict = {'used_price':y_test[:3]}
    for name, model in model_dict.items():
        pred_dict['prediction_'+name] = model.predict(prediction).round(6)

    pd.DataFrame(pred_dict)

![alt text](<img width="837" alt="predict_results" src="https://github.com/renhardjh/Predictive-Analytics-Used-Phone-Price/assets/24643123/74be14e0-a135-4029-b616-99ce24ca81f3">
)

Dari hasil tersebut SVR mempunyai nila mse terkecil, sehingga SVR merupakan algoritma yang paling tepat untuk kasus memprediksi harga ponsel bekas, model SVR inilah yang akan digunakan.

## Kesimpulan

Dalam proyek prediksi harga handphone bekas menggunakan Machine Learning, kami menggunakan penggunaan algoritma KNN, Boosting, Linear Regression, dan SVR sebagai solusi untuk menangani permasalahan tersebut, karena algoritma tersebut yang pada umumnya digunakan untuk penyelesaian regresi. Dari keempat algoritma tersebut SVR merupakan yang menghasilkan error MSE terkecil yang berarti model dengan algoritma ini menjadi pilihan yang terbaik. 

Dalam pengembangan proyek ini, dapat dipertimbangkan juga penggunaan kombinasi dari algoritma-algoritma tersebut untuk memperoleh hasil prediksi yang optimal. Misalnya, penggunaan KNN untuk menemukan tetangga terdekat berdasarkan atribut serupa, kemudian menggunakan Boosting untuk meningkatkan performa model dengan menggabungkan beberapa model KNN. Selain itu, Linear Regression dan SVR juga dapat digunakan untuk memodelkan hubungan linier dan non-linear yang ada antara fitur-fitur dan harga. 

Dengan menggunakan pendekatan ini, proyek prediksi harga handphone bekas dapat memberikan solusi yang akurat dan berguna bagi penjual dan pembeli handphone bekas. Penjual dapat menentukan harga yang adil dan kompetitif, sementara pembeli dapat mengevaluasi harga yang wajar sebelum melakukan pembelian.
