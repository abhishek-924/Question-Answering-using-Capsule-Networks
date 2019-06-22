# Capsule-Network
 Capsule networks are used for understanding the spatial information, as they help in making sense of words even if they are not adjacent, which makes the approach not one of the words to word analysis but provides the classifier to understand the context of the entire network.
A capsule consists of a group of neurons along with the activation, which is the vector representation of instantiation parameters which helps in providing the probability for the existence of an entity in a piece of textual information.
Capsule network uses the dynamic routing algorithm which helps in preserving not only one, but all the useful features for a sentence or a part of the text.


## Requirements
* Anaconda
* Keras
  * pip install keras
  
## Usage
Run the files in the following order:
* **Libraries.py** contains all the libraries to be imported initially. 
* **preprocessing.py** has all the functions for preprocessing the dataset.
The ‘question’ and ‘specification’ columns were merged together into a new column named ‘question_text’. For preprocessing the data, first, the short forms of words are changed to their original forms such as changing ‘cause’ to ‘because’ or ‘i’m’ to ‘I am’. After correcting such spellings removal of the punctuations like{ ',', '.', '"', ':', ')', '(',} is carried out. Next, the numbers such as{1,2,3} and special characters such as {@, #, $}are removed along with stop words like {is, are, will}. All the missing values in the dataset are then replaced by a random string.

*
