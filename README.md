# Mosaic - Udyam '22, Problem Statement 1
   
## Team - Chaos 
- Atharva Bhatt (Team Leader)
- Ayush Gangwani  
- Dhruv Agarwal  

## Steps to test the model:
1. Put the testing images in TESTING_CAPTCHAS Folder.
2. Run main.py file.

## Steps to train the model:
1. Put the emoji dataset in DATA\\Emoji Dataset\\{Emoji_Name} Folder according to the emoji.
2. Run emoji_augmentation.py for the augmentation of the given emoji dataset.
3. Run data_processing.ipynb to make a .csv file containing dataset of both, letters (from emnist-balanced dataset) and emojis (from emoji-augmented dataset) as chosen in the character set and mentioned in character.txt.
4. Run train_model.ipynb to train the model. The weights will be saved in WEIGHT Folder as model.h5.

## Special Features 
1. This model can recognize captchas with letter rotation upto 30 deg.
2. Can detect captchas having letters of variable thickness and size.

## The mapping of the emojis is as follows:
Checkmark : 1  
Cloud: 2  
Croissant: 3  
Heart: 4  
Laugh: 5  
Smile: 6  
Sun: 7  


