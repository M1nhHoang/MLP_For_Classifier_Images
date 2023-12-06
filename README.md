# MLP_For_Classifier_Images

## Các bước làm
1. Load dữ liệu từ file `/data`.
2. Tiền xử lí dữ liệu.
  - Tạo dữ liệu pretrain bao gồm `x_pretrain, y_pretrain` bằng cách data augmentation (thêm nhiễu, xoay, zoom, lật ảnh, ...).
  - Chuyển labels thành vector `one-hot`
3. Thiết kế model.
4. Pretrain tập dữ liệu `x_pretrain, y_pretrain`.
5. Train model dự đoán bằng cách `fine tune` model pretrain.
6. Dự đoán x_test và xuất ra file `.csv` .

## Model

![image](https://github.com/M1nhHoang/MLP_For_Classifier_Images/assets/106025710/1627bd4e-0fcf-48e2-bffa-1c58c255e5ae)

![image](https://github.com/M1nhHoang/MLP_For_Classifier_Images/assets/106025710/65a5ff96-736d-4b09-b989-0029ba0e40fa)

## Dataset

Total 40,000 different 28 x 28 grayscale images.  

![image](https://github.com/M1nhHoang/MLP_For_Classifier_Images/assets/106025710/45fff3a8-0774-46e4-8e9a-8dbc994bc15e)

## Result 

![image](https://github.com/M1nhHoang/MLP_For_Classifier_Images/assets/106025710/ddcdb3fc-265a-45a6-9c61-9cfa2b1101e4)

### [Kaggle compertitions](https://www.kaggle.com/competitions/mlp-competition-123-2/leaderboard)
### [Final result](https://docs.google.com/spreadsheets/d/1q-2ltaBjoGufW0XxyljoMNXtRKogu-SZR0V123Up438/edit#gid=472643203)


