## Analysis of chest x-ray images

The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.

### Libraries required
    fastai
    pytorch
    matplotlib

### For installing fastai library:
1. Download project: git clone https://github.com/fastai/fastai.git
2. Move into root folder: `cd fastai`
3. Set up Python environment: `conda env update`
4. Activate Python environment: `conda activate fastai`
5. If this fails, use instead: `source activate fastai`
    
### For installing pytorch
    conda install pytorch torchvision -c pytorch

### For running this project
1. Copy `Lung Pneumonia detection` jupyter notebook in cloned fastai repository folder.
2. Activate the fastai environment: `source activate fastai`
3. Run the notebook: `jupyter notebook`
