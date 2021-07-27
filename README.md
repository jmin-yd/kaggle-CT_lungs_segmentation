# CT Lung Segmentation

512 이미지 사이즈 그대로 학습 시도. 
preprocessing 진행한 데이터 파일은 용량이 큰 관계로 업로드 못함.  

아래. 결과 이미지

**Left** CT image | **Center** manually segmented lungs | **Right** Predicted result  
![result.png](https://github.com/jmin-yd/kaggle-CT_lungs_segmentation/blob/test_512size/result/result_512.png)


## Dependencies
### Training
- Python 3.8.10
- numpy 1.20.2
- keras / tensorflow 2.5.0
- matplotlib 3.4.2
### Preprocessing
- scikit-image 0.18.2
- scikit-learn 0.24.2
- pandas 1.3.0

## Dataset
Finding and Measuring Lungs in CT Data https://www.kaggle.com/kmader/finding-lungs-in-ct-data

