# Inten_OpenVINO_EdgeApp_ChallengeCourse
* ## Project Showcase
  * **Project Name:** Pet Characterization
  * **Project Story:** Whenever I see a pet, whether it is a dog, or a cat, or even a bird, I always want to know what its breed is, what kinds of charcteristics the pet has, e.g. active/quiet/aggressive. And as an owner of any pet, he or she must want to know what the dietary preference the pet has. For that purpose, an edge app could be developed with the output including 4 classes: type, breed, characteristics, dietary preference. Since the app will be deployed at the edge, it would reduce network communications and free up computation compared to cloud usage. 
  * **Data Preparation:** Use deep learning to detect the type and breed of the pet. The characteristics and dietary preference could be stored in a dictionary with the breed as the key. Once the breed has been detected, use key to find the pet's characteristics and dietary preference. Something like the example shown below. 
  ```python
  char = {'german_shepherd':('aggressive','meat'), 'golden_retriever':('friendly','meat), 'british_shorthair':('active','mix')}
  ```
  * **The output would include 4 classes**: \['dog','german_shepherd','aggressive','meat']
  <img src='https://3c918j3kwt6a3vrcmw3irl7u-wpengine.netdna-ssl.com/wp-content/uploads/2017/01/german-shepherd-puppies-4.jpg' width='300'>
