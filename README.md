# Eye-Disease-Diagnostics-Computer-Vision

The purpose of this study is to employ computer vision methodologies for the advancement of eye disease classification. To ensure better patient outcomes and clinical efficiency, research focus must be on utilizing and developing robust algorithms that will progress screening/early detection, diagnisis support, and treatment of eye diseases. This computer vision model based off advanced machine learning methodolgies known as deep learning (multi-layered neural networks) will detect eyes having:
glaucoma (= 0), normal (= 1), diabetic retinopathy (= 2), and cataract (= 3).

# About the diseases:

Cataract:

is a common age-related eye condition characterized by the clouding of the lens, leading to blurry vision and visual impairment. It can be treated surgically by replacing the cloudy lens with an artificial one, restoring clear vision and improving quality of life.

Diabetic retinopathy:

is a complication of diabetes that affects the blood vessels in the retina. It can cause vision loss, including blurred or distorted vision, and in severe cases, lead to blindness. Early detection, regular eye exams, and proper management of diabetes are crucial for preventing and managing this condition.

Glaucoma: 

is a group of eye diseases that damage the optic nerve, often due to increased fluid pressure in the eye. It gradually leads to vision loss, starting with peripheral vision and potentially progressing to complete blindness. Timely diagnosis, treatment, and ongoing monitoring are vital for preserving vision and preventing irreversible damage.

# Model Results (90% Accuracy in overall detection) and (>/= 90% accuracy in glaucoma, diabetic retinopathy, and cataract). High true positives for disease classes show model's robustness and predictive power. Lower true positives for normal class will need to be improved to avoid false negatives and ensure clinical relevance and efficiency.
<img width="319" height="123" alt="{3505AAB2-ED99-48B2-8ED3-4CB98622229A}" src="https://github.com/user-attachments/assets/697f5bbf-2f23-4005-bab5-38c836e97602" />

# Model Architecture: 
Pre-trained RestNet-18 model. ResNet-18 is composed of multiple residual blocks, which are designed to address the problem of vanishing gradients in deep neural networks. These blocks introduce skip connections, allowing information to bypass several layers and flow directly to deeper layers. This helps in mitigating the degradation problem and enables the network to learn more effectively, even with very deep architectures. Two new dense layers were added and 70% of model's former layers were freezed while remaining left trainable, such that tranfer learning will be easier with the new eye dataset.

For any queries on code used, project details, or collaboration - please send an email to ahmed1000hassan@yahoo.com 
Credit for Dataset = https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification 
