# FakeAudioDetection
Machine learning classification for Fake Audio Detection


## **** Chú Thích ****

Về file data:

frame_length_data: Chứa data sau khi preprocess với n_mfcc = 68 với từng frame length

processed : Để chứa data đã được preprocessed, thành các mfcc features, save ở dạng json

result_chart: Chứa data average (accuracy, f1-macro, precision,recall) sau 10 lần split stratified kfold (Dùng để vẽ chart)

result_frame: chứa data average accuracy của các model dựa trên frame length (Dùng để vẽ chart)

compare: Compare 2 file âm thanh fake và real (cùng source) để EDA

Tổng hợp link file data: (email tui để xin: 22520675@gm.uit.edu.vn)


images reuslt: Chữa những image sẽ sử dụng trong báo cáo

removing silence: script loại bỏ silence audio
signal EDA: file EDA analyse âm thanh
modelin_analysis: run model cũng như plot chart
Preprocessing experiment and tuning: Để thử preprocessing và tune model
