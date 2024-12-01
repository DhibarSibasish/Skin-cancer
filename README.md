🌟
## Project Overview 

Skin cancer is a crucial health issue that requires timely detection for higher survival rates. Traditional computer vision techniques face challenges in addressing the advanced variability of skin lesion features, a gap partially bridged by convolutional neural networks (CNNs). To overcome the existing issues, we introduce an innovative convolutional ensemble network approach named deep autoencoder (DAE) with ResNet101. This method utilizes convolution-based deep neural networks for the detection of skin cancer. The ISIC-2018 public data taken from the source is used for experimental results, which demonstrate remarkable performance with the different in terms of performance metrics.

# Model Architecture
          ![image](https://github.com/user-attachments/assets/0f23bb16-8005-49c8-bf31-d20ba183685a)


## ![Categories:](https://img.shields.io/badge/Categories-orange)
- akiec: Actinic keratoses and intraepithelial carcinoma
- bcc: Basal cell carcinoma
- bkl: Benign keratosis-like lesions
- df: Dermatofibroma
- mel: Melanoma
- nv: Melanocytic nevi
- vasc: Vascular lesions

| Class | Example |
|-------|---------|
| akiec | ![image](https://github.com/user-attachments/assets/923df9a6-10ba-4f07-b708-a443b856f27e) |
| bcc   | ![image](https://github.com/user-attachments/assets/0f6ace7d-987d-4c3b-af61-e7e2ade91d25) |                                                           |
|bkl    | ![image](https://github.com/user-attachments/assets/95e5c8e3-ee06-44c7-be26-17c7579d2ba2) |
|df     | ![image](https://github.com/user-attachments/assets/8c35da64-d845-4e48-9618-f7cd72641c9b) |
| mel   | ![image](https://github.com/user-attachments/assets/043b5882-0235-4579-aaaa-dbb7ec2a6951) |
| nv    | ![image](https://github.com/user-attachments/assets/179371f7-a79d-4cf2-b46d-22608e372b92) |
| vasc  | ![image](https://github.com/user-attachments/assets/71b02554-7ace-4fac-bc29-48fabb459c58) |

### Play with Skin Cancer Images(https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)

        📂 Dataset
        
### The dataset used in this project is the HAM10000 dataset.
  - Source: HAM10000 Dataset
  - Images: 10,015 dermoscopic images, categorized into seven classes.
  - Preprocessing: Images resized to 128x128 for consistency.

## How to Run the App:

### Method 1
- Run the `app.py` file
- Go to [http://localhost:5000/](http://localhost:5000/) on your browser
- Use the **Upload** button to browse and upload the image you want
- Hit **Submit** to get the results.

### Method 2
- Deploy it to **Azure Web App** or **Heroku App** through your GitHub repository
- Go to the URL generated after deployment on your browser
- Use the **Upload** button to browse and upload the image you want
- Hit **Submit** to get the results.

---

## Libraries Used:
- `numpy`
- `keras`
- `tensorflow-cpu==2.5.0`
- `pandas`
- `matplotlib`
- `pillow`
- `flask`
- `seaborn`
- `gunicorn`


